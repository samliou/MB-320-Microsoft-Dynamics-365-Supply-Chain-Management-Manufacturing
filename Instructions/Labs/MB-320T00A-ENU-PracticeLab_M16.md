Exercise 1: Set up Commodity Pricing
====================================

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples. The sales price of the Apple
Pie, part P9300, manufactured from this sugar should be based on a margin of 45%
and a cost multiple of 1.25 for all quantities. As the pricing employee in the
company, set up the cost basis and pricing template for this scenario.

Configure an item
-----------------

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the **Quick Filter** to filter on the **Item number** field with a value
    of **'P9100'**.

3.  On the Action Pane, select **Manage inventory**.

4.  Select **Default order settings**.

5.  Select **Edit**.

6.  In the **Default order type** field, select **'Production'**.

7.  Select **Save**.

8.  Close all pages.

Create Cost Basis
-----------------

1.  Go to **Inventory management \> Setup \> Commodity pricing \> Cost basis
    type.**

2.  Click **New** if necessary.

3.  In the Cost basis type field, type **'NYMEX'**.

4.  In the Description field, type **'New York Mercantile Exchange'**.

5.  Click **Save**.

6.  Close the page.

Create Pricing Template
-----------------------

1.  Go to **Inventory management \> Setup \> Commodity pricing \> Pricing
    template**.

2.  Click **New**.

3.  In the Pricing template field, type **'Apples'**.

4.  In the Description field, type **'Apples'**.

5.  Click **Save**.

Create Quantity and Margin Template
-----------------------------------

1.  Click Quantity and margin template.

2.  Click **New**.

3.  In the Item relation field, type **'P9100'**.

4.  In the Site field, type '**1**'.

5.  Set Cost multiplier to **'1.25'**.

6.  Set Margin percentage to **'45'**.

7.  In the Warehouse field, type **'12'**. If it’s not visible, find it in the
    Dimension fast tab.

8.  Click **Save**.

9.  Close the page.

Complete Inventory Parameter Setup
----------------------------------

1.  Go to **Inventory management \> Setup \> Inventory and warehouse management
    parameters**.

2.  Click the Commodity pricing tab.

3.  In the Dimension set field, enter or select **MA+BU**.

4.  In the Cost basis type field, enter or select **NYMEX**.

5.  Select **Yes** in the Keep BOM/Formula calculations field.

6.  Right click Trade agreement and view details.

7.  Click **New**.

8.  In the Name field, type **'Price_S'**.

9.  In the Description field, type **'Sales Price Adjustment Journal'**.

10. In the Relation field, select **'Price (sales)**'.

11. Click **Save**.

12. Close the page.

13. In the Trade agreement field, enter or select **Price_S**.

14. Click **Save**.

15. Close the page.

Pricing calculation
-------------------

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Pricing calculation.**

2.  Click **New**.

3.  Note that the **Cost basis type** field is set to **NYMEX**.

4.  In the Run effective date field, enter today’s date.

5.  In the Run expiry date field, enter a date in the future.

6.  Click **Save**.

7.  Close the page.

Exercise 2: Create Price Data and Update Agreements
===================================================

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples. The sales price of the apple
sauce manufactured from the apples is to be based upon the fluctuations in the
pricing of the apples. Complete the calculation of the sales pricing for the
apple sauce for the weeks of 2/20/17 and 2/27/17 and approve and post the trade
agreements that are created.

Complete Price Calculations
---------------------------

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Create price and margin data**.

2.  In the Pricing calculation field, enter or select **000001** for NYMEX.

3.  In the Pricing template field, enter or select **Apples**.

4.  Click **OK**.

Review Price Calculation data and create trade agreements
---------------------------------------------------------

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \> Price
    margin update**.

2.  If the price calculations completed successfully, you will see your new
    pricing. Click **Lines**.

3.  Click **Update trade agreements**.

4.  Click **OK**.

5.  Close the page.

6.  In the list, find and select the desired record.

7.  Click **Lines**.

8.  Click **Update trade agreements**.

9.  Click **OK**.

10. Close the page.

Post Trade Agreements
---------------------

1.  Go to **Sales and marketing \> Prices and discounts \> Trade agreement
    journals**.

2.  Click **Lines**.

3.  Click **Post**.

4.  Click **OK.**

5.  Click **Lines**.

6.  Click **Post**.

7.  Click **OK**.

8.  Close the page.

Exercise 3: Setup Pricing Calculation
=====================================

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples. The sales price of the apple
sauce manufactured from the apples is to be based upon the fluctuations in the
pricing of the apples. The weekly pricing for the week of 02/20/17 and 02/27/17
has been received as 0.14/lb and 0.15/lb respectively. Enter the pricing
calculation based upon this data.

Create Pricing Calculation for 02/20/2017 – 02/26/2017
------------------------------------------------------

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Pricing calculation**.

2.  Click **New**.

3.  In the Cost basis type field, enter or select **NYMEX**.

4.  In the Site field, type **'1'**.

5.  In the Run effective date field, set the date to **'2017-02-20'** or your
    local equivalent.

6.  In the Run expiry date field, set the date to **'2017-02-26'** or your local
    equivalent.

7.  Click **Save**.

Enter commodity pricing data
----------------------------

1.  Click **Commodity pricing**.

2.  Click **New**.

3.  In the Item number field, type **'M9103'**.

4.  In the Warehouse field, enter or select a value.

5.  Set New cost to **'0.14'**.

6.  Click **Save**.

7.  Close the page.

Create Pricing Calculation for 02/27/2017 – 03/05/2017
------------------------------------------------------

1.  Click **New**.

2.  In the Cost basis type field, enter or select **NYMEX**.

3.  In the Site field, type **'1'**.

4.  In the Run effective date field, set the date to **'2017-02-27'.**

5.  In the Run expiry date field, set the date to **'2017-03-05'**.

6.  In the Previous run field, enter or select a value.

Enter commodity pricing data
----------------------------

1.  Click **Commodity pricing**.

2.  Click **New**.

3.  In the Item number field, type **'M9103'**.

4.  In the Warehouse field, enter or select a value.

5.  Set New cost to **'0.15'**.

6.  Click **Save**.

7.  Close the page.

Exercise 4: Product compliance
==============================

Create PSDS for an Item
-----------------------

In company USP2, product M7001, Sulfur Dioxide, has been setup as a regulated
and restricted product. A new PSDS has been obtained from the vendor and must be
attached to the item. Using the attached file, create the PSDS record and
activate it based upon an effective date range of 6/1/2016 to 5/31/2019.

### Create PSDS List

1.  Go to **Inventory management \> Setup \> Product compliance \> Product
    safety data sheet**.

2.  Click **New**.

3.  In the Country/region field, type **'USA'**.

4.  Click **Save**.

5.  Close the page.

### Create PSDS Record

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **'M7001'**.

3.  On the Action Pane, click **Manage inventory**.

4.  Click **Safety data sheet**.

5.  Click **New**.

6.  In the Document Name field, type a value.

7.  Select **Yes** in the Active field.

8.  In the Country/region field, type a value.

9.  In the Approval source field, enter or select a value.

10. In the Major version field, enter a number.

11. In the Approval date field, set the date to **'2016-06-01'** or your local
    equivalent.

12. In the Effective date field, set the date to **'2016-06-01'.**

13. In the Expiry date field, set the date to **'2019-05-31'**.

14. Click **Save**.

### Upload PSDS File

1.  Click **Attach**. It’s the paper clip near the top right.

2.  Click **New**.

3.  Click **File**.

4.  Click **Browse**

5.  Select the MSDS file, or any file to act as it.

6.  In the Restriction field, select **'External'**.

7.  Click **Save**.

8.  Close the page.

9.  Refresh the page.

10. Click **Open** document.

11. Close the page.

Reporting Details for an Item
-----------------------------

In company USP2, product M7001, Sulfur Dioxide, has been setup as a regulated
and restricted product. As the product safety manager, the OSHA Product Name
should be set a Sulfur Dioxide with a threshold quantity of 5, an EHS reportable
quantity of 500 and a TPQ of 500. The CAS number should also be set as
7446-09-5. The annual usage quantity must also be updated for reporting.

### Enter Product Reporting Details

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **'m7001'**.

3.  On the Action Pane, click **Manage inventory**.

4.  Click **Reporting details**.

5.  Click **Edit**.

6.  In the OSHA product name field, type **'Sulfur Dioxide'**.

7.  Set OSHA threshold quantity to '**5'**.

8.  Set EHS reportable quantity to **'500'**.

9.  Set EHS threshold planning quantity to **'500'**.

10. Click **Save**.

### Enter CAS Number

1.  Click **Item CAS relations**.

2.  In the CAS number field, type **'7446-09-5'**.

3.  In the CAS name field, type **'Sulfur Dioxide'**.

4.  Click **Save**.

5.  Close the page.

### Update annual usage quantities

1.  Click **Update quantities**.

2.  Close the page.

Create SO and Print PSDS
------------------------

In company USP2, product M7001, Sulfur Dioxide, has been setup as a regulated
and restricted product. A new request for 100 oz of M7001 from customer US-031
on April 4, 2017 has been received. As the sales representative, enter the sales
order and note the messages received. Ship the material and verify that the
valid PSDS printed upon posting of the packing list.

### Create Sales Order

1.  Go to **Accounts receivable \> Orders \> All sales orders**.

2.  Click **New**.

3.  In the Customer account field, type **'us-031'.**

4.  In the Warehouse field (General section), type **'11'**.

5.  In the Requested receipt date field, set the date to **a near future date**.

6.  Click **OK**.

7.  In the Item number field, type **'m7001'**.

8.  Set Quantity to **'100'**.

9.  In the Unit price field, enter a number.

10. Click **Save**.

### Complete Reservation

1.  Click **Inventory**.

2.  Click **Reservation**.

3.  Click **Reserve lot**.

4.  Close the page.

### Post Packing Slip and Print PSDS

1.  Click **Pick and pack \> Post packing slip**.

2.  Click **OK**.

3.  Click **OK**.

4.  Verify PSDS was printed if that option was desired.

5.  Close the page.
