# Practice Lab 5 – Entitlements and SLAs

## Scenario

As a customer service manager at City Power & Light, you need to create entitlements and entitlement templates to manage complex service offerings and guide your team in processing cases from various channels. In this lab, you will create an entitlement with entitlement channels. You will also create an entitlement template and create an entitlement from the template.

## Exercise 1 – Entitlements

In this exercise, you will create an entitlement for your user, this entitlement will allow you to create 50 cases through the Email channel, 30 Cases through the Web channel, and 10 Cases each for Twitter and Facebook channels.

### Task 1 – Create Entitlement

1.  Click on the **Customer Service Hub** app from the top and select **Customer service admin**.

    ![](../images/Customer-service-admin-1.png)
    
1.  Using the navigation on the left, select **Service Team** under **Operations**.

1.  Select **Manage** next to **Entitlements**.

    ![](../images/manage-1.png)

1.  Click **+ New** located on the command bar.

1.  Enter **odl_user_DID_Entitlement 1** for **Name**, select the account you created for **odl_user_DID_Relecloud** in the earlier lab for **Primary Customer**, select today's date for **Start Date**, and select a month from today for **End Date**.

1.  Select **Yes** for **Restrict based on entitlement terms**.

    ![](../images/Entitlement-2.png)

1.Under **ENTITLEMENT TERMS** select **Number of Cases** for **Allocation Type**, select **Case Creation** for **Decrease Remaining On**, and enter **100** for **Total Terms**.

1.  Click **Save**. DO NOT navigate away from the Entitlement form.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

### Task 2 – Add Channels to the entitlement

In this task, you will add entitlement channels to the default entitlement and then activate the entitlement.

1.  In the **Entitlement Channel** section of the Entitlement form, click on the ellipsis (...) and select **+ New Entitlement Channel**.

    ![](../images/new-1.png)

2.  Select **Email** for **Name**, enter **50** for **Total Terms** and click **Save & Close**.

    ![](../images/email.png)

3.  Click on the ellipsis button and select **+ New Entitlement Channel**.

4.  Select **Web** for **Name**, enter **30** for **Total Terms** and click **Save and Close**.

5.  Click on the ellipsis button and select **+ New Entitlement Channel**.

6.  Select **Facebook** for **Name**, enter **10** for **Total Terms** and click **Save and Close**.

7.  Click on the ellipsis button and select **+ New Entitlement Channel**.

8.  Select **Twitter** for **Name**, enter **10** for **Total Terms** and click **Save and Close**.

9.  Click on the ellipsis button and select **+ New Entitlement Channel**.

10. Select **Phone** for **Name**, enter **0** for **Total Terms** and click **Save and Close**.

11. Click on the ellipsis button and select **+ New Entitlement Channel**.

12. Select **IoT** for **Name**, enter **0** for **Total Terms** and click **Save and Close**.

    ![](../images/activate.png)

13. Click **Activate**.

14. Click **Activate**.

15. Click **Set as Default**.

16. Click **Confirm**.

### Task 3 – Test the Entitlement

In this task, you will test the default entitlement for Relecloud.

1.  Switch back to the **Customer service Hub** tab.

1.  Click on **Home** at the top of the left-hand side navigation.

2.  Click on **Cases** in the **Service** section of the sitemap.

3.  Click **+ New Case**.

4.  Enter **odl_user_DID_Audio_System_Setup_Issues** for **Case Title**, select the **odl_user_DID_Relecloud** account you created in the earlier lab for **Customer**, select **Email** for **Origin** and click **Save & Close**. The entitlement should be applied automatically.

    ![](../images/newcase1.png)

5.  Click **+ New Case**.

6. Enter **odl_user_DID_Defective Speaker** for **Case Title**, select the **odl_user_DID_Relecloud** account you created in the earlier lab for **Customer**, select **Facebook** for **Origin**, select the **odl_user_DID_Entitlement 1** record you created for **Entitlement** and click **Save & Close**.

    ![](../images/newcase2.png)

7.  Click **+ New Case**.

8.  Enter **odl_user_DID_Product_Query** for **Case Title**, select the **odl_user_DID_Relecloud** account you created in the earlier lab for **Customer**, select **Phone** for **Origin**, select the **odl_user_DID_Entitlement 1** record you created for **Entitlement** and click **Save**.

    ![](../images/newcase3.png)

9. The following message will be displayed, *You can't create a case for this entitlement because there are no available terms.*

    ![](../images/error.png)

10. Click **OK**.

11. Scroll to the **Entitlement** field and click on the **odl_user_DID_Entitlement_1**. Click **Discard changes**.

12. Switch back to the **Customer service admin** page opened in the browser and click on the **odl_user_DID_Entitlement _1** created and refresh the page.

12. Go to the **Entitlement Terms** section and make sure you have **98 Remaining Terms**.

13. Go to the **Entitlement Channel** sub-grid and make sure you have **49 Remaining Terms** for **Email**, **9 Remaining Terms** for **Facebook**, **10 Remaining Terms** for **Twitter**, and **30 Remaining Terms** for **Web**.

    ![](../images/Entitlement-4.png)
    
> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

## Exercise 2 – Entitlement Templates

In this exercise, you will create an entitlement template that will have 20 free terms and the customer will be able to select the channel they prefer during the entitlement creation.

### Task 1 – Create Entitlement Templates

In this task, you will create an entitlement template with 20 terms.

1.  Click on the **Customer Service Hub** app from the top and select **Customer service admin**.

    ![](../images/Customer-service-admin-1.png)
    
1.  Using the navigation on the left, select **Service Team**.

1.  Select **Manage** next to **Entitlements Templates**.

    ![](../images/Entitlement-3.png)

5.  Click **+ New**.

1.  Enter **odl_user_DID_20_Free Terms** for **Entitlement Template Name**,select the account you created for **odl_user_DID_Relecloud** in the earlier lab for **Primary Customer**, select today's date for **Start Date**, and select a month from today for **End Date**.select **Yes** for **Restrict on Entitlement Terms**, select **Number of Cases** for **Allocation Type**, select **Case Creation** for **Decrease Remaining On**, enter **20** for **Total Terms**.

7.  Click **Save**. DO NOT navigate away from this page.

    ![](../images/templates-2.png)

8.  Go to the **Entitlement Channel** sub-grid, click on the ellipsis and select **+ New Entitlement Template Channel**.

9.  Select **Phone** for **Name**, enter **20** for **Total Terms** and click **Save & Close**.

10. Click on the ellipsis and select **+ New Entitlement Template Channel**.

11. Select **Email** for **Name**, enter **0** for **Total Terms** and click **Save & Close**.

12. Click on the ellipsis and select **+ New Entitlement Template Channel**.

13. Select **Web** for **Name**, enter **0** for **Total Terms** and click **Save & Close**.

14. Click on the ellipsis and select **+ New Entitlement Template Channel**.

15. Select **Facebook** for **Name**, enter **0** for **Total Terms** and click **Save & Close**.

16. Click on the ellipsis and select **+ New Entitlement Template Channel**.

17. Select **Twitter** for **Name**, enter **0** for **Total Terms** and click **Save & Close**.

18. Click on the ellipsis and select **+ New Entitlement Template Channel**.

19. Select **IoT** for **Name**, enter **0** for **Total Terms** and click **Save and Close**.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

### Task 2 – Create Entitlement from Template

In this task, you will create 20 phone call only entitlement from the entitlement template you created.
    
1.  In the site map, select **Service terms** in Operations. The Service Terms page appears.

1.  In the **Entitlement** section, select **Manage**.

    ![](../images/Entitlement-6.png)

2.  Click on the **V** chevron button next to the **+ New** button and select **From Template**.

    ![](../images/Entitlement-5.png)

3.  Select **20 Free Terms** template you created for **Entitlement Template** and click **Select**.

4.  Some of the fields will be auto-filled from the template.

5.  Enter **odl_user_DID_Phone_Call _Only_Terms** for **Name**, select the **odl_user_DID_Relecloud** account for **Primary Customer**, select today's date for **Start Date**, select a year from today for **End Date**, and click **Save**.

1. Click **Activate**.

7.  Confirm activation. DO NOT navigate away from this page.

### Task 3 – Test the Entitlement

In this task, you will test the entitlement you created from the entitlement template.

1.  Switch back to the **Customer service Hub** tab.

1.  Click on **Home** at the top of the left-hand side navigation.

2.  Click on **Cases** in the **Service** section of the sitemap.

3.  Click **+ New Case**.

4.  Enter **odl_user_DID_Missing Parts** for **Case Title** and select the **odl_user_DID_Relecloud** account for **Customer**.

5.  Select **Phone** for **Origin**, select **Phone Call Only Terms** for **Entitlement** and click **Save**.

    ![](../images/Entitlement-7.png)

6.  Click **Go back**, click **+ New Case**.

7.  Enter **odl_user_DID_Wrong cables** for **Case Title** and select the **odl_user_DID_Relecloud** account for **Customer**.

8.  Select **Web** for **Origin**.

9.  Scroll down to the **Entitlement** field and select **Phone Call Only Terms**.

10. Click **Save**. You will get an error telling you that there are no available terms.

11. Click **OK**.

    ![](../images/error2.png)

12. You should get the same error if you select Email, Facebook or Twitter for Origin.

13. Select **Web** for **Origin** and clear the **Entitlement** field.

14. Click **Save**.

15. Since you didn’t select the **Phone Call Only Terms** entitlement, the case will now be created.

16.  Click on the **Customer Service Hub** app from the top and select **Customer service admin**.

    ![](../images/Customer-service-admin-1.png)
    
7.  In the site map, select **Service terms** in Operations. The Service Terms page appears.

18. Click on **Manage** in the **Entitlement** section.

19. Click to open the **Phone Call Only Terms** entitlement.

20. Make sure you have **19 Remaining Terms** and **19 Phone** channel **Remaining Terms**.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

## Exercise 3 – Service Level Agreements

In this exercise, you will create a Service Level Agreement and make it the default agreement.

### Task 1 – Holiday Schedule

In this task, you will create A holiday schedule to be used with Customer Service calendars.

1.  Click on the **Customer Service Hub** app from the top and select **Customer service admin**.

    ![](../images/Customer-service-admin-1.png)
    
1.  In the site map, select **Calendar** in Operations. The Calendar page appears.

1.  In the **Holiday calendar** section, select **Manage**.

    ![](../images/Entitlement-8.png)

1.  Click **+ New**.

1.  Enter **odl_user_DID_Holidays** for **Name**.

1.  Click **Create**. If a pop-up appears stating "service-level agreements (SLAs) are deprecated in the web client" Click **I acknowledge**.

1.  In the Holidays section, click **+ New**.

1.  Enter **Local festival** for **Name**, set the **Start Date** and **End Date** to be in two days time.

1. Click **OK**.

1. Click **Save & Close**.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

### Task 2 – Customer Service Schedule

In this task, you will create a Customer Service Schedule to use with SLAs.

1.  Click on the **Customer Service Hub** app from the top and select **Customer service admin**.

    ![](../images/Customer-service-admin-1.png)
    
1.  In the site map, select **Calendar** in Operations. The Calendar page appears.

1.  In the **Customer service calendar** section, select **Manage**.

    ![](../images/Entitlement-9.png)

2.  Click **+ New**.

3.  Enter **odl_user_DID_Customer Service Schedule** for **Name**.

4.  Click **Create**.

5.  Uncheck **Saturday** and **Sunday**.

6.  Click **Set Work Hours**.

7. Set Start to **9:00AM** and End to **5:00PM**.

8. Click **OK**.

9. Set **Holiday Schedule** to **Observe** and select the Holiday Schedule you created.

10. Select your local **Time Zone**

11. Click **Save & Close**.

    ![](../images/Entitlement-10.png)

### Task 3 – Create Service Level Agreement

In this task, you will create a SLA that sets a 1 hour response time on a problem case.

1.  Click on the **Customer Service Hub** app from the top and select **Customer service admin**.

    ![](../images/Customer-service-admin-1.png)
    
1.  In the site map, select **Service Teams** in Operations.

1.  In the **SLA KPIs** section, select **Manage**.

    ![](../images/Entitlement-11.png)

1.  Click **+ New**.

1.  Enter **odl_user_DID_Case Response By** for **Name**.

1.  Select **Case** for **Entity Name**.

1.  Select **First Response By KPI** for **KPI Field**

1.  Select **Created On** for **Applicable From**

1. Click **Save**. DO NOT navigate away from this form.

    ![](../images/Entitlement-12.png)

1. Click **Activate** in the command bar.

1. Click **Activate**.

1.  In the site map, select **Service Teams** in Operations.

1.  In the **Service Level Agreements** section, select **Manage**.

    ![](../images/Entitlement-13.png)

1. Click **+ New**.

1. Enter **odl_user_DID_SLA** for **Name**.

1. Select **Case** for **Primary Entity**.

1. Click **Save**.

1. Click **+ New SLA Item**

1. Enter **Problems** for **Name**.

1. Select the **SLA KPI** you created for **KPI**.

1. Select the **Customer Service Schedule** you created for **Business Hours**.

1. Under **Applicable When**, click on **Add** and **Add row**.

1. In the left-hand side of the condition, select **Case Type (Case)**.

1. Select **Equals** for the operator.

1. In the right-hand side of the condition, select **Problem**.

1. Under **Success Conditions**, click on **Add** and **Add row**.

1. In the left-hand side of the condition, select **First Response Sent (Case)**.

1. Select **Equals** for the operator.

1. In the right-hand side of the condition, select **Yes**.

1. Set **Warn After** to **45 minutes**.

1. Set **Failure After** to **1 hour**.

1. Click **Save**.

    ![](../images/Entitlement-15.png)

1. Click **Configure Actions**.

    ![](../images/Entitlement-16.png)

1. If prompted to connect to Dataverse, click **Continue**.

1. Expand the **Switch** step.

1. In the **Non-compliant** path, click on **Add an action**.

1. Search for an select **Microsoft Dataverse**.

1. Select the **Update a row** action.

1. Select **Cases** for **Table name**.

1. Select **Regarding ID** for **Row ID**.

1. Click **Show Advanced options**.

1. Set **Is Escalated** to **Yes**.

1. Click **Save** and close the Power Automate browser tab.

    ![](../images/Entitlement-17.png)

1. Click **Close** in the *SLA Item* dialog.

1. Click **Save**.

1. Click **Activate**.

1. Click **Activate**.

1. Click **Set As Default**. Click **OK** in the **Change default SLA** pop-up.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

### Task 4 – Service Level Agreement settings

In this task, you will configure the settings for service level agreements.

1.  Open the **Customer Service Hub** app.

1.  Click on **Settings** from the top right corner and select **Advanced settings**.

    ![](../images/Advanced-settings.png)
    
1.  On the new page, select the Settings drop down and select **Administration**.

    ![](../images/Entitlement-18.png)

1.  In the Administrator page, select **System Settings**.

1.  Verify that the **Disable SLAs** option is set to **No**.

1.  Set the **Apply SLA after manual override** to **Yes**.

1.  In **Select SLA Pause Status**, move **On Hold** and **Waiting for Details** from **Available** to **Selected**.

1.  Click **OK**.

    ![](../images/Entitlement-19.png)

### Task 5 – Test Service Level Agreements

In this task, you will test that the SLA is applied to cases.

1.  Switch back to the **Customer service Hub** tab.

1.  Click on **Home** at the top of the left-hand side navigation.

1.  Click on **Cases** in the **Service** section of the sitemap.

1.  Click **+ New Case**.

1.  Enter **odl_user_DID_SLA_Test #1** for **Case Title** and select the **odl_user_DID_Relecloud** account for **Customer**.

1.  Select **Web** for **Origin** and click **Save**.

1.  Select **Details tab** and in **Type section** select **Problem** from the drop down click **Save**.

    ![](../images/Entitlement-20.png)

1.  Select the **SLA** tab. You should see the Case Response By SLA KPI in progress with failure time set to 1 hour's time.

1.  Select the **Details** tab and set **First Response Sent** to **Yes** and click **Save**.

1.  Select the **SLA** tab. You should see the Case Response By SLA KPI with status on **Succeeded**.

1.  Click **Go back**, click **+ New Case**.

1. Enter **odl_user_DID_SLA_Test #2** for **Case Title** and select the **odl_user_DID_Relecloud** account for **Customer**.

1. Select **Email** for **Origin** and click **Save**.

1. Select the **SLA** tab. There should be no SLA KPI items.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

**Result:** You have successfully created the Entitlements, Entitlement Templates, and Service Level Agreements in this lab. 
