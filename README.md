# Robot Framework Level II Certification

This repo includes a robot program from the Robocorp Python [rpaframework](https://github.com/robocorp/rpaframework). This robot was created as an assigment for the level II certification and was bootstrapped with the Python - Minimal template. In order for you to run this, you should install on VS Code the following extensions: Robocorp Code and Robot Framework Language Server. In the conda.yaml file you will find all the dependencies which should not be installed with 'pip install...', that is what this file is here for. 

Once ran, the robot will do the following: 
- Open the browser and navigate to: 'https://robotsparebinindustries.com/#/robot-order'
- Click on the OK button in the pop up
- Download the csv file at: 'https://robotsparebinindustries.com/orders.csv'
- For each row in the table submit an order (even in case of server errors)
- Take a screenshot of the receipt and the image of each robot, merge the two in a pdf and insert all the PDFs in a zipped folder
- Close the browser
