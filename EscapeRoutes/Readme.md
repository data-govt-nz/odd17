# Escape Routes

## Team

- **●●** Ben O'Brien
- **●●** Eszter Hardi
- **●●** John Gonzales (john@govtech.nz)

## Solution Definition:

A web and mobile app that:

- **●●**** Map with official escape routes overlaid onto it.** Local Authorities: City Councils, Regional Councils, NZ Civil Defence
- **●●**** Alternative routes from the crowd are also overlaid onto the map.** Locals will probably have alternative paths for escaping as they have more knowledge of the area. These could be useful for other people.
- **●●**** Different routes for different geographical features** (i.e., mountain, river, bridges)
- **●●**** Different routes for different types of disasters**
- **●●**** Different routes for different modes of transportation** (i.e., car, boat, helicopter, etc.)
- **●●**** Different routes for different demographics** (i.e., age groups, disabilities, families, etc.)
- **●●**** Routes are vetted by crowds.** When a route is published and people use it, the crowd can rate the route on various metrics (i.e., congestion, speed, does it actually work, etc.) and post photos or comments about the route or points in the route (i.e., picture of a washed out bridge, etc.)
- **●●**** Routes are updated by crowds.** By vetting the routes, the route information is updated so that people know whether or not take them.
- **●●**** Multiple safety points based on all of the above.**
- **●●**** Use existing media infrastructure to disseminate information** (i.e., any digital or smart boards, radio, TV, etc.)
- **●●**** Preventative information.** Provide users with information before a disaster strikes so they can be prepared.

Data

- **●●** Government information on evacuation zones based on the types of disaster
  - **○○** How far do we need to move inland / move up in elevation when a tsunami hits?
- **●●** Accessibility information. Is this route for:
  - **○○** Cars?
  - **○○** Wheelchairs?
  - **○○** Children?
  - **○○** Senior citizens
- **●●** Google Maps Road API
- **●●** DOC Road Information
- **●●** LINZ LDS
- **●●** Koordinates
- **●●** Population density
- **●●** Migration patterns (i.e., where are people usually at this time of the year when a disaster strikes so routes and safety points can be planned accordingly)
- **●●** Likely disasters in areas
- **●●** User generated data
  - **○○** Points on a map for a escape route
  - **○○** Vetting / feedback / rating routes
- **●●** Traffic Web Cams API - NZTA
- **●●** Traffic Road Event Information System (TREIS)
- **●●** DOC Walking Trails
- **●●** Safety Points
  - **○○** Designated Safe Areas from Local Authorities / Civil Defense
  - **○○** Bunkers
  - **○○** Strong buildings that can withstand disaster if you can&#39;t make it out
  - **○○** Earthquake building ratings
- **●●** Public transportation information for sharing methods of getting out of a disaster area

Assumptions

- **●●** Assuming NZ&#39;s infrastructure holds up in a disaster scenario
- **●●** Assuming that there will always be one path out.
- **●●** Assuming that we have full permission to use people&#39;s user generated content
- **●●** Assuming that we have full permission to use all data that we gather from government and other sources
- **●●**** Assuming that everyone wants to help each other. People believe in humanity and community!**
- **●●** Only applies to disasters that do not create complete chaos (i.e., lesser earthquakes). In the event of a more stressful scenario (i.e., higher magnitude earthquake) it&#39;s likely people won&#39;t care enough to add information into the app and will be more likely to focus on just getting out.