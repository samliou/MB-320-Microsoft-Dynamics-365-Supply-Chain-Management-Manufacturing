Exercise: Start a discrete production order
===========================================

The production of the ash enclosure back sides of the speakers is ready for
production start. Use the Start form and select the Production order with status
of Scheduled to start.

1.  Click **Production control \> All Production orders**.

2.  Select any production order with the production order status set to
    **Scheduled, for example, P000171.**

3.  On the **Production order** Action pane click **Start**.

4.  On the **Overview** tab, in the **Quantity** field, enter the quantity 2.00
    of the production order to produce.

5.  In the **Date** field, enter today’s date for the date that the production
    starts.

6.  Select the **Start production** check box.

7.  Click **OK**.

8.  The Status on the current production order is changed from **Scheduled** to
    **Started**.  
    ‎

Exercise: Run a Resource Schedule
=================================

Having bought a new assembly robot, Tony, the Production Manager, wants to
increase flexibility in their production. In the past, when he designed the
production process (route) for a product, he had to specify where each operation
was to be performed. Instead, he wants the allocation of where and by whom an
operation is performed to be deferred until the production is scheduled, and to
use excess capacity in other workshops to eliminate bottlenecks in heavily
loaded workshops.

To create capabilities and resources, follow these steps:
---------------------------------------------------------

1.  Navigate to **Organization administration \> Resources \> Resource
    capabilities**.

2.  Click **New**.

3.  Type "20" in the **Capability** field and "Assembly" in the **Description**
    field.

4.  Click **New**.

5.  Type "30" in the **Capability** field and "Packing" in the **Description**
    field.

6.  Expand the **Resources** fast tab.

7.  Click **Add**.

8.  Select "1222", Speaker packing worker 1, in the **Resource** field.

9.  Accept the default **Expiration** date of Never.

10. Accept the default **Level** of 0.00.

11. Type "1" in the **Priority** field.

12. Close the **Resource capabilities** form.

13. Open **Organization administration \> Resources \> Resources**.

14. Click **New**.

15. Type "000727" in the **Resource** field.

16. Type "Assembly robot" in the **Description** field.

17. Accept the default of **Machine** in the **Type** field.

18. Open the **Capabilities** fast tab.

19. Click **Add**.

20. Select 20 in the **Capability** field.

21. Accept the default **Expiration** date of Never.

22. Accept the default **Level** of 0.00.

23. Type "1" in the **Priority** field.

24. Expand the **Resource groups** fast tab.

25. Click **View \> All**.

26. Click **Add**.

27. Type "1210" in the **Resource group** field, type the next working day in
    the **Effective** field and then accept the default **Expiration** date of
    Never.

28. Accept the default **Input warehouse**.

29. Accept the default **Input location**.

30. Scroll up, expand **Calendars** tab and click **Add**.

31. Select **24hr** in the **Calendar** field.

32. Close the **Resources** form.

To identify resources applicable for the operation, follow these steps:
-----------------------------------------------------------------------

1.  Navigate to **Production control \> Operations \> All routes**

2.  Select route 000002 : STANDARD SPEAKER - D0003 by clicking on the link for
    000002.

3.  Click Route \> Route details.

4.  Verify operation 10 is selected in the grid of the **Route** form.

5.  Click **Applicable Resources**.

6.  Notice that all the resources from the 1210 resource group are listed.

7.  Click Scroll one day forward by clicking the **Next day** button or choose
    the date picker field.

8.  Click **OK**.

9.  Close the **Applicable resources** form.

To add requirements for a capability to an operation, follow these steps:
-------------------------------------------------------------------------

1.  In the **Route details** form for route 000002, with operation 10 selected
    in the grid, select the **Resource requirements** tab.

2.  In the Resource requirements grid, select the line where **Requirement
    type** is Capability and **Requirement** is Assembly.

3.  Click **Delete**, and then click **Yes** to delete the record.

4.  Click **Maintain resource requirements.** This starts the wizard.

5.  On the Welcome screen, click Next.

6.  On the Search criteria screen, select **Capability** in the **Requirement
    type** field.

7.  Type "20" in the **Requirement** field.

8.  Click Next.

9.  In the Action screen, leave the defaults and click Next.

10. In the New resource requirements screen, set Requirement type to Capability,
    Requirement to 20, and check the **Operation scheduling** and **Job
    scheduling** check boxes.

11. Click Next.

12. On the Summary screen, review your options and click Finish.

13. Close all pages.

To create and confirm a sales order, follow these steps:
--------------------------------------------------------

1.  Open **Sales and marketing \> Sales orders \> All Sales orders**.

2.  Click **New**.

3.  Type " US-013" for customer Pelican Wholesales in the **Customer account**
    field.

4.  Accept the default settings in all other fields. Click **OK**.

5.  In the Sales order form, open the Sales order Lines fast tab.

6.  Type"D0003" in the **Item number** field.

7.  Type "12" in the **Quantity** field.

8.  Accept the default values for the remaining fields.

9.  Click **Save**.

10. Click **Confirm sales order** from the **Sell** tab in the action pane.

11. Accept all the default settings in the **Confirm sales order** form.

12. Click **OK**.

13. Click **OK**.

14. Close all pages.

To run master scheduling, follow these steps:
---------------------------------------------

1.  Open **Master Planning \> Master Planning \> Run \> Master Planning**.

2.  Select StaticPlan, in the **Master plan** field.

3.  Click **OK**
