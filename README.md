# CompatabilityTest

Question 1:

Test cases for Front end specifications:
1. Verify if the component is present at the top of page to add inventory
2. Verify if the component is clickable
3. Verify if the component has "name, price, description" as mandatory fields and "Upload photo" option as optional field
4. Verify if the user is able to give inputs to the fields in the component
5. Verify if any non alphabetic characters are allowed in the "name" field
6. Verify if only numerical values are allowed in "Price" field
7. Verify if all the characters are allowed in "Description" field
8. Verify if the user is allowed to enter the characters upto maximum limit in "Name" and "Description" field
9. Verify if the option to section CURRENCY value is present next to "Price" field
10. Verify if the user is able to upload the photo in the "Upload photo" option
11. Verify if the user is not able to add the item to inventory without any of "Mandatory fields" filled
12. Verify if the user is able to add the item to inventory with the mandatory fields and without "Photo" option
13. Verify if the list of items present in the inventory is displayed below the component which adds the item to inventory
14. Verify if the newly added item to the inventory is present below the component
15. Verify if the list of items displayed below the component contains name, price and thumbnail of the image(if uploaded)
16. Verify if the "Remove" option is present next to each items in the inventory
17. Verify if the item is removed from the inventory when the "Remove" option is clicked
18. Verify if the new page is opened when the user clicks on any item in the inventory
19. Verify if the new page for each item contains "Name, Price, Description, Photo(if uploaded)"
20. Verify if the values of "Name, Price, Description, Photo" are similar to the values uploaded by the user
21. Verify if the page load is happened when the user navigates from Inventory list page to each item specific page
22. Verify if the page load is not happened when the user adds the item to the inventory using the component at the top
23. Verify if all the fields in Inventory page is horizontally and vertically centered such that it fits in mobile as well as laptop
24. Verify if all the fields in Item details page is horizontally and vertically centered such that it fits in mobile as well as laptop

Test case for Backend specifications:
1. Verify if the items added in the inventory are stored in database.
2. Verify if the database contains a table with column "ID, Name, Price, Description, Photo path"
3. Verify if the item is deleted from the database when "Remove" action is performed in Inventory

All the test cases mentioned in the Front end specification can be automated.
