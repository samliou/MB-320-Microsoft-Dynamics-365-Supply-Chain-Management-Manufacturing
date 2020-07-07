Exercise: Create a simple BOM without a version
===============================================

As a new assistant to the product designer at **USMF**, you are asked to create
a simple BOM for a new Light Cabinet. Use the following specifications and
approve the BOM by using employee 000020, Julia Funderburk. Remember you do not
have to add versions to this BOM. Create a simple BOM by using the following
parameters:

-   Name: Light Cabinet

-   Item group: Audio

-   Site: 1

-   Item:

    -   M0005 Enclosure

    -   M0006 Binding posts

    -   P0002 Speaker Damping Foam

-   Quantity for each item: 1

1.  Go to **Product information management \> Bills of materials and formulas \>
    Bills of materials**.

2.  Click **New**.

3.  In the **Name** field, type 'Light Cabinet'.

4.  In the **Site** field, enter or select 1

5.  In the **Item group** field, enter or select Audio

6.  Click **Save**.

7.  In the Bill of materials lines section, click **New**.

8.  In the **Item number** field, type 'M0005'.

9.  Click **New**.

10. In the **Item number** field, type 'M0006'.

11. Click **New**.

12. In the **Item number** field, type 'P0002'.

13. In the action pane, click **Approval**. Select 000020, Julia Funderburk

14. Click **OK**.

15. Click **Save**.

16. Close all pages.

Exercise: Create a BOM in the BOM Designer
==========================================

As a new assistant to the product designer at **USMF**, you have received a new
specification for the enclosure side. An item is not set up for this
specification. Therefore, you only need to create a simple BOM with component
lines. Create a BOM titled “High Quality Speaker” and assign it to the Audio
item group at site 1. Use the BOM designer to add the following items and
quantities from the list and approve the BOM by using employee 000020, Julia
Funderburk. Add items with warehouse 11 and the following quantity:

-   1 qty of M0008 / High End Cabinet / Black

-   2 qty of M0002 / Mid-Range Speaker Unit

-   1 qty of M0009 / Protective Corners

1.  Go to **Product information management \> Bills of materials and formulas \>
    Bills of materials**.

2.  Click **New**.

3.  In the **Name** field, type 'High Quality Speaker'.

4.  In the **Site** field, type '1'.

5.  In the **Item group** field, enter or select Audio

6.  In the action pane, click **Designer**.

7.  Click **BOM lines**.

8.  Click **Add to component BOM**.

9.  In the list, find and select M0008 / High End Cabinet / Black

10. Click **OK**.

11. Click **BOM lines**.

12. Click **Add after line.**

13. In the list, find and select M0009 / Protective Corners

14. Click **OK**.

15. Click **BOM lines**.

16. Click **Add before line**.

17. In the list, find and select M0002 / Mid-Range Speaker Unit

18. Click **OK**.

19. Close the BOM lines page.

20. Refresh the Bill of Materials page.

21. In the Bill of materials lines, find and select the row for M0002 /
    Mid-Range Speaker Unit

22. Set **Quantity** to '2.0000'.

23. Click **Approval**. Select 000020, Julia Funderburk

24. Click **OK**.

25. Close all pages.

Exercise: Creating a BOM with a version
=======================================

The sales department has identified a need for High Quality Speaker, with the
color Rosewood instead of the Black. As the product designer, you are asked to
create a BOM item by using the following specifications:

-   Item number: 72708

-   Item name: High Quality Speaker Rosewood

-   Item group: Audio

-   Item model group: FIFO

-   Storage Dimension group: SiteWH

-   Tracking Dimension group: None

-   Warehouse 11

-   Approved by: 000020, Julia Funderburk

First, create a version named High Quality Speaker Red. Because the
configuration setting is the same as the item D0004, make a copy of the existing
BOM. After the components are copied to the new BOM, remove item M0008 / High
End Cabinet / Black and add item M0008 / High End Cabinet / Red for a quantity
of 1.

Employee 000020, Julia Funderburk must approve the version. Do not activate the
BOM because the item is not ready for use yet.

1.  Go to **Product information management \> Products \> Released products.**

2.  Click **New**.

3.  In the **Product number** field, type '72708'.

4.  In the **Product name** field, type 'High Quality Speaker Red'.

5.  In the **Item model group** field, enter or select FIFO

6.  In the **Item group** field, enter or select Audio

7.  In the **Storage dimension** group field, enter or select SiteWH

8.  In the **Tracking dimension** group field, enter or select None

9.  Click **OK**.

10. On the Action Pane, click **Manage inventory**.

11. Click **Default order settings**.

12. In the **Default order type** field, select 'Production'.

13. Under the **Inventory** fasttab, In the **Default warehouse** field, type
    '11'.

14. Close the page.

15. On the Action Pane, click **Engineer**.

16. Click **Designer**.

17. Click **BOM**.

18. Click **Create version**.

19. In the **Name** field, type 'High Quality Speaker Rosewood'.

20. Select **Yes** in the **Copy** field.

21. In the **Site** field, type '1'.

22. Click **OK**.

23. In the **Item number** field, enter or select D0004

24. Click **OK**.

25. In the tree, select 'Item number: 72708\\M0008 / High End Cabinet'.

26. Click **BOM lines**.

27. Click **Delete**.

28. Click **BOM lines**.

29. Click **Add before line**.

30. In the list, find and select M0008 / High End Cabinet / Rosewood

31. Click **OK**.

32. In the tree, select 'Item number: 72708'.

33. Click **BOM**.

34. Click **BOM versions**.

35. Click **Approve**. Select 000020, Julia Funderburk

36. Select **Yes** in the **Do you also want to approve the bill of materials?**
    field.

37. Click **OK**.

38. Close all pages.

Exercise: Create a Production Order
===================================

Manually create a production order for 10 pcs of Item: '72708' as follows:

-   Use Production PRD_00000582.

-   Use Item '72708'. You must have completed exercise 3.

-   Set Order quantity to 10 pieces.

-   Set the Delivery date to the current date plus four days.

-   Set the Delivery time to 10:15 A.M.

1.  Go to **Production control \> Production orders \> All production orders**.

2.  Click **New production order**.

3.  In the **Item number** field, enter or select 72708

4.  Set **Quantity** to '10.00'.

5.  In the **Time** field, enter 10:15 AM

6.  Click **Create**.

7.  Click **Estimate**.

8.  Click **OK**.

9.  Click **Release**.

10. Click **OK**.

11. Click **Start**.

12. Click **OK**.

13. Click **Report as finished**.

14. Click **OK**.

15. Click **End**.

16. Click **OK**.

17. Close all pages.
