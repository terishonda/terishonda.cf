
<style>
  @font-face {
		font-family: 'Hauss'; 
		src: url(ALSHAUSS-BOOK.TTF); 
	}
	 
	/* Жирный */
	@font-face {
		font-family: 'ALSHAUSS-MEDIUM.TTF'; 
		src: url(bold.ttf); 
	}

*{
	font-family: Hauss;
}
  
  </style>

<script>

var days = ['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday'];


function updateTime(){
    var currentTime = new Date();
var status = "Available ✔️";
var  t_str ="";
    var h = currentTime.getHours();
    var m = currentTime.getMinutes();
    if (m < 10){
        m = "0" + m;
    }
	if (h != 0) { var t_str = h + ":" + m + " ";}
	if (h == 0) { var t_str = 12 + ":" + m + " ";}
    if(h > 11){
        t_str += "PM";
    } else {
        t_str += "AM";
    }

var d = currentTime.getDay();
    var h = currentTime.getHours();



 if (h >= 2 && h <= 7) {
  status = "Sleeping... 💤";
}


if (d == 1 && h>=13 && h<=19)
{
	status = "Busy...  ⚠️ Do not disturb.";
}

if (d == 2 && h>=7 && h<=21)
{
	status = "Busy...  ⚠️ Do not disturb.";
}

if (d == 3 && h>=12 && h<=15)
{
	status = "Busy...  ⚠️ Do not disturb.";
}

if (d == 4 && h>=7 && h<=13)
{
	status = "Busy...  ⚠️ Do not disturb.";
}

if (d == 5)
{

}

if (d == 6 && h>=7 && h<=12)
{
	status = "Busy...  ⚠️ Do not disturb.";
}


if (d == 0)
{

}
    document.getElementById('time_span').innerHTML = t_str;
	document.getElementById('status_span').innerHTML = status;
    check();
}
setInterval(updateTime, 1000);
</script>



<!---
terishonda/terishonda is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

- 👋 Hello, that's homepage of <b>Teris Labendzki</b><br>
It's<br>
<div style="margin:0; padding:0;" id="time_span">timetimetimetime</div><br>
Right now I’m...<br>
	<div style="margin:0; padding:0;" id="status_span"><b>status</b></div><br>
- 📫 How to reach me ... <br>
EMail: <a href="mailto:terislabendzki@wp.pl">terislabendzki@wp.pl</a><br>
GMail: <a href="mailto:terislabendzki@gmail.com">terislabendzki@gmail.com</a><br>
TG: <a href="https://terrishonda">TELEGRAM (main)</a><br>

📩 For <u>personal issues</u> contact me at:<br>
<select id="telegram">
<option selected="selected" value="T3R15H0ND4.t.me">@T3R15H0ND4</option>
<option value="TerisLabendzki.t.me">@TerisLabendzki</option>
<option value="labedzki.t.me">@labedzki</option>
<option value="MrLabendzki.t.me">@MrLabendzki</option>
<option value="terishondaa.t.me">@terishondaa</option>
<option value="TerisLabedzki.t.me">@TerisLabedzki</option>
<option value="terrrishonda.t.me">@terrrishonda</option>
<option value="terish0nda.t.me">@terish0nda</option>
<option value="terishond4.t.me">@terishond4</option>
</select><br>
👇👇
<div style="margin:0; padding:0;" id="tglink">T3R15H0ND4.t.me</div><br>
<script type="text/javascript">
 document.getElementById("telegram").addEventListener("change", function(){
	document.getElementById('tglink').innerHTML = this.value;
    });
</script>


Twitter: <a href="https://twitter.com/@terishonda">Teris Labendzki</a><br>
Tox: 671653251EC1749E8DA508084BD67D82F0843A4268EDB7DC4FD2657260AA9E669064921F2E75
<hr>


