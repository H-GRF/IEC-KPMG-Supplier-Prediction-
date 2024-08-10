# IEC-KPMG-Supplier-Prediction

**Overview:**
Welcome to the IEC Algeria Data Cup - "KPMG Supplier Prediction," a thrilling machine learning competition organized by the student club "IEC" to showcase their data science and machine learning skills.

**Objective:**
The goal is to help the company Okkla better manage its finances by predicting the suppliers they should work with in the upcoming three months (October 1, 2023 - December 31, 2023). Participants will analyze and clean datasets containing information such as purchase orders, ordered items, suppliers, etc., and use various techniques to build a predictive model.

**Evaluation:**
Submissions will be evaluated based on the accuracy of predicting the suppliers Okkla should collaborate with for the upcoming three months. The main evaluation metric will be accuracy, which measures the proportion of correct predictions.

**Submission File:**
Participants must submit predictions for each pair ID = (Purchasing_Document_Number, Item_Number_of_Purchasing_Document), predicting the Account_Number_of_Vendor_or_Creditor. The submission file should maintain the exact format:
```
ID,Account_Number_of_Vendor_or_Creditor
4400010190_10,0
4500171069_10,0
4210140249_20,0
```

**Dataset Description:**
The provided dataset includes several files:
- **train.csv**: Contains information about Okkla's past orders (order date, total amount, material, etc.).
- **test.csv**
- **simplesubmission.csv**
- **suppliers.csv**: Includes details about suppliers, such as account numbers and addresses.

**Key Columns:**
- **Account_Number_of_Vendor_or_Creditor:** Unique identifier for suppliers/creditors.
- **Purchasing_Document_Number:** Unique ID for purchase documents.
- **Item_Number_of_Purchasing_Document:** Number of the item in the purchase document.
- **Is_the_order_deleted:** Indicates if the order was deleted (X for yes, empty otherwise).
- **Purchasing_Document_Item_Date:** Date when a purchase was confirmed.
- **Material_Number:** Unique identifier for materials/products.
- **Account_Assignment_Category:** Category of the organization from which the purchase was made.
- **Created_On:** Date the material was created in the system.
- **Net_Weight:** Net weight of the material.

**Suppliers Table:**
- **Account_Number_of_Vendor_or_Creditor:** Unique account number for suppliers/creditors.
- **Country_Key:** Country code associated with the supplier.
- **Name_1:** Name associated with the supplier/creditor.
- **City:** City where the supplier is located.
- **Central_Deletion_Flag_for_Master_Record:** Indicates if the supplier's record is marked for deletion.
- **Indicator:_Is_the_account_a_one-time_account?:** Specifies if the account is used for a one-time transaction.


This competition challenges participants to predict future supplier collaborations using historical data, focusing on the accuracy of predictions.
