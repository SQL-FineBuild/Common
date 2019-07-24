{anchor:Top}
| Previous [Group Policy Management](Group-Policy-Management) | [Install Preparation](Documentation#InstallPreparation) Next |
# Configure SQL Server Certificates
Setup of SQL Server Certificates is not included in the automated processing.

If it is required to use Encryption or register CLR assemblies on the SQL Server instance, a Certificate must be configured.  

Information about setting up Encryption for SSL connections to SQL Server is given at [http://www.mssqltips.com/sqlservertip/3299/how-to-configure-ssl-encryption-in-sql-server/?utm_source=dailynewsletter&utm_medium=email&utm_content=headline&utm_campaign=20140812](http://www.mssqltips.com/sqlservertip/3299/how-to-configure-ssl-encryption-in-sql-server/?utm_source=dailynewsletter&utm_medium=email&utm_content=headline&utm_campaign=20140812).

1) Using SQL Server Configuration Manager, locate the _Protocols for MSSQLSERVER_.  Right-click on _Protocols for…_ and select _Properties_.
: [Image:Config Manager.png)(Image_Config-Manager.png)
2) Specify the Certificate details as required for the specific instance.  It is normal that no certificates are required.
: [Image:Certificate.png)(Image_Certificate.png)
[Copyright FineBuild Team](Copyright-FineBuild-Team) © 2014 -2015.  [License and Acknowledgements](License-and-Acknowledgements)
| Previous [Group Policy Management](Group-Policy-Management) | [#Top](#Top) | [Install Preparation](Documentation#InstallPreparation) Next |