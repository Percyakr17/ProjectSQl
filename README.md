<h1 align="center"> Demo Not ready <Working> </h1>


The provided SQL script is designed to create and manage the database schema for a railway system. The script starts by dropping the schema railway_system if it exists and then recreating it. This ensures a clean setup of the database. Several tables are then created to store information relevant to the railway system's operations.
<br>

<li>user_login table holds information about users who log into the system, including their details and sign-up dates.</li>
<li>passenger table stores passengers' data, overlapping with some user data but with additional fields like contact details.</li>
<li>train_type defines different types of trains and their associated characteristics like coach count and passenger strength.</li>
<li>stations table contains data such as names, cities, and states.</li>
<li>train_details stores the data of individual trains, linking train types to stations and defining the duration and availability of the train.</li>
<li>journey table records passenger journeys, booking details, and payment status.</li>
<li>train_routes manages the specific routes a train takes, including the order of stations, estimated arrival and departure times, and halt duration.</li>
<br>

The script ensures relational integrity using foreign keys to link related tables, such as train_type, stations, and train_details. This database design is crucial for managing a railway system efficiently.
