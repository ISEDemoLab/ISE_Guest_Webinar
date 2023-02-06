# ISE_Guest_Webinar
This repository was used for the ISE Guest Access Basics and ISE Guest Access Advanced Configurations webinars that were given on January 6 and February 7, 2023.  The purpose of the webinars was to show The built-in guest flows for Cisco ISE and how you can customize these flows and portals using Javascript and HTML.

Though not all of the scripts in this repository were shown, this is the collection of scripts that I have used in customer deployments to solve specific issues or wants.  I had a hand in developing a lot of these, but not all of them.  To see what other scripts you can use and to get an idea on how to create others, please visit [ISE Guest & Web Authentication](https://cs.co/ise-guest).

The breakdown of the repository should be self-explanatory, but I'll break it down into a table

|Folder|Function|
|---|---|
|root|Global scripts to be used for any portal|
|Hotspot Portal|Scripts specific to the Hostspot Portal or flow|
|Self-Registered Guest Portal|Scripts specific to the Self-Registered Guest Portal or flow|
|Sponsored Guest Portal|Scripts specific to the Sponsored Guest Portal or flow|
|Sponsor Portal|Scripts specific to the Sponsor Portal for creating/maintaining guest accounts|

## Quick Start
You do not need to clone this repository, just choose the file you want and either download it or open it and copy the contents to your clipboard.

## Requirements
If using ISE 3.0 or older, you need to **Enable Portal Customization with HTML and JavaScript**. To do this, navigate to **Administration · System > Admin Access**.  Choose **Settings > Portal Customization** and enable the radio button.  Remember to **Save**.

![Enable Portal Customization](https://github.com/ISEDemoLab/ISE_Guest_Webinar/blob/main/images/enable_javascript.png)

This is the default setting in version 3.1 and newer and cannot be changed.

## Default script location
The scripts in this repository are meant to be used in the Optional Content 2 text area in the **Portal Page Customization** area of the portal you wish to customize.

You _do_ have to follow a specific sequence for the script to work.  Before pasting the script into the Optional Content 2 text area, you _**must**_ click the 'Toggle HTML Source' button (shown below).  Once the script is pasted, click the same button again.  If you do the, the script _WILL NOT WORK_. 

![html_source](https://github.com/ISEDemoLab/ISE_Guest_Webinar/blob/main/images/html_source.png)

## Instructions per script
Some of the scripts in this repository have specific instructions and these instructions will be contained in the .txt file for the script.

## License

MIT

## Author

Charlie Moreton, <https://github.com/ISEDemoLab>