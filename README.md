# NIDS-Pi
NIDS using plug and play raspberry-pi.
------------------------------------------------------------------------------------------------------------------------------

.bashrc is used to automate the raspberry pi as plug and play, ssh is used to islote the system in case infected. YARA rules is used for malware detection in network, tshark is used to capture packets and bro is used to analyze them and extract the files.

# Basic work flow

![Alt text](https://github.com/wolf1892/nids-pi/blob/master/upes.jpeg?raw=true "Workflow")

![Alt text](https://github.com/wolf1892/nids-pi/blob/master/upes1.jpeg?raw=true "Workflow")

------------------------------------------------------------------------------------------------------------------------------

KitNET is combined with current solution to detect MITM or any network intrusion using ANN.

# Future work

The current idea is to convert the logs into images and train the model using deep learning to detect any zero days in the network, the idea is to convert the conn.log into matrix consisting of each network request as 1 or a 0. Every malware after certain succession reaches out to its CnC server, however these connections made form a pattern. N number of patterns can be made and converted into image (since we convert logs into matrix, there after converting them into image) and irregularities can be reported.


(The project was made during UPES Hackathon 2020)





