
# Before Hands on Lab


# Before conducting the tutorial, please prepare yourself with Azure account. 

## I. Create an free Azure Subscription
    
You can use your own Azure Subscription, or use below link to apply an Azure trial subscription.    
https://azure.microsoft.com/en-us/free/

There will be around 10-30 USD of workshop Azure cost, if you are using trial version of Defender for IoT and shutdown/stop VM while not using it.
For details of Azure pricing, please refer to Azure Pricing Calculator, https://azure.microsoft.com/en-us/pricing/calculator

1. To apply for a free Azure Account, Open Cloud Computing Services | Microsoft Azure
Click "start free"

![Alt text](figures/bhol-1.jpg?raw=true "start")

2. Register Microsoft personal account to sign in and apply for free credit

![Alt text](figures/bhol-2.jpg?raw=true "start")


## Or, II. Bring your enterprise Azure account

If you bring your own enterprise Azure account, please make sure you have proper Azure service access right with following actions. 
Either ask support from your Azure admin and/or with proper network constraints relaxed (firewall, etc):

    * Create VM of SKU D4s_v3 - 4 vcpus, 16 GiB
    * Remote access to your VM with RDP or basion 
    * Create workspace in Microsoft Sentinel
    * Access to Defender for IoT
    * Create and configure IoT Hub

# Environment preparation (Complete before you attend workshop)

## Run Action B in tutorial

Before workshop, please help complete environment setup following by below BHOL tutorial of Action B: 

https://github.com/mpram/Azure-Defender-for-IoT/blob/main/Before%20HOL/Microsoft%20Defender%20for%20IoT%20BHOL.md

Please ignore Action A (all) and Action B (Task 4, Step 5 and 6), as we are leveraging Azure Free account or enterprise Azure account for this workshop.

Action B: Set up Environment

    Task 1: Resources
    Task 2: Virtual Machine
    Task 3: Connect to Virtual Machine
    Task 4: Enable Hyper-V

        In Task 4, Step 5 and 6, you don't have to download and install Storage Explorer.
        You can just download the HOLfiles via below link from your browswer in RDP Windows envrionment.
        https://aka.ms/md4iotpcaps    

    Task 5: Microsoft Sentinel

## [IMPORTANT] To save Azure credit/cost from your free trial account. Please be reminded to stop/shutdown your Defender sensor VM after environment setup


# PCAP file download link:

On Hands on lab day, after intstallation of Defender completed, please use below link to download PCAP files for replay.

    pcap files download: 
    https://aka.ms/md4iotpcaps

    sensor iso image downlaod:
    https://aka.ms/md4iotiso


