# WholeSaleOrderProcessing
It's guided project where I created Alteryx workflow for Data Warehouse.
- Task included following:
  1. Update the Existing Data Warehouse Orders table with the latest POS orders, placed in August 2021.

  2. Update the POS and Existing Data Warehouse Orders table with the returns information. That is, set the RETURNED column, to the right value.

   3. Update the Data Warehouse Customers table with the latest customer information from the POS input. That is, a customer may have changed their details, like   address (anything that s not the customer ID) during their latest order. We want the Data Warehouse to be updated with the most recent customer details. Note that the POS system has the US State name in full. Ensure you change that to the State code prior to loading it into the Data Warehouse Customers table. For example, “Florida” should become “FL”. The State Lookup file provides a mapping you may use.
