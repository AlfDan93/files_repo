<?php
$username = "query_user";
$password = "micr0game";
$database = "TEST";
$ip = "172.28.5.111";
$port = "3306";
$dbc = mysqli_connect($ip, $username, $password, $database, $port);
$query = "SELECT name FROM test_tbl WHERE name='CLUSTER2'";
$result = mysqli_query($dbc, $query) or die("Bad Query: $query");
while($row = mysqli_fetch_assoc($result)){
?>
<html>
<h1>Welcome To Nginx on Kubernetes</h1>
</br>
<h1>I AM THE BACKEND ON "<?php echo $row['name'] ?>"</h1>
</html>
<?php } ?>
