---
title: Flipclock for TechExpo
comments: true
categories:
  - Javascript
tags:
  - TechExpoX 2017
---

<script
			  src="//code.jquery.com/jquery-3.3.1.slim.min.js"
 			  integrity="sha256-3edrmyuQ0w65f8gfBsqowzjJe2iM6n0nKciPUp8y+7E="
			  crossorigin="anonymous"></script>
<link rel="stylesheet" href="/~kds38/assets/css/flipclock.css">
<script src="/~kds38/assets/js/flipclock.min.js"></script>

I found a replacement countdown js widget to replace the garish one we used last year.

You can find the source code here: <a href="http://flipclockjs.com/">http://flipclockjs.com/</a>

<div class="clock" markdown="1"></div>

<script type="text/javascript">
  var today = new Date();
  var t2 = new Date(2019, 03, 07, 9, 0, 0, 0);
  var dif = t2.getTime() - today.getTime();

  var Seconds_from_T1_to_T2 = dif / 1000;
  var Seconds_Between_Dates = Math.round(Seconds_from_T1_to_T2);
	var clock = $('.clock').FlipClock(Seconds_Between_Dates, {
		clockFace: 'DailyCounter',
		countdown: true
	});
</script>
