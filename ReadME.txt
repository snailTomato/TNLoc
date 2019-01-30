README

This solution includes two projects, is triplet_network_model and TNLocWeb. 
triplet_network_model trains the model and TNLocWeb uses this trained model for localization.
TNLocWeb is a web app and available in http://129.204.114.108:5000 


Requirement:
If you want to run my source code, please prepare:
python 3.x
tensorflow 1.12.0 (pip3 install -U tensorflow==1.12.0)
Flask 1.0.2 (pip3 install -U Flask==1.0.2)


How to use:

Project triplet_network_model
	command: cd /triplet_network_model 
			 python3 main.py  

Project TNLocWeb
	command: cd /TNLocWeb
			 python3 app.py