Exercise: Create Value streams
==============================

After defining and mapping the Lean manufacturing Value stream for **USMF**, you
acting as the Value Stream Manager, must create the Value stream within
Microsoft Dynamics 365 for Operations.

Follow the steps below:

1.  Go to **Production control\>Setup\>Lean production flow\>Value streams**.

2.  Click **New** to create a new value stream.

3.  Enter the following details for the new value stream:

4.  Name: **SeaLeanVS**

5.  Search Name: **SeaLean**

6.  Manager: **Jodi Christiansen**

7.  Click **Save**.

Exercise: Create production flows
=================================

You, as the production (shop) floor supervisor, has a logical grouping of work
cell capacity with similar behavior in capacity load for the work cells used to
model his Car Speaker production flow.

You must create a new production flow (SeaPFModel) to model the process of
painting the covers for the car speakers. The capacity and load of the
production flow will be measured in quantities of product that are produced
(Throughput).

The Cycle for this production flow will define 1 days as the number of days used
in automatic planning (i.e., EPE cycle is **1** day). The **Add** method of
Kanban scheduling will be used if there is no capacity available during the
required periods; the planning period type is **Day** and the planning time
fence is **10**.

1.  Go to **Production control\>Setup\>Lean production flow\>Production flow
    models.**

2.  Click **New**.

3.  In the **Production flow model** field enter **SeaPFModel**

4.  In the **Model type** field enter **Throughput**

5.  In the **EPE Cycle in days** field enter **1**

6.  In the **Capacity shortage reaction** field enter **Add**

7.  In the **Planning period type** field enter **Day**

8.  In the **Planning time fence** field enter **10**

9.  In the **Capacity shortage reaction** drop down select **Postpone**.

10. Click **Save**.

You also must create a production flow version for the USMF eBook production
flow and set up the Takt and Cycle times as part of the configuration.

Details for the production flow
-------------------------------

-   **Name**: eBookProdFlow

-   **Description**: eBook Production Flow

-   **Legal entity**: USMF

-   **Value stream**: SeaLeanVS

-   **Production group**: 10

-   **Per cycle unit of measure**: pcs

-   **Quantity per cycle**: 1

-   **Average takt time**: 1

-   **Minimum takt time**: 1

-   **Maximum takt time**: 2

-   **Period for actual cycle time (days):** 1

1.  Navigate to **Production control\>Setup\>Lean production flow\>Production
    flows**.

2.  Click **New** on the action pane. A new production flow record is created.

3.  In the **Name** field, enter **eBookProdFlow**.

4.  In the **Description** field, enter **eBook Production Flow**.

5.  In the **Legal entity** field, select **USMF**.

6.  In the **Value stream** field, select **LeanProduction**.

7.  In the **Production group** field, select **10**.

8.  Click **Save**.

9.  On the **Versions** FastTab, click **Add**.

10. Click **OK**.

Configure the Takt requirements for the new production flow version
-------------------------------------------------------------------

1.  Expand **Versions** and **Version details** FastTabs.

2.  In the **Per cycle unit of measure** field, select **pcs**.

3.  In the **Quantity per cycle** field, enter **1**.

4.  In the **Average takt time** field, enter **1**.

5.  In the **Minimum takt time** field, enter **1**.

6.  In the **Maximum takt time** field, enter **2**.

7.  In the **Period for actual cycle time** (**days**) field, enter **1**.

8.  Click **Save** in the action pane.

9.  Note the **Plan status** field for the version is set to **Draft**.

10. Close all forms.

Create the process activity
---------------------------

A new eBook Stylus is being developed to compliment the eBook kits that are sold
at USMF. The Stylus is purchased from an outside vendor and configured at USMF.
A process activity is needed to configure the Stylus and place it in stock for
use elsewhere.

Details for the process activity:

-   Name: Transfer Activity

-   Process quantity: 10 pcs

-   Operating unit: LeanProduction

-   Work cell: 1260

1.  Navigate to **Production Control \> Setup \> Lean Production Flows \>
    Production flows**.

2.  Open the **Mid Range Speaker 2PF** production flow.

3.  On the **Versions** FastTab, click the **Activities** button.

4.  Click **Create new plan activity** button.

5.  Click **Next**..

6.  Enter **Transfer Activity** in the **Name** field.

7.  Enter **10** in the **Process quantity** field.

8.  In the **Unit** drop-down list, select **pcs**.

9.  In the **Operating unit** drop-down list, select **LeanProduction**.

10. Click **Next**.

11. In the **Work cell** replenished drop-down list, select **1260**.

12. Set the **Update on hand on receipt** option to **Yes**.

13. Click **Next**.

14. Select **1260** in the **Replenishing** field.

15. Select **Finished product** in the **Product type** field.

16. Click **Next.**

17. Select Warehouse **13** in the **Transfer from location - warehouse** field.

18. Select location **13** in the **Transfer from location – location** field.

19. For the transfer to location:

20. Select **22** in the **Warehouse** field.

21. Select location **01-01-2-1** in the **Location** field.

22. Select **Shipper** in the **Freighted by** field.

23. Click **Next.**

24. Select **Queue time after** record.

25. Enter **4** in **time** field.

26. Select **hr** in the **time unit** field.

27. Enter **10** in **per quantity** field.

28. Select the **Runtime** record.

29. Enter **2** in **time** field.

30. Select **hr** in **time unit** field.

31. Enter **10** in **per quantity** field.

32. Click **Next.**

33. Click **Finish.**

Configure Process and Transfer
------------------------------

A new car speaker remote is being developed to complement the car speaker kits
sold at Contoso. The CarSpeakProdFlow Standard speaker assembly production flow
needs to be amended to include a transfer activity to move the configured remote
to the Electrical Component warehouse.

Details for production flow transfer activity:
----------------------------------------------

-   Name: RemoteTransfer

-   Process quantity: 10

-   Operating unit: PFModel_1 SeaLeanVS

-   Replenishing resource group: 1250

-   Update on hand on receipt: Yes

-   Update on hand on pick: No

-   Transfer to warehouse ElComp, location Output

-   Freighted by shipper

-   Runtime: 1 min per 25 pcs

Deactivate the current production flow version
----------------------------------------------

1.  Navigate to **Production Control \> Setup \> Lean manufacturing \>
    Production flows.**

2.  Open the **CarSpeakProdFlow Standard speaker assembly** production flow.

3.  On the **Versions** FastTab, select Version **1**.

4.  Click **Deactivate**.

5.  Click **OK**.

Create a new transfer activity
------------------------------

1.  On the **Versions** FastTab, click **Activities**. The **Production flow
    activities** form opens.

2.  Click **Create new plan activity** in the action pane.

3.  Click **Next**.

4.  Enter **RemoteTransfer** in the **Name** field.

5.  In the **Activity type** drop-down list, select **Transfer**.

6.  Enter **10** in the **Process quantity** field.

7.  In the **Unit** drop-down list, select **pcs**.

8.  In the **Operating unit** drop-down list, select **SeaLeanVS**.

9.  Click **Next**. The **Create transfer activity** page opens.

10. In the **Replenishing** drop-down list, select **1250**.

11. Set the **Update on hand on receipt** check box to **Yes**.

12. Set the **Update on hand on pick** check box to **No**.

13. In the **Product type** field, select **Finished product**.

14. Click **Next**. The **Assign transfer locations** page opens.

15. In the **Transfer to location** group, in the **Warehouse** drop-down list,
    select **ElComp 11**.

16. In the **Location** drop-down list, select **Output 11**.

17. In the **Freighted by** drop-down list, select **Shipper**.

18. Click **Next**. The **Assign** activity **time** page opens.

19. In the **Time** field for the **Runtime** row, enter **1**.

20. In the adjacent **Time unit** drop-down list, select **min**.

21. In the **Per quantity** field, enter **25**.

22. Click **Next**. The **Confirm selection** page opens.

23. Click **Finish**. The wizard closes, and a new production flow activity
    appears in the list.

24. Click **Save** in the action pane.

Create the predecessor/successor relationship between the process and transfer activity with no constraints
-----------------------------------------------------------------------------------------------------------

1.  Highlight the **RemoteConfig Wiring Process** activity and, on the
    **Successor** tab, click the **Add successor** button.

2.  Select the **Successor Activity** of **RemoteTransfer**.

3.  For Cycle time ration, type 1.

4.  Select the **OK** button.

5.  Activate the production flow version.

6.  Close the **Production** flow activities form.

7.  On the **Versions** tab, click the **Activation \> Activate** menu button.

8.  Click **OK**

Creating Activity Relations
---------------------------

Pierre needs to revise the Mid-Range Speaker 2 PF production flow to have the
Transfer_W12_to_W11 activity succeeded by the Process_Activity_1 activity.

Details for production flow transfer activity relations:

-   Constraint: 1 hour

-   Cycle time ratio: 2

Add a successor to the production flow activity.
------------------------------------------------

1.  Navigate to **Production control**\>**Setup**\>**Lean production
    flow**\>**Production flows**.

2.  Click the **Name** of the **Mid-Range Speaker 2 PF** production flow.

3.  On the **Versions** FastTab, click **Activities**.

4.  In the list on the left, select the **00074 – Transfer from Warehouse 13 to
    51** activity.

5.  On the **Successors** FastTab, click **Add successor**. The **Create
    activity relation** dialog opens.

6.  In the **Successor** group, in the **Activity** drop-down list, select
    Activity **000082**.

7.  Select the **Constraint** check box.

8.  In the **Constraint value** field, enter **1**.

9.  In the **Units** drop-down list, select **hr**.

10. In the **Cycle time ratio** field, enter **2**.

11. Click **OK**.

12. Click **Save** in the action pane.

13. Close the forms.

Perform Validation and Activation
---------------------------------

Pierre needs to validate the Mid-Range Speaker 2 PF production flow, Version 2,
to confirm that the changes have been correctly implemented.

Validate the production flow.

1.  Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows.** The Production flows form opens.

2.  Click the **Name** of the **Mid-Range Speaker 2 PF** production flow. The
    **Production Flows** form for the selected production flow opens.

3.  On the **Versions** FastTab, select Version **1**.

4.  Click **Validate**. The **Validate production flow** dialog opens.

5.  Click **OK**.

6.  Click **Save** in the action pane.

7.  Close the forms.
