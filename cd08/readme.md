[v0.0.3](https://github.com/littleflute/a21-2/edit/master/cd08/readme.md)

[show this page](https://littleflute.github.io/a21-2/cd08)

[home](../)




<audio controls id="player"> 
  <source src="https://littleflute.github.io/a21-2/cd08/01 01.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
for(var n=1; n<=23; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a21-2/cd08/";
    if(i<10) 
    {
    	s += "0";
    } 
    s += i;
    if(i<10) 
    {
    	s += " 0";
    } 
    else
    {
      s += " ";
    }
    s += i;
    s += ".mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>



