# TransitFusion
TransitFusion - Seamless Multi-Modal Travel Planning

## Required Equipment
To develop TransitFusion, I will need a mobile device (iOS or Android) for
testing, access to APIs from transportation services like Greyhound, Google
Flights, and various local transit systems, as well as a development environment
such as Android Studio or Xcode. Additionally, web scraping tools will be
required for transportation data that lacks API access.

## Problem Formulation
Planning complex trips involving multiple modes of transportation, such as
buses, flights, and local transit systems, often requires navigating multiple plat-
forms. Travelers face confusion and delays when they need to switch between
websites, especially when standard tools like Google Maps don’t fully support
the journey. This project aims to solve this logistical problem by consolidating
transportation schedules from various sources into a single mobile app. The
technical challenges include aggregating data from fragmented or missing APIs,
ensuring real-time updates, and integrating data formats from diverse sources
into a unified travel plan that takes into account user preferences.

## Motivation
This project was inspired by the frustrations of planning international travel
from small towns like Grinnell, Iowa, United States to distant cities like Hanoi,
Vietnam, where different transport services are not covered by a single tool.
With travel surging post-pandemic, there is a rising demand for more integrated
travel tools that simplify the user experience by minimizing the need for manual
itinerary construction. The goal is to improve quality of life by reducing the
time and stress involved in creating a seamless, multi-modal travel plan.

## Approach
TransitFusion will function by allowing users to input their travel origin and
destination. The system will then collect transport schedules from multiple
APIs and scraped websites, organizing this data into a coherent travel itinerary
that spans all modes of transport, even when traditional tools like Google Maps
don’t offer full coverage. The app will consist of a user interface for inputting
trip details, a data aggregator that handles the collection of schedules, a route
optimizer that generates the most efficient travel path based on user preferences,
and a real-time notification system for delays or schedule changes.

## Related Work
TransitFusion builds on existing systems like Google Maps and Rome2Rio, both
of which offer multi-modal travel solutions but face significant limitations in
small towns and across international borders. While Rome2Rio consolidates
some travel data, it lacks real-time updates and complete coverage, particu-
larly in regions where official APIs are unavailable. This project addresses
those gaps by integrating web scraping and real-time notifications to provide
more comprehensive and dynamic coverage of transportation options. It also
draws from several key works in multi-modal journey planning. Aditjandra et
al.’s “A Multi-Modal International Journey Planning System: A Case Study
of WISETRIP” (2009) highlighted challenges in integrating international travel
data, which TransitFusion tackles through real-time data handling. Ali and
Jiang’s “Traveling Itinerary Problem in a Scheduled Multimodal Transporta-
tion Network” (2023) further illustrates the complexity of fixed-sequence city
travel, which TransitFusion resolves by offering flexible, dynamic itinerary up-
dates. Lastly, Potthoff and Sauer’s “Efficient Algorithms for Fully Multimodal
Journey Planning” (2022) provide critical insights that inform the algorithms
TransitFusion uses to optimize travel plans.

## Experiments/Demo
The success of TransitFusion will be evaluated through several metrics, including
the accuracy of travel plans, response time when generating routes, and user
satisfaction compared to existing tools like Google Maps. The app will be tested
by inputting a complex, multi-modal travel route, with TransitFusion generating
a seamless travel itinerary. Users will be able to compare the suggested routes
against traditional travel apps to demonstrate the advantages of the app in
creating more comprehensive and personalized travel plans.
