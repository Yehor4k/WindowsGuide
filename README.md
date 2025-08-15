## Simple guide on how to install Windows 11

### 1. Download Windows files

#### 1. Firstly go to microsoft: 
Link to Microsoft [Windows 11](https://www.microsoft.com/en-us/software-download/windows11) or [Windows 10](https://www.microsoft.com/en-us/software-download/windows10)
#### 2. Your screen will look like this then download the Installation Media:
![Screenshot from Microsoft website](/assets/images/windows%2011.png)

### 2. Make a bootable flash drive

Open the installation Media and follow the steps:

1. Accept the terms:
![Screenshot of accepting the Terms](/assets/images/terms.png)

2. Select language and region:
![Screenshot of selecting language and region](/assets/images/lang%20and%20reg.png)

3. Select "USB flash drive" to make bootable flash drive:
![Screeenshot of choosing options for installation](/assets/images/flash%20iso.png)

4. Plug in your flash drive and select it via list and click "Next":
![Screenshot of choosing your flash drive](/assets/images/select%20drive.png)

5. Wait till your Windows files will download:
![Screenshot of Installation Meadia downloading Windows files](/assets/images/downloading%20windows.png)
![Screenshot of Installation Meadia done](/assets/images/ready%20flash.png)

### 3. (OPTIONAL) Make your Windows a little less bloat

Microsoft made option to debloat your Windows a bit by creating answer file in your bootable flash drive: [Documentation](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/update-windows-settings-and-scripts-create-your-own-answer-file-sxs?view=windows-11).

1. Use the best tool(created by Christoph Schneegans) in your browser to create your answer file: [Link to answer file creation tool](https://schneegans.de/windows/unattend-generator/) Or just download/"use as import" mine answer file that i did with this tool where you get mostly debloated Windows and with "offline" Windows account: [My Answer File](/assets/autounattend.xml)

    Just read all the settings and select what you will need in your installation on your screen:

    ![Screenshot of the webtool](/assets/images/answer%20tool.png)

2. Download your answer file at the bottom of the page by clicking "Download .xml file":

    ![Screenshot of the tool's bottom](/assets/images/tools%20bottom.png)

3. Place your .xml file in your ready flash drive:

    ![Screenshot of flash drive explorer](/assets/images/flash%20explorer.png)


### 4. Windows installation

### WARNING: Make sure to preinstall drivers for your internet adapter on your flash drive

#### 1. Now enter your BIOS and select boot override page then select your flash and proceed to Windows install

### 5. You are done!