# GRAD-521_DMP_GATES2020

This is a Data Management Plan for GRAD 521
  The DMP will include the following sections
    1. Describe your data
    
This research project attempts to define and quantify the determinants of high school dropout rates by public school district, in both Florida and Georgia. Two types of data will be generated during this project as follows: 
Data table
Regression output
The analysis includes a particular focus on the effects of socio-economic indicators, and the demographic makeup of the student body and the surrounding community. The regression model contains several independent variables, for which data must be collected. These include demographic information percent of the student body that is black, percent hispanic as well as social wellness indicators the teen birth rate, unemployment rate, and violent crime rate in the surrounding counties. Other educational statistics considered were the district student teacher ratio, as well as the average salary for teachers in the district. These will be compiled into a single CSV file of approximately 100-200 kb. This data will be collected from state and federal public databases, provided by the Florida and Georgia departments of education, and the Federal Reserve. In addition data from countyhealthrankings.org is used. 
In addition to the input data, regression outputs will also be generated using SPSS during the research process. These will be stored as .SPV SPSS output files. There will be two regression files, one for Georgia and one for Florida. Each file will be approximately 1-2 Mb in size. They will include the regression table outlining the different parameters and their statistical significance as well as all related descriptive statistics and tables. Specifically, I will generate correlation matrices, residual plots and scatterplots to visualize the relationships between each regressor and the dependent variable (high school dropout rate). 

    2. Roles and Responsibilities
    
I will be responsible for implementing all aspects of the data management plan. The project and research question were approved by my academic advisor and it is my responsibility as the researcher to gather, format and ensure proper treatment of the data. In the event I leave the project or am unable to complete the research, the academic advisor will take over as the primary overseer of the data and follow the data management plan. 
Eckerd College, the institution at which the research will be taking place does not have a formal data management plan in place. This means that while the data needs to be managed responsibly the specific requirements are not dictated by such a plan. The research is funded indirectly by the college as the software licenses are provided, along with physical resources such as computers and work space. However, tuition is paid for the right to use this equipment. Beyond these resources the research requires no additional funding and no other parties are involved. 
As a student my research will belong to me, however the terms of use from the data sources must be considered in planning for future sharing and reuse. A majority of the data procured for the project is from public databases on state and federal sites. Because they are readily publicly available and owned by the government they are free for anyone to use for any purpose, even for profit. However, the County Health Rankings site owned by the Robert Wood Johnson Foundation and University of Wisconsin Population Health Institute does have a terms of use policy that limits some use of the data. Users are allowed to “view, play, print and download content...for noncommercial purposes only”. This means that while use of the data is free of charge and the academic purposes of this project are within the terms of service some sharing and reuse of the data will need to be limited. 

    3. Data Standards and metadata
       	
The metadata standard that will be used to document data for this project will be the DDI framework. Over the course of the project version history will be stored both locally using a chronological “order-by-date” strategy with the ISO formatted date preceding the title, and backed up publicly using GitHub, as a secondary organizational tool. The XML format will work well to manage the tabular data, as well as tracking versions of the regression that are generated as the project moves forward. The information that will be recorded will include methodology, including the data sources and any manipulations to the data, descriptions of the variables including definitions and units, and overviews of the regression models. These will be taken from the CSV and SPSS files described in part 1 for storage in the XML format. 
It will be necessary to supplement the data table used for analysis with a tabular metadata file. This will include a description of each of the variables recorded in the data file, the sources, as well as units so a reader will be able unambiguously determine the meaning of the data. This will follow the example format given by the Oregon State University library (https://guides.library.oregonstate.edu/ld.php?content_id=45294345). The tabular metadata section will be formatted as follows:

Name: [variable name]
Description: [description of variable]
Unit: [definition of units used to describe variable values]
Source: [source from which data on the variable was collected]

    4. Storge and security
    5. Access and data sharing
    6. Archiving and preservation
