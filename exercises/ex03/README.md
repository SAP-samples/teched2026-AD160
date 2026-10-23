[Home - AD160 - Build apps and web APIs with ABAP Cloud using agentic AI](../../README.md)

# Exercise 3: Generate a RAP UI Service and Preview the Travel App with ADT MCP Tools

## Introduction

In this exercise, you will publish the local service endpoint of your OData V4 service binding and open the **Preview** in your default browser, to see the running Travel application.

---

### Exercises

- [3.1 - Publish the RAP UI Service](#exercise-31-publish-the-rap-ui-service)
- [3.2 - Preview the Travel App in the Browser](#exercise-32-preview-the-travel-app-in-the-browser)
- [Summary & Next Exercise](#summary--next-exercise)

> ℹ️ **Reminder**: Don't forget to replace all occurrences of the placeholder **'###'** with your group ID in the exercise steps below.

---

## Exercise 3.1: Publish the RAP UI Service
[^Top of page](#)

> Publish the local service endpoint of the service binding **'ZUI_TRAVEL_O4###'** to make the OData service available for preview and consumption.

<details>
  <summary>🔵 Click to expand!</summary>

1. Open the service binding using **'Ctrl+Shift+A'** and search for **'ZUI_TRAVEL_O4###'**. 

2. Enter *'#type:SRVB'* and select the entry **Service Binding** (SRVB).

![Display of the type filter](images/ex03_type_srvb_open.png)

3. Click the **Publish** code lens on top in the editor.

   > ℹ️ The "Publish" action registers a local service endpoint that allows the  preview and external consumers to discover the service.  

   ![Display of the generated service binding in the structure of the ABAP package in the Explorer](images/ex03_service_binding_structure_package.png)

   ![Publish Service binding published](images/ex03_publish_service_binding.png)

5. Wait for the publishing to be completed. 

   > ✅ You should see on the bottom _Publish/unpublish action in progress_.

      ![Status information about the publishin process in the primary side bar on the bottom left](images/ex03_execution_publishing_status.png)

</details>

---

## Exercise 3.2: Preview the Travel App in the Browser
[^Top of page](#)

> Preview the app for the travel entity in your default browser.

<details>
  <summary>🔵 Click to expand!</summary>

1. Open your service binding **'ZUI_TRAVEL_O4###'** and click the **Preview** code lens in the source code.

   ![Service binding preview](images/ex03_service_binding.png)

2. In the dialog to be opened, select the 'Travel' entity. 
   
   ![Select entity](images/ex03_select_entity.png)

3. In the dialog to be opened of you operating system, choose **Open** to confirm opening the link in your default browser.

   ![Windows dialog to open the app in the default browser ](images/ex03_preview_travel_selection_entity_open_browser.png)

   You default browser is opened and displays the **Preview** for your **Travel** application.

3. Try creating a new 'Travel' entity as follows:  
   a. Click **Create** and enter some fields, such as **Destination**, **Starting Date**, **End Date**.  
   b. Fill in **Agency ID** and **Customer ID** (Note: Use any valid IDs from the DMO flight reference data, e.g., '070001' for Agency, '000001' for Customer).  
   c. Confirm with **Save**.

   > ✅ If you can create and save a Travel entry, the app is working correctly!

</details>

---

## Summary & Next Exercise
[^Top of page](#)

Now that you've:
- Published the local service endpoint of the service binding **'ZUI_TRAVEL_O4###'**
- Opened and tested the preview of the app in the browser
- Created a test travel entry to verify the RAP UI service is working

You can continue with the next exercise — **[Exercise 4: Add a Validation](../ex04/README.md)**

---
