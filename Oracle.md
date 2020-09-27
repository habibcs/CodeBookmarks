Oracle with their Advance Queue (AQ) on .NET

$/PSSSOA/Common/POC/OPS/OracleOPSSuiteSubscriber/OracleOPSSuiteSubscriber/.nuget
https://www.oracle.com/technical-resources/articles/java/intro-java-message-service.html
https://docs.oracle.com/database/121/ADQUE/jm_create.htm#ADQUE1100
https://docs.oracle.com/cd/E11882_01/java.112/e16548/streamsaq.htm#JJDBC28801
https://www.nuget.org/packages/Oracle.ManagedDataAccess 
https://docs.oracle.com/cd/E48297_01/doc/win.121/e41125/OracleAQQueueClass.htm 
Oracle Advance Queue - to access it.
OracleAQ access from .NET without oracle client installation
https://stackoverflow.com/questions/32122164/oracle-aq-topic-queue-dequeue-with-odp-net 
ODP.NET does not require Oracle Drivers?
https://docs.oracle.com/database/121/ODPNT/intro004.htm#ODPNT8146 
Looks like you will have to use ODP.net and not the managed driver
https://www.oracle.com/database/technologies/appdev/dotnet/odp.html 
There are three driver types: ODP.NET, Managed Driver; ODP.NET, Unmanaged Driver; and ODP.NET Core. ODP.NET, Managed Driver is 100% .NET code.
Developers deploy a single assembly in a deployment package smaller than 10 MB. ODP.NET, Unmanaged Driver contains more features than the managed driver since it can access functionality built into the Oracle Database Client.
ODP.NET Core is designed for multi-platform .NET Core applications. 
https://community.oracle.com/thread/2146707
https://community.oracle.com/thread/1055452
