### SSRS Branding File Editor

A new feature of branding has been introduced for SSRS in SQL Server 2016. This feature is useful for customizing the SSRS Report Manager Portal with Display colors and a logo also can be added to the portal. This Branding consists of a process of zipping and uploading the below 3 files into the SSRS Report Manager portal.

1.Metadata.XML - This file holds the Branding Name , Colors file name and Logo Name (optional).

2.Colors.JSON -- This file has the Hex color values for the various elements applicable to the SSRS Report Manager.

3.LogoFile -- The logo file to be displayed on the top left corner of the SSRS Report Manager. This file is optional.

This tool will be used to edit the Colors.JSON file to apply the colors for each relevant element. This is an excel based macro tool. This tool generate the above files based on the settings in the sheet. Also the colors can be chosen using the cells back color in Color column. For the selected color, the relevant hex code will be written in the colors JSON file. This tool can be used for generating new branding file and edit the existing branding file.

#### How to use the tool 

Video on How to use the tool - [SSRS Branding Editor Tool](https://www.youtube.com/watch?v=-AEWr1t1-4k&feature=youtu.be)

Reference Links

Detailed Blog post by Vesa Tikkanen (Data Plaform MVP) on JSON Elements with screen shots

https://www.qumio.com/Blog/Lists/Posts/Post.aspx?ID=39

Video on SSRS Branding       - [SSRS Branding](https://www.youtube.com/watch?v=r5sfzCPFYBg&feature=youtu.be)


#### Create New Branding File

Step 1 - Provide the Branding Name 

Step 2 - Provide Colors File Name 

Step 3 - "Select a logo from any path. This is optional and can be left Blank.                                  Note : Please use the Select Logo button only to choose the logo".

Step 4 - On the color cell , set the back color to colors what needs to be set. Click on Default Colors button to get standard default Color.

Step 5 - Provide a Destination Path

Step 6 - Click Generate Button. This will generate below files in the destination folder             

              1. <Branding Name>.JSON             

              2. Metadata.XML             

              3. <Logo File> (If any files Chosen) 

Zip all the 3 files and upload the zip file to the SSRS Branding Settings

#### Edit Existing Branding File 
Step 1 - Click Import and choose the JSON file in the path. Make sure to have all the relevant   Metadata.XML and Logo file (if any) in the same path. This will populate all the file details and colors in the sheet.

Step 2 - On the color cell, modify the back color to colors what needs to be set as required. Click on Default Colors button to get standard default Color.

Step 3 - Select a logo from any path if to be changed. This is optional and can be left Blank.
         Note: Please use the Select Logo button only to choose the logo.

Step 4 - Modify the Destination Path if required. If not a message will be shown confirming the overwrite of the existing file.

Step 5 - Click Generate Button.

            This will generate below files in the destination folder

             1. <BrandingName>.JSON

             2. Metadata.XML

             3. <Logo File> (If any files Chosen)

 Zip all the 3 files and upload the zip file to the SSRS Branding Settings
