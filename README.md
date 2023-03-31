# Hospital-Management-System


This is a Java program for a Hospital Management System that provides a basic interface to manage patient and doctor records. The system allows users to perform various tasks such as viewing patient records, adding a new patient record, updating an existing patient record, deleting a patient record, viewing doctor records, adding a new doctor record, updating an existing doctor record, deleting a doctor record, and viewing the number of remaining beds available in the hospital.

The program has a static variable bedsRemaining that stores the number of beds remaining in the hospital. Users can only add a new patient record if there is at least one bed available. The program uses text files to store patient and doctor records, and the program uses BufferedReader and BufferedWriter classes to read and write to these files.

The system is menu-driven, and users can select options by entering a number corresponding to the desired option. The program utilizes a switch case statement to perform the selected option. The program uses a do-while loop to keep the menu running until the user selects the option to exit.
