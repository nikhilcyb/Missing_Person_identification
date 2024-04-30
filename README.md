# Missing_identification
Web-based Missing Person Identification System with Face Recognition

This system aims to help find missing people using facial recognition technology through a user-friendly web interface. Here's a breakdown of the key aspects:

System Functionality:

* Users can upload pictures of people they suspect are missing.

* The system analyzes the uploaded image for faces using a Convolutional Neural Network (CNN).

* If a face is detected, it's compared against a database of missing persons' faces.

* If a match is found, the user sees the missing person's information and can choose to inform the police.

Benefits:

* Faster and more efficient than traditional methods.

* More accurate due to the power of face recognition.

* Accessible to anyone with an internet connection.

* Protects privacy by not revealing missing persons' contact information.

System Components:

* Admin Module: For managing the system, including adding/editing users, viewing reports, and managing the missing person database.

* User Module: For users to upload photos, search for missing persons, and inform the police.

* Searching Module: Enables searching the database by name, age, location, etc.

* Inform to Police Module: Allows users to report a suspected missing person to the nearest police station.

Technical Details:

* The system can run on various hardware and software platforms.

* Minimum recommended requirements include a 2.0 GHz processor, 2 GB RAM, 10 GB storage, and a modern web browser.

Evaluation Results:

* Tested on a dataset of 200 missing person images and 100 non-missing person images.

* Achieved 98.89% accuracy in face detection and database matching.

* Identified missing persons in 80% of cases and informed police in 75% of cases.

User Interface Highlights:

* Simple search interface on the home page.

* Option to search by uploading an image or taking a picture with a device camera.

* User verification step for confirmed matches.

* Informative messages for cases with no match or unclear images.

* List of all missing people with details and images for easy browsing.

Conclusion:

  This project proposes a web application that uses deep learning for face recognition to help find missing people. It focuses on situations where there are no security cameras, allowing anyone to upload pictures of people they suspect are missing. The system then checks the uploaded image against a database of missing persons and, if there's a match, provides information and the option to alert the police.

  This system has the potential to significantly improve missing person searches by offering a fast and accurate way to identify individuals through photos. Their approach utilizes a deep learning algorithm called a CNN to achieve an impressive 98.89% accuracy rate.
