# Practice Lab 4 – Routing cases

## Scenario

You are a customer service manager at City Power & Light who has been tasked with trying the new case routing functionality before rolling it out to your users. In this lab, you will create record creation rules, and case routing rules and test how they work.

## Exercise 1 – Configure record creation rules

### Task 1 – Enable a case to be created from an email in a queue

1.  Open the **Customer Service Hub** app.

2.  Click on **Settings** from the top right corner and select **Advanced settings**.

    ![](../images/Advanced-settings.png)
    
3.  On the new page, select the Settings drop down and select **Service Management**.

    ![](../images/service-management..png)

4.  Click on **Automatic record creation and update rules** in the **Case Settings** section.

5.  Click **+ New** located on the command bar.

6.  Enter **odl_user_DID_Create case for support email** for **Rule name**, and select **Email** for **Activity type to monitor**.

7.  Under the Queue list select **Look up more records** and select the check box of **show only my records** and select the **odl_user_DID_support** from the list .

    ![](../images/look-up.png)
    
    ![](../images/support-select-1.png)

8.  Click **Save**.

    ![](../images/support-select-2.png)

9.  Under the **SPECIFY CONDITIONS FOR RECORD CREATION**, select the check box for **Create records for email from unknown senders**.

22. Under the **SPECIFY AUTORESPONSE SETTINGS**, select the check box for **Send automatic email response to customer on record creation**.

23. In *Select email template to resopond to customer*, search for and select **Case Auto Response**.

24. Click **Save**.

25. Click **Activate**.

26. Click **Activate**.

    ![](../images/support-select-3.png)

27. Due to the lack of administrative access to email mailboxes, you will not be able to test this rule.

## Exercise 2 – Basic routing

### Task 1 – Configure basic routing rule set

1.  Open the **Customer Service Hub** app.

2.  Click on **Settings** from the top right corner and select **Advanced settings**.

    ![](../images/Advanced-settings.png)
    
3.  On the new page, select the Settings drop down and select **Service Management**.

    ![](../images/service-management..png)

4.  Click on **Routing Rule Sets** in the **Case Settings** section.

5.  Click **+ New** located on the command bar.

6.  Enter **odl_user_DID_basic case routing rules** for **Name**.

7.  Click **Save**.

    ![](../images/rules1.png)

8.  Click **+ New Rule Item**.

    ![](../images/rules2.png)

9.  Enter **Problem** for **Name**.

14. Select **Queue** for **Route To**.

15. Search for and select the **Gold** queue you created in the earlier lab.

    ![](../images/rules3.png)

16. Click **Save & Close**.

    ![](../images/rules4.png)

17. Click **+ New Rule Item**.

23. Select **Queue** for **Route To**.

24. Search for and select the **Silver** queue you created in the earlier lab.

25. Click **Save & Close**.

26. Click **+ New Rule Item**.

27. Enter **Questions and Requests** for **Name**.

32. Select **Queue** for **Route To**.

33. Search for and select the **Bronze** queue you created in the earlier lab.

34. Click **Save & Close**.

36. Click **Activate** and click **Yes**.

## Exercise 3 – Route cases

### Task 1 – Route cases

1.  Open the **Customer Service Hub** app.

2.  Click on **Home** at the top of the left-hand side navigation.

3.  Click on **Cases** in the **Service** section of the sitemap.

5.  Open the **Defective Screen** case you created.

6.  Click **Queue Item Details** located on the command bar.

7.  The following message should be displayed *This record is not added to any queue.*

8.  Click **OK**.

    ![](../images/rules5.png)

9.  Click **Save & Route** and click **Route**.

10. Open the **Defective Screen** case again.

11. Click **Queue Item Details** located on the command bar.

12. The case will be have been routed to the *Gold* queue.

13. In the case view, click to the left of the **Service Required** case to select it.

14. Click **Apply Routing Rule** and click **Route**.

    ![](../images/rules6.png)

15. Open the **Service Required** case.

16. The case will be have been routed to the *Silver* queue.

