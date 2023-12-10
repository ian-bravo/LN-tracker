### Epicodus Capstone Proposal
#### Name of Student: 
* Ian Bravo

#### Name of Project: 
* Liquid Nitrogen Tracker

#### Project's Purpose or Goal: (What will it do for users?) 
* This application will help organize and keep track of various biological samples that are stored within semi-organized liquid nitrogen freezers.

#### List the absolute minimum features the project requires to meet this purpose or goal: 
* A UI to allow users to read/create/update/delete database entries.
* Data is stored through a MySQL database

#### What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.
* HTML
* CSS
* React or ASP.NET Core Web App (Model-View-Controller)
* C#
* ASP.NET Core Web API 
* MySQL

#### If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.
* Search function
* Authentication
* Convert pictures into database entries

#### What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?
* OCR (optical character recognition) - Tesseract
* ASP.NET Core Identity

#### Is there anything else you'd like your instructor to know?
* These numbered LN (liquid Nitrogen) freezers each have metal racks (that are also numbered) that encase up to 5 cardboard boxes that hold various biological samples. 
* Each box can hold 81-100 samples (9x9 or 10x10 box). There is information on each sample that is in the form of a sticker, both on the side of the vial and the top. These samples can sit in the same place for years or can get moved around/removed for shipping or further testing. 
* Currently the data on these samples are split across multiple excel sheets, oftentimes incorrect.
* My aim is to have a single place to organize samples for further use. I would love to implement a script that takes a picture containing necessary information to automatically store the data (Tesseract).