<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title></title>
<script type="text/javascript">
function alertwin(){
var yes_check = document.getElementById("radio_true").checked;
if(yes_check == true){
alert("it's true");
}
}


</script>

<body>
<form action="test.html" onsubmit="alertwin()">
<input type="radio" id="radio_true">
<input type="submit" value="submit">
</form>
</body>
</html>
