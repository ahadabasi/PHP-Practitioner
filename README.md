# PHP-Practitioner
## A custom freamwork

### Create config.php in master directory of project

<pre>
	<code>
return [
	'database' => [
		'name' 		=> 'database_name',
		'username'	=> 'user',
		'password'	=> 'your_password',
		'connection'=> 'mysql:host=127.0.0.1',
		'options'	=> [
			PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION
		]
	],
]; 
	</code>
</pre>
