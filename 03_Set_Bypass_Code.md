# Task 3: Create Bypass Code for User  

As an IT administrator, you often have the responsibility of assisting users with their access needs on the fly. In this task, you'll address a common scenario where the user you created earlier has left their mobile device at home and needs temporary access to company resources. Management has authorized providing the user with a bypass code to help them gain access to protected applications. You will generate a **single-use bypass code** that will expire in **3 hours**.  

## **1. Create Bypass Code**  
Navigate to the **Duo Admin API** folder >> **Users** >> **Create Bypass Codes for Users**  

1. Go to the **Params** tab and configure the following parameters:  
   - **count**: `1` (Generate a single bypass code)  
   - **valid_secs**: `10800` (Set expiration to 3 hours)  
2. Save the changes.

![Alt Text](imgages/create_bypass_code.png)

[Continue to Next Task](04_Pull_Bypass_Report.md)  
