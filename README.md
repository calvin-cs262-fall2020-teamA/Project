![Mercury logo](https://github.com/calvin-cs262-fall2020-teamA/Project/blob/designModels/images/logo.png)

# Project Mercury

### *Streamlining dorm delivery for Calvin University*

## Our Vision

The Mercury Package Management app seeks to provide a simple and hassle-free platform for managing deliveries for Calvin’s Residence Halls and notifying the intended recipients. Online shopping is the primary method of purchasing items for many students, especially for those who don't have cars, and even more so during the COVID-19 pandemic. All packages for Calvin's campus arrive at mail services where they are sorted and delivered to the building of its recipient. From there, it is up to the dorms' deskies to sort and log each package, notifying the recipient that it is available to pickup.

Currently, dorm deskies keep track of packages using a Google Sheets spreadsheet. This table keeps track of the recipient, their room number, the date the package arrived, and a description of the package. Deskies then notify the recipients over email that their package has arrived. This manual submission process can be rather slow, especially at certain times of the year when packages are filing in quickly, such as move-in week. We have heard stories where packages could be not picked up by their recipients on the day the were delivered because the deskie could not sort them in a timely fashion before their shift was over. Our hope is that automating this system will speed up the sorting process and get the packages into the hands of the recipients more efficiently. 

Mercury Package Management will improve this process on two fronts: the deskie interface and the recipient interface. Deskies will be able to quickly enter package information with the assitance of automation from the app, and recipients will be able to view packages that are available for pickup. Instead of relying on a spreadsheet that has no quick way to lookup and enter data, a database will be used to store package information and status, as well as information about the building's current residents. Mercury will interface with these databases to provide the following functionality:

1. Quickly search for package recipients without scrolling through a list of all the residents to find their email address.
2. Present simple buttons to the deskie to select tags or descriptions for a package (box, envelope, brown, blue, large, small, etc.)
3. Generate a package ID number that is not currently being used by a package in inventory.
4. Search the database by package ID when a resident comes to pick up a package.
5. Log the date of pickup and the deskie who dispersed the package.
6. Send email notifications to the recipient when the package arrives and confirming when it has been picked up.
7. View a report of the entire database to see which packages are still in inventory and which have been picked up.
8. Show a resident the packages that they have available to pick up and a history of ones they have already picked up.

References to additional files:
- [Domain Model](https://github.com/calvin-cs262-fall2020-teamA/Project/blob/designModels/domainModel.md)
- [User Interface Model](https://github.com/calvin-cs262-fall2020-teamA/Project/blob/UIModel/UIModel.md)

## Our Team

![Team Photo](https://github.com/calvin-cs262-fall2020-teamA/Project/blob/designModels/images/GroupATeamPhoto.jpg)

Jake Boers || Emily Costa || Ben DeVries || Andrew Feikema || Coleman Ulry || Jack Westel  
