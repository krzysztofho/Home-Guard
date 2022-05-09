# Home-Guard
The Home guard is project which will help you protect your propery.
The main aim is detect people in one of three areas:
* green - no danger zone like your neighbour yard
* yellow - it common area like street
* red - your property
Of course system should filter people which are your friend or family and neutral like postman.

First iteration will be detection people:
* no areas
* no people segmentation and tracing
* creating alert: People detected

Second iteration will be people tracing, so it means that we want to reduce all false positive alerts: 
* people tracing
* creating one of three alerts:
  * Person detected on yellow area which was observing your property
  * Person pass into red area and was there more than X seconds

Second iteration should reduce cases as neigbours or pedastrians

Third iteration will have face recognition, what will allow:
* Recognize people and make segmentation for neutral, family
* Give new information, like person X was in area eg. yellow Y times in this week/month/year

Project is realese for learning how to detect/track object.
