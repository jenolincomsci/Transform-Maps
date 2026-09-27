# Project Testing Phase

## Project Title
Import Data Using Transform Maps

## 1. Testing Overview

The testing phase is performed to verify that the data is imported, transformed, and stored correctly in the ServiceNow target table.

## 2. Test Cases

| Test Case | Test Description | Expected Result | Status |
|---|---|---|---|
| TC01 | Upload the source data file | File should be uploaded successfully | Pass |
<img width="1366" height="515" alt="WhatsApp Image 2026-09-27 at 1 09 12 PM" src="https://github.com/user-attachments/assets/c10fafc6-af04-49b7-b4a8-3002e04640c3" />

| TC02 | Create Import Set | Import Set should be created successfully | Pass |
<img width="1366" height="525" alt="WhatsApp Image 2026-09-27 at 1 08 01 PM" src="https://github.com/user-attachments/assets/16f4ed66-a38c-43d2-9940-003050dc32f1" />

| TC03 | Import source records | Records should be imported into the Import Set table | Pass |
<img width="1366" height="521" alt="WhatsApp Image 2026-09-27 at 1 07 42 PM" src="https://github.com/user-attachments/assets/ebac8886-eab6-4f03-9e7a-6d89a652124f" />

| TC04 | Create Transform Map | Transform Map should be created successfully | Pass |
<img width="1366" height="530" alt="WhatsApp Image 2026-09-27 at 1 26 34 PM" src="https://github.com/user-attachments/assets/9ded45eb-aec5-4dd3-b62d-68c8b6c18c3b" />

| TC05 | Configure field mapping | Source fields should map to target fields correctly | Pass |
<img width="1366" height="510" alt="WhatsApp Image 2026-09-27 at 1 08 22 PM" src="https://github.com/user-attachments/assets/378c60f4-2a94-427e-ac23-32a92f784a05" />

| TC06 | Run transformation | Records should be transferred to the target table | Pass |
<img width="1365" height="515" alt="WhatsApp Image 2026-09-27 at 1 25 30 PM" src="https://github.com/user-attachments/assets/3aebd8c7-af9d-44c4-93c2-374eb4c7ad64" />

| TC07 | Verify target records | Imported records should contain correct values | Pass |
<img width="1366" height="530" alt="WhatsApp Image 2026-09-27 at 1 26 34 PM (1)" src="https://github.com/user-attachments/assets/26937ac0-42e3-4eef-8044-d2c555a980c0" />



## 3. Testing Process

1. Prepare the source data.
2. Upload the data into ServiceNow.
3. Verify the Import Set records.
4. Check the Transform Map configuration.
5. Verify all field mappings.
6. Run the transformation.
7. Open the target table.
8. Compare the target records with the source data.
9. Check for any transformation errors.

## 4. Expected Test Results

The source records should be successfully imported and transformed into the target table. The mapped fields should contain the correct values and the transformation should complete without unexpected errors.

## 5. Error Handling

If an error occurs during transformation:

- Check the source data.
- Verify the field mappings.
- Check the Transform Map configuration.
- Review the import and transformation logs.
- Correct the issue and run the transformation again.

## 6. Conclusion

Testing confirms that the Import Data Using Transform Maps process works as expected and that the imported records are correctly available in the ServiceNow target table.
