# mysql-redefine
Redefines all MySQL functions as mysqli (for PHP>=7)

For PHP versions greater or equal to 7, this script serves as a workaround and replaces all mysql functions with their mysqli equivalents.
Vulnerability issues may arise, so it is advisable to use the recommended more recent mysqli-functions instead.
You can update old code by adding this line at the beginning of it if you're confident it won't put your server at risk.

Use:<br>
&nbsp;    Download and include the file at the top of your PHP script<br>
<code>`include_once('mysql.conf.php');`</code><br><br>
&nbsp;
