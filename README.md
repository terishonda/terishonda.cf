
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
	(function (global) {
    "use strict";
    function Clock(el) {
        var document = global.document;
        this.el = document.getElementById(el);
        this.months = ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December'];
        this.days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
    }
    Clock.prototype.addZero = function (i) {
        if (i < 10) {
            i = "0" + i;
            return i;
        }
        return i;
    };
    Clock.prototype.updateClock = function () {
        var now, year, month, dayNo, day, hour, minute, second, result, self;
        now = new global.Date();
        year = now.getFullYear();
        month = now.getMonth();
        dayNo = now.getDay();
        day = now.getDate();
        hour = this.addZero(now.getHours());
        minute = this.addZero(now.getMinutes());
        second = this.addZero(now.getSeconds());
        result = this.days[dayNo] + ", " + day + " " + this.months[month] + " " + year + " " + hour + ":" + minute + ":" + second;
        self = this;
        self.el.innerHTML = result;
        global.setTimeout(function () {
            self.updateClock();
        }, 1000);
    };
    global.Clock = Clock;
}(window));

function addEvent(elm, evType, fn, useCapture) {
    "use strict";
    if (elm.addEventListener) {
        elm.addEventListener(evType, fn, useCapture);
    } else if (elm.attachEvent) {
        elm.attachEvent('on' + evType, fn);
    } else {
        elm['on' + evType] = fn;
    }
}

addEvent(window, "load", function () {
    if (document.getElementById("clock")) {
        var clock = new Clock("clock");
        clock.updateClock();
    }
});
</script>


<!---
terishonda/terishonda is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

- 👋 Hello, that's homepage of <b>Teris Labendzki</b><br>
<p id="clock">Javascript Clock</p>
Right now I’m...<br>

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


