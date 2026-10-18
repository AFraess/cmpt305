Individual assignment - Atlantis Fraess

RUN PROGRAMS ---------

There are two ways the programs can be ran

Method One:
  Right clicking the given file, (Lab2Main-lab4Main) and selecting the run option given

Method Two:
  Selecting a designated file to run in the top (If availible) , 
and running it by pushing the green outlined play button (Lab#Main, cmpt305<> is testing)

Method Three:
  Making sure the filepath at the top of the page is selected to be on "Current File",
  when accessing the file in the view window, and selecting the green outlined play button

All files will need an inputted filename. There are three unaltered files included with the package:
Property_Assessment_Data_2026.csv, Property_Assessment_Data_2026_Small.csv, and Property_Assessment_Data_2026_Test.csv

TESTING --------------

To test the classes, right click on the green test folder in intelliJ,
hover over "More Run/Debug", and select "Run 'All Tests' with Coverage"


Test Notes: 
The testing for the PropertyAssessment class is down 6 branches,
  due to the equals() function always catching the testing on account number,
  not any of its other data

The PropertyAssessments class will have a single not covered line in testing,
  this is due to code taken from lab1, that is used to read the filename

Additionally, CsvParser does not have test code, because that file was pulled from lab1
