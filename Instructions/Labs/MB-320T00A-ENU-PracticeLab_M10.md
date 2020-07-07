Exercise: Configure a Fixed Quantity Kanban Rule
================================================

A new car speaker remote has been developed to complement the car speaker kits
that are sold at **USMF**. The production flow is already configured with
multiple activities and now the products and Kanbans required to process the
flow must be created.

Products have been set up for the purchased un-programmed remote and for the
remote that will be programmed through the activities of the production flow.
The Bill of material (BOM) has also been created, adding the purchased
unprogrammed remote as a BOM line.

Once the BOM is created, Kanban rules are set up for the process activity to
program the remote and for the transfer activity to transfer the programmed
remote (now a finished good) to the warehouse and location where it will be
stored until it is sold.

Creating the Kanban Rule for the Process Activity
-------------------------------------------------

1.  To create a new Kanban rule for the process activity, navigate to **Product
    information management \> Lean manufacturing \> Kanban rules**.

2.  Click **New**.

3.  Select the **First plan activity** called SpeakerTestAndPackaging.

4.  Expand the **Details** FastTab

5.  In the **Product**, select L0001

6.  Expand the **Quantities** FastTab

7.  Enter a **Default quantity** of “100”.

8.  Enter a **Fixed Kanban quantity** of “4”.

9.  Expand the **Kanban and cards** FastTab

10. Select the **Circulating cards** check box.

11. Change the **Card assignment** to “Automatic”.

12. Click **Save**.

13. Click the **Create cards** button.

14. Deselect the **Print new cards** box.

15. Click **Create**.

16. Switch to the **Kanbans** FastTab.

17. Click **Add**.

18. Verify that the default number of new Kanbans is 4.

19. Click **Create**.

20. Close all forms.

Creating the Kanban Rule for the Transfer Activity
--------------------------------------------------

1.  To create a new Kanban rule for the transfer activity, navigate to **Product
    information management \> Lean manufacturing \> Kanban rules**.

2.  Click **New**.

3.  Change the **Type** to “Withdrawal”.

4.  Update the **First plan activity** to “ReplenishSpeakerComponents”.

5.  Expand the **Details** FastTab

6.  Enter the **Product** L0001.

7.  Switch to the **Quantities** FastTab.

8.  Enter the **Default quantity** of “10”.

9.  Enter the **Fixed Kanban quantity** of “4”.

10. Click **Save**.

11. Switch to the **Kanbans** FastTab.

12. Click **Add**.

13. Verify that the number of new Kanbans defaults to 4.

14. Click **Create**.

15. Close all forms.

Planning a Kanban on the Kanban Board
-------------------------------------

When the Kanban jobs are not automatically planned, they must be dragged and
dropped onto the desired period on the Kanban schedule board.

1.  To plan the Kanban, navigate to **Production control\>Kanban\>Kanban job
    scheduling**.

2.  Change Work cell to "1250”.

3.  In the **Display job status** field select **Not scheduled**.

4.  Select a Kanban job from the unplanned Kanban jobs, and then Click
    **Schedule** button. Repeat for the remaining Kanban jobs of your choice.

Exercise: Fixed Kanban Job processing
=====================================

Kanban processing on the Kanban Board for Process Jobs
------------------------------------------------------

The scheduled Kanbans are now ready to be processed. The **Production
control\>Kanban\>Kanban board for process jobs** will be used to prepare, start,
and complete the Kanbans.

1.  To prepare the Kanban, **Production control\>Kanban\>Kanban board for
    process jobs**.

2.  For the first time when you open this form, all jobs from all work cells are
    shown. You can select the **Work cell** to filter the jobs.

3.  Change the **Work cell** to 1250.

4.  Select the appropriate Kanbans to prepare.

5.  Click **Prepare**.

6.  To start the Kanbans, click **Start** button.

7.  To complete the Kanbans, click **Complete**.

Kanban processing on the Kanban Board for Transfer Jobs
-------------------------------------------------------

The manufactured Kanban is now ready to be transferred to its final location.
The Kanban board for transfer jobs will be used to start and complete the
Kanban.

1.  To begin the transfer process, navigate to **Production
    control\>Kanban\>Kanban board for transfer jobs**.

2.  If entering the board for the first time you see all jobs from all
    production flows. Alternatively, you can expand **Filters** FastTab and
    change Production flow to only show jobs for a specific production flow such
    as Mid-Range Speaker 2 PF.

3.  Select the Kanbans of your choice, as long as they have a card number.

4.  To start the transfer, click **Start**.

5.  To complete the transfer, click **Complete**.
