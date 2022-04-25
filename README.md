# Getting started with the Biochemistry Analyzer CCL-210 from China Care Medical 

The following is a guide to getting started with the equipment. It also helps to ensure that the software and the equipment are working as expected. 
In this tutorial, you can expect a step by step guide on how to:

- Prepare your working environment 
- Connect the equipment to your computer and other cables and pipes
- Setting up your Windows system 
- Installing the main Software and setting it up
- Run and print the first Test



| 🟥: Disclaimer          |
|:---------------------------|
| This post is not a User Manual Guide for Biochemistry Analyzer. But it can be used for first use or to check if the tool is working as expected. For a copy of the official manual guide, please check with your local supplier or get a copy [here](https://github.com/py-tony/China-Care-Full-Automated-Benchtop-Clinical-Blood-Chemistry-Biochemistry-Analyzer-/blob/main/1582d062ab01d45b284ed9752829c434.pdf)   |


## China Medical

China Care Medical supplies medical, Lab, and veterinary Equipment in many countries. The company is committed to making quality medical tools more accessible to people while saving them time and money. Customers can order any (available) medical equipment online. ---> [order online](https://www.chinacaremedical.com/) or get in touch with an approved [local facilitor](https://py-tony.netlify.app/contact_china_care.html#gsc.tab=0).

In this article, we'll take a closer look at the Biochemistry Analyzer CCL-210, one of the machines I had the privilege of installing in the Republic Democratic of Congo.

We assume some computer literacy and familiarity with medical tools to follow this article, but the author will do his best to be helpful. When it comes to computer concepts or technical concepts, we will try to hold each other's hands and climb the mountain together. However, we won't be teaching how to use a computer or how to hold a mouse.

## What is a Biochemistry Analyzer


![image](https://user-images.githubusercontent.com/55901714/164881338-4753afc2-ad3c-4062-bd7f-63228912b30a.png)

In simple terms the tools is designed to measure metabolites present in biological samples such as blood or urine.

The tedious part about getting human blood or other body fluid samples for testing is the actual analysis of each sample to test for anomalies. Traditionally, these tests were done manually by a human technologist who carefully examined each sample for results. Over time, however, it became apparent that the task takes too much time and effort, not allowing more than a few samples to be tested and analyzed every day. That is where the Biochemistry Analyzer intervine.


Also Known as a Full Automated Benchtop Clinical Blood Chemistry Biochemistry Analyzer CCL-210, is a tool used to measure the concentration of certain proteins, enzymes, electrolytes, metabolites, or even drugs in the provided samples of urine, blood, serum, plasma, or other body fluids. The machine consists of a tray where the samples are loaded to be tested. To reduce human error, the tool is controlled by software installed on a computer. You can get a quottation or a fully live explanation of the product by a local representative [here](https://py-tony.netlify.app/contact_china_care.html#gsc.tab=0) or order directly online at [www.chinacaremedical.com](https://www.chinacaremedical.com/).

If you're already have one and struggling with installations, you can get in touch with a local technician by filling up this [form](https://py-tony.netlify.app/contact_china_care.html#gsc.tab=0) or just by following this handy how-to guide.


## Prepare your environment

After buying your Full Auto Biochemistry Analyzer, you still need some other device and setup to get the tool working. 

| Prerequisites          |
|:---------------------------|
1. Computer has nine-pin serial port and is connected to the Machine 💯✔️
2. The Biochemistry Analyzer has been turned on and The tempture has reached 37 degree 💯✔️
3. Printer ordinary A4, A5 paper printers can be used Successfully connected and installed 💯✔️
4. Pure water (Can be barreled pure water or pure water with pure water mechanism) 💯✔️
5. A waste tank needs to be prepared and waste pipe connected successfully💯✔️
6. Experimental equipment (pipette gun, bullet reservoir) 💯✔️
7. Biochemical reagents on site (Biochemical reagents must be refrigerated at 2-8 degrees) 💯✔️


## Connecting the Auto Analyzer machine to your computer

https://user-images.githubusercontent.com/55901714/164883601-981ad10b-4503-4365-b261-74b651775aff.mp4

Make sure that your computer has a nine-pin serial port. We recommend that you do not connect to power source until all the cable connection step is done.

## Getting your System ready to install the software and run it

Here we're going to setup our Windows system to make it ready for the Biochemistry Analyzer software by: 

- Creating or making sure that we have a partition dedicated for our program
- Add the D: drive to Windows Firewall whitelist
- Change the Current System Language to Chinese(simplified) and change the time zone
- Download and copy the Auto Chemistry Analyzer [software] (Auto Chemistry Analyzer-210 (1) (1).rar) 
- Copy the software to the :D drive or the drive that is in th firewall whitelisted
- Unzip the file and Run the software

#### Create partition
We recommend that you create a dedicated partition for this software because the software won't work if the drive is not in the firewall whitelist. You can deactivate the security of the system or put the system drive (C:) in the whitelist but that will make your system vulnerable to virus attacks and we do not recommend doing that.

If you already have a D: drive skip this step. 

![image](https://user-images.githubusercontent.com/55901714/164978318-b4c44293-7a58-4c21-be1f-d3a626a2a8b9.png)





If you do not have a partitioned drive, please watch the tutorial below on how to partition a :C drive and create a :D drive.

[how to partition disk in windows 10](https://www.youtube.com/watch?v=wQQ-ohOdcZU)




### Add the D: or the partitioned drive to Windows Firewall whitelist 

From your desktop in the windows search box type Windows security select the first result ----> virus & threat protection ---> Manage settings ----> Under `Exclusions` type Add or remove exclusions ---> (accept if prompt for admin permissio) ---> 'Add an exclusion` ---> `Folder` ---> Navigate to the drive (partitioned) select it and `select folder` to confirm the entry. 

Congratulations, you just made your drive vulnerable 😊 

Demo:
![windows_whitelist](https://user-images.githubusercontent.com/55901714/164981728-9fd6cfbd-4149-41b8-9e39-7c94e64b4f6b.gif) 

Your system might be different from the one in the above example, feel free to search on google for your particular system.

From your desktop click on Start and 
- Change the Current System Language to Chinese(simplified) and change the time zone
- Download and copy the Auto Chemistry Analyzer [software] (Auto Chemistry Analyzer-210 (1) (1).rar) 
- Copy the software to the :D drive or the drive that is in th firewall whitelisted
- Unzip the file and Run the software


### Change the Current System Local Language (Unicode) to Chinese(simplified) 
- Why do we need to do this?
Unicode is a character encoding standard, developed by the Unicode Consortium, which defines a set of letters, numbers, and symbols that represent almost all of the written languages in the world. Its success in unifying character sets has led to widespread use in the creation of software [source](https://www.digitalcitizen.life/changing-display-language-used-non-unicode-programs/).


Check out this [tutorial](https://www.tenforums.com/tutorials/132050-change-system-locale-windows-10-a.html#:~:text=The%20system%20locale%20controls%20the,that%20do%20not%20support%20Unicode.) for a step by step guide.


From your Destop search in the search bar `control panel` ----> Go to `Clock and Region` ----> Go to `Region` ---> navigate to `Administrator` Tab on the top most bar ---> Click on `Change System Locale` ---> Under `Current System Locale`, drop down the list and select `Chinese (Simplified, China)` Click `OK` and Restart your computer.


### Download and copy the Auto Chemistry Analyzer [software](Auto Chemistry Analyzer-210 (1) (1).rar) in the partitioned drive

Now we're almost there. We need now to put the software in the drive that we just prepared, Unzip it and Run the Program.

#### Step one: 
Download the software [here](https://github.com/py-tony/China-Care-Full-Automated-Benchtop-Clinical-Blood-Chemistry-Biochemistry-Analyzer-/raw/main/Auto%20Chemistry%20Analyzer-210%20(1)%20(1).rar).

#### Step two
Copy the software to the :D drive or the drive that you just put in the firewall whitelist.

#### Step Three
Unzip or extract the file using any .rar or .zip file extrator you can [download a free winrar here](https://www.win-rar.com/predownload.html?&L=0)


Demo:
![copy_unzip](https://user-images.githubusercontent.com/55901714/164985769-461643ae-bcb1-4230-b892-7147e9d35c87.gif)


## Installing the main Software and setting it up



Make sure that all the cables and pipes are connected from and to the computer.

1. Computer has nine-pin serial port and is connected to the Machine 💯✔️
2. The Biochemistry Analyzer has been turned on and The tempture has reached 37 degree 💯✔️
3. Printer ordinary A4, A5 paper printers can be used Successfully connected and installed 💯✔️
4. Pure water (Can be barreled pure water or pure water with pure water mechanism) 💯✔️
5. A waste tank needs to be prepared and waste pipe connected successfully💯✔️
6. Experimental equipment (pipette gun, bullet reservoir) 💯✔️
7. Biochemical reagents on site (Biochemical reagents must be refrigerated at 2-8 degrees) 💯✔️



Open the folder that you just Extract and double click on the file named `MainSoft_V9.2.0.7.exe` or `MainSoft_V9.2.0.7`.

![image](https://user-images.githubusercontent.com/55901714/164986193-f735edf9-6ab3-40c7-b070-63a00430ab2a.png)


If you followed all the instructions above correctly the software should open up and prompt for password. Enter `123` in the password field and login.

![image](https://user-images.githubusercontent.com/55901714/164986311-1078ddd3-e3e3-4979-b6c1-56929603330f.png)

Congratulations! You've just made your computer ready for your Auto Biochemistry Analyzer software.

![image](https://user-images.githubusercontent.com/55901714/164986510-e7bf167a-9982-4353-b121-b7fff033f57a.png)


### Setup and Run your first test

Here we have a couple of things that we need to configure before running and printing our first test. Find the `Setting` Tab ![image](https://user-images.githubusercontent.com/55901714/164991014-835485ff-4f4e-4b32-a85c-fece393919e4.png) and enter the following basic informations:

⚠️ Make sure you press the `Modify` button to activate the text field. ![image](https://user-images.githubusercontent.com/55901714/164991286-0b7ddedf-a965-4975-896f-bff894cdf370.png) Located at the bottom part of the screen.



![image](https://user-images.githubusercontent.com/55901714/164991538-fdf97e97-83f4-44d3-a6a3-4a8488905c61.png)




#### Hospital Information
![image](https://user-images.githubusercontent.com/55901714/164991565-346893ca-95ca-41a7-8d07-7b02dd585da0.png)


 * Hospital Info
     * Enter basic information of your Hospital.
 * Department Info
     * Enter Basic Information of the related department example: Biochimie.
 * Physician Info
     * Enter Basic informatio about the Head Physician of the hospital.

### User Management
![image](https://user-images.githubusercontent.com/55901714/164992161-e62cfdf6-3705-4620-9381-602bf3022cfb.png)


* Password Editor
    * Here is where you get to modify the password of different Users.
    * On the left you get to modify the password of the current user.
    * On the right you get to change the current user (if you have multiple users registered.
* User Management
    * Here is where you get to register New Users. ⚠️ Make sure to press `New` on the bottom part of the screen to activate the text field ![image](https://user-images.githubusercontent.com/55901714/164992724-4fbd3a62-4f34-4c8c-bdc6-4acfc5a729af.png)
* Permission
    * Here is where you get to control what each registered User is allowed to do.
    * By default the Administrator have the right to do anything on the app.
    * If you want to experiment with the `Permission` feature, you need to Add an account of under `User Management`
    * If an account is registered (other then the Administrator account), It will appear here (`Permission`) on the left in red.
    * To modify the permission of an account or the task a particular user can perform on the App:
        * Highlight the account on the left it should be highlighted in red.
        * Navigate and get familiarised with different permissions.
        ![image](https://user-images.githubusercontent.com/55901714/164993411-12e87f4b-0606-466b-bd26-fd063b78cdcc.png)
* Workload Status
    * Once you have some tests setup and they will appear here. for now let us skip this part.

### Test Setup
* This where you will configure the sequence of your tests. For now let us skip this part.


### Setting the Printer

* Here is where you get to check if your printer is connected and working.
    * If your printer is connected and installed successfully, it will appear here under Current Printer.
    * If your printer supports only A4 paper format, change the page sizes.
        * Under Report Editor Locate Page Sizes, set it to A4 and `Save` the changes.
         ![printting_setting](https://user-images.githubusercontent.com/55901714/164994409-ef9bdd45-6543-4fc3-ac54-5d87e300cac0.gif
         
## First Test
Now that you've entered all the basic information and setup your printer, it's time to test if the equipement is working. First we need to enter some data and parameter to let the computer know what kind of test we want to do. For a demo we're going to use Glucose as our reagent for sugar level test.

⚠️ *The data that we're going to use are only for testing purpose. This is by no mean a trusted configuration for Glucose test. Feel free to enter your own data if you know what you're doing. Otherwise, seek help from qualified Physician or Laboratory assistant to help you with the measurements and units for different tests.*

### Reagent Parameter settings
Navigate to the `Reagent` Tab on the top most part of your app. ![image](https://user-images.githubusercontent.com/55901714/164995230-d85ece6d-d4bf-48d7-a9a9-af16550d1816.png)

Click on `New` and fill in the fields as shown bellow.

![image](https://user-images.githubusercontent.com/55901714/164996970-862e3ed8-c938-4746-9aa0-864660257e78.png)

### Calibration Setting

Navigate to the `Calibration` Tab on the top most part of your app. ![image](https://user-images.githubusercontent.com/55901714/164997376-bccd8621-ba76-4599-8b01-18e2dae89424.png)
Then go to `Calib Setup` ![image](https://user-images.githubusercontent.com/55901714/164997526-dee75891-99e0-4b73-b87f-22455b4ec983.png).

On the left under `Calib Solution List`, click `New`, enter any number or test as identifier of the calibration and hit `Save`
On your right under `Calib. Solution Concentrate` click `Modify` then double click on the concentrate field.

![image](https://user-images.githubusercontent.com/55901714/164997745-6cfb19a5-db6b-4482-8667-aa7a742d7090.png)

Demo:

![calib_setup](https://user-images.githubusercontent.com/55901714/164997760-dbdb2743-8bbd-4d3d-87a6-506c8a4a1d65.gif)


### Set Location of the Reagent on the Wheel

Now we need to set the location of the reagent on the to harmonize the flow of the machine. Pay close attention on the number we will select here and how we going to place the reagent and sample on the Wheel.

Navigate to the `Status` Tab on the top most part of your app. ![image](https://user-images.githubusercontent.com/55901714/164998045-2567f3f3-1356-424e-8b48-d4271d0d459d.png)
Then go to `Reagent Wheel` and find on the left side bottom part of the app `Reagent Position Setup` ![image](https://user-images.githubusercontent.com/55901714/164998185-4c0dbd17-b95b-408a-a4dc-c55e2e5b4153.png)

Click on `Reagent Position Setup` highlight our reagent by pressing `Gluc` on the right located under Reagent info. 


![reagent_wheel setup](https://user-images.githubusercontent.com/55901714/164998397-264858e1-618e-48d9-9990-1d020971fb34.gif)


### Request Calibration Test

Now we're on the final part of our mission. We're going to request the Calibration Test.
Navigate to the `Samp. Test.` Tab on the top most part of your app ![image](https://user-images.githubusercontent.com/55901714/164998825-0427435d-140a-44e1-8882-a3d1097435a5.png).
Then go to `Calibrated Req.`, highlight our Calib test under `Calib. Test List` by pressing on it.
On left bottom part of the app under `Calib Solution` check ✔️ the first Calib solution, click on the drop down icon 🔽 and select the calib solution number that you entered on the Calib solution setting (mine is 123).

Demo:
![sample_req](https://user-images.githubusercontent.com/55901714/164999317-3133c466-736b-42dc-a6db-45a7b7a96929.gif)


### Run the test and Print the Result

Last but not least. We're going to Run and Print our first Test.
Before we proceed let's do this boring but critical check:

1. Computer has nine-pin serial port and is connected to the Machine 💯✔️
2. The Biochemistry Analyzer has been turned on and The tempture has reached 37 degree 💯✔️
3. Printer ordinary A4, A5 paper printers can be used Successfully connected and installed 💯✔️
4. Pure water (Can be barreled pure water or pure water with pure water mechanism) 💯✔️
5. A waste tank needs to be prepared and waste pipe connected successfully💯✔️
6. Experimental equipment (pipette gun, bullet reservoir) 💯✔️
7. Biochemical reagents on site (Biochemical reagents must be refrigerated at 2-8 degrees) 💯✔️


Fill the Triangle shapped bottle with reagent and place it on the wheel number1 as shown on the pic bellow and place the sample tube or cup on the sample wheel number1 as shown bellow.


![wheel_sample_placement](https://user-images.githubusercontent.com/55901714/165000481-7f25a96e-316a-4c42-a8df-090002a72050.jpg)

#### Run

Navigate to the `Run` ![image](https://user-images.githubusercontent.com/55901714/165001279-d8fd1993-3333-4d65-9820-1ff7c154f030.png) select our test under `Test Stand By` and run the test by pressing `Run` located and the bottom right most part of the app.


#### Print
Once the test has finished, Navigate to the `Results` Tab ![image](https://user-images.githubusercontent.com/55901714/165001563-25d743bc-053a-4d32-9480-c37b8620f3a2.png).
Fill in the patient info, highlight the test under `Result Details` and print the test 


