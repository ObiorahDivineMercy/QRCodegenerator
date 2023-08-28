# QRCodegenerator

<b>PROJECT TITLE<b> </br></br>
QRCodegenerator

<b>DESCRIPTION<b></br></br>
The QRCode Generator is a GUI program to generate QRCodes based on some user metrics. These metrics are the user's full name, email address, website address and phone number. Furthermore, the program asks the user to input the name of the file with the svg file extension. The current version is version 1.0 but more features will be added soon.
<b>USAGE</b></br></br>
<b>STEP 1:</b> When the application loads, you will see the Graphical User Interface (GUI) as shown below:</br></br>
![QRCode](https://github.com/ObiorahDivineMercy/QRCodegenerator/assets/143182629/9d0b5d5f-c630-49e1-956c-473668ba87a5)

<b>STEP 2:</b> Input your Full Name, Email Address, Website, and the name of the svg file in each field's respective textbox (See Figure 1 above)</br></br>
STEP 3: Click the Click to Generate button to generate the file in the current directory where the python file is executed from (Figure 2)</br></br>

<b>ERROR CORRECTION</b></br></br>
As with any good program, each input is checked first before  generating the QRCode.</br></br>
![errorcatcher](https://github.com/ObiorahDivineMercy/QRCodegenerator/assets/143182629/405bd37b-d8f1-4cca-9078-2bdc555a3183)

<b>VERSION UPDATE</b></br></br>
The version is QRCode Ver 1 and any update will be shown here.</br></br>
<b>DEPLOYMENT</b></br></br>
To run this file, make sure that python is installed (Using Python 3.9 or more) and press F5 using IDLE IDE. But any IDE like Visual Studio Code or any IDE will do.
To convert to an executable (.exe), you have two options: </br></br>
<b>STEP 1: First install pyinstaller via the command line or terminal by typing...pip install pyinstaller</br></br>
<b>STEP 2:</b> Type the following in the command line</br></br>
pyinstaller --onefile --windowed --add-data "xi.icon;" qrcodegenerator.py </br></br>
<b>STEP 3:</br></br> Allow pyinstaller to compile the file and add all the resources and dependencies needed to create the executable.</br></br>
<b>STEP 4:</b></br> Check the folder and run the exe in another computer. It will successfully run</br></br>
Alternatively (and even better option), you can use auto-py-to-exe to generate the executable. This normally opens a GUI for compiling your programs. First install auto-py-to-exe by typing the following in the commandline: pip install auto-py-to-exe and then follow the steps as shown below: </br></br>
![autopytoexe](https://github.com/ObiorahDivineMercy/QRCodegenerator/assets/143182629/17ba9296-b644-49a5-8e73-1c1efad8b4a2)

Notice that python39.dll was added. This will help run the program in older versions of Windows eg Windows 7, 8, 8.1 (probably they have not been updated for a long time. This will avoid generating errors such as the one shown in issues section). </br></br>
<b>ISSUES</b> </br></br>
Please note that your Windows Defender Antivirus (and some other antimalware programs) may block the application from running. This is a false positive error message. Kindly pause the protection for a while and run again.</br></br>
The dependency python39 must be added to avoid errors such as the one shown below:</br></br>
![autopytoexe](https://github.com/ObiorahDivineMercy/QRCodegenerator/assets/143182629/da738775-d54e-49cb-9f76-a103ce27422c)

The python39 is saved in the AppData folder. As shown in the image below:</br>

![python39 error](https://github.com/ObiorahDivineMercy/QRCodegenerator/assets/143182629/279dada1-8f0c-4a2d-b4be-0ab6127a38ef)</br></br>
![i](https://github.com/ObiorahDivineMercy/QRCodegenerator/assets/143182629/44c5cab7-c2ef-4dff-9ab8-542a9f355c7d)
