# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="862" height="544" alt="image" src="https://github.com/user-attachments/assets/10e38735-4a09-4a86-925e-649d30efa8a1" />
<img width="854" height="537" alt="image" src="https://github.com/user-attachments/assets/7c64d6c5-5e42-47c8-bca0-06a7cbcf8f28" />
<img width="865" height="539" alt="image" src="https://github.com/user-attachments/assets/422acaf8-dcbc-4337-94c1-af4864dac43d" />
<img width="857" height="542" alt="image" src="https://github.com/user-attachments/assets/d1398809-a3e4-4fb3-9e37-14a64b0108a3" />
<img width="858" height="534" alt="image" src="https://github.com/user-attachments/assets/14ceb152-8f95-411a-8ec3-d1be03c2e991" />
<img width="1534" height="805" alt="WhatsApp Image 2026-11-02 at 12 41 34 PM" src="https://github.com/user-attachments/assets/32540a06-b37c-405e-8c05-f2483ddcd6fe" />
<img width="1535" height="821" alt="WhatsApp Image 2026-11-02 at 12 36 35 PM" src="https://github.com/user-attachments/assets/dfb32aa0-39a2-4934-ad57-b9e12d005c17" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
