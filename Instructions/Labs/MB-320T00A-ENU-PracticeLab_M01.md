### Before you begin

To get the most out of this exercise and the other exercises that are included
with this module, we recommend that you have the standard sample data available
in Finance and Operations that is installed using Lifecycle services (LCS).

Exercise - Define production control parameters
===============================================

Jerry, the Operations manager at **USMF**, wants to make some changes to the
policies. He has instructed you that routes should not be allowed to be modified
or have their approvals removed. Instead, a new route operation should be
created, and the effective dates updated. Your task is to update the parameters
to meet these business requirements.

1.  Go to **Production control \> Setup \> Production control parameters**.

2.  Set the **Block removal of approval** slider to **Yes** under the **Routes
    group**.

3.  Set the **Block editing** slider to **Yes** under the **Routes group**.

4.  Click **Save**.

5.  Close all pages.

Exercise - Create production pools
==================================

Jerry, the Operations manager at USMF, wants more visibility into production
orders that are delayed. He has given you instructions to track the following:

-   Subcontracted production orders that are missing deliveries.

-   Production orders with missing materials.

-   Orders delayed dues to machine failures.

Using the information provided, create three new production pools for use on new
production orders.

Create a production pool for delayed subcontracted work
-------------------------------------------------------

1.  Open **Production control \> Setup \> Production \> Production pools**

2.  Click **New** to create a new pool.

3.  Type “Delay-Sub” in the **Pool** field.

4.  Type “Subcontracted Work Delayed” in the **Name** field.

Create a production pool for missing materials
----------------------------------------------

1.  Click **New** to create a new pool.

2.  Type “MATMISSING” in the **Pool** field.

3.  Type “Materials Missing” in the **Name** field.

Create a production pool for machine failures
---------------------------------------------

1.  Click **New** to create a new pool.

2.  Type “MACHFAIL” in the **Pool** field.

3.  Type “Machine Failure” in the **Name** field.

4.  Close all pages.

Exercise - Create and manage resources
======================================

Company USMF has bought a new packing robot for their speaker packing workshop.
The packing robot will reduce the need for manual labor in the speaker packing
workshop. Therefore, some workers from this group can be reassigned to perform
other work, as the new packing robot becomes fully operational.

Create capabilities
-------------------

1.  Go to **Organization administration\>Resources\>Resource capabilities**.

2.  Click **New**.

3.  Type "GTL-Assembly " in the **Capability** field and "Assembly" in the
    **Description** field.

4.  Click **New**.

5.  Type "GTL- Packing" in the **Capability** field and "Packing" in the
    **Description** field.

6.  Close the **Resource capabilities** page.

Assign resources to capability
------------------------------

1.  Go to **Organization administration \> Resources \> Resource capabilities**.

2.  Select **GTL-Assembly** from the list of capabilities.

3.  Click **Add** from the Action Pane.

4.  Select "5110", Assembly worker 1, in the **Resource** field.

5.  Accept the default **Expiration** date of **Never**.

6.  Type "1" in the **Priority** field.

7.  Accept the default **Level** of 0.00.

8.  Repeat steps 3 to 7, for the resource 5111.

9.  Close the **Resource capabilities** page.

Assign capabilities to a resource
---------------------------------

1.  Go to **Organization administration \> Resources \> Resources**.

2.  Select resource 5111 in the grid.

3.  Expand the **Capabilities** FastTab.

4.  Select **View \> All** from the Action Pane.

5.  Click **Add** from the Action Pane.

6.  Type "GTL-Packing" in the **Capability** field.

7.  Accept the default **Effective** date of today's date.

8.  Accept the default **Expiration** date of **Never**.

9.  Accept the default **Level** of 0.00.

10. Type "2" in the **Priority** field

11. Close the **Resources** page.
