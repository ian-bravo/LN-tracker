Name of Student: Ian Bravo

Name of Project: Liquid Nitrogen Tracker

Project's Purpose or Goal: (What will it do for users?) This application will help organize and keep track of various biological samples that are stored within semi-organized liquid nitrogen freezers.

List the absolute minimum features the project requires to meet this purpose or goal: 
* CRUD
* DB management system (SQL or NoSQL)

What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.
* C#/.NET and/or Python/Django

If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.
* Add OCR (optical character recognition) - Tesseract using Python + QR codes
* GUI such as ASP.NET Core OR HTML/CSS/React OR Google Sheets.
* Search function
* Authentication 

What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?
* TBD

Is there anything else you'd like your instructor to know?
* These numbered LN (liquid Nitrogen) freezers each have metal racks (that are also numbered) that encase up to 5 cardboard boxes that hold various biological samples. Each box can hold 81-100 samples (9x9 or 10x10 box). There is information on each sample that is in the form of a sticker, both on the side of the vial and the top. These samples can sit in the same place for years or can get moved around/removed for shipping or further testing. Currently the data on these samples are split across multiple excel sheets, oftentimes incorrect. My aim is to have a single place to organize samples for further use. I would love to implement a script that takes a picture containing necessary information to automatically store the data (Tesseract + Python). As for a UI, I would like to use Google Sheets as a minimum, expanding to other technologies if time allows. I'm leaning towards utilizing some kind of SQL given that the samples have had the parameters for decades. However, there are thousands of samples so query time will need to be accounted for when deciding to utilize SQL or NoSQL. 