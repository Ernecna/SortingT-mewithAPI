Java Sorting Algorithm Analysis with API Integration
Introduction
This Java application offers sorting functionality with an API interface for json.Vulnerability objects. It utilizes Jackson libraries for JSON parsing, ideal for cybersecurity data sorting and analysis.

File Overview
hw2.java: Provides various sorting algorithms and an API to process vulnerability data.
json.java: Outlines the json.Vulnerability class and JSON handling methods.

Sorting Algorithms 
Merge Sort
Insertion Sort
Heap Sort
AVL Sort
Quick Sort.

API Functionality
Provides sorting via API endpoints.
Allows for seamless integration and batch processing.

Running the Code with Jackson Libraries
To run the code, which relies on Jackson libraries for JSON operations:
1.Install the Java Development Kit (JDK) if it's not already installed.
2.Obtain the JAR file of the application, which should include all the necessary Jackson library dependencies.
3.Open a terminal or command prompt.
4.Navigate to the directory where the JAR file is located.
5.Run the JAR file with the following command:
java -jar pa2.jar data1.txt
Note: If the JAR file does not contain the dependencies, ensure the Jackson library JARs are in the classpath when executing the application. You can specify the classpath using the -cp flag in the Java command.

Usage and Performance Testing
Performance is evaluated based on sorting algorithms' execution times on various-sized data sets and API latency measurements.

Conclusion
The application's rich sorting capabilities, coupled with Jackson for JSON processing, make it a powerful tool for sorting and analyzing data. Efficiency and response time are key when integrating with systems that require real-time data handling.

