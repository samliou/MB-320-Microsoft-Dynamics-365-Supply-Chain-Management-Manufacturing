Exercise: Build a product configuration model
=============================================

Create components for product configuration models
--------------------------------------------------

As a product designer in **USMF,** you need to create components before a
product model can be built. Constraint-based product configuration models use
components as building blocks to establish the product model structure.

1.  Go to **Product information management \> Products \> Product configuration
    models**.

2.  Click **Components**.

3.  Click **New**.

4.  In the **Name** field, type **'eBook'**.

5.  In the **Description** field, type 'Guide to Constraint-based
    configuration'.

6.  Click **Save**.

Create a product configuration model
------------------------------------

1.  Go to **Product information management \> Products \> Product configuration
    models**.

2.  Click **New**.

3.  In the **Name** field, type **'eBook II'**.

4.  Click **Ok**.

5.  In the **Reuse configurations** field, select **'Yes'**.

6.  Expand the **Attributes** tab.

7.  Click **Add**.

8.  In the **Name** field, type **'Case color**'.

9.  In the **Solver name** field, type **'CaseColor'**.

10. In the **Description** field, type **'Available colors for eBook'**.

11. In the **Attribute type** field, enter or select **Cabinet finish**.

12. Select the **Set default** check box.

13. In the **Default value** field, enter or select **Oak**.

14. Select the **Include in reuse** check box.

15. Select the **Include in reuse** check box.

16. Click **Add**.

17. In the **Name** field, type **'Front grill**'.

18. In the **Solver name** field, type **'FrontGrill'**.

19. In the **Description** field, type '**Select the type of front grill for
    your eBook'**.

20. In the **Attribute type** field, enter or select **Front grill**.

21. Clear the **Set default** check box.

22. Select the **Include in reuse** check box.

23. In the **Default value** field, enter or select **Black**. Click **Add**.

24. In the **Name** field, type **'Corner protection**'.

25. In the **Solver name** field, type **'CornerProtection'**.

26. In the **Description** field, type '**Should the eBook have corner
    protection?'**.

27. In the **Attribute type** field, enter or select **Corner protection**.

28. Select the **Include in reuse** check box.

29. Collapse the **Attributes** tab.

Add sub components
------------------

1.  Expand the **Subcomponents** section.

2.  Click **Add**.

3.  In the **Name** field, type **Insurance.**

4.  In the **Solver name** field, type **Insurance.**

5.  In the **Description** field, type **Do you need Insurance?**

6.  In the **Component** field, enter or select **Insurance**.

7.  Click **Save**.

8.  Collapse the **Subcomponents** section.

Add sub BOM lines
-----------------

1.  Expand the **BOM lines** section.

2.  Click **Add**.

3.  In the **Name** field, type **M0055**.

4.  In the **Description** field, **M0055**.

5.  Click **Save**.

6.  Click **BOM line details**.

7.  In the **Item number** field, enter or select **M0055**.

8.  Click the Calculation checkbox, and select **Yes** in the **Calculation**
    field.

9.  Click the **Setup** tab.

10. Set **Quantity** to '1.0000'.

11. Set **Per series** to '1'.

12. Click the **Dimension** tab.

13. In the **Warehouse** field, type '**11**'.

14. Click **OK**.

15. Collapse the **BOM lines** section.

Add an expression constraint to a product configuration model
-------------------------------------------------------------

1.  Expand the **Constraints** section.

2.  Click **Add**.

3.  In the **Constraints** field select **Expression constraint**.

4.  Click **Create.**

5.  In the name field type **eBook Oak.**

6.  Click **Save**.

7.  Click **Edit expression.**

8.  In the **Expression** type **Implies[FrontGrill !=
    "Metal",!CornerProtection]**

9.  Click **Validate.**

10. Ensure there are no errors.

11. Click **Close.**

12. Click **OK.**

13. From the **MODEL** action pane, click **Validate.**

14. **Click Close.**

15. From the **MODEL** action pane, click **Test.**

16. In the **Case color** select **Rosewood**.

17. In the **Front grill** select **White**.

18. Note that the **Corner protection** is not available and is set to
    **false**.

19. In the **Front grill** select **Metal**.

20. Note that the **Corner protection** can be set to either **true** or
    **false**.

21. Click **Next**.

22. Click **OK.**

23. Close all pages.
