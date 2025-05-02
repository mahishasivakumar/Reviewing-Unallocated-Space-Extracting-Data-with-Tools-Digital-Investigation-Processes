# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
### Reg no:212222040095
### Name: Mahisha S
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage

```
lsblk
```
````
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
````
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```


## OUTPUT:

![Screenshot 2025-05-02 213638](https://github.com/user-attachments/assets/f1dd9dd7-9ac8-45a7-98be-a46e60b76891)


![Screenshot 2025-05-02 213704](https://github.com/user-attachments/assets/fa007dbf-e152-4433-bca5-37eb366cdc0b)


![Screenshot 2025-05-02 213833](https://github.com/user-attachments/assets/5ea1840e-de20-4bd3-ba70-33fcbadd59a4)


![Screenshot 2025-05-02 213900](https://github.com/user-attachments/assets/4d5f5b5f-4353-4943-81bf-a42e30c9b8a7)


![Screenshot 2025-05-02 213925](https://github.com/user-attachments/assets/29b595aa-7dd0-44f7-849e-cbd6d871f2b0)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

