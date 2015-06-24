*Dont make any files or directories outside of "root"

FILE STRUCTURE:

root: contains everything
	css: contains css files
		main.css: css that applies to every page
		-all other filenames should correspond to a file in root/pages and contain css only for that page
	js: contains javascript files
		main.js: js that applies to every page
		-all other filenames should correspond to a file in root/pages and contain js only for that page
	min.js: contains minified js files
		-this folder can be ignored until launch; all JS code should be minified with filenames corresponding to those in the js folder
	pages: contains the actual pages users will see
		-the name of each page should describe its pupose; index.php is the HOME page
	server: contains all PHP classes and functions to be used by pages
		base.php: contains universal basic classes and functions we might need everywhere
		-all other filenames will contain classes and functions involving the name of said file