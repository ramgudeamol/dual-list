// This project shows one pager application with 1 text box ,button and 2 list box
// text from text box will be added to 1 list box on button click
// and all data from both list box will be saved to MySQL db on change of list box content
1. use git clone https://github.com/ramgudeamol/dual-list
   Keep all files at PATH/htdocs/dual-list/
   
   for windows example: C:/xampp/htdocs/dual-list
   for linux /var/www/dual-list/
	
3. import SQL file test.sql in MySQL using command:
	mysql -u root -p test < test.sql
	
4. set mysql credentials i.e. values for $host, $username, $password, $dbname in saveData.php file

5. use url to access in browser : 	http://domain/dual-list/index.html
   or http://localhost/dual-list/index.html
