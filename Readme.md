This is a UI path project which contains the robot which can scrape data from PDF invoices and write the scraped data in an excel file with the success/failure status for each invoice. PDF invoices from which data could be successfully scraped will be transferred to the folder Output/Success and those from which the bot couldn't scrape data successfully will be transferred in the folder Output/Failure.


General Instructions:

1. Change the file addresses wherever needed in the tasks. 

2. Comment out the Move File activity in both try and catch blocks.

3. Create a folder called "Output" and create two new folders within it "Success" and "Failure" within the project folder.