# TheGarageSale


simple consice explanation of how and what the code does. In detail description is available in the code notebook!


The garage sale is meant to be an ecommerce platform for 3rd world countries where the use of telegram is prevelant than website visits. The case for this versions commit is Ethiopia hence the currency and categories refllect that.

The main file is TheGarageSale.py (File which gets the ball rolling) inside this file 2 other independet files are imported which are TheGarageSaleDB.py and yenepay.py . TheGarageSaleDB.py houses all functions that is related to database reading, writing, creating and updating. However in rare cases these functions are defined and implemented in the main function. 


yenepay.py is a webscrapper used to generate transaction reference numbers so users can deposit money to their accounts. This version lacks a function that checks new incoming transactions and updates the respective users balance. However in its current state the user can get a CBE birr transaction reference number and successfully deposit money to be used in the program for various perks such as post boosts etc through the telegram bot interface.
