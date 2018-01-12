Activity 2
==============

Description
-----------
This design activity focuses on providing effective solutions to the goals required by the Seaspan shipping company. 
This design suggests a better way to manage, organize and supervise the schedule of their 7 vessels across 3 routes. 
Following are the assumptions made for our design:
* Routes are From Vancouver to Victoria/Nanaimo and Victoria-Nanaimo instead of the Tilbury-Swartz Bay/Nanaimo and Surrey-Nanaimo
* The Ships sizes in the map are roughly divided based on their capacity. We assume that it is possible.

Design Mockup
-------------
![Mockup](design.png)

What-Why-How
------------
### What
* Dataset: Networks (items, links, attributes)
* Data Types: 
	* Items: the berths (nodes) that contain instances of the attributes.
	* Links: routes (connections) between berths (nodes).
	* Attributes: info at each node such as ship id, max ship capacity, actual ship capacity, departure time, 
		arrival time, route, departure berth, arrival berth, ifDelayed

### Why
Actions
* Analyze:
	* consume: discover where vessels currently are, and the departure and arrival times. 
	* present: the design will be used to communicate information that is already know to the user. For example, the departure and arrival times. 
	* produce: use the information about how many passengers are on each vessel, and change schedules accordingly.

Targets
* Trends: Can notice that on specific days , or during specific hours of the day more people use the ferries. So for these times, they would need longer schedules for the day.
* Netwrok Data: berths = nodes, routes = paths betwenn nodes.

### How
Arrange
* Use: 
	* Use the existing Google Maps to show the different routes, ships and their information.
	* There are routes shown in the map and there are ships that are shown on those routes. These ships are interactive and hovering/clicking on them provides information like ship's id, max capacity and other attributes mentioned above.
	* Ships that are docked also mention the information related to berth in addition to their own information.

Map
* Color: 
	* The routes are encoded using different colors to clearly distinguish between them. It is also easier for the user to visually interpret the information.
	* The ships are also color coded based on the routes they are on. This discards any further ambiguity.

* Size:
	* Ships are divided into 3 different sizes (by roughly equally dividing them) so the user can quickly (at a glance) figure out which ship is where without having to interact with it.

Design Study Methodology
------------------------
### Learn
Learn about what current methods exist that would be helpeful in solving this problem ...

### Pitfalls



