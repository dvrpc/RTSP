# Regional Transit Screening Platform Toolbox

DVRPC's Regional Transit Screening Platform is a web tool to identify different types of transit gaps to assist in making data-driven decisions to evaluate and prioritize transit improvements throughout the region.

## Project Overview

The primary goal of DVRPC's Regional Transit Screening Platform Study was to develop regionally-consistent, data-driven tools that the Commission and its planning partners can use to evaluate service, operational, and new capacity transit investments. Before starting the 2050 Long Range Plan, DVRPC wanted a fresh look at transit throughout the region. The tools aim to separate the worthwhile transit projects on the existing list from those that are less beneficial, and also generate new transit improvement ideas.

This study consists of four primary sections:

- Network Gaps
- Transit Accessibility
- Service Frequency
- Surface Transit Reliability

## Local Development

`git clone https://github.com/dvrpc/RTPS.git`

`cd RTPS`

Create a .env file and create the `API_BASE` variable that points to the location of the API, e.g.
`API_BASE="https://cloud.dvrpc.org/api/rtsp/v2"`

`npm install`

`npm start`

Open <http://localhost:9000/> (likely) in your browser.
