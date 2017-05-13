<html>
<head>
<script src="jquery-3.2.0.min">
</script>
<script>
var jsonobject={"person":[
{"name":"mahendran" , "price": 75}
{"name":"karthi" , "price": 89}
{"name":"bhasha" , "price": 100}
]};H
function viewResult()
{
var count=jsonobject.person.length;
alert(count);
}
</script>
</head>
<body>
<p onClick="viewResult()">demo</p>
</body>
</html>
