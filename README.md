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
	
mark {
  background-color: #C5DDE6;
  color: black;
}
	
mark:hover {
  background-color: #3EBCE6;
	text-decoration: underline;
  color: black;
}	
  
  </style>

<script>

var days = ['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday'];


function updateTime(){
    var currentTime = new Date();
var status = "Available ✅";

d = currentTime.getUTCDay();
    h = currentTime.getUTCHours();



 if (h >= 0 && h <= 4) {
  status = "Sleeping... 💤";
}


if (d == 1 && h>=10 && h<16)
{
	status = "Busy. ⚠️ Do not disturb. ⛔";
}

if (d == 2 && h>=4 && h<18)
{
	status = "Busy. ⚠️ Do not disturb. ⛔";
}

if (d == 3 && h>=8 && h<12)
{
	status = "Busy. ⚠️ Do not disturb. ⛔";
}

if (d == 4 && h>=4 && h<10)
{
	status = "Busy. ⚠️ Do not disturb. ⛔";
}

if (d == 5 && h < 7)
{
 status = "Sleeping... 💤";
}

if (d == 6 && h>=4 && h<18)
{
	status = "Busy. ⚠️ Do not disturb. ⛔";
}


if (d == 0 && h < 7)
{
	status = "Sleeping... 💤";
} else {
if (d == 0 && h >= 7)
	status = "Having a weekend. 📵";
}

    
	document.getElementById('status_span').innerHTML = status;
    
}
setInterval(updateTime, 1000);


</script>




<!---
terishonda/terishonda is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<body>
༝ <big>👋 Hello, that's homepage of <b>Teris Labendzki</b></big><br>

Right now I’m...<br>
<div id="status_span">Refreshing...</div><br>
༝ <big>📫 How to reach me ...</big> <br>
EMail: <a href="mailto:terislabendzki@wp.pl">terislabendzki@wp.pl</a><br>
GMail: <a href="mailto:terislabendzki@gmail.com">terislabendzki@gmail.com</a><br>
Jabber: <a href="xmpp:terishonda@jabbim.pl?message">terishonda@jabbim.pl</a><br>
TG: <a href="https://terrishonda.t.me">TELEGRAM [main]</a><br><br>

༝ <big>📩 For <u>personal issues</u> contact me at : </big><br>
<a href="https://T3R15H0ND4.t.me">@T3R15H0ND4</a><br>
<a href="https://TerisLabendzki.t.me">@TerisLabendzki</a><br><br>
<!--
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
👇👇<br>
<div style="margin:0; padding:0;" id="tglink">https://T3R15H0ND4.t.me</div><br>
<script type="text/javascript">
 document.getElementById("telegram").addEventListener("change", function(){
	document.getElementById('tglink').innerHTML = "https://"+this.value;
    });
</script>
-->

༝ <big>👁‍🗨 Also look out ...</big><br>
[matrix]: @terishonda:matrix.org<br>
IRC: terishonda@Libera<br>
Wire: <a href="https://account.wire.com/user-profile/?id=24850570-86b7-45f4-ae94-77eef86043ea">@terishonda</a><br>
Tox: <mark><small>671653251EC1749E8DA508084BD67D82F0843A4268EDB7DC4FD2657260AA9E669064921F2E75</small></mark><br>	

Twitter: <a href="https://twitter.com/@terishonda">Teris Labendzki</a><br>
<br><br>
༝ <big>💰 Wallets :</big><br>
XMR: <mark><small>43JuFNejybMYXgq6zJL51f3QJhdRM2HxwBqJ9bmjX9wbHsPm5KmYKq82gLybRYqDXy2r6PDxBJHEjX4PdMrpBmiNEDzNQau</small></mark><br>
BTC: <mark><small>bc1qjlh3h622pwewx6fepad0v4v44xrygpvrerxak5</small></mark><br>
ETH: <mark><small>0x5b0E72a4708251280EbA2d39d51222ce91113F0D</small></mark><br>

<hr>
<div align="center"><small>terishonda.cf    </small>
<small><a href="http://ed5hju7ynb3r44rpfbllahhgubivsnbkqtpggxy53hywafy56qzturad.onion">.onion [TOR]</a><br>	
<small> 2022 </small>
<body>

