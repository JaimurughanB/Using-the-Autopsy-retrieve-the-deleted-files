# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
## 1. Copy Files to the Virtual Disk
 Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
 
 Create a new folder (Autospy) and copy images or files into it.
 
## 2. Delete the Files
Select any one or two images → Press Delete.

Empty the Recycle Bin to permanently delete them.\

## 3. Recover Deleted Files Using Autopsy

## Open Autopsy & Create a New Case

Launch Autopsy and Run as a administrator

Click Create New Case.

![image](https://github.com/user-attachments/assets/3bb1d7b2-79ab-4c0d-b69b-0517435b4f47)
Enter a Case Name (e.g., Autopsy1).

Choose a Case Folder location.

Click Next → Click Finish.

![image](https://github.com/user-attachments/assets/ebb8b3ce-e377-4388-81a0-a4962a721c27)

## Add the Virtual Disk as an Evidence Source
Click Add Data Source → Select Host

![image](https://github.com/user-attachments/assets/429a3311-3ea8-4de8-a839-0f76fa6d6d68)

Select Local Disk → next

![image](https://github.com/user-attachments/assets/39c1ae82-31c8-491a-acf5-408be50f1872)

Select Disk → Choose the VHD drive (Drive1)

![image](https://github.com/user-attachments/assets/4c92002e-67b5-42da-807c-8ff3ca4adcd1)

Click Next → Keep default settings → Click Finish.

Wait for Autopsy to process the disk.

## Recover Deleted Files

Go to File Views (left panel).

![image](https://github.com/user-attachments/assets/1ab45a03-4fcf-4c81-87b3-60bb61ec5ce6)

![image](https://github.com/user-attachments/assets/8b57a509-2f26-49e4-88e8-4de9715e02b3)

Click Deleted Files → Find your deleted images.

Right-click an image → Click Extract File.
![image](https://github.com/user-attachments/assets/459ea299-4200-4d20-a093-ed42b46934d2)

Select a folder to see the recovered files (e.g., C:\forensic).

Image is recovered successfully.



## OUTPUT:
## Folder before deleting the files
![image](https://github.com/user-attachments/assets/d3038b66-4099-4c05-9976-82c407a3c96f)

## Folder after deleting the files
![image](https://github.com/user-attachments/assets/dab3108f-1ed2-4085-b405-8d51687d1492)

## Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/578de1b5-166a-44c2-8c10-2c18bb4950b0)




## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
