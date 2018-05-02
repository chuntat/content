# Salesforce Custom Content Block SDK - Sitecore Mock up v2.1

Changelog:
v1: 	Draft project skeleton
v2: 	Improved version with image presented in a list format
v2.1:	checkbox for scale to fit and align to center will automatically make changes to content block 


Hi my name is Chun Tat (CT), Solution Engineer in covering Asia markets. If you're here, it should mean that you're interested to get Sitecore content blocks into your Email Studio Editor. You will also need to create an Installed Package in your MC Account and a new Heroku project to host this.

Basically there are a couple of files in this Github repo where you can use. 


- Index.php 
This is for Heroku to run the static HTML page

- Composer.json
Required to run these static HTML pages on Heroku

- Index.html
This is where all the action takes place. Contains the javascript, html, etc. Currently this is not pulling data from Sitecore at all. All images URL are hardcoded.

DragIcon.png
- You must strictly follow this naming convention as this is how MC recognise which image to be used as drag icon

Icon.png
- Same as bove

- blocksdk.js
This is the Salesforce Content Block SDK. It allows you to get,set Content onto Email Editor Canvas

Package.json
- Part of the SDK 

*Important Note*
THIS IS JUST A MOCK UP/PROTOTYPE. IT IS NOT THE PRODUCTISED SITECORE CONNECTOR NOR HOW THE CONTENT BLOCK WILL EVENTUALLY LOOK LIKE. THIS IS PURELY FOR DEMONSTRATION USE AND SHOULD NOT BE SOLD AS A COMMERCIALISED PRODUCT. PLEASE MENTION OUR SAFEHARBOUR BEFORE SHOWING THIS.