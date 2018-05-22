# Azure VMSS Runcommand Execution
This repository contains files for VMSS scripting automation. 

## Synopsis
Iterate thru each VMSS instance either Windows or Linux and run either a PowerShell or Bash Script . 

## Description

This script will query the Azure subscription for existing VMSS deployments and allow you to select which one you want to work with and run a script agains.
  
In order to authenticate you will need to have an account in the customer subscription to execute the command. 

You will need to be running AzureRM module version 6 or higher, if not the script will exit. 

Update you Azure modules by running the following command in this link:

https://docs.microsoft.com/en-us/powershell/module/powershellget/update-module?view=powershell-6

## Example script execution
    .\azr-vmss-runcommand
    
    Follow prompts
