Exercise: Create an event Kanban from a sales order
===================================================

A sales order has been received for a green speaker set, which triggers event
Kanbans for the speaker set on the packaging work cell and the speaker kits on
the speaker assembly work cell. Produce the speaker kits and speaker set to
fulfill the customer sales order.

Kanban Line Event
-----------------

1.  Navigate to **Sales and marketing\>Sales orders\>All sales orders**.

2.  Click **New**.

3.  Select the **Customer account** as US-016.

4.  Click **OK**.

5.  Enter **Item number** of “L0026”.

6.  Enter **Quantity** of “12.00”.

7.  Click **Update confirmed date**.

8.  Select **Site** of 1 (scroll or tab right).

9.  Select **Warehouse** of 13.

10. Select **Location** of 13.

11. If **Location** is not set on the sales order, select the Sales order line
    \> Display \> Dimensions button. Tick on the location and configuration.

12. Select Configuration 01.

13. When you save, if the date cannot be promised, select **Update confirmed
    ship date**.

14. Select the **Product and supply \> View pegging tree** menu button to view
    the event Kanbans created for the sales order.

Plan the Kanbans
----------------

Follow these steps to plan the Kanbans on the packaging and speaker assembly
work cells.

1.  Navigate to **Production control\>Kanban\>Kanban schedule board**.

2.  Change the Work cell to 1250.

3.  Plan the Kanban for 1250 by selecting the Kanban job in the board.

4.  Close all forms.

5.  Navigate to **Production control \> Kanban \> Kanban board for process
    jobs**

6.  Select the Change cell button.

7.  Change Work cell to 1250.

8.  Highlight the desired Kanbans and click **Start**.

9.  Click **Complete**.

10. Select the **Change cell** button.

11. Change **Work cell** to 1250.

12. Highlight a Kanban and switch to the **Pegging** FastTab on the **Kanban
    board for process jobs** work cell form. View the complete lower level
    speaker set Kanbans on the pegging tree.

13. Click **Start**.

14. Click **Complete**.

Transfer the Speaker Set
------------------------

Follow these steps to transfer the speaker set to the warehouse.

1.  Navigate to **Production control \> Kanban \> Kanban board for transfer
    jobs**.

2.  Expand **Filters** FastTab

3.  Select a **Production Flow**

4.  Click **Update picking list** on the Transfer tab in the action pane

5.  Click **Add picking** line

6.  Click **Confirm** pick all

7.  Close the form

8.  Select **Start**

9.  Select **Complete**

Exercise: Create a kanban line event
====================================

In **USMF**, a sales order has been received for a product L0001, a
MidRangeSpeaker2, which triggers event Kanbans for the MidRangeSpeaker2 on the
packaging work cell and the speaker kits on the speaker assembly work cell.
Produce the speaker kits and speaker set to fulfill the customer sales order.

Enter sales order
-----------------

1.  Go to **Sales and marketing \> Sales orders \> All sales orders**.

2.  Click **New**.

3.  In the **Customer account** field, enter or select US-003.

4.  Click **OK**.

5.  In the Item number field, enter or select L0001.

6.  Set **Quantity** to '1.00'.

7.  Click **Product and supply**.

8.  Click **Event kanban**.

9.  Click **Product and supply**.

10. Click **View pegging tree**.

11. Close the page.

Plan the Kanbans
----------------

1.  Go to **Production control \> Kanban \> Kanban job scheduling**.

2.  Click **Plan entire pegging tree** under Plan in the action pane.

3.  Select a few rows for those unplanned kanbans.

4.  Click **Plan entire pegging tree**.

5.  In the **Work cell** field, enter or select 1250.

6.  Close the page.

Process jobs
------------

1.  Go to **Production control \> Kanban \> Kanban board for process jobs**.

2.  In the **Work cell field**, enter or select 1250.

3.  Select a few rows for those planned kanbans

4.  Click **Prepare**.

5.  Expand the **Details** section. Note the details

6.  Collapse the **Details** section.

7.  Expand the **Picking list** section. Note the raw materials needed.

8.  Click **Start**.

9.  Click **Complete**.

10. On the Action Pane, click **View**.

11. Click **Process job list**.

12. Select the **Site** check box.

13. Select the **Warehouse** check box.

14. Select **Yes** in the Save setup field.

15. Select the **Location** check box.

16. Click **OK**.

17. Select a planned job.

18. On the Action Pane, click **Pick**.

19. Click **Update picking list**.

20. Click **Add picking line**.

21. Click **Confirm pick all**.

22. Close all forms.

Perform transfers
-----------------

1.  Go to **Production control \> Kanban \> Kanban board for transfer jobs**.

2.  Select a job to start the transfer. Click **Start**.

3.  Click **Complete**.

4.  On the Action Pane, click Transfer.

5.  Select few rows for those jobs to start transfer. Click **Start**.

6.  On the Action Pane, click **Transfer**.

7.  Click **Update picking list**.

8.  Click **Add picking line**.

9.  Click **Confirm pick all**.

10. Close all forms.
