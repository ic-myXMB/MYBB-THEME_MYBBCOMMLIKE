# MYBB-THEME_MYBBCOMMLIKE


This theme started simply as a written tutorial provided for users via a community post describing step by step on how to create such.


If your desire is to see just the tutorial steps done to create this theme from start to finish:

View:

https://github.com/ic-myXMB/MYBB-THEME_MYBBCOMMLIKE/blob/main/TUT_Createanewmybbcomliketheme.txt

* Tutorial credits: ic_myXMB 
* Further credits to: Justin S. (as viewing their sources helped write the tutorial)
* Further credits to: Vintagedaddyo (as viewing their sources helped write the tutorial)
* A special thanks goes out to Vintagedaddyo ( https://github.com/vintagedaddyo ) for reading my tutorial as I wrote it and adding input, suggestions & corrections and or additions to such. Also a special thanks to him for providing permission for his previous release of MyBBComm_Default theme (2018) to be used as a reference while writing my tutorial and also for his past tutorial on the teamlike groupimage styling.
* The tutorial is free to re-share as long as you retain any mentioned credits

Eventually as I completed the tutorial, I submitted a theme.xml file via that tutorial post simply for anyone having trouble with tutorial steps and or just wanted to see the finished steps for visual example via a basic theme file. This eventually led to this repository being created and the theme being place here and the theme named being changed from "Dev" as is used for examples in the tutorial steps to now "MYBBCOMMLIKE".

Author note: Sadly but also mildly amusing, part of the reason the repository for the tutorial and theme was required is that since I was able to understand the previous sources and tutorials provided in the past by the former & no longer active mybb contributor mentioned above and was able to get help from them as they are actually a very nice and friendly and helpful person whenever asked for help, some overzealous staff member at the community in what appears to be simply an act of spite, deleted all of my tutorials and banned me for life for the following reason "having multiple accounts"* (without any actual proof of such I might add, as I only had one recently created account and that is the only account I have had, period & that is a fact, jack!), laughably, as while I based the tutorials off of the sources provided in the past by the former & no longer active mybb contributor mentioned above and may have received input and suggestions from them via electronic correspondance during the process of such writing and creation, laughably we are two completely different people much to the contrary and disappointment of the hastily jumping to conclusions & overzealous and spiteful mindset of the specific mybb community staff member that so rudely deleted my tutorials and instituted a lifetime ban for multiple accounts in some hastily self-assumed victory without even taking the time to communicate with me, nor consider that they may be incorrect and or even listen to reason, lol. Regardless, I still kindly wanted folks to have access to the tutorial and or theme files if so desired and I knowingly in full confidence do not need the community totalitarian dictatorship control type drama or nonsense of certain staff members in the first place to still happily provide such content to any that may still desire such content. Cheers to that.


Ok, onwards now to the theme details:


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

    <i>administrator</i>

For super moderator:

    <i>super moderator</i>

For moderator:

    <i>moderator</i>

For registerred:

    <i>registered</i>

For guest:

    <i>guest</i>

For banned:

    <i>banned</i>


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
