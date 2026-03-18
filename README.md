# ohio-trialcrtrecs
Centralized Web Directory for the Court Case Information Databases Across Ohio's Trial Courts

This project comprises of the raw dataset, which is held in CSV format with "ohioCourtData.csv" and in JSON format with "courtData.js," and the web tool.  The web tool is a simple proof-of-concept that reads "courtData.js" and permits simple browsing with nothing more than Vanilla JS.  

[Skeleton CSS](http://getskeleton.com/) is used with this web tool to permit a lightweight, responsive design across devices.

If there is interest in this project, the next steps would be a hosted SQLite database and a web app that actively queries said database.  

# Court Data Schema
Each Ohio trial court is represented as a row in the file, "ohioCourtData.csv".  For each record, there are the following attributes (columns):
1. Associated Ohio County
2. Name of the Court
3. Record Search Page URL for the Court
4. Main URL for the Court

Note that not all courts have publicly-available online record searches (e.g., most juvenile courts). However, the majority of Ohio's trial courts do have online case information (or an online docket) available. Moreover, some record search pages might be used for multiple courts (e.g., Common Pleas, Probate, Domestic Relations).

# More Information

More information about the various trial courts in the State of Ohio can be found on [this page](https://www.supremecourt.ohio.gov/courts/judicial-system/ohio-trial-courts/) from the Supreme Court of Ohio. 
