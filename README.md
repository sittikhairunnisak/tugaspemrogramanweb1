Sitti khairunnisak
# tugaspemrogramanweb1
<!DOCTYPE html>
<html>
<body>

<?php
$t = date("50");
echo "<p>The hour (of the server) is " . $t; 
echo ", and will give the following message:</p>";

if ($t < "10") {
  echo "Alana makan soto!";
} elseif ($t < "20") {
  echo "Anggi beli tas baru!";
} else {
  echo "Ashka liburan bersama keluarga!";
}
?>
 
</body>
</html>
