# Safe Ryde
Developed at VTHacks7
By Ryan Gniadek, Ben Bernstein, Bryan Wells, Ronin Jayden


## Inspiration
Everyone wants a safe ride home. On the one hand, ride sharing services have a convenient interface but are expensive. On the other hand, coordinating rides with friends is difficult to organize. Safe Ryde is a way to streamline rides from friends.

## What it does
Safe Ryde has two user modes, Driver and Passenger. Passengers can request a ride and be added to the queue. Drivers can pick up the next passenger in line and receive information about the ride. They even have buttons to place a call to the passenger and let them know they've arrived and buttons to open the locations (pickup and drop-off) in Google Maps).

## How we built it
Front End: HTML, CSS (W3.CSS framework), JavaScript
Back End: Firebase Live Database, Google Cloud Platform

## Challenges we ran into
Initially, we attempted to implement our own API using Java Spring. After attending a workshop at the hackathon about Firebase, we decided to use it as our back-end system instead. We learned a lot about JavaScript and RESTful services.

## Accomplishments that we are proud of
We initially set out to create a mobile friendly web interface, which is exactly what we accomplished. We have a responsive front-end and a functional link to the back-end. Our app is published at [saferyde.tech](https://saferyde.tech) thanks to a free domain from Domain.com.

## What we learned
We learned about REST APIs, database technologies, JavaScript, and the importance of planning and research.

## What's next for Safe Ryde
If we can add authentication, user groups, and make our database ACID (atomicity, consistency, isolation, durability) friendly, the app would be deployable to a large audience.
