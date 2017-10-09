<!DOCTYPE html>
<html>
<body>
<script>
function changeImage()
{
x=document.getElementById("demo");
element=document.getElementById('myimage')
if (element.src.match("bulbon"))
  {

	x.innerHTML="灯泡已熄灭   "+new Date();
  element.src="/dp/i/eg_bulboff.gif";
	
  }
else
  {
x.innerHTML="灯泡已点亮   "+new Date();
  element.src="/dp/i/eg_bulbon.gif";
	
  }
}
</script>

<img id="myimage" onclick="changeImage()" src="/dp/i/eg_bulboff.gif">

<p id="demo">点击灯泡来点亮或熄灭这盏灯</p>

</body>
</html>

