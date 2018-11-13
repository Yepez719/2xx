# 2xx
php/mysql steps to the inside-out-project

https://2xx.yepezdesigns.com

Version 200.0
-Pulled files from clients HTML site and uploaded to development server.
-Updated title tag and header title with PHP variables
-Converted all HTML comments to PHP comments

Version 201.0
-Replaced top level pages by changing them to php files.(Love, Who, Challenges, You)
-Removed header and footer from the pages replaced
-Created the include folder
-Created the header.inc.php and footer.inc.php files

Version 202.0
-Replaced top level pages by creating a function and array to dynamically create the menu. (Love, Who, Challenges, You)
-Created the functions.inc.php file
	-created the menuBuilder function
-Created the menu.data.php
	-created menuItems array
-Included in the very top of the header.inc.php require_once to the include/menu.data.php file
-Included in the very top of the header.inc.php require_once to the include/functions.inc.php file