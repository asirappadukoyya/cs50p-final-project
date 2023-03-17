# cs50p-final-project
Here is my final project of cs50p 
Project title : BAGS SALES
Description : This "BAGS SALES" project is to write a program for reading  bags data from a csv file and writing into a csv file according to rows it contain.

The csv file has to read as follows :
Bag_model,Size_in_cm,No.of_bags_sold
Puma_backpack,35,3
Aristocrat_trolly,55,2
Safari_trolly,56,1
Fastrack_backpack,32,4
Aristocrat_backpack,37,5
American_tourister_trolly,66,1

Prices according to bag model and size as follows :
Bag_model,Size_in_cm,cost
Puma_backpack,35,1500
Aristocrat_trolly,55,1950
Safari_trolly,56,2099
Fastrack_backpack,32,1699
Aristocrat_backpack,37,1750
American_tourister_trolly,66,2600

In this program i have used three custom functions as follows first one is "check_arg()" to check correct no.of.arguments,second function is "cost()" to
check the size of the bag and returns  cost of that bag,third function is "no_bags()" to return how many bags are left out of five bags.

The csv file after program excution :
Bag_model,cost,No.of_bags_left_out_of_5
Puma_backpack,1500,2
Aristocrat_trolly,1950,3
Safari_trolly,2099,4
Fastrack_backpack,1699,1
Aristocrat_backpack,1750,0
American_tourister_trolly,2600,4

Testing : I have tested my three custom functions by unit testing with the help of pytest.
Requirements : pytest installation.
