# CODETECH_IT_SOLUTIONS_INTERNSHIP

NAME: B LAKSHMI PRASANNA

INTERN ID:CTIS8437

DOMAIN: JAVA PROGRAMMING

DURATION: 8 WEEKS

MENTOR: VAISHALI

# Task 1 – File Handling Utility
# Overview:
This project is part of the CodTech Java Internship program. It demonstrates a comprehensive file handling utility built in Java that performs essential operations such as creating, reading, writing, appending, modifying, and deleting text files using Java's built-in I/O libraries.
# Objective:
The primary goal of this task is to gain hands-on experience with Java's file handling capabilities. File operations are a fundamental part of real-world applications including logging systems, configuration managers, and data storage solutions. This program covers all core file operations with proper exception handling and clean code structure.
# Features:
Write – Creates a new text file and writes initial content to it
Read – Opens and displays the complete content of an existing file
Append – Adds new lines to an existing file without erasing previous content
Modify – Searches for specific text inside the file and replaces it with updated content
Delete – Removes the file from the system after operations are complete
Exception Handling – Catches and handles errors like FileNotFoundException and IOException with meaningful messages
# Key Concepts Learned:
Understanding the File class and its methods in Java
Reading files efficiently line by line using BufferedReader
Writing and appending content to files using FileWriter and BufferedWriter
Modifying file content by reading, replacing, and rewriting
Properly closing file streams to prevent memory leaks
Handling checked exceptions using try-catch blocks
# Technologies Used:
Java SE (Standard Edition)
java.io package
BufferedReader and BufferedWriter classes
FileReader and FileWriter classes
File class for file management


# Task 2 – REST API Client
# Overview:
This project is part of the CodTech Java Internship program. It is a Java application that connects to a public REST API, sends HTTP GET requests, receives JSON responses, and displays the fetched data in a well-structured and readable format. A weather data API is used as a demonstration example.
# Objective:
The goal of this task is to understand how Java applications interact with external web services over the internet. This involves establishing HTTP connections, reading server responses, and parsing JSON formatted data into meaningful output. These skills are essential for building modern Java backend applications and microservices.
# Features:
HTTP Connection – Establishes a connection to a public REST API using Java's HttpURLConnection
GET Request – Sends a properly formatted HTTP GET request with required parameters
Response Reading – Reads the full server response using BufferedReader
JSON Parsing – Extracts specific fields from the JSON response using Gson or org.json
Structured Display – Presents the fetched data in a clean and organized console output
Error Handling – Manages HTTP errors, connection timeouts, and invalid responses gracefully
# Key Concepts Learned:
Establishing HTTP connections using HttpURLConnection and URL classes
Sending GET requests and reading input streams
Parsing and extracting data from JSON responses
Working with third-party libraries like Gson or org.json
Handling network exceptions and non-200 HTTP status codes
Understanding REST API structure and endpoints
# Technologies Used:
Java SE (Standard Edition)
java.net package
java.io package
Gson or org.json library for JSON parsing
Public REST API (e.g., OpenWeatherMap API)

# Task 3 – Multithreaded Chat Application
# Overview:
This project is part of the CodTech Java Internship program. It is a fully functional real-time client-server chat application developed using Java Socket programming and Multithreading. The server can handle multiple clients simultaneously, allowing users to exchange messages with each other in real time through a central server.
# Objective:
The goal of this task is to understand the fundamentals of network programming and concurrent execution in Java. By building this chat application, key concepts such as socket communication, thread management, and message broadcasting are explored and implemented. These skills form the foundation of networked applications and real-time communication systems.
# Features:
Server Setup – A dedicated server that continuously listens for incoming client connections on a specified port
Multiple Client Support – Each client connection is handled on a separate thread allowing simultaneous communication
Real-Time Messaging – Messages sent by one client are instantly broadcast to all other connected clients
Username Support – Each client joins the chat with a unique username for identification
Join and Leave Notifications – Server notifies all users when someone joins or leaves the chat
Exception Handling – Handles unexpected client disconnections and network interruptions gracefully
# Key Concepts Learned:
Socket programming using ServerSocket and Socket classes
Creating and managing multiple threads using the Thread class and Runnable interface
Broadcasting messages to all connected clients using a shared client list
Synchronizing shared resources in a multithreaded environment
Managing input and output streams over a network connection
Handling client disconnection and cleaning up resources properly
# Technologies Used:
Java SE (Standard Edition)
java.net package (ServerSocket, Socket)
java.io package (BufferedReader, PrintWriter)
java.lang.Thread for multithreading
java.util.ArrayList for managing client connections


# Task 4 – AI-Based Recommendation System
# Overview:
This project is part of the CodTech Java Internship program. It is an intelligent recommendation system built in Java that analyzes user preferences and behavior from a sample dataset and suggests relevant products or content using collaborative filtering techniques. The system is implemented with the help of the Apache Mahout machine learning library.
# Objective:
The goal of this task is to understand how AI-powered recommendation engines work and how they are implemented in Java. Recommendation systems are widely used in platforms like Amazon, Netflix, and Spotify to personalize user experiences. This project provides a foundational understanding of how such systems analyze patterns and generate intelligent suggestions.
# Features:
Dataset Loading – Loads user preference and rating data from a CSV file using FileDataModel
Similarity Computation – Calculates the degree of similarity between users using Pearson Correlation or Euclidean Distance
User-Based Filtering – Identifies users with similar tastes and preferences to the target user
Item Recommendations – Suggests top-rated items that similar users have liked but the target user has not yet interacted with
Configurable Results – Allows setting the number of recommendations to be generated
Sample Dataset – Includes a built-in sample dataset for testing and demonstration purposes
# Key Concepts Learned:
Understanding collaborative filtering and how recommendation algorithms work
Loading and processing structured data using Apache Mahout's FileDataModel
Computing user similarity scores using PearsonCorrelationSimilarity
Building a user-based recommender using GenericUserBasedRecommender
Evaluating recommendation quality using basic metrics
Integrating third-party machine learning libraries into a Java project
# Technologies Used:
Java SE (Standard Edition)
Apache Mahout Library
FileDataModel for data loading
PearsonCorrelationSimilarity for similarity measurement
GenericUserBasedRecommender for generating recommendations
CSV file as the sample data source
