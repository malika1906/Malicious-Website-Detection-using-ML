# Malicious-Website-Detection-using-ML

The aim of this project is to address malware detection and to secure a browser plugin by warning the users 
against malware. It warns users when they come upon a malicious or blacklisted website which could harm 
their system or make them vulnerable to various forms of cyber-crimes.

This browser extension can be loaded onto google chrome browser and enabled active there. 

To determine maliciousness,  a classified list of features was selected and used for the detection process.
The data against these features are extracted from the input url and used to predict the outcome. 
The two classifiers that were used are Random Forest and Support Vector Machine.

The extension will raise an alert/popup to caution the users whether the website is safe or not. 
