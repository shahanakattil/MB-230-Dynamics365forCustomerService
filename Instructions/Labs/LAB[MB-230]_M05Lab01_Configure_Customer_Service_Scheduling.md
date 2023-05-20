# Practice Lab 8 – Customer Service Scheduling Configuration

## Scenario

You are the scheduling manager at City Power & Light who has been tasked with setting up the new Service Scheduling functionality to perform services for customers at three of your locations.

## Exercise 1: Configure Customer Service Scheduling

In this exercise, you will create organizational units, define a business closure, and create facility/equipment records for organization units.

### Task 1: Define Organization Units

In this task, you will define three organizational units to act as service locations for scheduling.

1.  Open the **Customer Service Hub** app.

2.  Click **Settings** and select **Personalization Settings**.

3.  Select your **Time Zone** and click **OK**.

    ![](../images/Personalization-Settings-1.png)

4.  Click on **Home** at the top of the left-hand side navigation.

5.  Click on **Service** at the bottom of the **Site Map** in the left-hand navigation and select **Scheduling**.

6. Click on (hierarchy icon) **Organization Units** in the **Settings** section.

7.  Click **+ New**.

    ![](../images/Personalization-Settings-2.png)

8. Enter **odl_user_DID_Main_Ave_Location** for **Name**. Click on the **Scheduling** tab and enter a valid number for both Latitude and Longitude(Example: Latitude- 40, Longitude- 40).

    ![](../images/Personalization-Settings-3.png)

9. Click **Save and Close**.

10. Create two more **Sites** by following the steps 7 to 9 with the name listed in the table below.

 odl_user_DID-19th_Ave_Location
 odl_user_DID-35th_St_Location

11. You should now have three Sites.

    ![](../images/Personalization-Settings-4.png)

12. Do not navigate away from this application.

## Task 2: Define Business Closure

In this task, you will define a new business closure.

1.  Click on **Business Closures** in the **Settings** section.

2.  Click **+ New**.

3.  Enter **odl_user_DID_Worldwide_Rest_Day** for **Name**, Select **All Day Event** as **No**, select a date one week from now for **Start Date**, and click **OK**.

    ![](../images/Personalization-Settings-5.png)

4.  Do not navigate away from this application.

## Task 3: Create Facilities/Equipment Records

In this task, you will create facilities/equipment records for the organizational units you created and set their working hours.

1.  Click on **Facilities/Equipment** in the **Scheduling** section.

2.  Click **+ New**.

3.  Enter **odl_user_DID_Main_Ave-Service_Bay_1** for **Name**, select **odl_user_DID_Main_Ave_Location** for **Organizational Unit**, select a *Time Zone*, select the root **Business Unit**, and click **Save **.

    ![](../images/Personalization-Settings-6.png)

4.  Select the **Work Hours** tab, click on one of the events listed on the calendar, click **Edit**, and select **All events in the series**.

    ![](../images/Personalization-Settings-7.png)

5.  Select **08:00 AM to 08:00 PM**, remove **Saturday** and **Sunday**, and click **Remove end date**, if there is an end date selected.

6.  Toggle **Observe Business Closure** to **On**.

    ![](../images/Personalization-Settings-8.png)

7.  Click **Save** to save the working hours.

8.  Click **Save and Close**.

9.  Click **+ New**.

10. Enter **odl_user_DID_Main Ave-Service_Bay_2** for **Name**, select **odl_user_DID_Main_Ave_Location** for **Organizational Unit**, select your **Time Zone**, select the root **Business Unit**, and click **Save**.

11. Select the **Work Hours** tab, click on one of the events listed on the calendar, click **Edit**, and select **All events in the series**.

12. Select **08:00 AM to 08:00 PM**, remove **Saturday** and **Sunday**, click **Remove end date** if one is selected, and click Save.

13. Toggle **Observe Business Closure** to **On**

14. Click **Save** to save the working hours, and then click **Save and Close**.

15. Repeat the previous 5 steps and create the **Facilities/Equipment** listed in the table below.

| **Name**                 | **Organizational Unit** | **Time Zone**  | **Business Unit**  | **Working Hours**        |
|--------------------------|-------------------------|----------------|--------------------|--------------------------|
| Main Ave - Tire Jack     | Main Ave Location       | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |
| 19th Ave - Service Bay 1 | 19th Ave Location       | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |
| 19th Ave - Service Bay 2 | 19th Ave Location       | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |
| 19th Ave - Tire Jack     | 19th Ave Location       | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |
| 35th St - Service Bay 1  | 35th St Location        | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |
| 35th St - Service Bay 2  | 35th St Location        | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |
| 35th St - Tire Jack      | 35th St Location        | Your time zone | Root business unit | Mon-Fri 8:00AM to 8:00PM |

16. You should now have total of 9 Facilities/Equipment records.

    ![](../images/Personalization-Settings-9.png)
    
> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

## Exercise 2: Resource Configuration

In this exercise, you will create contact records, create resource categories, and create resources.

### Task 1: Create Contacts

In this task you will create new contact records.

1.  Open the **Customer Service Hub** app.

2.  Click on **Home** at the top of the left-hand side navigation.

3.  Click on **Contacts** in the **Customers** section.

4.  Click **+ New**.

    ![](../images/Personalization-Settings-10.png)

5.  Enter **odl_user_DID_Mike** for **First Name**, **Smith** for **Last Name**, and click **Save and Close**.

    ![](../images/Personalization-Settings-11.png)

6.  Repeat the previous two steps and create the **Contact** records listed in the table below.

    | **First Name** | **Last Name** |
    |----------------|---------------|
    | Jennifer       | Leary         |
    | Judy           | Anderson      |
    | Allan          | Jackson       |
    | Sven           | Locarte       |
    | Alex           | Nelson        |

7.  You should now have six contact records.

    ![](../images/Personalization-Settings-12.png)

8.  Do NOT navigate away from this application.

## Task 2: Create Resource Categories

In this task you will create new resource categories.

1.  Click on **Service** at the bottom of the **Site Map** in the left-hand navigation and select **Scheduling**.

2.  Click on **Resource Categories** in the **Scheduling** section.

3.  Click **+ New**.

    ![](../images/Personalization-Settings-13.png)

4.  Enter **odl_user_DID_Senior_Technician** for **Name** and click **Save and Close**.

5.  Click **+ New**.

6.  Enter **odl_user_DID_Technician** for **Name** and click **Save and Close**.

7.  Create two more **Resource Categories** and name them **odl_user_DID_Service_Bay_Facility** and **odl_user_DID_Tire_Jack_Equipment**.

8.  You should now have 4 **Resource Categories**.

    ![](../images/Personalization-Settings-14.png)

9.  Do NOT navigate away from this application.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

## Task 3: Create Resources

In this task you will create resources using the contacts you created.

1.  Click on **Resources** in the **Scheduling** section.

2.  Click **+ New**.

    ![](../images/Personalization-Settings-15.png)

3.  Select **Contact** for **Resource Type**, select **odl_user_DID_Mike_Smith** for **Contact**, and select the **Scheduling** tab.

    ![](../images/Personalization-Settings-16.png)

4.  Select **Organizational Unit Address** for **Start** and **End Locations**, select **Main_Ave_Location** for **Organizational Unit**, and click
    **Save**.
    
    ![](../images/Personalization-Settings-17.png)

5.  Select the **Work Hours** tab, click on one of the events on the calendar, click **Edit**, and select **All events in the series**.

6.  Select **08:00 AM** to **04:30 PM** and click **Add Break**.

7.  Remove **Saturday** and **Sunday**, select **Observe Business Closure** to **On**, then click **Save**.

    ![](../images/Personalization-Settings-18.png)

8.  Select the **General** tab.

9.  Select the **Related** tab and select **Resource Category Assns**  and click **+ New Bookable Resource Category Assn**.

    ![](../images/Personalization-Settings-19.png)

10. Select **Senior Technician** and click **Save and Close**.

    ![](../images/Personalization-Settings-20.png)

11. Repeat the previous 9 steps and create the resources listed in the table below.

    | **Resource Type** | **Contact**    | **Start and End Locations** | **Organizational unit** | **Work Hours**                                               | **Resource Category Assn** |
    |-------------------|----------------|-----------------------------|-------------------------|--------------------------------------------------------------|----------------------------|
    | Contact           | Judy Anderson  | Organizational Unit Address | 19th Ave Location       | Mo – Fr 08:00AM to 04:30 PM + Break Observe Business Closure | Senior Technician          |
    | Contact           | Sven Locarte   | Organizational Unit Address | 35th St Location        | Mo – Fr 08:00AM to 04:30 PM + Break Observe Business Closure | Senior Technician          |
    | Contact           | Jennifer Leary | Organizational Unit Address | Main Avenue Location    | Mo – Fr 08:00AM to 04:30 PM + Break Observe Business Closure | Technician                 |
    | Contact           | Allan Jackson  | Organizational Unit Address | 19th Ave Location       | Mo – Fr 08:00AM to 04:30 PM + Break Observe Business Closure | Technician                 |
    | Contact           | Alex Nelson    | Organizational Unit Address | 35th St Location        | Mo – Fr 08:00AM to 04:30 PM + Break Observe Business Closure | Technician                 |

12. You should now have 6 resources. Click **+ New**.

    ![](../images/Personalization-Settings-21.png)

13. Select **Facility** for **Resource Type**, select **19th Ave – Service Bay 1** for **Facility Equipment**, and select the **Scheduling** tab.

    ![](../images/Personalization-Settings-22.png)

14. Select **Organizational Unit Address** for **Start** and **End Locations**, and then click **Save**.

15. Select the **General** tab.

16. Select the **Related** tab and select **Resource Category Assns**  and click **+ New Bookable Resource Category Assn**.

    ![](../images/Personalization-Settings-23.png)

17. Select **Service Bay Facility** and click **Save and Close**.

18. Repeat the previous steps from 12 to 17 and create the resources listed in the table below.

| **Resource Type** | **Facility Equipment**   | **Start and End Locations** | **Resource Category Assn** |
|-------------------|--------------------------|-----------------------------|----------------------------|
| Facility          | 19th Ave – Service Bay 2 | Organizational Unit Address | Service Bay Facility       |
| Facility          | 35th St – Service Bay 1  | Organizational Unit Address | Service Bay Facility       |
| Facility          | 35th St – Service Bay 2  | Organizational Unit Address | Service Bay Facility       |
| Facility          | odl_user_DID_Main_Ave–Service_Bay_1 | Organizational Unit Address | Service Bay Facility       |
| Facility          | odl_user_DID_Main_Ave–Service_Bay_2 | Organizational Unit Address | Service Bay Facility       |
| Equipment         | 19th Ave – Tire Jack     | Organizational Unit Address | Tire Jack Equipment        |
| Equipment         | 35th St – Tire Jack      | Organizational Unit Address | Tire Jack Equipment        |
| Equipment         | Main Ave – Tire Jack     | Organizational Unit Address | Tire Jack Equipment        |

19. You should now have 15 Resources.

    ![](../images/Personalization-Settings-25.png)
    
> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Select the **Lab Validation** tab located at the upper right corner of the lab guide section.
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task. 
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.

**Result:** You have successfully Configured Customer Service Scheduling and Resource Configuration in this lab. 
