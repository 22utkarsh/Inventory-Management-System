# Inventory-Management-System
Inventory Management System using python and Dataset in JSON format.

#--Read and write funtion--
1. In this section user can read the data from "data.json" by calling the read() funtion
2. In this section user can write the updated data into the "data.json" by calling the write() funtion

#--Add new Items in Inventory funtion--
In this section to add the new item Using 'Add_item()' function-
1. Product Id
2. Product name
3. Product type (kg/litr/pack)
4. product price
5. product available quantity
6. product discount if available else N/A

#--Purchase function--
User have to enter  some details and then final bill is calculates with "purchase()" funtion:
Ënter customer's Name :utkarsh
Ënter Product Id :20210730
Ënter Product Quantity Purchased(Kg/Litre/item) :1
*******************
Ïtem Purchased : Football
Total Billing Amount : 300 .00 rupees

#--sale funtion--
in this section all the purchased record with date and time is saved in "sale.json" using sale() funtion.
