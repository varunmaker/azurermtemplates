# Execute Dependent script extensions to Configure and Install Mongo DB on a Ubuntu Virtual Machine

<a href="https://azuredeploy.net/" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template deploys Configures and Installs Mongo DB on a Ubuntu Virtual Machine in two separate scripts. This template is a good example that showcases how to express dependencies between two scripts running on the same virtual machine. This template also deploys a Storage Account, Virtual Network, Public IP addresses and a Network Interface.

Below are the parameters that the template expects

| Name   | Description    |
|:--- |:---|
| newStorageAccountName  | Unique DNS Name for the Storage Account where the Virtual Machine's disks will be placed. |
| adminUsername  | Username for the Virtual Machines  |
| adminPassword  | Password for the Virtual Machine  |
| dnsNameForPublicIP  | Unique DNS Name for the Public IP used to access the Virtual Machine. |
| vmSize | Size of the Virtual Machine |