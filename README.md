# Using-the-Autopsy-retrieve-the-deleted-files
### NAME: MOHAN S
### REGISTER NUMBER: 212223240094
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
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.

![Screenshot 2025-04-23 094100](https://github.com/user-attachments/assets/2cb93934-63b4-4436-ae63-8675eb88287b)




- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![Screenshot (22)](https://github.com/user-attachments/assets/2764336e-1ea9-4972-8a94-4dd1f733201d)



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![Screenshot (23)](https://github.com/user-attachments/assets/ed9bd564-98ae-4594-affa-d41a2b1aee17)



- Select **Local Disk** → **next** 
![Screenshot (24)](https://github.com/user-attachments/assets/bcb3336f-5329-4bee-9001-cdc51f660f66)



- Select Disk → **Choose the VHD drive (`Drive1`)**

![Screenshot (25)](https://github.com/user-attachments/assets/36ebe6bd-5613-4a98-a596-459a58405e8a)



- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
![Screenshot (27)](https://github.com/user-attachments/assets/8364b0e4-3a88-4c48-bf5c-ee0398443921)

![Screenshot (28)](https://github.com/user-attachments/assets/4d389e6e-8f81-47b8-b998-254ea4b1b82c)



- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![Screenshot (29)](https://github.com/user-attachments/assets/67d42ab1-a0b6-406e-84c5-efbdc224c66e)



- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot 2025-04-23 094009](https://github.com/user-attachments/assets/3536c01e-b369-4ccd-ab5c-34110a5489c9)



### Folder after deleting the files
![Screenshot 2025-04-23 111141](https://github.com/user-attachments/assets/2bb96478-0595-49e0-8f64-9f660d4df9b3)



### Folder after extracting the deleted images using autopsy
![Screenshot (31)](https://github.com/user-attachments/assets/b574756d-4f92-4e2d-a7b6-29be35ee33d3)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
