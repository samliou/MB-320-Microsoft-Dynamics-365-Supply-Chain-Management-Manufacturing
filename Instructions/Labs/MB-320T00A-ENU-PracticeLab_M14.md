Exercise 1: Create Approved Vendor List
=======================================

In company **USP2** it has been determined that approved vendor control shall be
placed on item M7001, with the approved vendor being US-113. Create the approved
vendor list for the item and set the vendor check method to Warning Only.

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'M7001'.

3.  Click the item number to get from the grid to the details page.

4.  On the Action Pane, click **Purchase**.

5.  Click **Setup**.

6.  Click **Add**.

7.  In the **Vendor** field, type 'US-113'.

8.  Click **Save**.

9.  Close the page.

Set Vendor Check Method to Warning Only
---------------------------------------

1.  Click **Edit**.

2.  In the **Approved vendor check method** field in the Purchase Fast Tab,
    select **Warning** Only.

3.  Click **Save**.

4.  Close the page.

Exercise 2: Create Co-Products and By-Products
==============================================

**Contoso Process Company (USPI)** has purchased a small oil refinery and will
start to manufacture gasoline from a stream of crude oil. In this process the
co-products of Kerosene and Diesel fuel are also produced. A by-product of
wastewater is also created. As the product designer you have been asked to
create the following items in Finance and Operations:

-   Product Number: P15000

    -   Product Name: Gasoline

    -   Production Type: Formula

-   Product Number: P16000

    -   Product Name: Kerosene

    -   Production Type: Co-Product

-   Product Number: P17000

    -   Product Name: Diesel Fuel

    -   Production Type: Co-Product

-   Product Number: B18000

    -   Product Name: Waste Water

    -   Production Type: By-Product

-   Product Number: M12000

    -   Product Name: Crude Oil

    -   Production Type: None

Create new Formula product
--------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Click **New**.

3.  In the **Product number** field, type 'P15000'.

4.  In the **Product name** field, type 'Gasoline'.

5.  In the **Item model group** field, enter or select a value.

6.  In the **Item group** field, enter or select a value.

7.  In the **Storage dimension group** field, enter or select a value.

8.  In the **Tracking dimension group** field, enter or select a value.

9.  In the I**nventory unit** field, type 'gal'.

10. In the **Purchase unit** field, type 'gal'.

11. In the **Sales unit** field, type 'gal'.

12. In the **BOM unit** field, type 'gal'.

13. Click **OK**.

14. In the **Production type** field in the Engineer Fast Tab, select 'Formula'.

15. In the Shelf life period in days, in Manage inventory Fast Tab, enter 365.

16. Click **Save**.

17. Close the page.

Create the new Co-Products
--------------------------

1.  Click **New**.

2.  In the **Product number** field, type 'P16000'.

3.  In the **Product name** field, type 'Kerosene'.

4.  In the **Item model group** field, enter or select a value.

5.  In the **Item group** field, enter or select a value.

6.  In the **Storage dimension group** field, enter or select a value.

7.  In the **Tracking dimension group** field, enter or select a value.

8.  In the **Inventory unit** field, type 'gal'.

9.  In the **Purchase unit** field, type 'gal'.

10. In the **Sales unit** field, type 'gal'.

11. In the **BOM unit** field, type 'gal'.

12. Click **OK**.

13. In the Shelf life period in days, in Manage inventory Fast Tab, enter 365.

14. In the **Production type** field in the Engineer Fast Tab, select
    'Co-product'.

15. In the **Planning formula** field, enter P15000

16. Click **Save**.

17. Close the page.

18. Click **New**.

19. In the **Product number** field, type 'P17000'.

20. In the **Product name** field, type 'Diesel Fuel'.

21. In the **Item model group** field, enter or select a value.

22. In the **Item group** field, enter or select a value.

23. In the **Storage dimension group** field, enter or select a value.

24. In the **Tracking dimension group** field, enter or select a value.

25. In the **Inventory unit** field, type 'gal'.

26. In the **Purchase unit** field, type 'gal'.

27. In the **Sales unit** field, type 'gal'.

28. In the **BOM unit** field, type 'gal'.

29. Click **OK**.

30. In the **Production type** field in the Engineer Fast Tab, select
    'Co-product'.

31. In the **Planning formula** field, enter P15000

32. Click **Save**.

33. Close the page.

Create the new By-Products
--------------------------

1.  Click New.

2.  In the **Product number** field, type 'B18000'.

3.  In the **Product name** field, type 'Waste Water'.

4.  In the **Item model** group field, enter or select a value.

5.  In the **Item group** field, enter or select a value.

6.  In the **Storage dimension group** field, enter or select a value.

7.  In the **Tracking dimension group** field, enter or select a value.

8.  In the **Inventory unit** field, type 'gal'.

9.  In the **Purchase unit** field, type 'gal'.

10. In the **Sales unit** field, type 'gal'.

11. In the **BOM unit** field, type 'gal'.

12. Click **OK**.

13. In the Shelf life period in days, in Manage inventory Fast Tab, enter 365.

14. In the **Production type** field, select 'By-product'.

15. Click **Save**.

16. Close the page.

Create the new raw material
---------------------------

1.  Click **New**.

2.  In the **Product number** field, type 'M12000'.

3.  In the **Product name** field, type 'Crude Oil'.

4.  In the **Item model group** field, enter or select a value.

5.  In the **Item group** field, enter or select a value.

6.  In the **Storage dimension group** field, enter or select a value.

7.  In the **Tracking dimension group** field, enter or select a value.

8.  In the **Inventory unit** field, type 'gal'.

9.  In the **Purchase unit** field, type 'gal'.

10. In the **Sales unit** field, type 'gal'.

11. In the **BOM unit** field, type 'gal'.

12. Click **OK**.

13. In the **Production type** field, select 'None'.

14. Click **Save**.

15. Close all pages.

Exercise 3: Create a Formula with Co-Products and By-Products
=============================================================

The engineering department has finished the review of the data in the new
refinery and determined the formula should be as specified below. As the product
definition employee, create the formula, along with assigning the co-products
and by-products to the formula and cost allocation.

-   Product Number: P15000

-   Product Name: Gasoline

-   Formula Size: 500 gal

-   Formula Line: M12000 (Crude Oil), QTY 1000 gal

-   Formula Line: M2001 (DI Water), QTY 600 gal

-   Co-Product Line: P16000 (Kerosene), QTY 50 gal 10% cost allocation

-   Co-Product Line: P17000 (Diesel Fuel), QTY 350 gal 32% cost allocation

-   By-Product Line: B18000 (Waste Water), QTY 600 gal, 5% cost allocation

-   Approved by: Glen John

Create a formula for part P15000
--------------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to find records. For example, filter on the Item number
    field with a value of 'p15000'. Note the lowercase – it is not case
    sensitive.

3.  Click the ellipsis, if needed, to get to the Engineer tab on the action
    pane.

4.  Click **Formula versions**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type ‘GAS001’.

8.  In the **Name** field, type 'Gasoline'.

9.  In the **Site** field, enter or select 1.

10. Click **OK**.

11. In the **Lines** or **header** field, select Header

12. In the version, set **Formula size** to '500'.

13. Click **Save**.

Add Formula Lines to Formula
----------------------------

1.  In the **Lines** or **header** field, select Lines

2.  Click **New**.

3.  In the **Item number** field, type 'M12000'.

4.  In the **Warehouse** field, enter or select a value.

5.  Set **Quantity** to '1000'.

6.  Click **New**.

7.  In the **Item number** field, type 'M2001'.

8.  Set **Quantity** to '600'.

9.  Click **Save**.

10. Close the page.

Add Co-Products and By-Products with Cost Allocation
----------------------------------------------------

1.  Click **Co-products**.

2.  Click **New**.

3.  In the **Item number** field, type 'P16000'.

4.  In the **Warehouse** field, enter or select a value.

5.  Set **Quantity** to '50'.

6.  In the **Co-product cost allocation** field, select 'Manual'.

7.  Set **Cost allocation percent** to '10'.

8.  Click **Save**.

9.  Click **New**.

10. In the **Item number** field, type 'P17000'.

11. In the **Warehouse** field, type a 11.

12. Set **Quantity** to '350'.

13. In the **By-product cost allocation** field, select ‘Percent’ .

14. Set **Cost allocation percent** to '32'.

15. Click **Save**.

16. Click **New**.

17. In the **Item number** field, type 'B18000'.

18. In the **Warehouse** field, type a value.

19. Set **Quantity** to '600'.

20. In the **By-product cost allocation** field, select 'Percent'.

21. Set **By-product burden amount** to '5'.

22. Click **Save**.

23. Close the page.

Approve and activate the formula
--------------------------------

1.  Click **Approve**.

2.  In the **Approved by** field, enter or select **000528** for Glen John.

3.  Select the Do you also want to approve the formula? check box.

4.  Click **OK**.

5.  Click **Activate**.

6.  Close the page.

Exercise 4: Create a New Formula with a Version from the Released Products Form
===============================================================================

The marketing department at Contoso Orange Juice factory has determined the need
for production of a new product for Frozen Apple Juice Concentrate. As the
product designer you are asked to create a formula version with the following
details.

-   Product Number: P7100

-   Product Name: Frozen Apple Juice Concentrate

-   Formula Size: 1000 gal

-   Formula Line: M9103 (Apples), QTY 800

-   Formula Line: M8001 (Asorbic Acid), QTY 660

-   Formula Line: M8003 (Vitamin A), QTY 40

-   Formula Line: M8004 (Vitamin C), QTY 18

-   Formula Line: M7003 (Sucrose), QTY 33

-   Formula Line: M8008 (Can), QTY 2400

-   Approved by: Glen John

Create new product
------------------

1.  In the **USP2** company go to **Product information
    management\>Products\>Released products**

2.  Click **New**.

3.  In the **Product number** field, type 'P7100'.

4.  In the **Product name** field, type 'Frozen Apple Juice Concentrate'.

5.  In the **Search name** field, type 'FrozenAppleJuice'.

6.  In the **Item model group** field, enter or select a value.

7.  In the **Item group** field, enter or select a value.

8.  In the **Storage dimension group** field, enter or select a value.

9.  In the **Tracking dimension group** field, enter or select a value.

10. In the **Inventory unit** field, enter 'lb'.

11. In the **Purchase unit** field, type 'lb'.

12. In the **Sales unit** field, type 'lb'.

13. In the **BOM unit** field, type 'lb'.

14. Click **OK**.

15. In the **Production type** field in the Engineer Fast Tab, select 'Formula'.

16. In the Shelf life period in days field in the Manage inventory Fast Tab,
    type 180.

17. Click **Save**.

Create a formula with description 'For making Frozen Apple Juice Concentrate’
-----------------------------------------------------------------------------

1.  Click **Formula versions** in the Engineer tab in the action pane.

2.  Click **New**.

3.  Click **Formula and formula version**.

4.  In the **Formula** number field, type 'FOR-7100'.

5.  In the **Name** field, type ''For making Frozen Apple Juice Concentrate'.

6.  In the **Site** field, enter or select 1.

7.  Click **OK**.

Create formula lines to enter the ingredients with quantities and relevant unit of measurement
----------------------------------------------------------------------------------------------

1.  In the **Lines** or **header** field, select 'Header'.

2.  Set **Formula size** to '1000'.

3.  Set **From formula size** in the Formula versions Fast Tab to '1000'.

4.  In the **Lines** or **header** field, select 'Lines'.

5.  In the Formula lines fast tab, click **New**.

6.  In the **Item number** field, type 'M9103'.

7.  Set **Quantity** to '800'.

8.  Click **New**.

9.  In the **Item number** field, type ‘M8001’.

10. Set **Quantity** to '660'.

11. Click **New**.

12. In the **Item number** field, type 'M8003'.

13. Set **Quantity** to '40'.

14. Click **New**.

15. In the **Item number** field, type 'M8004'.

16. Set **Quantity** to '18'.

17. Click **New**.

18. In the **Item number** field, type 'M7003'.

19. Set **Quantity** to '33'.

20. Click **New**.

21. In the **Item number** field, type 'M8008'.

22. Set **Quantity** to '2400'.

23. Click **Save**.

Approve and activate the formula
--------------------------------

1.  Click **Approve formula**.

2.  In the **Approved by** field, enter or select 000528 for Glen John.

3.  Click **OK**.

4.  In the **Lines** or **header** field, select 'Header'.

5.  Click **Approve** in the versions section.

6.  In the **Approved b**y field, enter or select a value.

7.  Click **OK**.

8.  Click **Activate**.

9.  Close the page.

Exercise 5: Copy and Modify Formula Versions
============================================

Analysis of the production orders for P8000 in company USP2 have shown that the
scrap factors and consumption amount of part P6000 need to be updated. The
formula is to be revised, updated and approved/activated with an effective date
of 12/15/2016.

Copy the existing formula for P8000
-----------------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'P8000'.

3.  In the list, click the link in the selected row.

4.  Click **Formula versions in the Engineer tab on the action pane**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type F01.

8.  In the **Name** field, type V01.

9.  Set the **Copy** to Yes

10. In the **Site** field, enter or select 1.

11. Click **OK**.

12. In the **Formula version** field, select the previous formula version
    For-00002.

13. Click **OK**.

Update line for P6000
---------------------

1.  In the list, find and select the record for **P6000**.

2.  Set **Quantity** to '0.35'.

3.  Click the **Setup** tab.

4.  In the **Variable scrap** field, enter a number.

5.  Click **Save**.

6.  Close the page.

Date out the old version and date in the new version
----------------------------------------------------

1.  In the list, find and select the original formula version For-00002.

2.  In the **To date** field, set the date to '12/14/2016'.

3.  Click **Save**.

4.  In the list, find and select the new formula version F01.

5.  In the **From date** field, set the date to '12/15/2016'.

6.  Click **Save**.

Approve and activate the formula
--------------------------------

1.  Click Formulas \> Formula.

2.  Click **Approve formula**.

3.  In the **Approved by** field, enter or select a value.

4.  Close the screen to go back to the Formula versions screen.

5.  Click Formula version \> Approve.

6.  In the **Approved by** field, enter or select a value.

7.  Click **OK**.

8.  Click **Activate**.

9.  Close the page.

Exercise 6: Create and Update Scalable Formula
==============================================

Your manufacturing plant has obtained a new mixer that is 1.5 times the size of
the current mixer used to make part P9500 in company USP2. Engineering has
determined that the vitamin compounds do not need to increase in quantity but
the other ingredients do. Create a new formula for the larger size based on the
existing formula for the part.

Copy the existing formula for P9500
-----------------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'P9500'.

3.  In the list, click the link in the selected row.

4.  Click **Formula versions in the Engineer tab in the action pane**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type **P9500V0**.

8.  In the **Name** field, type a V0.

9.  Select the **Copy** option.

10. In the **Site** field, enter or select 1.

11. Click **OK**.

12. In the **Formula version** field, select the current version

13. Click **OK**.

Verify the lines are flagged as scalable for P9500 except for the vitamin compounds
-----------------------------------------------------------------------------------

1.  In the lines, find the vitamin compounds.

2.  Select or clear the **Scalable** check boxes.

3.  Click **Save**.

Update the formula size and from formula size in the new formula
----------------------------------------------------------------

1.  In the Lines or header field, select **header**.

2.  Set **Formula size** to '1500'.

3.  Set **From formula size** to '1500'.

4.  Click **Save**.

Approve and activate the formula
--------------------------------

1.  In the Lines or header field, select **lines**.

2.  Click **Save**.

3.  Click **Approve formula**.

4.  In the **Approved by** field, enter or select a value.

5.  Click **OK**.

6.  In the Lines or header field, select **header**.

7.  Click **Approve** in the Versions grid.

8.  In the **Approved by** field, enter or select a value.

9.  Click **OK**.

10. Click **Activate**.

11. Close the page.

Exercise 7: Create A Percentage Based Formula
=============================================

Company USP2 has been contracted to make a new orange juice with the following
volume percentages for the final mixture. The mixture should also have Vitamin C
and Vitamin A added per the mixing instructions below. The volume batch size is
to be 1500 gallons.

| **Ingredient** | **Recipe percent / quantity** |
|----------------|-------------------------------|
| P9500          | **5%**                        |
| M9001          | **92%**                       |
| M7004          | **3%**                        |
| M8004          | **1.33 lb/1500 gal.**         |
| M8003          | **1.1 LB/1500 gal.**          |

Create new released product
---------------------------

1.  In the **USP2** company go to **Product information
    management\>Products\>Released products**

2.  Click **New**.

3.  In the **Product number** field, type 'P6100'.

4.  In the **Product name** field, type ‘Orange Juice'.

5.  In the **Search name** field, type 'Orange Juice'.

6.  In the **Search name** field, type 'Orange Juice'.

7.  In the **Item model group** field, enter or select a value.

8.  In the **Item group field**, enter or select a value.

9.  In the **Storage dimension group** field, enter or select a value.

10. In the **Tracking dimension group** field, enter or select a value.

11. In the **Inventory unit** field, enter gal

12. In the **Purchase unit** field, type gal.

13. In the **Sales unit** field, type gal.

14. In the **BOM unit** field, type gal.

15. Click **OK**.

16. In the **Production type** field in the Engineer Fast Tab, select
    **'Formula'**.

17. In the Shelf life period in days field in the Manage inventory Fast Tab,
    enter 180.

18. Click **Save**.

Copy the existing formula for P9500
-----------------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'P9500'.

3.  In the list, click the link in the selected row.

4.  Click **Formula versions** in the Engineer tab in the action pane.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type a value.

8.  In the **Name** field, type a value.

9.  Select the **Copy** option.

10. In the **Site** field, enter or select 1.

11. Click **OK**.

12. In the **Formula version** field, select the current version

13. Click **OK**.

Verify the lines are flagged as scalable for P9500 except for the vitamin compounds
-----------------------------------------------------------------------------------

1.  In the lines, find the vitamin **compounds**.

2.  Select or clear the **Scalable** check boxes.

3.  Click **Save**.

Update the formula size and from formula size in the new formula
----------------------------------------------------------------

1.  In the Lines or header field, select **header**.

2.  Set the version’s **Formula size** to '1500'.

3.  Set the version’s **From formula size** to '1500'.

4.  Click **Save**.

Approve and activate the formula
--------------------------------

1.  In the Lines or header field, select **lines**.

2.  Click **Save**.

3.  Click **Approve formula**.

4.  In the **Approved by** field, enter or select a value.

5.  Click **OK**.

6.  In the Lines or header field, select **header**.

7.  Click **Approve** in the Versions grid.

8.  In the **Approved by** field, enter or select a value.

9.  Click **OK**.

10. Click **Activate**.

11. Close all pages.

Exercise 8: Create a Step Consumption Formula
=============================================

The formula for product **P9500** in company **USP2** is to be updated to change
Formula Line **M9003** from a linear consumption to a step-wise consumption. The
consumption on the line shall be:

-   0-1400: 5.5

-   1400-2400: 10.6

-   2400+: 15.8

Copy the existing formula for **P9500**
---------------------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **'P9500'**.

3.  In the list, click the link in the selected row for **P9500**.

4.  Click Engineer \> Formula \> **Formula versions**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type **P9500V1**.

8.  In the Name field, type **V1**.

9.  Select the **Copy** option

10. In the **Site** field, enter or select 1.

11. Click **OK**.

12. In the **Formula version** field, select the current version

13. Click **OK**.

Set the line for **M9003** in the new formula to step-wise consumption and set the step levels
----------------------------------------------------------------------------------------------

1.  In the lines, find the line for **M9003**.

2.  Click the **Setup** tab in line details

3.  In the **Formula** field, select **'Step'**.

4.  Click the **Step consumption** tab.

5.  Set **Quantity** to '5.5'.

6.  Click **New**.

7.  Set **From series** to '1400'.

8.  Set **Quantity** to '10.6'.

9.  Click **New**.

10. Set **From series** to '2400'.

11. Set **Quantity** to '15.8'.

12. Click **Save**.

13. Close all pages.

Date out the old formula and date in the new one
------------------------------------------------

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **'P9500'**.

3.  In the list, click the link in the selected row for **P9500**.

4.  Click Engineer \> Formula \> **Formula versions**.

5.  In the list, find and select the old formula.

6.  Click **Edit**.

7.  In the **To date** field, set the date to '12/27/2016'.

8.  Click **Save**.

9.  In the list, find and select the new formula.

10. In the **From date** field, set the date to '12/28/2016'.

11. Click **Save**.

Approve and activate the formula
--------------------------------

1.  Click **Approve**.

2.  In the **Approved by** field, enter or select an employee.

3.  Select the **Do you also want to approve the formula?** option.

4.  Click **OK**.

5.  Click **Activate**.
