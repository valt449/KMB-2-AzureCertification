## Placeholder for scripts and useful stuff for this part of the exam

### CLI
```shell
az group create --name something --location eastUS
az vm create --name LinuxVMFromCLI -image UbuntuLTS --resource-group Linux
az vm delete --name LinuxVMFromCLI --resource-group Linux
```

### Powershell

```powershell
Get-Command -verb Get -noun AzureRm*

New-AzureRmVm -Name LinuxVM -Image UbuntuLTS -ResourceGroupName Linux
Remove-AzureRmVm -Name LinuxVM -ResourceGroupName Linux
```

### Cloudshell commands 
```shell
az configure
```
```shell
az interactive
```



