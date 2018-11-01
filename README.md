# Gaia-Mission
Final Project - Master in Innovation and Research in Informatics

Gaia is an ambitious space mission adopted within the scientific porgramme of the European Space Agecy (ESA) in October 2000. It measures  with very high accuracy the positions and velocities of a large number of stars and astronomical objects.
At the end of the mission, a detailed three-dimensional map of more than one billion stars will be obtained.

The Data Analysis and Procesing Consortium (DPAC), a large team of scientifics and software developers, is in charge of processing the Gaia data with the aim of producing the Gaia Catalogue. 

One of the most important DPAC system is the Intermediate Data Updating (IDU), exected at the Marenostrum supercomputer hosted by the Barcelona Supercomututing Center (BSC). Every few months, all the raw data accumulated up to that moment need to be reprocess in order to:

 - refine the parameters from the strometric images acquired by the instrument
 - refine the Cross Match (XM) for all the detections. 
 
The number of data will be huge and it won't be possible to handle them in a single process. Moreover, limitation and contrains imposed by the features of the execution environment should be considered. 
Therefore, it is necessary to optimize the Data Access Layer (DAL) in order to efficiently store the huge amount of data coming from the spacecraft and to access them in a smart manner, which was the main scope of the project. 

It has been developed and implemented an efficient and flexible file format based on Herarchical Data Format 5 (HDF5) (two different solutions a have been developed). It has been necessary to use the Java Native Interface (JNI) in order to adapt the software developed of the entire systen in this project. 

Project developed in C and Java.



