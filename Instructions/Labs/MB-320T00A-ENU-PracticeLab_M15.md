Exercise 1: Work with batch attribute
=====================================

In company USPI a new requirement for part P4000, Polypropylene Pellets, to test
and record the melting point for each batch is needed. As the product definition
employee, create the batch attribute for melting point as an integer attribute
with a min of 0 and max of 500.

Create new Batch Attribute
--------------------------

1.  Go to Inventory Management -\> Setup -\> Batch -\> Batch attributes.

2.  Click New.

3.  In the Attribute field, type 'MeltingPoint'.

4.  In the Description field, type 'Melting Point (C)'.

5.  In the Attribute type field, select ‘Integer’.

### Set Attribute MIN and MAX

1.  In the Minimum field, type '0'.

2.  In the Maximum field, type '500'.

3.  In the Increment field, type '1'.

4.  Click Save.

5.  Close the page.

Assign a Batch Attribute
------------------------

In company USPI a new requirement for part P4000, Polypropylene Pellets, to test
and record the melting point for each batch is needed. The item specific
requirements are 130 – 171o C. Customer US-024 requires a melting point of 135 –
165o C for use in their manufacturing processes. As the product definition
employee, associate the batch attribute with the item and the customer with the
correct attribute ranges.

### Associate Batch Attribute to the item

1.  Go to **Product Information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **'p4000'**.

3.  Click **Product specific** in Batch Attributes group on Manage Inventory tab

4.  Click **New**.

5.  In the Attribute relation field, select **Melting Point**

### Set Item Attribute MIN and MAX

1.  In the Tolerance action field, select **'Not allowed'**.

2.  Set Minimum to **'130'**.

3.  Set Maximum to **'171'**.

4.  In the Target field, type **150**.

5.  Click **Save**.

6.  Close the page.

### Assign default Financial dimension to the item

1.  Go to **Product Information management \> Products \> Released products**.

2.  Use the **Quick Filter** to filter on the **Item number** field with a value
    of 'M2005'.

3.  Click the link for ‘M2005’ to go to the details page.

4.  Click **Edit**.

5.  Expand **Financial dimensions** fasttab, select a product group for
    **ProductGroup** financial dimension.

6.  Click **Save**.

7.  Close all pages.

### Associate Batch Attribute to the customer

1.  Go to **Product Information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **'p4000'**.

3.  Click **Customer specific** in Batch Attributes group on Manage Inventory
    tab

4.  Click **New**.

5.  In the Attribute relation field, enter or select **Melting Point**

6.  In the Account selection field, type **'US-024'**.

### Set Customer Attribute MIN and MAX

1.  Set Minimum to **'135'**.

2.  Set Maximum to **'165'**.

3.  Click Save.

4.  Close the page.

Record Batch Attribute at Batch Creation
----------------------------------------

A new batch number for part P4000 in company USPI needs to be created, as the
inventory manager create a new batch number and enter the required batch
attribute data for the batch.

### Create new batch number

1.  Go to **Warehouse management\>Setup\>Inventory\>Batches**.

2.  Click New.

3.  In the Batch number field, type ’**GTL0001**’.

4.  In the Item number field, type **'PW4000'**.

5.  In the Manufacturing date field, enter today’s date.

6.  Click **Save**.

### Record Batch Attribute data for batch

1.  On the Action Pane, click **View**.

2.  Click **Inventory batch attributes**.

3.  Click **Load item attributes**.

4.  In the Attribute value field, type **163**.

5.  Click **Save**.

6.  Close all pages.

Record Batch Attributes using Quality Orders
--------------------------------------------

In company USPI, item M2005 is set to have a quality order created upon the
purchase order product receipt. Create a new PO for 500 lbs of material, receive
the material and enter the information in the quality order that is created.
Verify the batch attribute data was updated upon completion of the quality
order.

Create new purchase order
-------------------------

1.  Go to **Procurement and sourcing \> Purchase orders \> All purchase
    orders.**

2.  Click **New**.

3.  In the Vendor account field, enter or select **US-102**.

4.  Click OK.

5.  In the Item number field, type **'m2006'**.

6.  Set Quantity to **'500'**.

7.  Set the Unit price to **6.99**.

8.  Click **Save**.

9.  On the Action Pane, click **Purchase**.

10. Click **Confirm**.

11. Note the purchase order number.

12. Close the page.

### Receive the purchase order

1.  Go to **Inventory management \> Inbound orders \> Arrival overview**.

2.  Expand Arrival query details.

3.  Set the value of **Restrict to site** to 1.

4.  Click **Update**.

5.  In the **Arrival overview profile name** field, enter or select a value.

6.  Click **Update**.

7.  Search for the purchase order created and select the record.

8.  Click **Start arrival** in the Receipts fast tab.

9.  Re-select your PO.

10. Click **Journals**.

11. Click **Show arrivals from lines**.

12. Click **Inventory**.

13. Click **Display dimensions**.

14. Select the **Site** check box.

15. Select the **Warehouse** check box.

16. Select the **Batch number** check box.

17. Click **OK**.

18. Right click and view details on the **Batch number** field.

19. Click **New**.

20. In the **Batch number** field, type ‘**GTLB001’**.

21. In the **Manufacturing date** field, enter today’s date.

22. Click **Save**.

23. Close the page.

24. Close the Batches page.

25. In the **Batch number** field, click on the pencil then enter or select the
    batch that was created (GTLB001).

26. Click **Post**.

27. Click **OK**.

28. Click **Functions**.

29. Click **Product receipt**.

30. In the **Product receipt** field, type a value.

31. Click **OK**.

32. Close the page.

### Complete the quality order

1.  Go to **Inventory Management -\> Periodic tasks -\> Quality Management -\>
    Quality orders**.

2.  Click **Results**.

3.  Click **Edit**.

4.  Set Result quantity to **'5'**.

5.  Set Test result to **'15.4'**.

6.  Click **Save**.

7.  Close the page.

8.  Click **Validate**.

9.  In the Validated by field, enter or select a value.

10. Click **OK**.

### Verify the batch attribute data

1.  Click the **Inventory dimensions** tab.

2.  Click to follow the link in the **Batch number** field.

3.  On the Action Pane, click **View**.

4.  Click **Inventory batch attributes**.

5.  Close the page.

Batch Attribute Reservation on Sales Orders
-------------------------------------------

In company USPI, part P5000 is set up with internal requirements for batch
attributes. For this example a new customer requirement for US-026 must be
created. After that a new batch order of 500,000 lbs of material shall be
created to meet the requirements of a sales order from customer US-026. As the
operations manager, you must enter the batch order, manufacture the material and
record the test results. Then the shipping operator will use the batch
reservation form to reserve a batch based upon the customer testing
requirements.

### Create customer attribute requirement

1.  Go to Released products.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'p5000'.

3.  Click Customer specific.

4.  Click New.

5.  In the Attribute relation field, enter or select a value.

6.  In the Account selection field, type 'us-026'.

7.  Set Minimum to '98'.

8.  Click Save.

9.  Close the page.

### Create new batch order

1.  Go to All production orders.

2.  Click New batch order.

3.  In the Item number field, type 'p5000'.

4.  In the Delivery field, enter a date.

5.  Click Create.

### Process batch order

1.  On the Action Pane, click Production order.

2.  Click Estimate.

3.  Click OK.

4.  Click Start.

5.  Click OK.

6.  On the Action Pane, click View.

7.  Click Picking list.

8.  In the list, click the link in the selected row.

9.  In the journal lines, select each row and complete batch reservation

10. Click Inventory.

11. Click Reservation.

12. Click Reserve lot.

13. Close the page.

14. Click Post.

15. Click OK.

16. Close the page.

17. Close the page.

18. On the Action Pane, click Production order.

19. Click Report as finished.

20. Click OK.

### Complete the quality order

1.  On the Action Pane, click View.

2.  Click Quality orders.

3.  Click Results.

4.  Click Edit.

5.  Set Result quantity to '5000'.

6.  Set Test result to '98.5'.

7.  Click Save.

8.  Close the page.

9.  Click Validate.

10. In the Validated by field, enter or select a value.

11. Click OK.

12. Close the page.

### Create the sales order

1.  Go to All sales orders.

2.  Click New.

3.  In the Customer account field, type 'us-026'.

4.  Click OK.

5.  In the Item number field, type 'p5000'.

6.  Set Quantity to '500000'.

7.  Click Save.

### Complete the batch reservation and shipment

1.  Click Inventory.

2.  Click Batch reservation.

3.  Click Batch attribute search.

4.  Click Customer attributes.

5.  Click OK.

6.  Click Reserve lot.

7.  Refresh the page.

8.  Close the page.

9.  Click Post packing slip.

10. Click OK.

11. Close the page.

Exercise 2: Create and Use Partial Visibility Catch Weight Item
===============================================================

In company USP2 a new catch weight item for sugar in 20 lb bags is to be created
as item M7010. Create the new released product as a partial visibility catch
weight item. After creation of the item, a new purchase order for 15 bags shall
be created and the bags are to be received using the arrival overview process
while specifying the total weight for the 15 bags of sugar.

Create Released Product and set CW conversions
----------------------------------------------

1.  Go to Product information management \> Products \> Released products.

2.  Click New.

3.  In the Product number field, type 'M7010'.

4.  In the Product name field, type 'Sugar in 20 lb bags'.

5.  Select Yes in the Catch weight field.

6.  In the Item model group field, enter or select a value.

7.  In the Item group field, enter or select a value.

8.  In the Storage dimension group field, enter or select a value.

9.  In the Tracking dimension group field, enter or select a value.

10. In the Inventory unit field, type 'lb'.

11. In the Purchase unit field, type 'lb'.

12. In the Sales unit field, type 'lb'.

13. In the BOM unit field, type 'lb'.

14. Click OK.

15. Click Unit conversions.

16. Click the Inter-class conversions tab.

17. Click New to open the drop dialog.

18. Set Factor to '20'.

19. In the To unit field, type 'lb'.

20. In the From unit field, type 'bag'.

21. Click OK.

22. Close the page.

23. In the Purchase Unit field, type 'bag'.

24. In the Price field, enter a number.

25. In the CW unit field, type 'bag'.

26. Set Minimum quantity to '19'.

27. Set Maximum quantity to '21'.

28. Click Save.

29. Close the page.

Create purchase order for 15 bags of M7010
------------------------------------------

1.  Go to Procurement and sourcing \> Purchase orders \> All purchase orders.

2.  Click New.

3.  In the Vendor account field, enter or select a value.

4.  Click OK.

5.  In the Item number field, type 'm7010'.

6.  Set CW quantity to '15'.

7.  On the Action Pane, click Purchase.

8.  Click Confirm.

9.  Close the page.

Create and post arrival journal for Purchase Order
--------------------------------------------------

1.  Go to Inventory management \> Inbound orders \> Arrival overview.

2.  In the Arrival overview profile name field, enter or select a value.

3.  Expand the Arrival query details section.

4.  Select No in the Production orders field.

5.  Select No in the Transfer orders field.

6.  Select No in the Quarantine orders field.

7.  Click Update.

8.  In the list, find and select the desired record.

9.  Select the Select for arrival check box.

10. Click Start arrival.

11. Click Journals.

12. In the list, find and select the desired record.

13. Click Journals.

14. Click Show arrivals from lines.

15. Click the Dimension tab.

16. Click Edit.

17. Click to follow the link in the Batch number field.

18. Click New.

19. In the Batch number field, type a value.

20. In the Manufacturing date field, enter a date.

21. In the Expiration date field, enter a date.

22. Click Save.

23. Close the page.

24. In the Batch number field, enter or select a value.

25. Set Quantity to '295'.

26. Click Save.

27. Click Post.

28. Click OK.

29. Post Product Receipt and review Inventory

30. Click Functions.

31. Click Product receipt.

32. In the Product receipt field, type a value.

33. Click OK.

Exercise 3: Use of Catch Weight Items
=====================================

In company USP2, item number M9401 for Cheese requires a new purchase trade
agreement to be set up for \$175/tray. A new demand forecast shall be entered
for 25 trays of cheese to be sold. After entering the trade agreement and demand
forecast a new purchase order for 15 trays shall be entered and confirmed.
Master planning shall then be run and reviewed to determine if additional trays
shall be purchased.

Create Purchase Trade Agreement
-------------------------------

1.  Go to Product information management \> Products \> Released products.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'm9401'.

3.  On the Action Pane, click Purchase.

4.  Click Create trade agreements.

5.  Click Edit.

6.  In the Name field, enter or select a value.

7.  Click Lines.

8.  In the Item relation field, type 'M9401'.

9.  In the Site field, type '1'.

10. In the Warehouse field, type '11'.

11. Set Amount in currency to '175'.

12. Click Post.

13. Click OK.

14. Close the page.

Create Demand Forecast
----------------------

1.  On the Action Pane, click Plan.

2.  Click Demand forecast.

3.  Click New.

4.  In the Model field, enter or select a value.

5.  In the Date field, enter a date.

6.  In the Site field, type '1'.

7.  In the Warehouse field, type '11'.

8.  Set CW quantity to '25'.

9.  Click Save.

10. Close the page.

Create purchase order for 15 trays of M9401
-------------------------------------------

1.  Go to Procurement and sourcing \> Purchase orders \> All purchase orders.

2.  Click New.

3.  In the Vendor account field, enter or select a value.

4.  Click OK.

5.  In the Item number field, type 'm9401'.

6.  Set CW quantity to '15'.

7.  Click Confirm.

Run net requirements and review output
--------------------------------------

1.  Click Product and supply.

2.  Click Net requirements.

3.  Click Update.

4.  Click Master planning.

5.  Click OK.

Exercise 4: Work with potency items
===================================

Create Potency Item
-------------------

In company USPI, part number M2004, ETDA, has been determined to need to be
adjusted to be a potency-controlled item for the Acidity batch attribute. The
target value for Acidity should be 1.7. Setup the batch attribute and assign it
to the product along with setting the product as a potency item.

### Create Batch Attribute

1.  Go to Inventory management \> Setup \> Batch \> Batch attributes.

2.  Click New.

3.  In the Attribute field, type 'Acidity'.

4.  In the Description field, type 'Acidity'.

5.  In the Attribute type field, select 'Fraction'.

6.  In the Maximum field, type '10'.

7.  In the Increment field, type '.01'.

8.  Click Save.

9.  Close the page.

### Assign Attribute to Item

1.  Go to Product information management \> Products \> Released products.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'M2004'.

3.  On the Action Pane, click Manage inventory.

4.  Click Product specific.

5.  Click New.

6.  In the Attribute relation field select Acidity.

7.  Set Minimum to '1'.

8.  Set Maximum to '3'.

9.  In the Target field, type '1.7'.

10. Click Save.

11. Close the page.

### Assign Potency Information

1.  Click Edit.

2.  Click Save.

3.  In the Base attribute field, enter or select a value.

4.  Click Save.

Create Formula with Potency Item
--------------------------------

In company USPI, part M2004 has been determined to be a potency controlled item.
The formula for item P2000 needs to be adjusted to set M2004 as an active
potency item. The formula for P2000 shall be modified to indicate the change and
item M2007 shall be set as a compensating material for part M2004 with a
compensation factor of 1.

### Copy formula

1.  Go to Product information management \> Products \> Released products.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'p2000'.

3.  On the Action Pane, click Engineer.

4.  Click Formula versions.

5.  Click New.

6.  Click Formula and formula version.

7.  In the Name field, type a value.

8.  Select Yes in the Copy field.

9.  In the Site field, enter or select a value.

10. Click OK.

11. In the Formula version field, enter or select a value.

12. Click OK.

### Modify M2004 and M2007 lines

1.  In the list, select row M2004.

2.  In the Ingredient type field, select 'Active'.

3.  In the list, select row M2007.

4.  In the Ingredient type field, select 'Compensating'.

5.  Click Save.

6.  Click Ingredients.

7.  Click Compensation principle.

8.  In the Active ingredient field, Select M2004.

9.  Click OK.

10. Close the page.

### Approve and Activate Formula

1.  In the list, select the old formula version.

2.  In the To date field, enter a date.

3.  In the list, select the new formula version.

4.  In the From date field, enter a date.

5.  Click Approve.

6.  In the Approved by field, enter or select a value.

7.  Click Select.

8.  Select Yes in the Do you also want to approve the formula? field.

9.  Click OK.

10. Click Activate.

Configure Attribute Based Pricing
---------------------------------

In company USPI, part M2004 has been determined to be a potency controlled item.
The pricing of part M2004 shall be based upon the acidity level where the ratio
of the actual acidity level against the target is multiplied by the based price
of \$4.70 and a constant of 1.5 to determine the purchase price of the batch. As
the purchase agent, set up this pricing for the item.

### Create Attribute Pricing Expression

1.  Go to Procurement and sourcing \> Setup \> Prices and discounts \>
    Attribute-based pricing details.

2.  Click New.

3.  In the Name field, type a value.

4.  In the Description field, type a value.

5.  Click Add variable.

6.  In the Equation element type field, select 'Unit price'.

7.  Click Add variable.

8.  In the Equation element type field, select 'Constant'.

9.  Set Constant to '1.5'.

10. Click Add variable.

11. In the Equation element type field, select 'Batch attribute - Target'.

12. In the Attribute field, select Acidity.

13. Click Add variable.

14. In the Equation element type field, select 'Batch attribute - Actual'.

15. In the Attribute field, select Acidity.

16. In the Equation field, type 'A*B*(D/C)'.

17. Click Validate equation.

18. Close the page.

### Complete and post trade agreement

1.  Go to Product information management \> Products \> Released products.

2.  Use the Quick Filter to filter on the Item number field with a value of
    'm2004'.

3.  On the Action Pane, click Purchase.

4.  Click Create trade agreements.

5.  Click Edit.

6.  In the Name field, select Price.

7.  Click Lines.

8.  In the Item relation field, type 'M2004'.

9.  In the Site field, type '1'.

10. In the Warehouse field, type '11'.

11. Set Amount in currency to '4.7'.

12. In the Attribute-based pricing ID field, enter the pricing ID just created.

13. Click Save.

14. Click Post.

15. Click OK.

16. Close the page.

Record Potency Attribute upon Receipt
-------------------------------------

A new batch of M2004 is to be purchased into inventory and received with the
batch attribute result being entered upon receipt. Based upon the attribute
value entered, the pricing of the M2004 shall be reviewed to verify calculation
meets the requirements of the attribute-based pricing.

### Create purchase order for M2004

1.  Go to Procurement and sourcing \> Purchase orders \> All purchase orders.

2.  Click New.

3.  In the Vendor account field, enter or select a value.

4.  In the Warehouse field, select 13

5.  Click OK.

6.  In the Item number field, type 'm2004'.

7.  Set Quantity to '800'.

8.  On the Action Pane, click Purchase.

9.  Click Confirm.

### Receive and enter a batch attribute value

1.  On the Action Pane, click Receive.

2.  Click Product receipt.

3.  In the Product receipt field, type a value.

4.  Click Update line.

5.  Click Registration.

6.  Click Add registration line.

7.  Click to follow the link in the Batch number field.

8.  Click New.

9.  In the Batch number field, type a value.

10. Click Save.

11. Close the page.

12. In the Batch number field, select the batch created.

13. In the Actual value field, type a value.

14. Click Confirm registration.

15. Click Save.

16. Close the page.

### Invoice and Review pricing

1.  In the Quantity field, select 'Registered quantity'.

2.  Click OK.

3.  On the Action Pane, click Invoice.

4.  Click Invoice.

5.  In the Number field, type a value.

6.  In the Invoice date field, enter a date.

7.  Click Update match status.

8.  Click Post.

9.  Click Inventory.

10. Click Transactions.

Perform Batch Balancing
-----------------------

A new batch order is to be created for part P2000 including reserving batches of
the active ingredients and performing the batch balancing and posting the
picking list. As the production manager, create the production order and process
the order for a new batch of part P2000.

### Create batch order for P2000 and Process batch order through Start

1.  Go to Production control \> Production orders \> All production orders.

2.  Click New batch order.

3.  In the Item number field, type 'p2000'.

4.  Click Create.

5.  On the Action Pane, click Production order.

6.  Click Estimate.

7.  Click OK.

8.  Click Start.

9.  Click OK.

### Complete Batch Reservation and Balancing for active ingredients

1.  Click Batch balancing.

2.  In the list, select row 2.

3.  Select the Marked check box.

4.  In the list, select row 4.

5.  Select the Marked check box.

6.  In the list, select row 5.

7.  Select the Marked check box.

8.  Click Balance batch ingredients.

9.  Click Confirm the formula.

10. Click OK.

### Post Picking list and Report as Finished Batch Order

1.  On the Action Pane, click View.

2.  Click Picking list.

3.  In the list, click the link for the picking list.

4.  Click Post.

5.  Click OK.

6.  Close the page.

7.  Close the page.

8.  On the Action Pane, click Production order.

9.  Click Report as finished.

10. Click to follow the link in the Batch number field.

11. Click New.

12. In the Batch number field, type a value.

13. In the Manufacturing date field, enter a date.

14. Click Save.

15. Close the page.

16. In the Batch number field, select the created batch number.

17. Click OK.
