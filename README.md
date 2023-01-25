# Overview
This project is aimed at analyzing various aspects of the business processes of a major airline company to discover new opportunities for expansion. The company has hired me to assist with this analysis. The first deliverable focuses on flight activity, while future deliverables will include the reservation process and customer interactions.

Data Modeling Technique
The chosen technique for storing and analyzing the data is Data Vault, with Dimensional Modeling being used for reporting and querying. Data Vault is used because it allows for the tracking of changes to passenger data in a single entity and increases performance through parallel loading.

# Business Processes
The analysis will focus on three main business processes:

Reservation process - measured per transaction
Customer care - measured per transaction
Flight activity - measured per day

# Dimension Tables
There will be sixteen dimension tables used in these three processes, each representing different aspects of the data. These include:
Booking_Channel
Airport
Flight
Location
Route
Airplane
Flight_Type
d_date
Interaction
Survey
Fare
Booking_Class
Ticket
Frequent Flyer information

# Goal
The goal of this project is to discover new opportunities for the airline company by understanding their current business processes in greater detail. The Data Vault and Dimensional Modeling techniques, along with the specific dimension tables chosen, will support this analysis by allowing for the efficient storage and querying of the data.
