Exercise 1: Set up a Manual Production Wave
===========================================

**USMF** is planning to use the advanced warehouse management features to
process production orders. Vince, the Operations manager, has asked you to
create a production wave

Set up a manual production wave.
--------------------------------

1.  Open **Warehouse management \> Outbound waves \> Production waves \> All
    production waves.**

2.  Select **New** in the action pane.

3.  Type **Testing WH 51** in the **Wave description** field.

4.  Select **51 Production** in **Wave template name.**

5.  Click **OK.**

6.  Click **Process.**

7.  Close the window.

Set up Reservations to Require Full Reservation
-----------------------------------------------

Vince the Operations Manager at **USMF** needs to implement a new policy to help
the flow of production. The new policy states that a production order cannot
start for certain products at **USMF** company unless all raw materials are
available. Your task is to set up reservation requirements to require all
materials in order to start production on a new product, and then test the
settings on a new production order.

### Configure the production control parameters to require full reservation.

1.  Open **Production control \> Setup \> Production control parameters**.

2.  Click the **Release to warehouse** / **Requirement for material
    reservation** drop-down box.

3.  Select **Require full reservation**.

4.  Click **Save**.

5.  Close the window.

### Create a new production order and verify the reservation settings.

1.  Open **Production control \> Production orders \> All production orders**.

2.  Click **New production order.**

3.  Select **Item number** D0002.

4.  On the right side of the form, Verify the Release to warehouse field is set
    to **Require full reservation.**

5.  Click **Create**.

6.  Close the window after the production order is created.

Exercise 2: Define Input Locations for Resource Consumption
===========================================================

Designate an input location for the USMF company Cabinet polishing resource
group.

Designate an input location.
----------------------------

1.  Open **Organization administration** \> **Resources** \> **Resource
    groups**.

2.  Select resource group **1120 Cabinet assembly**

3.  Click **Edit** on the action pane

4.  On the **General** tab, select the input warehouses and locations in the
    **Locations** field group.

5.  Select **Warehouse 11** from the drop-down menu for each.

6.  Click Save.

7.  Close the form.
