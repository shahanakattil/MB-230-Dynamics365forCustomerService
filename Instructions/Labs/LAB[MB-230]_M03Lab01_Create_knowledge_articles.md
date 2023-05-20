# Practice Lab 6 – Knowledge management

## Scenario

As a customer care coordinator at City Power & Light, you are responsible for instructing the customer service team and providing them with troubleshooting articles to support case resolution. You need to create a knowledge article within Dynamics 365 for Customer Service. In this lab, you will create a knowledge article, walk through the publishing process and then revise that article.

## Exercise 1 – Knowledge Management

In this exercise, you will create, approve, publish, and revise an internal Knowledge Article for missing parts.

### Task 1 – Create Internal Article

In this task, you will create an internal Knowledge Article for missing parts.

1.  Open the **Customer Service Hub** app.

1.  Click on **Home** at the top of the left-hand side navigation.

1.  Click on **Knowledge Articles** in the **Knowledge** section.

1.  Click **+ New**.

1.  Enter **odl_user_DID_Missing_Parts** for **Title**, enter **missing, parts** for **Keywords** and click **Save**.

    ![](../images/knowledge.png)

1.  Go to the **Content** area and make sure you have the **Designer** tab selected.

1.  Type **Purpose & Scope**.

1. Click on the **Paragraph Format** selector and select **Heading 2**. This option will only appear if your screen is fully expanded.

    ![](../images/Knowledge-management-1.png)

1. Hit the **Enter** key to start a new line. The **Format Selector** should change back to **Normal**.

1. Type the paragraph below.

    Use procedure below to resolve Phone call cases that are related to missing parts.

1. Hit the **Enter** key to start a new line.

1. Click on the **Paragraph Format** selector and select **Heading 2**.

1. Type **Procedure**.

1. Hit the **Enter** key to start a new line.

1. Go to the ribbon and click **Insert/Remove Numbered List**. This action will insert numbered list.

1. Provide the steps below.

    1.  Get Order Number for Customer.
    2.  Locate Order record.
    3.  Locate the product in question and open it.
    4.  Is the product the Customer received listed?
    5.  If yes, Send the Customer a replacement order and a return label.
    6.  If no, escalate case.

    ![](../images/h2.png)

1. Click **Save**.

1. Go to the **Business Process Flow** and click on the **Author** stage.

1. Select **Maintenance** for **Article Subject**, check the **Mark for Review** checkbox, and click **Next Stage**.

    ![](../images/Knowledge-management-2.png)
    
> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

### Task 2 – Approve and Publish Knowledge Article

In this task, you will assume the role of the Knowledge Article Approver and Approve the Knowledge Article you created, and then publish it.

1.  Go to the **Business process flow** and click on the **Review** stage.

1.  Select **Approved** for **Review**.

1.  Click **OK**.

1.  Go to the **Business process flow** and click on the **Review** stage.

1.  Click **Next Stage**.

1.  Click on the **Publish** stage.

1.  Check the **Set Product Associations** checkbox and click **Finish**.

    ![](../images/Knowledge-management-3.png)

1.  Go to the command bar and click **Publish**. You may need to click the ellipsis to see it.

1.  Select **Now** for **Publish**, **Published** for **Published Status**, and click **Publish**. Do NOT navigate away from this page.

    ![](../images/Knowledge-management-4.png)

### Task 3 – Revise Knowledge Article

In this task, you will change step 6 of the Knowledge Article you created from Escalate Case to Assign to Manager, and then you will revise the Knowledge
Article.

1.  Make sure you still have the Knowledge Article you created opened.

1.  Click **Create minor version** from the command bar. You may need to click the ellipsis to see this

    ![](../images/Knowledge-management-5.png)

1.  Click **OK**.

1.  Go to the **Content** section.

1.  Replace step **6** of the **Procedure** from **If no, escalate case** to **If no, assign to manager**.

1.  Click **Save**.

    ![](../images/Knowledge-management-6.png)

1.  Click **Approve**. You may need to click the ellipsis to see this. Click **OK**.

    ![](../images/Knowledge-management-7.png)

1.  Click **Publish**.

    ![](../images/publish.png)

1. Select **Now** and click **Publish** again.

1. Click on **Knowledge Articles** in the **Knowledge** section.

1. You should find the new version of the **Missing Parts** article in the **My Active Articles** view but not the old version.

    ![](../images/Knowledge-management-8.png)

1. Change the view to **Archived Articles**. You should find the old version of the **Missing Parts** article in this view.

    ![](../images/Knowledge-management-9.png)
    
> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

**Result:** You have successfully created the Knowledge Management and approved and publish knowledge article in Dyamic 365 customer services. 
