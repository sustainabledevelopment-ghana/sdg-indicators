---
title: Frequently Asked Questions (FAQ)
permalink: /faq/
layout: page
---

## How do I suggest new or different data sources?
If you have feedback on the data sources we have used or have suggestions for new data sources then please email us at <a href="mailto:{{site.email_contacts.questions}}">{{sdg.secretariat@statsghana.gov.gh}}</a>.

## What does the reporting status mean?
We have used three different types of reporting status for an indicator, which are also colour coded:

* Reported online (green) – as a minimum the headline national data for this indicator is available on this website but the data might not be fully disaggregated yet. We are continuing to source additional disaggregations.
* Statistics in progress (amber) – we have found a suitable source of data for this indicator or relevant proxy at national level. We are currently quality assuring the data and preparing it for publication.
* Exploring data sources (red) – we are still looking for a suitable data source for this indicator.

Where there is additional information about the status of indicator data collection and reporting, this will be displayed at the top of the indicator page.

## How often will new data be added to this site?
We will add data as soon as it has been sourced and checked. This includes new data as well as updates to data we have already published. We will continue to collect data from existing sources where possible, in cooperation with topic experts.

## What browsers can I use to view this website?
We are developing and testing our site in line with the UK ONS team. Our website works with most of the latest versions of the commonly used browsers. There are some issues with using the site on older versions of browsers eg IE8 and we are working to fix these. The website can best be viewed with a chrome browser.

<!-- DO NOT REMOVE ANYTHING BELOW THIS LINE -->
<script type='text/javascript'>
document.addEventListener("DOMContentLoaded", function () {
  $('#main-content h2').addClass('roleHeader');
 	$('#main-content h2').attr({
 	  'tabindex': 0,
 	  'role': 'button'
 	});
 	$('.roleHeader').click(function () {
 	  $(this).nextUntil('h2').stop(true, true).slideToggle();
	 }).nextUntil('h2').hide();
	 $('.roleHeader').keypress(function (e) {
 	  if (e.which == 13) { // Enter key pressed
			   $(this).trigger('click');
		  }
	 });
})
 </script>
