# Syntax & Soliloquies

## Technical Blog

# Michael A. Canfield
### mcanfield@student.sierracollege.edu

## Biography
I am a Double Major Criminal Justice/Computer Forensics student studying at Sierra College and CSU Sacramento.
My professional goal is to receive my Bachelor's Degree, obtain a GCFE Certification, and be commissioned into the United States Coast Guard.
My IT experience comes from my time volunteering aboard the Battleship IOWA Museum in the Port of Los Angeles, where I assisted in the development of the shipboard network infrastructure.

I live in Meadow Vista, CA with my wife, and enjoy working on construction and landscape projects in my spare time.
I am also a student pilot, and will be attempting my final practical examination soon!



# Post I - 08-27-2018

## How many computers are in the classroom?

Assuming that 'Computer' is defined as a physical device possessing a CPU, memory, and an operating system, there are an estimated 64 computers in the classroom. 
This number is derived from the 32 desktops, an estimated 1 cell phone per 26 occupants, and an estimated 6 personal laptops carried by students.



# Post II - 09/03/2018
## Skill 1.1

I chose to use the computer in Hanger F at the Auburn Municipal Airport. This machine is a Dell Inspiron laptop running Windows 7 Professional.

The primary users of this PC are the pilots who own the hangar. They are all current or former airline pilots who are accustomed to interacting with technology.
The PC is primarily used for flight planning, maintenance logging, and time tracking, and requires the ability to run fairly substantial charting programs such as ForeFlight.

The machine's technical specifications are as follows:

- Processor - Intel Core i5
- Storage   - 1TB SSD
- Memory    - 4 GB
- Graphics  - DirectX 10

These all exceed the hardware requirements for Windows 10, which are as follows:
    Processor - 1 GHz or Faster
    Storage   - 16 GB Free Space
    Memory    - 1 GB (2 GB for x64)
    Graphics  - DirectX 9

I would upgrade this machine using an in-place upgrade. I would choose this option due to the large number of important spreadsheets and other files (>500 GB) that are on the local machine's SSD. The effort required to transfer those files to another storage location, then to reimport them once a clean install was completed, makes an in-place upgrade the most logical option. Additionally, as this PC is not used for personal computing, the amount of bloatware present is limited. I did not use any Microsoft tools to make this determination.

I would likely choose to install Windows 10 Professional on this PC, as some of the documents contain information regarding financial partnerships that would be better secured with the added features included in the Professional version of the OS.



# Post III - 09-10-2018

## Since We Last Met - Recent Technology News 

BBC posted an article today detailing the extradition of Russian citizen Andrei Tyurin to the United States on federal hacking charges.
This incident is notable for its rarity, as foreign nationals have historically been safe from extradition on charges such as these. 
The crimes Tyurin is being charged with relate to the 2014 security breach of several major banks, principally J.P. Morgan Chase, resulting in the the personal information of nearly 80 Million Americans being compromised. 
U.S. Attorney Geoffrey Berman stated that the extradition represented a "Significant Milestone" in the legal fight against international cyber crime.

<https://www.bbc.com/news/technology-45472766>



# Post IV - 09-10-2018
## Skill 1.2

There are several reasons to use multiple partitions:

- Better organize your data
- Run different operating systems on one PC
- Reduce the threats of data loss
- More convenient for backup and restore
- More selective when encrypting drive
- Improve performance

**Steps to create a partition in Command Line:**

1. Open Command Prompt and type the diskpart command
2. To view the available disks type the list disk command
3. To select a disk to work with type the select disk command followed by the number of the disk you want to use
4. To create a new partition use the create partition command followed by the partition type and size
    Example: create partition primary size=1024
5. To assign a drive letter to the new partition use the assign letter command followed by the letter you wish to assign
    Example: assign letter = F
6. To format the new partition use the format command followed by the desired filesystem and the format type
    Example: format fs=ntfs quick

**Windows 10 Install Steps:**

1. Select preferred Language, Time Zone, and Keyboard Layout
2. Click 'Install Now'
3. Accept Windows 10 EULA and click 'Next'
4. Select Install Destination Drive & Create Initial Partitions (Optional)
5. Wait for Install to complete
6. Select Region
7. Confirm Keyboard Layout
8. Add Secondary Keyboard Layouts (Optional)
9. Sign in with Microsoft Account or Create Local Account
10. Select Cortana Settings
11. Select Privacy Settings

**Enabling Windows Features:**

To enable Windows Features go to Control Panel>Turn Windows Features On or Off and select the features you want to add.

# Post V - ??



# Post VI - 09-17-2018
## Skill 1.3

**Devices and Drivers**

1. Common Hardware Requiring Device Drivers:
    - Keyboard
    - Mouse
    - Speakers
    - Microphone
    - Network Interface Card
    - Printer
    - USB Input/Output
    - HDMI Output
    - Internal Storage Devices
    - External Storage Devices
    - Chipset        

2. External USB Drive was installed on Windows 10

3. Device Drivers Located and Current

4. Device Disabled - System Performance Unaffected
    Network Interface Card Disabled - Unable to connect to network

5. Updates Disabled over Metered Connections is used to avoid unwanted data usage

6. Rollback Performed using Device Properties

7. Disable Device Driver and examine system performance

# Post VII - 09-24-2018
## Windows 10 Virtualized Operating System

On September 24, 2018, Microsoft announced what it's calling the Windows Virtual Desktop (WVD). WVD will allow users to virtualize Windows 7 and 10, Office 365 ProPlus apps and other third-party applications by running them remotely in Azure virtual machines
Using WVD, customers will be able to provide remote desktop sessions with multiple users logged into the same Windows 10 or Windows Server virtual machine. They also can opt to virtualize the full desktop or individual Microsoft Store and/or line-of-business applications. The WVD service also supports full VDI with Windows 10 and Windows 7, Microsoft officials told Ars Technica. (Those wanting to virtualize Windows 7 after Microsoft support ends in January 2020 will be able to do so for three years without paying for Extended Security Updates.)
Licenses for WVD will be provided for no additional cost as part of Windows Enterprise and Education E3 and E5 subscriptions. The aforementioned Windows 10 Enterprise for Virtual Desktops edition won't be released as a separate version of Windows 10 at all.

# Post VIII - 09-24-2018
## Skill 1.4

**Configure Cortana**

To configure Cortana on a clean install of Windows 10, there are several tasks you need to complete. 

To set up the initial configuration, perform the following steps:
- Click the Start Menu, or press the Windows key
- Click All Apps
- Click Cortana
- Click Use Cortana
- Select Yes/No for Speech, Inking, and Typing Personalization options

To pin Cortana to the Taskbar, perform the following steps:
- Right-click the Taskbar
- Click Cortana
- Select from the Hidden, Show Icon, and Show Search Box options

To configure voice activation, perform the following steps:
- Press Windows + S to open Cortana
- Click the Notebook icon
- Click Settings
- Select On/Off on the Hey Cortana selector

To configure voiceprint recognition, perform the following steps:
- Press Windows + S to open Cortana
- Click the Notebook icon
- Click Settings
- Click Learn My Voice
- Click Start
- Follow instructions given by Cortana

**Configure Accessibility**

Ease of Access allows the user to configure most Accessibility options. These settings are designed to provide better options for users with learning disabilities, physical disabilities, or other impairments.

To open Ease of Access before logon, perform the following steps:
- Power on the PC
- Click to dismiss the Lock Screen
- Click Ease of Access icon in lower right corner

To open Ease of Access after logon, perform the following steps:
- After logon, search for and open Ease of Access from Start Menu

The following Accessibility settings can be configured from the Ease of Access window:
- Narrator
- Magnifier
- On-Screen Keyboard
- High Contrast
- Sticky Keys
- Filter Keys

To configure Narrator, select the desired setting from each of the following on-screen options:
- On/Off
- Start Automatically
- Choose Voice
- Speed/Pitch
- Intonation Pauses
- Voice Hints for Controls and Buttons
- Voice characters when typed
- Voice words when typed
- Lower volume of other apps
- Play Audio Cues
- Highlight Cursor
- Configure for Braille display (beta)

To configure Magnifier, select the desired setting from each of the following on-screen options:
- Follow Cursor/Narrator
- Select View




# Post IX - 10-01-2018
## What is UAC?

According to Microsoft.com, User Account Control (UAC) is a security feature of Windows which helps prevent unauthorized changes to the operating system. These changes can be initiated by applications, users, viruses or other forms of malware. User Account Control makes sure certain changes are made only with approval from the administrator. If the changes are not approved by the administrator, they are not executed, and Windows remains unchanged. It is as if nothing happened. UAC was first made available for Windows Vista, and since then it was improved with each new version of Windows.

Due to the apparent configuration of the Sierra College domain account, the user experience in regards to UAC is nearly identical on the Host and Virtual machines.



##Post X - 10-01-2018
###Skill 1.5

**Notes:**

LSDO
  -Local
  -Site
  -Domain
  -OU

Group Policy
  -Block Microsoft Accounts
  -Enforce Password Length
  -Disable Secure Desktop in UAC

# Post XI - 10-08-2018
## Software Bugs

**What is a software bug?**

    The term "Bug" as used in reference to a software issue is generally credited to US Navy RADM Grace Hopper, a pioneer Computer Scientist working with the Harvard Mk II computer.
    RADM Hopper was investigating a malfunction with the computer's systems when she discovered that they were the result of a moth who had caused a short in the electrical system.

    Today , a software bug refers an error, flaw, failure or fault in a computer program or system that causes it to produce an incorrect or unexpected result, or to behave in unintended ways.

**Windows 10 1809 Build Software Bug**

    The following is an excerpt from Microsoft's statement regarding the major bug found in Windows 10 1809 Build:

    The Windows 10 October 2018 Update was made available last Tuesday and was due to begin rolling out automatically from tomorrow. However, on Saturday, Microsoft announced it had "paused" the rollout, removing the ability for general users to receive the update manually.
    Microsoft's decision is in response to a growing number of complaints from users who say the update deleted files in their user Documents and Photos folders — in some instances resulting in the loss of many thousands of files dating back years.
    At present there is no indication as to when the rollout of the update will continue, with Microsoft simply stating: "We will provide  an update when we resume rolling out the Windows 10 October 2018 Update to customers".

# Post XII - 10-22-2018
## Skill 2.2

You have a new desktop running Windows 10. However, you try to copy your file repository and find out that you do not have enough disk space. 
You have 400 GB of free disk space on your C drive and you have 3 smaller 500 GB drives. What can you do?

In this scenario, I would make use of the Storage Spaces tool to create a larger Virtual Drive from the four smaller physical drives. Microsoft provides the following steps to implement this solution:
- Add or connect the drives that you want to group together with Storage Spaces.
- Go to the taskbar, type Storage Spaces in the search box, and select Storage Spaces from the list of search results.
- Select Create a new pool and storage space.
- Select the drives you want to add to the new storage space, and then select Create pool.
- Give the drive a name and letter, and then choose a layout. Two-way mirror, Three-way mirror, and Parity can help protect the files in the storage space from drive failure.
- Enter the maximum size the storage space can reach, and then select Create storage space. 

You create a new storage pool for the following disks on your Windows 10 computer:
- Serial ATA (SATA): 1 TB
- Serial Attached SCSI (SAS): 1 TB
SATA and SAS are two different types of drives with different connectors/interfaces.
What is the maximum size you can allocate for your new storage space?

A 1 TB SATA Drive can be used to create a storage capacity of up to 2 TB.
A 1 TB SCSI Drive can also be used to create a storage capacity of up to 2 TB.
Therefore, by combining the two together using Storage Spaces, we can create a storage space with a maximum size of 4 TB.

# Post XIII - 10-29-2018
## Skill 2.3

**NetLab 9 Questions:**

1. How many printer devices are initially installed on the machine?

          3

2. How many printer devices are installed after Lab Part 2?

          4

3. What is the title of the window that appears in Lab Part 3?

         Save Print Output As

4. What extension is assigned to the Printed File document?

          .prn

5. Besides the original message, what else is displayed in the .prn file?

          Header displaying File Name
          Footer displaying Page Number

6. Which device becomes the default print device after the Virtual Printer is removed?

          Microsoft Print to PDF


**NetLab 10 Questions:**

1.1. How many printer devices are initially installed on the machine?

          3

2. How many printer devices are installed after Lab Part 2?

          4

3. What is displayed in the device description after Lab Part 3?

          Printer Sharing Status

4. How many printer devices are initially installed on PC1?

          3

5. How many printer devices are installed on PC1 after Lab Part 4?

          4

6. What is the title of the window that appears in Lab Part 4.1?

         Save Print Output As

7. Did the file save to the desktop?

          Yes


**NetLab 12 Questions:**

1. What type of account was created for the TEST User account? What benefits are provided by an Administrator Level Account?

          Standard User Account
          Administrator Accounts grant the user elevated privileges to make changes to the system

2. Who is the folder initially shared with?

          Student, the owner

3. Which 3 User Accounts can the folder be shared with?

          Student, TEST, and Everyone

4. Which two accounts are listed?

          Student & TEST

5. What message appears? Why is the TEST user unable to alter the file?

          Access is Denied
          The TEST User does not have write privileges


# Post XIV - 11-04-2018
## Skill 2.4

According to the Microsoft Support Website, you can use Group Policy to distribute computer programs by using the following methods:

**Assigning Software:**

You can assign a program distribution to users or computers. If you assign the program to a user, it is installed when the user logs on to the computer. When the user first runs the program, the installation is completed. If you assign the program to a computer, it is installed when the computer starts, and it is available to all users who log on to the computer. When a user first runs the program, the installation is completed.

**Publishing Software**

You can publish a program distribution to users. When the user logs on to the computer, the published program is displayed in the Add or Remove Programs dialog box, and it can be installed from there.

In light of this information, I would use GPOs to push the appropriate software to each user group, assigning the required software packages and publishing the optional software packages for selective installation.


# Post XV - 11-12-2018
## kill 2.5

**NetLab 7 Questions:**

What is the most likely reason that Remote Desktop is unable to connect to the remote computer?

- As we can verify that the remote computer is powered on, and is connected to the network, the most likely reason that the connection attempt failed is that remote access to the computer is not enabled.

After the Remote Desktop successfully connects, what is displayed on the top of the
screen that identifies PC1 is being used?

- The remote computer's IP Address

While remotely connected to PC1, click on the Start Menu and select the Power icon.
What option(s) is listed there at this time?

- Disconnect

Why is it necessary to login to the PC1 machine again when accessing it locally?

- As Windows cannot support multiple simultaneous users like UNIX, the Local User is signed out when the Remote User connects to the computer.

Is the file created by PC2 on the desktop?

- Yes

What are some benefits of using the Remote Desktop Connection?

- It allows support technicians or administrators to access and troubleshoot or configure a computer without having to be physically present at that computer's location.


**Additional Questions**

Joe is a new IT Director who is tasked with making sure his Windows 10 computer users can be assisted remotely. On his first day at the company, Joe was told that the Remote Assistance feature was not working for users after a new firewall was installed. What could be causing the problem and how should it be addressed?

The Network Administrators who installed and configured the new firewall likely chose to block TCP Port 3389, the port generally used for RDP Access, to prevent unauthorized computers from connecting remotely and compromising company assets. Joe needs to create a firewall exception for packets from authorized Remote Assistance machines to be allowed through Port 3389 or a custom RDP Port.

You are an administrator at the Contoso Corporation. You have a 12-person help desk that supports about 10,000 users spread out over a 5-building campus. You don’t have enough people to provide support staff visits to a user who is having problems. Describe the actions you can take to support your company users.

You can use Remote Assistance so that your support staff can connect to a computer remotely and can interact with the user's session. To use Remote Assistance, users will call the help desk. The Help Desk can then walk a user through in creating an invitation, to be sent to the user via email. After getting the password from the user, you can connect to the user's session and help the user.


# Post XVI - 11-12-2018
## Skill 3.1

**NetLab 13 Questions:**

Why is it beneficial to leave the Allow scheduled maintenance to wake up my computer
at the schedule time option check-marked?

- If this box is not checked, the user will have to manually wake up the computer at the scheduled time in order for the maintenance to proceed as intended. 

After Start Maintenance has completed, what message is shown next to Automatic
Maintenance?

- Action Not Needed

What would occur if the Value data field used a value of 0?

- The Boolean State of the DWORD would be set to False

**Additional Questions**

You are an IT manager and would like to use a virtual machine to keep up to date on the latest development in Windows 10 and access the preview builds.  How would you go about doing this?

According to Microsoft, you can run Insider Preview builds as a virtual machine in Hyper-V. This option enables you to run Insider Preview builds without changing the Windows 10 production build already running on a PC.

As an IT manager, one of the departments you support is Physical Plant Operations.  They use a specialized application to run power generators that does not need access to the Internet or require any operating software updates.  Which branch of Windows 10 will you recommend for use by the Physical Plant Operations department?  Why?

I would recommend using Windows 10 IoT for this implementation. According to Microsoft, Windows 10 IoT Enterprise is a full version of Windows 10 that delivers enterprise manageability and security to IoT solutions. Windows 10 IoT Enterprise shares all the benefits of the world-wide Windows ecosystem. It is a binary equivalent to Windows 10 Enterprise, so you can use the same familiar development and management tools as client PCs and laptops.

As an IT manager, you have developed a custom image of Windows 10 that is deployed to all general users.  You do not want the users to be able to install additional software, including applications found in the Windows Store.  How could you prevent users from installing apps from the Windows Store?

I would accomplish this using the Windows AppLocker feature. Windows AppLocker was introduced in Windows 7 and includes some new features in Windows 8/10. With AppLocker, an administrator can block or allow certain users or user groups from installing or using certain applications using blacklisting or whitelisting rules.











































