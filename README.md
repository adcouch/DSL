# DSL

This is a boxstarter script for a DSL Laptop.

To deploy:

```powershell
. { Invoke-WebRequest -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force
```

```powershell
$Cred = Get-Credential $env:USERNAME
```
```powershell
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/adcouch/dsl/main/windply/dsl_deploy.choco -Credential $Cred 
```
