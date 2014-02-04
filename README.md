SED_Examples
============

SED (Streamline EDitor Example code)

#--------------SED REMOVE DOUBLE QUOTES FROM FILE---------------

(windows)
sed s/\"//g file_input.txt file_output.txt

#--------------SED REMOVE Backslashes then DOUBLE QUOTES FROM FILE---------------

sed -n -i s/\\//g Basket_Analysis_Data.csv

sed -n -i s/\"//g Basket_Analysis_Data.csv

#--------------SED REMOVE Backslashes and DOUBLE QUOTES FROM FILE---------------

sed -n -i s/[\"]//g Basket_Analysis_Data.csv
