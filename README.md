# Spring 2023 exam project overview

## Overview
This project is a route planning app for the New York City public transit network, with a function to view points of interest near the stops.<br>
It features a Neo4J graph database for route planning queries, a MongoDB for keeping points of interest and doing geospatial queries for them, and redis for caching API request data.<br>

## requirements
### functional
- The system should be able to provide a viable route between any two stops that can be connected by the network.
- The system should provide points of interest for the user to experience around their destination.

### non-functional
- The system must remain responsive under load, such that users will not miss connections due to unresponsiveness, etc...
- 
