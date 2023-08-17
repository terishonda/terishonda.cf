<style>
  @font-face {
		font-family: 'Hauss'; 
		src: url(ALSHAUSS-BOOK.TTF); 
	}
	 
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



 if (h >= 0 && h <= 7)
{
	status = "Sleeping... 💤";
}

if (h>=8 && h<=16)
{
	status = "Busy. ⚠️ Do not disturb. ⛔";
}

if (d == 0 && h < 9)
{
	status = "Sleeping... 💤";
}
else
{
if (d == 0 && h >= 9) status = "Having a weekend. 📵";
}
document.getElementById('status_span').innerHTML = status;
    
}
setInterval(updateTime, 10000);


</script>




<!---
terishonda/terishonda is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<body>
<big>👋</big> Hello, that's homepage of <b>Teris Labendzki</b><br>
Right now I’m...<br>
<div id="status_span">Refreshing...</div><br>

<big>📫</big> How to reach me ... <br>
EMail: <a href="mailto:terislabendzki@wp.pl">terislabendzki@wp.pl</a><br>
GMail: <a href="mailto:terislabendzki@gmail.com">terislabendzki@gmail.com</a><br>
Jabber: <a href="xmpp:terishonda@jabbim.pl?message">terishonda@jabbim.pl</a><br>
TG: <a href="https://T3R15H0ND4.t.me">TELEGRAM [main]</a><br><br>

<big>📩</big> For <u>working issues</u> contact me at : <br>
<a href="https://T3R15H0ND4.t.me">@T3R15H0ND4</a><br>
<a href="https://TerisLabendzki.t.me">@TerisLabendzki</a><br><br>

<big>🤝</big> Also check ...<br>
[matrix]: @terishonda:matrix.org<br>
IRC: terishonda@Libera<br>
Wire: <a href="https://account.wire.com/user-profile/?id=24850570-86b7-45f4-ae94-77eef86043ea">@terishonda</a><br>
Tox: <mark><small>671653251EC1749E8DA508084BD67D82F0843A4268EDB7DC4FD2657260AA9E669064921F2E75</small></mark><br>	

Twitter: <a href="https://twitter.com/@terishonda">Teris Labendzki</a><br>
TG Channel: <a href="https://t.me/+iOhnfO8JQqYzMDhi"><small>4PH0R15M35</small></a><br>
<br><br>
<big>💰</big> Wallets :<br>
XMR: <mark><small>43JuFNejybMYXgq6zJL51f3QJhdRM2HxwBqJ9bmjX9wbHsPm5KmYKq82gLybRYqDXy2r6PDxBJHEjX4PdMrpBmiNEDzNQau</small></mark><br>
BTC: <mark><small>bc1qjlh3h622pwewx6fepad0v4v44xrygpvrerxak5</small></mark><br>
ETH: <mark><small>0x5b0E72a4708251280EbA2d39d51222ce91113F0D</small></mark><br>
TON: <mark><small>EQAt9Xg4PLrNAz61pKe4tHk5ysr3VDf89zn4t6r6bxOsuW2q</small></mark><br>
<hr>
<div align="center"><small>terishonda.cf    </small>
<small><a href="http://ed5hju7ynb3r44rpfbllahhgubivsnbkqtpggxy53hywafy56qzturad.onion">.onion [TOR]</a><br>	
<small> 2023 </small>
<body>

