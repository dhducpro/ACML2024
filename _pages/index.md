---
permalink: /index.html
classes: wide

title: The 16th Asian Conference on Machine Learning
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/hanoi.jpeg
  actions:
    - label: "Explore Vietnam"
      url: /logistic/explore/
    - label: "Call for papers"
      url: /calls/papers/
    - label: "Call for Tutorials"
      url: /calls/tutorial/
  caption:
excerpt: ACML 2024 provides a leading international forum for researchers in machine learning and related fields to share their new ideas, progress and achievements. It will take place in Hanoi, Vietnam from 5-8th December 2024.


news:
  max_items: 3
---

# News

{% include news.html max_items=page.news.max_items %}

# Important Dates

<div class="events">

<div class="article-container">
	<div class="article">
	<h2>Conference Track Dates</h2>

<div style="overflow-x:auto;"> <!-- Responsive table -->
	<table>
		<thead>
			<tr>
				<th>Date</th>
				<th>Event</th>
			</tr>
		</thead>
		<tbody>


			<tr class="date" data-event-track="Conference Track Dates" data-event-name="Submission deadline" data-event-date="2024-06-26T23:59:59-07:00">
				<td>

					03 July 2024
				</td>
				<td>
					Submission deadline

				</td>
			</tr>

			<tr class="date" data-event-track="Conference Track Dates" data-event-name="Reviews released to authors" data-event-date="2024-08-14T23:59:59-07:00">
				<td>

					14 August 2024
				</td>
				<td>
					Reviews released to authors

				</td>
			</tr>

			<tr class="date" data-event-track="Conference Track Dates" data-event-name="Author rebuttal deadline" data-event-date="2024-08-21T23:59:59-07:00">
				<td>

					21 August 2024
				</td>
				<td>
					Author rebuttal deadline

				</td>
			</tr>

			<tr class="date" data-event-track="Conference Track Dates" data-event-name="Acceptance notification" data-event-date="2024-09-04T23:59:59-07:00">
				<td>

					04 September 2024
				</td>
				<td>
					Acceptance notification

				</td>
			</tr>

			<tr class="date" data-event-track="Conference Track Dates" data-event-name="Camera-ready submission deadline" data-event-date="2024-09-25T23:59:59-07:00">
				<td>

					25 September 2024
				</td>
				<td>
					Camera-ready submission deadline

				</td>
			</tr>

		</tbody>
	</table>


<script id="track_events_conference-track-dates" type="application/json">
{"name":"Conference Track Dates","id":0,"dates":[{"date":"2024-06-26T23:59:59-07:00","name":"Submission deadline"},{"date":"2024-08-14T23:59:59-07:00","name":"Reviews released to authors"},{"date":"2024-08-21T23:59:59-07:00","name":"Author rebuttal deadline"},{"date":"2024-09-04T23:59:59-07:00","name":"Acceptance notification"},{"date":"2024-09-25T23:59:59-07:00","name":"Camera-ready submission deadline"}]}
</script>
<script type="text/javascript">
	document.addEventListener('DOMContentLoaded', function() {
		var value = JSON.parse(document.getElementById("track_events_conference-track-dates").innerHTML);
		var tracks = { "Conference Track Dates": value };
	   	var dates = split_dates(tracks);

		// Strikethrough expired row
		for (var i = 0; i < dates['expired'].length; i++) {
			get_event_elem('.date', dates['expired'][i]).setAttribute("style", "color: gray;text-decoration: line-through;");
		}
		// Bold current row
		for (var i = 0; i < dates['current'].length; i++) {
			get_event_elem('.date', dates['current'][i]).setAttribute("style", "font-weight:bold;");
		}
	}, false);
</script>
</div>
</div>

<div class="article">
	<h2>Journal Track Dates</h2>

<div style="overflow-x:auto;"> <!-- Responsive table -->
	<table>
		<thead>
			<tr>
				<th>Date</th>
				<th>Event</th>
			</tr>
		</thead>
		<tbody>


			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Submission deadline" data-event-date="2024-05-29T23:59:59-07:00">
				<td>

					29 May 2024
				</td>
				<td>
					Submission deadline

				</td>
			</tr>

			<tr class="date" data-event-track="Journal Track Dates" data-event-name="1st round review results (accept, minor revision, or reject)" data-event-date="2024-07-03T23:59:59-07:00">
				<td>

					03 July 2024
				</td>
				<td>
					1st round review results (accept, minor revision, or reject)

				</td>
			</tr>

			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Revised manuscript submission deadline (for minor revision papers)" data-event-date="2024-08-07T23:59:59-07:00">
				<td>

					07 August 2024
				</td>
				<td>
					Revised manuscript submission deadline (for minor revision papers)

				</td>
			</tr>

			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Acceptance notification" data-event-date="2024-09-04T23:59:59-07:00">
				<td>

					04 September 2024
				</td>
				<td>
					Acceptance notification

				</td>
			</tr>

			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Camera-ready submission deadline" data-event-date="2024-09-29T23:59:59-07:00">
				<td>

					29 September 2024
				</td>
				<td>
					Camera-ready submission deadline

				</td>
			</tr>

		</tbody>
	</table>



<script id="track_events_journal-track-dates" type="application/json">
{"name":"Journal Track Dates","id":0,"dates":[{"date":"2024-05-29T23:59:59-07:00","name":"Submission deadline"},{"date":"2024-07-03T23:59:59-07:00","name":"1st round review results (accept, minor revision, or reject)"},{"date":"2024-08-07T23:59:59-07:00","name":"Revised manuscript submission deadline (for minor revision papers)"},{"date":"2024-09-04T23:59:59-07:00","name":"Acceptance notification"},{"date":"2024-09-29T23:59:59-07:00","name":"Camera-ready submission deadline"}]}
</script>
<script type="text/javascript">
	document.addEventListener('DOMContentLoaded', function() {
		var value = JSON.parse(document.getElementById("track_events_journal-track-dates").innerHTML);
		var tracks = { "Journal Track Dates": value };
	   	var dates = split_dates(tracks);

		// Strikethrough expired row
		for (var i = 0; i < dates['expired'].length; i++) {
			get_event_elem('.date', dates['expired'][i]).setAttribute("style", "color: gray;text-decoration: line-through;");
		}
		// Bold current row
		for (var i = 0; i < dates['current'].length; i++) {
			get_event_elem('.date', dates['current'][i]).setAttribute("style", "font-weight:bold;");
		}
	}, false);
</script>
</div>
</div>


<div class="article">
	<h2>Tutorials Dates</h2>

<div style="overflow-x:auto;"> <!-- Responsive table -->
	<table>
		<thead>
			<tr>
				<th>Date</th>
				<th>Event</th>
			</tr>
		</thead>
		<tbody>


			<tr class="date" data-event-track="Tutorials Dates" data-event-name="Tutorial proposals due (Anywhere on Earth time)." data-event-date="2024-10-20T23:59:59-07:00">
				<td>

					20 October 2024
				</td>
				<td>
					Tutorial proposals due (Anywhere on Earth time).

				</td>
			</tr>

			<tr class="date" data-event-track="Tutorials Dates" data-event-name="Acceptance notification." data-event-date="2024-10-28T23:59:59-07:00">
				<td>

					28 October 2024
				</td>
				<td>
					Acceptance notification.

				</td>
			</tr>

			<tr class="date" data-event-track="Tutorials Dates" data-event-name="Tutorial material/website due (Anywhere on Earth time)." data-event-date="2024-11-25T23:59:59-08:00">
				<td>

					25 November 2024
				</td>
				<td>
					Tutorial material/website due (Anywhere on Earth time).

				</td>
			</tr>

			<tr class="date" data-event-track="Tutorials Dates" data-event-name="ACML tutorials." data-event-date="2024-12-08T23:59:59-08:00">
				<td>

					08 December 2024
				</td>
				<td>
					ACML tutorials.

				</td>
			</tr>

		</tbody>
	</table>
</div>

<script id="track_events_tutorials-dates" type="application/json">
{"name":"Tutorials Dates","id":0,"dates":[{"date":"2024-10-20T23:59:59-07:00","name":"Tutorial proposals due (Anywhere on Earth time)."},{"date":"2024-10-28T23:59:59-07:00","name":"Acceptance notification."},{"date":"2024-11-25T23:59:59-08:00","name":"Tutorial material/website due (Anywhere on Earth time)."},{"date":"2024-12-08T23:59:59-08:00","name":"ACML tutorials."}]}
</script>
<script type="text/javascript">
	document.addEventListener('DOMContentLoaded', function() {
		var value = JSON.parse(document.getElementById("track_events_tutorials-dates").innerHTML);
		var tracks = { "Tutorials Dates": value };
	   	var dates = split_dates(tracks);

		// Strikethrough expired row
		for (var i = 0; i < dates['expired'].length; i++) {
			get_event_elem('.date', dates['expired'][i]).setAttribute("style", "color: gray;text-decoration: line-through;");
		}
		// Bold current row
		for (var i = 0; i < dates['current'].length; i++) {
			get_event_elem('.date', dates['current'][i]).setAttribute("style", "font-weight:bold;");
		}
	}, false);
</script>
</div>

<div class="article">
	<h2>Workshops Dates</h2>

<div style="overflow-x:auto;"> <!-- Responsive table -->
	<table>
		<thead>
			<tr>
				<th>Date</th>
				<th>Event</th>
			</tr>
		</thead>
		<tbody>


			<tr class="date" data-event-track="Workshops Dates" data-event-name="Workshop proposals due (Anywhere on Earth time)" data-event-date="2024-09-13T23:59:59-07:00">
				<td>

					13 September 2024
				</td>
				<td>
					Workshop proposals due (Anywhere on Earth time)

				</td>
			</tr>

			<tr class="date" data-event-track="Workshops Dates" data-event-name="Acceptance notification" data-event-date="2024-09-20T23:59:59-07:00">
				<td>

					20 September 2024
				</td>
				<td>
					Acceptance notification

				</td>
			</tr>

			<tr class="date" data-event-track="Workshops Dates" data-event-name="Workshop material/website due (Anywhere on Earth time)" data-event-date="2024-11-18T23:59:59-08:00">
				<td>

					18 November 2024
				</td>
				<td>
					Workshop material/website due (Anywhere on Earth time)

				</td>
			</tr>

			<tr class="date" data-event-track="Workshops Dates" data-event-name="ACML workshops" data-event-date="2024-12-08T23:59:59-08:00">
				<td>

					08 December 2024
				</td>
				<td>
					ACML workshops

				</td>
			</tr>

		</tbody>
	</table>
</div>

<script id="track_events_workshops-dates" type="application/json">
{"name":"Workshops Dates","id":0,"dates":[{"date":"2024-09-13T23:59:59-07:00","name":"Workshop proposals due (Anywhere on Earth time)"},{"date":"2024-09-20T23:59:59-07:00","name":"Acceptance notification"},{"date":"2024-11-18T23:59:59-08:00","name":"Workshop material/website due (Anywhere on Earth time)"},{"date":"2024-12-08T23:59:59-08:00","name":"ACML workshops"}]}
</script>
<script type="text/javascript">
	document.addEventListener('DOMContentLoaded', function() {
		var value = JSON.parse(document.getElementById("track_events_workshops-dates").innerHTML);
		var tracks = { "Workshops Dates": value };
	   	var dates = split_dates(tracks);

		// Strikethrough expired row
		for (var i = 0; i < dates['expired'].length; i++) {
			get_event_elem('.date', dates['expired'][i]).setAttribute("style", "color: gray;text-decoration: line-through;");
		}
		// Bold current row
		for (var i = 0; i < dates['current'].length; i++) {
			get_event_elem('.date', dates['current'][i]).setAttribute("style", "font-weight:bold;");
		}
	}, false);
</script>

</div>
</div>
</div>





# Why Vietnam?
* A South-East Asia's fastest developing economy.
* A growing interest in AI both in academia and industry
* ACML held in Vietnam last in 2014 in Nha Trang.
