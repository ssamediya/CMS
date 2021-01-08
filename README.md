# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

Building Contact Management System(CMS)

### How do I get set up? ###

Create database manually in the SSMS with the name as "CMS".

1. Run the Database scripts

2. Clone both CMS & CMS-UI on to your machine

3. In CMS project in appsettings.json change the connectionstring "CMSDBConnection" according to your DB connection. You might get error says "An error occured in 'Solution 'CMS' (2 of 2 projects)' while attempting to open 'NuGet - Solution'". But this will not restrict the project to run.

4. Run the CMS project.

5. There is no homepage for web api so it will show "This localhost page can’t be found".

Make sure that node.js is installed in your machine. You can intall it from https://nodejs.org/en/download/ 


6. Open CMS-UI and run "npm-install" to install node modules

7. In CMS-UI open env.local file and change the api base url as per your CMS project localhost. For exp - LocalHostPath/api/Contact.


8. Make sure CMS is running and then run CMS-UI by using "npm run serve" command

9. Copy the local url from terminal and run in chrome browser.

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
