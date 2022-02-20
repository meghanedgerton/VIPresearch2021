# VIPresearch2021
Achieving biometric identification/authentication using an EEG and a random forest classifier model.

This repository includes the work from the project done for a Vertically-Integrated Project (VIP) in my senior year of my undergraduate degree at Boise State University. For this project we used an electroencephalogram (EEG) on three subjects, taking recordings of each subject while they were asked to perform double-digit multiplication mentally in a restricted amount of time. The goal with this project was to use this data from the EEG as an alternate form of biometric identification and ultimately, authentication as well.

With the collected data, I built a Random Forest classifer in Python, using each subject as the classes. I used an 80/20 train/test split for this initially to minimize computational expense. In training, the model acheived an accuracy of 98% with an 1.24% error rate. After tuning the model it acheived a 98.6% accuracy with the test set data. 

This project was presented at the 2021 Undergrate Research Showcase hosted by Boise State in April of 2021. I built the Random Forest model while my teammates built a Convolutional Neural Network (CNN) for comparison. The others involved in this study were Gabe Miles, Marghece Barnes, Erin Kerr, and Callum Young.
