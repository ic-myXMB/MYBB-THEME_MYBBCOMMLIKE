# MYBB-THEME_MYBBCOMMLIKE


Theme installation notes:

You  will need to download the files for example:


Theme XML file:

https://github.com/ic-myXMB/MYBB-THEME_MYBBCOMMLIKE/blob/main/MYBBCOMMLIKE-theme.xml


Then in you forum ACP 

Go to themes

For example:

admin/index.php?module=style-themes

Select the import theme tab:

For example:

admin/index.php?module=style-themes&action=import


and import your theme XML file:

For example:

MYBBCOMMLIKE-theme.xml


That is all as far as the theme XML file side of theme istallation.



The next part is installing the required theme files.


Required theme files:

https://github.com/ic-myXMB/MYBB-THEME_MYBBCOMMLIKE/blob/main/Upload.zip

Once downloaded, you would extraxt the zip file "Upload.zip" and that will give you a directory folder "Upload". All files within upload are correctly placed so you just need to think of "Upload" as your "/forum root/" directory, so, for example if your forum root directory was say for example named "/forums/" then you would  simply rename the "/Upload/" directory to "/forums/" and then upload such via ftp to your server control panel file directory merging existing files and new files within your "forum root" directory.


That is all as far as the theme required files side of theme istallation.


Have fun with your new theme!


Final things:


Usergroup css groupimage styling notes:

To use the included css styled usergroup groupimages:

In user & groups: specific usergroup find: Group Image

    "Here you can set a group image which will show on each post made by users in this group."" 


Add for example:

For administrator:
[code]
<i>administrator</i>
[/code]

For super moderator:
[code]
<i>super moderator</i>
[/code]

For moderator:
[code]
<i>moderator</i>
[/code]

For registerred:

[code]
<i>registered</i>
[/code]

For guest:
[code]
<i>guest</i>
[/code]

For banned:
[code]
<i>banned</i>
[/code]


To use the other additional usergroups styling included you will need to Add additional usergroups 8 through 16 as follows:

8) Management
9) Development
10) Design
11) Security
12) DevOps
13) Support
14) Community
15) Web
16) Editorial
