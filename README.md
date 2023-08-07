# Registered-Vehicles-Software
A project in Java

In this project, I have developed a Vehicle Management System using Java that allows users to handle various aspects of vehicles, including registration, ownership, and essential details such as make, model, and mileage. The system is designed to manage a fleet of vehicles and is part of a larger application that assists in organizing vehicle-related information.

Key Features:

Vehicle Class Hierarchy: The project includes a comprehensive class hierarchy, with the Vehicle class serving as the parent class for all types of vehicles. This inheritance structure enables code reusability and promotes a modular approach.
Vehicle Data Input and Validation: The system employs setters and getters to manage vehicle data, ensuring that only valid and legal values are accepted for critical attributes such as registration number, odometer reading, year of manufacture, and license plate number. The IllegalVehicle exception class handles any input that violates the defined constraints.
CarOwner Class: The project utilizes a CarOwner class that encapsulates essential information about vehicle owners, allowing efficient association of vehicles with their respective owners.
Javadoc Documentation: The code is thoroughly documented using Javadoc comments, enabling developers to understand the functionality of classes, methods, and their parameters effectively.
Vehicle Signature and Comparison: The project includes methods to create a signature for each vehicle based on its top 25 frequently occurring words in the description. It employs Jaccard similarity to determine the most similar vehicles based on their signatures.
Graphical User Interface (GUI): While not shown in the provided code, the project is designed to have a user-friendly GUI for users to interact with the Vehicle Management System effectively. The GUI would allow users to input and visualize vehicle details, manage ownership records, and access similarity analysis results.
