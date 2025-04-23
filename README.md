# Analysis-of-the-Disk-Structure-using-Sleuth-Kit
## AIM:
To analyze the disk structure of a given disk image using Sleuth Kit tools in Kali Linux.

## DESIGN STEPS:
### Step 1:
Obtain or create a disk image file (e.g., disk.dd) to analyze. Open the terminal in Kali Linux.

### Step 2:
Use Sleuth Kit tools like mmls, fsstat, and fls to examine the partition layout, file system details, and file listing.

### Step 3:
Interpret the output of the tools to understand the disk structure, including partitions, sectors, and files.

## PROGRAM:
Sleuth Kit Disk Analysis Commands

✅ Option 1: Create a Sample Disk Image (for Testing)

Let’s create a 10MB blank disk image and simulate file system activity:

```
cd ~/Downloads

# Step 1: Create an empty disk image
dd if=/dev/zero of=disk.dd bs=1M count=10

# Step 2: Format it with a file system (like FAT32)
mkfs.vfat disk.dd

```

## OUTPUT:
Disk Structure Analysis Results

![img 1](https://github.com/user-attachments/assets/ca7dbafe-7cbd-4e2b-a7b1-78d3b3298460)

**Create Disk**

![image](https://github.com/user-attachments/assets/f66c5abd-c6e2-47c0-876f-c24cc670c2d4)

![image](https://github.com/user-attachments/assets/b430e432-25b8-455a-8134-fbaaa0742d64)

![image](https://github.com/user-attachments/assets/4ce18692-1b21-4852-85a5-291d90f56bfe)

![image](https://github.com/user-attachments/assets/73d76474-7e69-4f31-aced-44b499898e20)

![image](https://github.com/user-attachments/assets/a99c6da6-ea10-41c5-885e-8e15e7471f99)






## RESULT:
The analysis was performed successfully using Sleuth Kit, and the disk structure was understood in detail.
