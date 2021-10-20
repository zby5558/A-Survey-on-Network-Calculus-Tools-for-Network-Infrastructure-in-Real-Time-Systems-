# A-Survey-on-Network-Calculus-Tools-for-Network-Infrastructure-in-Real-Time-Systems

This zip file contains the analyses of a tandem network from 4 servers to 20 servers used in the paper. There are two files under the path DiscoDNC Analysis\DNC-2.5.0\src\main\java\implementation. Four2TwentyTandem_ServerGraph.java is used to create the server graph of the tandem network, and Analysis4to20.java is used to implement TFA, SFA, and PMOO methods to analyze the flow of interest. 

DiscoDNC-2.5.0 contain the DiscoDNC project used to do the analyses and two files we have mentioned. To run the code, we should import the DiscoDNC folder to the eclipse. Moreover, the project needs two libaries, which are rtc.jar and commons-math3-3.6.1.jar. Both jar files are contained in the zip file. Users should right click the DiscoDNC-2.5.0 in the eclipse and then choose build path->configure build path. Then add two jars under the libraries tag.
