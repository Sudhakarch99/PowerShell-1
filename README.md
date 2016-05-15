# PowerShell

Misc scripts to interact with TFS REST API, deploy SSIS projects, set IIS properties, upload logs to FTP site, etc.

### AggregateTFSCodeCoverageResults.ps1

Script to aggregate TFS 2015 build code coverage results for specified build definition 
SSRS reports do not work with new build system (Non XAML) to provide this info as of Update 2 

### UpdateTFSWorkItemsWithBuildLink.ps1

Adds build link to associate work items
Runs as the last step in build definitions  

### SSISDeploy.ps1
Script to deploy SSIS package (ISPAC) 

### SetIISPropertiesForFasterStartup.ps1
Sets IIS properties for faster load times

### RegisterGACAssemblies.ps1
UnRegisters/Registers list of assemblies to GAC
