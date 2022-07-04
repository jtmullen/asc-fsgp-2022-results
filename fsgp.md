---
layout: page-fullwidth
title: Formula Sun Grand Prix
description: "3 Days of Racing on the Track to qualify for ASC"
image: assets/images/illinois_track.jpg
nav-menu: true
---

FSGP 2022 is 3 days of racing on the 2.5 mile road course at [Heartland Motorsports Park](http://heartlandmotorsports.us/) in Topeka, Kansas. Solar Cars drive for 8 hours per day and have additonal solar charging time available in the morning and evening. FSGP is open to the public and free to attend! [Full Event Info →](https://www.americansolarchallenge.org/the-competition/2022-american-solar-challenge/)

-----

<ul class="actions">
<a href="#single-occupant-class" class="button special" style="margin:5px">Single Occupant Lap Results</a>
<a href="#multi-occupant-class" class="button special" style="margin:5px">Multi-Occupant Lap Results</a>
<a href="#mov-score" class="button special" style="margin:5px">Multi-Occupant Score Results</a>
</ul>

-----
## Single Occupant Class

In the Single Occupant Class vehicles are scored solely on laps completed. The team with the most laps (minus penalty laps) at the end of the three days wins!


{% include fsgp-lap class="sov" %}
<br>
<div style="margin:auto; text-align:center;"> <i> Scroll right to see all data on small screens </i></div>
{% include fsgp-table class="sov" %}
<div style="margin:auto; text-align:center;"> <b>Darkers Cells Indicate Teams Completing More Laps </b> </div>

-----
## Multi Occupant Class

In the Multi-Occupant Class vehicles are scored on a number of factors including:
- Total Person Laps (each additional passenger in the vehicle for a compeleted lap earns an additonal person lap)
- Target Speed (teams must average at least 30mph, if they do not their score is reduced)
- External Energy Usage (MOV cars can charge from non-solar sources, the amount of charging factors into the score)


{% include fsgp-lap class="mov" %}
<br>
<div style="margin:auto; text-align:center;"> <i> Scroll right to see all data on small screens </i></div>
{% include fsgp-table class="mov" %}
<div style="margin:auto; text-align:center;"> <b>Darkers Cells Indicate Teams Completing More Person Laps </b> </div>

## MOV Score

<link rel='stylesheet' href='{{site.baseurl}}/assets/css/charts.min.css'><link rel="stylesheet" href="{{site.baseurl}}/assets/css/fsgp-style.css">
<table id="stacked-example-3" class="charts-css column hide-data show-heading show-labels show-primary-axis show-2-secondary-axes data-spacing-2 multiple stacked">
  <caption> Iowa State </caption>
  <thead>
    <tr>
      <th scope="col"> Minnesota </th>
      <th scope="col"> #1 </th>
      <th scope="col"> #2 </th>
      <th scope="col"> #3 </th>
      <th scope="col"> #4 </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"> </th>
      <td style="--size: 0.5; --color: rgba(0,0,0,0);"><span class="data"> 30$ </span></td>
      <td style="--size: 0.25;"><span class="data"> 30$ </span></td>
    </tr>
    <tr>
      <th scope="row"></th>
      <td style="--size: 0.5; --color: rgba(0,0,0,0);"><span class="data"> 30$ </span></td>
      <td style="--size: calc(30 / 150);"><span class="data"> 30$ </span></td>
    </tr>
    <tr>
      <th scope="row"></th>
      <td style="--size: 0.25; --color: rgba(0,0,0,0);"><span class="data"> 30$ </span></td>
      <td style="--size: 0.25;"><span class="data"> 30$ </span></td>
    </tr>
    <tr>
      <th scope="row"></th>
      <td style="--size: 0.5; --color: rgba(0,0,0,0);"><span class="data"> 30$ </span></td>
      <td style="--size: 0.1;"><span class="data"> 30$ </span></td>
    </tr>
  </tbody>
</table>

<br>

### Scoring Formula
At FSGP the MOV Score (S) is calculated as follows: **S = (D / E) x C x T**

The variables are as follows:
- **D** - Total Personal Miles (Person Laps * 2.5 miles) minus penalty miles
- **E** - External Energy Used in kWh
- **C** - Completion Factor as a percentage of the highest person miles completed by any team
- **T** - Target Speed derating. For teams averaging below 30 mph their score is exponentially derated based on their average speed 

<i>Note for teams: See the regulations for full details, information here may be simplified</i>