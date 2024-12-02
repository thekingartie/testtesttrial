# Project Title: Waste Management System
### Description:
This Java-based program simulates a waste management system that allows users to select regions, assign routes, manage waste bins, and operate waste trucks. Users can perform various actions such as collecting waste, dumping waste, checking truck information, and monitoring the status of waste bins.

### Prerequisites
1. Java Development Kit (JDK) installed (version 8 or higher).
2. Terminal or Command Prompt to execute the program.
3. Ensure all `.java` files from this project are in the same directory.

### Files in the Project
1. Main.java: The entry point for the program.
2. WasteTruck.java: Defines the waste truck operations.
3. WasteBin.java: Represents waste bins.
4. Vehicle.java: Abstract base class for vehicles.
5. Region.java: Handles regions and associated waste bins.
6. RegionConstants.java: Contains predefined regions and routes.
7. Collectable.java: Interface for collectable entities.
8. Route.java: Manages route information (optional/future use).

## How to Compile and Run the Program
### Step 1: Open the Terminal/Command Prompt
Navigate to the directory where the .java files are located.

`cd /path/to/GroupJ_FinalProject`

### Step 2: Compile the Java Files
Use the following command to compile all the Java files:

`javac *.java`
This will generate `.class` files for each `.java` file.

### Step 3: Run the Program
Execute the Main class to start the program:

`java Main`


# Program Workflow
### 1. Select a Region:
- Choose a region from the predefined list.
- Example: Ashanti Region, Greater Accra Region, etc.

### 2. Add Waste Bins:
- Specify the number of bins and provide details like Bin ID and initial waste level (1–100%).

### 3. Assign a Route:
- Select one of three available routes in the chosen region.

### 4. Perform Actions:
1. Collect Waste: Operates the waste truck to collect rubbish from all bins along the route.
2. Dump Waste: Empties the waste truck.
3. Display Truck Info: Shows the truck's ID, fuel level, route, capacity, and load.
4. Check Bin Status: Displays the status of all bins, including their current waste levels.
5. Exit: Terminates the program.

## Notes/Assumptions
* The waste truck starts with 100% fuel and a capacity of 500 units.
* Collecting waste reduces fuel by 10% per bin. Warnings are displayed when fuel drops below 20%.
* Waste levels are percentage-based, and bins are reset to 0% after waste collection.
* All input is validated to ensure proper operation of the program.

