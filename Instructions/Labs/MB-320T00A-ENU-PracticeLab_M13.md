Exercise: Configure activity-based subcontractor work
=====================================================

Set up default vendor for a warehouse
-------------------------------------

1.  Go to **Inventory management \> Setup \> Inventory breakdown \>
    Warehouses**.

2.  In the list, find and select Warehouse **12-801**

3.  Verify the **Vendor account** field in the General tab is set to **US-801**

4.  Close the page.

Create a purchase agreement
---------------------------

1.  Go to **Procurement and sourcing \> Purchase agreements \> Purchase
    agreements**.

2.  Click **New**.

3.  In the **Vendor account** field, enter or select **US-801**

4.  In the **Purchase agreement classification** field, enter or select
    **General purchases**

5.  Expand the **General** section.

6.  In the **Expiration date** field, enter a date in future which agreements
    should be expired by.

7.  Click **OK**.

8.  Expand the **Purchase agreement header** section.

9.  In the **Default commitment** field, select **'Product value commitment'**.

10. Click **Add line**.

11. In the **Item number** field, enter or select **S0001**

12. In the **Warehouse** field, enter or select **12-801**

13. Set **Net amount** to '73570.00'.

14. Click **Add line**.

15. In the **Item number** field, enter or select **S0002**

16. In the **Warehouse** field, enter or select **12-801**

17. Set **Net amount** to '50848.00'.

18. In the **Status** field, select **'Effective'**.

19. Click **Save**.

20. Close all forms.

Create a work cell for subcontracting
-------------------------------------

1.  Go to **Organization administration \> Resources \> Resources**.

2.  Click **New**.

3.  In the **Resource** field, type 'GTL-Sub1'.

4.  In the **Description** field, type 'Subcontractor 1'.

5.  In the **Type** field, select 'Vendor'.

6.  Click **Save**.

7.  Close the page.

8.  Go to **Organization administration \> Resources \> Resource groups**.

9.  Click **New**.

10. In the **Resource group** field, type **'eBookSub'**.

11. In the **Description** field, type **'eBook subcontractor'**.

12. In the **Site** field, enter or select site **1**

13. Select **Yes** in the **Work cell** field.

14. In the **Input warehouse** field, enter or select **11**

15. In the **Input location** field, enter or select **11.**

16. In the **Output warehouse** field, enter or select **12-801**

17. In the **Output location** field, enter or select **801**.

18. In the Calendars fast tab, click **Add**.

19. In the **Calendar** field, enter or select **Production**.

20. Collapse the **Calendars** section.

21. In the Resources fast tab, click **Add**.

22. In the **Resource** field, enter or select **8821**.

23. Collapse the **Resources** section.

24. In the Work cell capacity fast tab, click **Add**.

25. In the **Production flow model** field, enter or select **Mid-Range Speaker
    2 Flow Model**.

26. In the **Capacity period** field, select **'Standard workday'**.

27. Set **Average throughput quantity** to '100.00'.

28. In the **Unit** field, type 'pcs'.

29. Click **Save**.

30. Close all forms.

Create Activity based subcontracting rule.
------------------------------------------

1.  Go to **Production control \> Setup \> Lean production flow \> Production
    flows**.

2.  In the list, find and click the **Speaker driver** link to get to the
    details page.

3.  Under **Versions** section, click **Add**.

4.  Click **OK**.

5.  In the list, find and select the new version with a status of **Draft**.

6.  Click **Activities**.

7.  Click **Create new plan activity**.

8.  Click **Next**.

9.  In the **Name** field, type **'GTL-Subcontracting activity**'.

10. Click **Next**.

11. In the **Work cell** field, enter or select **eBookSub**. You are assigning
    a work cell that is associated with the Vendor.

12. Click **Next**.

13. Click **Next**.

14. In the list, find and select the row for the **Runtime.** Type **1** in the
    **Time** field.

15. In the **Time unit** field, enter or select **hr**.

16. Set **Per quantity** to '10.00'.

17. Click **Next**.

18. Click **Finish**.

19. Click **Create new plan activity**.

20. Click **Next**.

21. In the **Name** field, type **'GTL-Transfer to subcontractor'**.

22. In the **Activity type** field, select **'Transfer'**.

23. Click **Next**.

24. In the **Replenishing** field, enter or select **eBookSub.**

25. In the **Replenished** field, enter or select **eBookSub**.

26. Click **Next**.

27. Click **Next**.

28. In the list, find and select the row for the **Runtime**; type 1 in the
    **Time** field.

29. In the **Time unit** field, enter or select **hr**.

30. Set **Per quantity** to '4.00'.

31. Click **Next**.

32. Click **Finish**.

33. In the list, find and select **GTL-Subcontracting activity**.

34. Click **Add successor**.

35. In the **Activity** field, select **GTL-Transfer to subcontractor**.

36. In the **Cycle time ratio** field, enter 1.

37. Click **OK**.

38. Select **GTL-Transfer to subcontractor** line.

39. Click **Details**

40. Expand **Service terms** Fasttab.

41. Click **Add**.

42. In the **Service** field select **S0001**.

43. Click **Next**.

44. In the **Service ratio** field type **1.2**

45. In the **Service unit** field select **hr**.

46. For the **Service quantity base** field select **Activity time**.

47. Click **Next**.

48. Click **Finish**.

49. Close the **Activity details** page.

50. Select **GTL-Subcontracting activity**

51. Click **Details**

52. Expand **Service terms** Fasttab.

53. Click **Add**.

54. In the **Service** field select **S0002**.

55. Click **Next**.

56. In the **Service ratio** field type **1.0**

57. In the **Service unit** field select **hr**.

58. For the **Service quantity base** field select **Activity time**.

59. Click **Next**.

60. Click **Finish**.

61. Close the **Activity details** page.

62. Select **GTL-Transfer to subcontractor**

63. Click **Add successor**.

64. In the **Activity** field, enter or select **Speaker driver**.

65. In the **Cycle time ratio** field, enter 1.

66. Click **OK**.

67. Close the **Activities** page.

68. Select version 1 and click **Deactivate.** Click **OK.**

69. Select version 2 and click **Activate.** Click **OK.**

70. Close all forms.

Create and schedule kanbans for subcontracting
----------------------------------------------

1.  Go to **Product information management \> Lean manufacturing \> Kanban
    rules**.

2.  Click **New**.

3.  In the **First plan activity** field, enter or select **GTL-Subcontracting
    activity**

4.  Select the **Multiple activities** check box.

5.  In the **Last plan activity** field, enter or select **GTL-Transfer to
    subcontractor**

6.  Click **OK**.

7.  In the **Product** field, type 'L0001'.

8.  Expand the **Quantities** section.

9.  Set **Default quantity** to '50.00'.

10. In the **Fixed kanban quantity** field, enter '25'.

11. Click **Save**.

12. Click **Add**.

13. Click **Create**.

14. Click **Details**.

15. Expand the **Jobs** section.

16. View jobs for process and transfer to a subcontractor

17. Close all forms.

18. Go to **Production control \> Kanban \> Kanban job scheduling**.

19. In the **Work cell** field select eBookSub

20. In the list, mark and select the first two rows.

21. Click **Schedule from date** to open the drop dialog.

22. Click **Schedule**.

23. Close all forms.

Process and transfer jobs
-------------------------

1.  Go to **Production control \> Kanban \> Kanban board for process jobs**.

2.  In the Work cell field, enter or select eBookSub

3.  In the list, mark the selected row.

4.  Click **Prepare**.

5.  Click **Start**.

6.  Click **Complete**.

7.  Expand the **Transfer jobs** section.

8.  In the list, mark the selected row.

9.  Click **Start**.

10. Click **Complete**.

11. Close the page.
