#### Update the package list
<pre>sudo apt update </pre>

#### Install MySQL Server (SQL database server)
<pre>sudo apt install mysql-server -y </pre>

#### Start the MySQL service
<pre>sudo systemctl start mysql</pre>

#### Enable MySQL to start automatically on boot
<pre>sudo systemctl enable mysql</pre>

#### Check the MySQL service status
<pre>sudo systemctl status mysql</pre>

#### Run the MySQL security setup (recommended)
<pre>sudo mysql_secure_installation</pre>

#### Log in to the MySQL command-line client
<pre>sudo mysql</pre>

#### Check the installed MySQL version
<pre>mysql --version</pre>