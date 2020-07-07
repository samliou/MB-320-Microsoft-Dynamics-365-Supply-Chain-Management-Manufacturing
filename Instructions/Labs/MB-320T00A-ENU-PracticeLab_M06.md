Exercise: Backflush on Operations
=================================

The Production Manager decided that the best way to post picking lists is to use
the Operation quantity feedback (backflush on operations) method. If the actual
consumption on BOM items differs from the estimated consumption, the employee
can enter the actual item consumption when providing quantity feedback.

1.  Open **Production control\>Setup\>Manufacturing execution\>Production order
    defaults**.

2.  On the **Start** tab, select **Status** in the **Update start on-line**
    field

3.  In the **Automatic BOM consumption** field, select **Never**.

4.  Click the **Operations** tab.

5.  Set the **Setup** option to **No**.

6.  In the **Automatic BOM consumption** field, select **Always**.

7.  Click the **Report as finished** tab.

8.  In the **Update finished report on-line** field, select **Quantity**.

9.  In the **Automatic BOM consumption** field, select **Never**.

10. Close the **Production order defaults** form.  
    ‎

Exercise: Automatic Route Consumption on Setup Jobs
===================================================

The estimation on operation setup is accurate, so the Production Manager decides
that it is not necessary for employees to register on setup jobs. The time
consumption on setup jobs must be posted automatically.

1.  Open **Production control\>Setup\>Routes\>Route groups**.

2.  From the list, select **Sfc Shop Floor Control Routing Group**.

3.  Click **Edit**.

4.  On the **General** FastTab, in the **Automatic route consumption** group,
    enable the **Setup time** field.

5.  Close the **Route groups** form.

6.  Open **Production control\>Setup\>Manufacturing execution\>Production order
    defaults**.

7.  On the **Start** tab, in the **Automatic route consumption** field, select
    **Route group dependent**.

8.  Enable the **Post route card now** field.

9.  Close the **Production order defaults** form.

Exercise: Test the Parameter Set Up
===================================

Note: You need to complete Exercise 1 and 2 in order to this exercise. In the
previous exercises, you changed the picking list posting to backflush on
operations, and arranged posting of setup time on a production order to be done
automatically when you start a new production. Now, you need to test the setup.

In order to test the parameter, set up, follow these steps.
-----------------------------------------------------------

1.  Open **Organization administration\>Number sequences\>Number sequences**.

2.  Select Number sequence code "**Prod_128**", Name "Production Journal", Next
    "1900" or higher

3.  Click **Edit** in the Maintain group

4.  Click to expand Scope parameters FastTab, if it is not expanded already.

5.  Verify that Company is "**USMF**".

6.  Click to expand **General** FastTab, if it is not expanded already.

7.  verify that **Continuous** field is set to No.

8.  Close the **Number sequences** form.

To run the Synchronize job table periodic job, follow these steps.
------------------------------------------------------------------

1.  Open **Production control \> Periodic tasks\> Update entities\> Synchronize
    job table**.

2.  Enable all four options which are: Synchronize production, Synchronize Time
    and attendance, Synchronize project and Synchronize HRM absence.

3.  Click **OK**. This process may take several minutes to complete.

Exercise: Use manufacturing execution
=====================================

You need to enable time registration for Shannon the machine operator in USMF.
Shannon needs to use the Job card terminal to control the execution of the
production order.

1.  Go to **Human resources \> Workers \> Employees**.

2.  Use the **Quick Filter** to filter on the **Name** field with a value of
    **'SHANNON'**.

3.  Click **Activate on registration terminals** in the Time tab of the Action
    pane.

4.  In the **Calculation group** field, enter or select **Man**

5.  In the **Default calculation group** field, enter or select **Man**

6.  In the **Approval group** field, enter or select **AdmMan**

7.  In the **Standard profile** field, enter or select **Standard**

8.  In the **Profile group** field, enter or select **Man**

9.  Select **Yes** in the **Use timecard** field.

10. In the **Configuration** field, enter or select Production

11. Select **Yes** in the **Supervisor options** field.

12. Click **OK**.

13. In the list, click on the **Shannon** link id to get to the detail page.

14. Click the **Time registration** tab.

15. Click **Edit**.

16. In the **Identification** field, type '069'.

17. In the **Badge ID** field, type '069'.

18. Click **Save**.

19. Close the page.

20. Go to **Production control \> Manufacturing execution \> Job card device**.

21. In the **Personnel number** field, type '069'.

22. Click **Log in**.

23. Click **Start job**.

24. Set **Quantity to start** to '1.00'.

25. Click **OK**.

26. Click **Report progress**.

27. Set **Error quantity** to '1.00'.

28. In the **Error cause** field, enter 'Material'.

29. Click **OK**.

30. Click **Break**.

31. In the list, select **break from work**

32. Click **OK**.

33. Click **Stop break**.

34. Click **Activity**.

35. In the list, find and select **Equipment repair**

36. Click **OK**.

37. Click **OK**.

38. Set **Error quantity** to '2.00'.

39. In the **Error cause** field, enter 'Machine'.

40. Click **OK**.

41. Click **Close**.

42. Click **Next job**.

43. Click **Previous job**.

44. Click **Report progress**.

45. Set **Good quantity** to '5.00'.

46. In the **Job status** field, enter **'Completed'**.

47. Click **OK**.

48. Close the page.  
    ‎
