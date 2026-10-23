---
layout: post
title: Earthquake Tracking Dashboard Using Tableau
image: "/posts/tableau-map-image.png"
tags: [Tableau, Data Viz]
---

This Tableau dashboard tracks global earthquake activity across a 30-day period.

# Table of Contents

- [00. Project Overview](#project-overview)
- [01. The Data](#the-data)
- [02. The Dashboard](#the-dashboard)
- [03. Insights](#insights)

___

# 00. Project Overview <a name="project-overview"></a>

The goal of this project is to create an interactive Tableau dashboard that allows users to explore recent earthquake activity across the world.

Rather than presenting the data as a static table, the dashboard allows the user to investigate earthquake frequency, location, magnitude, and regional patterns in a more visual and interactive way.

This is useful because geographic data is often much easier to understand when it can be explored on a map, filtered by date, and supported with simple summary charts.

___

# 01. The Data <a name="the-data"></a>

The dashboard uses earthquake data covering a 30-day period.

Each record represents an individual earthquake event, with information such as the date and time of the event, the latitude and longitude, the recorded magnitude, and the location.

To make the dashboard more useful, the data can be viewed at both a detailed location level and a broader regional level.

This helps the user understand not only where individual earthquakes occurred, but also how activity compares across wider parts of the world.

___

# 02. The Dashboard <a name="the-dashboard"></a>

The dashboard includes a global earthquake map, a table showing the top 10 largest earthquakes, a broad regional breakdown, and location-level analysis for frequency, average magnitude, and maximum magnitude.

This allows the user to quickly move from a high-level global view into more specific location-based insights.

Some useful questions this dashboard can help answer include:

- Where are earthquakes most frequently being recorded?
- Which locations have the highest average magnitude?
- Which individual earthquakes had the largest recorded magnitude?
- How does earthquake activity differ across broader global regions?

<div class="tableauPlaceholder" id="viz1792648161639" style="position:relative">
  <noscript>
    <img alt="DSI Earthquake Tracker"
      src="https://public.tableau.com/static/images/DS/DSIEarthquakeDashboard-GD/DSIEarthquakeTracker/1.png" />
  </noscript>
  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="DSIEarthquakeDashboard-GD/DSIEarthquakeTracker" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param name="filter" value="publish=yes" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("viz1792648161639");
  var vizElement = divElement.getElementsByTagName("object")[0];

  vizElement.style.width = "100%";
  vizElement.style.height = "900px";

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
___

# 03. Insights <a name="insights"></a>

From this view, we can see that earthquake activity is not evenly distributed across the world.

Some locations show a high frequency of earthquake records, while others stand out more because of their maximum magnitude values.

This is a useful example of how Tableau can be used to turn raw geographic data into an interactive dashboard that helps users explore patterns quickly, rather than relying only on static tables or written summaries.

It also shows how dashboards can combine different views of the same data, including maps, tables, filters, and summary charts, to create a more complete picture for the user.
