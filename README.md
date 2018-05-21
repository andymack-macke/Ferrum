# FerrumMasterNoder

###  Description

The FerrumMasterNoder is a Windows application - Wizard to install a Ferrrum Master Node.
* Assist with Windows Wallet.  
* Write the masternode.conf in the windows folder.
* Write the FerrumCoin.conf and send it to the Linux VPS.
* Execute / Mange the script to setup the Master Node on the VPS
* Monitor the status of the Masternode Server.

### Installation

download the install file at https://github.com/andymack-macke/FerrumMasterNoder/blob/master/Setup_FMN.msi

## Step One - VPS information

If you're using Vultr VPS just copy and paste the IP and Password into the relative Text Boxes.

If you are using Digital Ocean VPS, Simply highlight and copy all the relavant info from their Email, as shown in the diagram, and click the  `<Import>` button. The IP and initial Password will be copied in one action.  

Digital Ocean requires that the Pasword is changed immediately.  Yo can the contents of the Password entry will be made your final password.  (by clicking on the little orange square button will generate a random password)


![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-2.PNG)


![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-1.PNG)



## Step Two - Windows Wallet information

Click on the second button (BLUE - windows controller wallet)

![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-3.PNG)

Set up your collateral - do steps 1 to 5 in  https://github.com/FerrumCommunity/Ferrum-Guides/blob/master/Windows%20Cold%20Wallet/windows%20cold%20wallet%20setup.md

Open the console on the Ferrum wallet.
One at a time Click on the links shown below to copy the commands into clipboard, paste into the Ferrum Console and Enter.

![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-4.PNG)

Copy the result on the Console as shown below.

![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-5.PNG)

Click on the big Orange button `<Paste from Wallet Console>` and it will populate the appropriate entries.

![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-6.PNG)


## Step Three - Installation.

Click on the thrid button down (Green - Install).

Click on the square Orange button `<Run>`


![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-7.PNG)


After a few minutes it will finish the install phase.

![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-9.PNG)


The Master Node is now syncronising its wallet.  This will take some time to finish.

![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-10.PNG)


When the Master Node wallet has fully sync'ed it will look like this.  


![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-11.PNG)


It is time to shutdown the Ferrum Wallet and re-open it.  You should then Start the Master Node from the Cold wallet as in Step 9 of the Windows controller Guide.  
https://github.com/FerrumCommunity/Ferrum-Guides/blob/master/Windows%20Cold%20Wallet/windows%20cold%20wallet%20setup.md


![alt text](https://github.com/andymack-macke/FerrumMasterNoder/blob/master/FMN-13.PNG)

