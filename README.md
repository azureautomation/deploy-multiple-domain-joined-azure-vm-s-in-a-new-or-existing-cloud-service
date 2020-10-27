Deploy Multiple Domain joined Azure VM's in a new or existing Cloud Service
===========================================================================

            

 


 Using this script you can achieve:


  *  

Create Multiple Azure VM's under a New Cloud Service


  *  

 Add additional Azure VM's under an already created Cloud Service


  *  

Get the machines joined to the domain



**Requirements:**


  *  

Azure Powershell Module installed in the machine.


  *  

Your Subscription Name, you need to specify the subscription name while using the script.


  *  

Pre-created Affinity Group, you need to specify the name while using the script.


  *  

Pre-created Storage in Azure, you need to specify the storage name while using the script.


  *  

Pre-created Virtual Network in Azure, you need to specify the name while using the script.


  *  

Pre-created Subnet under Virtual Network in Azure, you need to specify the name while using the script.


  *  

Domain Controller configured and added to above VNET to get the machine joined to the domain during creation.


  *  

Azure Image Name using the command ( Get-AzureVMImage | where-object { $_.Label -like '<ImageLabel>*' })



 


**Points to remember while using script:**


The promt where it will ask for username and password, you need to define the name and password that you want the administrator to have for the newly created machines and not the Domain Admin credentials of your Domain.



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
