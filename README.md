# CMPG-323-Project-4-

# Automation in UiPath 
Automation in UiPath refers to the use of UiPath's platform to create, manage, and execute robotic process automation (RPA) workflows. UiPath is a leading RPA tool that enables businesses to automate repetitive and rule-based tasks across various applications and systems.


![image](here)

## Robotic Process Automation (RPA)
Definition: RPA involves using software robots or "bots" to automate routine tasks that were previously performed by humans. These tasks often involve interacting with multiple systems, applications, or data sources.

## Automation Benefits:
Efficiency: Automates repetitive tasks, reducing time and effort.
Accuracy: Minimizes human error by following predefined rules and steps.
Scalability: Easily scales to handle increased workloads without additional human resources.

## What does the automation do ?
### Adding data to the website 

1. The automation logs to the website https://techtrendstelemetryportal.azurewebsites.net/.
2. Logs in with the already existing credentials .
3. Clicks a tab in this order: Customers, Orders
4. It creates all records for the chosen tab , using the data from the Excel File "NWU Tech Trends Data" as a data source for each tab.
5. After creation ,it writes 'True' next to the data it created in the excel file to indicate the creation was sucessful . 

### Editing data  to the website
After the creation of records for either Clients or  Projects in the website, the automation can be able to edit each record on the website 
1. The automation clicks to the pencil icon of the record it wants to edit.
2. It removes the existing data in the text boxes and adds a new given data.
3. After population of new data , it clicks the save button.
4. After editing , it writes 'True' next to the data it edited in the excel file to indicate the editing was sucessful .

### Deleting data  to the website
After the creation of records for either Clients or Projects in the website, the automation can be able to delete each record on the website.
1. The automation clicks the dustbin icon the record it wants to delete.
2. After that it will be asked to confirm the deleting of the record , it confirms by clicking the delete button.
3. After deleting , it writes 'True' next to the data it deleted in the excel file to indicate the deleting of the record in the website was sucessful .

   

