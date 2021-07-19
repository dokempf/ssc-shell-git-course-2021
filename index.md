---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
venue: "Heidelberg University"        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: "online"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "de"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "en"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the
latitude: "45"        # decimal latitude of workshop venue (use https://www.latlong.net/)
longitude: "-1"       # decimal longitude of the workshop venue (use https://www.latlong.net)
humandate: "July 27-28th, 2021"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "9am - 1pm"    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate: 2021-07-27      # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2021-07-28        # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
instructor: ["Dominic Kempf"] # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper: ["Gwydion Daskalakis"]     # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["dominic.kempf@iwr.uni-heidelberg.de"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
collaborative_notes:  # optional: URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite:           # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---


<h2 id="setup">Setup instructions for courses based on Software Carpentry materials</h2>

<p>
  To participate in a
  {% if site.carpentry == "swc" %}
  Software Carpentry
  {% elsif site.carpentry == "dc" %}
  Data Carpentry
  {% elsif site.carpentry == "lc" %}
  Library Carpentry
  {% endif %}
  workshop,
  you will need access to software as described below.
  In addition, you will need an up-to-date web browser.
</p>
<p>
  We maintain a list of common issues that occur during installation as a reference for instructors
  that may be useful on the
  <a href = "{{site.swc_github}}/workshop-template/wiki/Configuration-Problems-and-Solutions">Configuration Problems and Solutions wiki page</a>.
</p>

{% include swc/setup.html %}
{% include install_instructions/videoconferencing.html %}