---js
const eleventyNavigation = {
	key: "Calendar",
	order: 4
};
const calendarUrl = "c_66e11d43417d0a41cd0c3a36238795af34cdf47bc3bf56fcb53034b109793a60%40group.calendar.google.com";
---
<h1>Event Calendar</h1>
<p>Stay up to date with all our upcoming events, workshops, and meetings.</p>

<div class="student-calendar-wrapper">
	<iframe 
		src="https://calendar.google.com/calendar/embed?src={{ calendarUrl }}&ctz=America%2FNew_York" 
		style="border: 0" 
		width="100%" 
		height="600" 
		frameborder="0" 
		scrolling="no"
		title="ACM Event Calendar">
	</iframe>
</div>
