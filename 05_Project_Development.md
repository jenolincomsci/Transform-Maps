# Project Development Phase

## Project Title
Import Data Using Transform Maps

## 1. Development Overview

The project is developed using ServiceNow Import Sets and Transform Maps to import external data and transfer it into the required target table.

## 2. Development Steps

### Step 1: Prepare Source Data
Prepare the required data in a CSV or Excel file with the necessary fields.
<img width="1366" height="519" alt="WhatsApp Image 2026-09-27 at 1 10 46 PM" src="https://github.com/user-attachments/assets/0db25871-0cc8-498f-a202-6ea0a58f121c" />




### Step 2: Create Data Source
Create a Data Source in ServiceNow and configure the source file for importing the data.
<img width="1366" height="515" alt="WhatsApp Image 2026-09-27 at 1 09 12 PM" src="https://github.com/user-attachments/assets/8b8baa7a-a83f-4840-94ea-620951b95478" />


### Step 3: Import the Data
Upload the source file and run the import process.
<img width="1366" height="521" alt="WhatsApp Image 2026-09-27 at 1 07 42 PM" src="https://github.com/user-attachments/assets/689b436a-9308-494d-aeca-595adb9ab0a8" />


### Step 4: Create Import Set
Create an Import Set to store the imported source data temporarily.
<img width="1366" height="525" alt="WhatsApp Image 2026-09-27 at 1 08 01 PM" src="https://github.com/user-attachments/assets/388a9c27-4e19-443e-8cfd-96b512deada4" />


### Step 5: Create Transform Map
Create a Transform Map and select the required source table and target table.
<img width="1366" height="510" alt="WhatsApp Image 2026-09-27 at 1 08 22 PM" src="https://github.com/user-attachments/assets/4aa84117-46fe-4a58-8c60-78ee2882c0c6" />


### Step 6: Configure Field Mapping
Map the source fields to their corresponding target fields.
<img width="1366" height="513" alt="WhatsApp Image 2026-09-27 at 1 08 44 PM" src="https://github.com/user-attachments/assets/0b18548c-238b-41d2-afa6-ec7b2b460108" />


Example:

| Source Field | Target Field |
|---|---|
| Name | Name |
| Email | Email |
| Department | Department |
| Location | Location |

### Step 7: Run Transformation
Run the Transform Map to transfer the data from the Import Set table to the target table.
<img width="1366" height="515" alt="WhatsApp Image 2026-09-27 at 1 09 12 PM" src="https://github.com/user-attachments/assets/5788f25a-5e86-45ba-b34a-a2ebe64dad41" />


### Step 8: Verify Records
Check the target table and verify that the records have been imported correctly.

## 3. Development Components

- Data Source
- Import Set
- Import Set Table
- Transform Map
- Field Maps
- Target Table

## 4. Expected Development Output

The source data should be successfully imported, transformed, and stored in the selected ServiceNow target table.

## 5. Development Verification

The imported records should be checked to ensure that:

- All required records are available.
- Source fields are mapped correctly.
- Target fields contain the expected values.
- No major transformation errors are present.

## 6. Conclusion

The development phase implements the complete data import process using ServiceNow Import Sets and Transform Maps. The developed process provides a structured way to import and transform external data into ServiceNow.
