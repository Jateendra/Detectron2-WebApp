1 . Download file : https://drive.google.com/u/0/uc?id=1zdwgVv3G_z9P1z8hPo9gUG4GuZHrcimK&export=download

2 . Unzip and place in location : C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project

3 . Open Anaconda prompt :

		cd C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project\detecron2_webapp
    
		conda create -n detectron2-webapp python==3.7
    
		conda activate detectron2-webapp
    
		pip install -r requirements.txt
    
		git clone https://github.com/facebookresearch/detectron2.git 
    
			- Here detectron2 folder will be created .
      
4 . Cut the folder "detectron2" from location : C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project\detecron2_webapp\detectron2
	and put it under location : C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project
  
5 . Delete folder "detectron2" from location : C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project\detecron2_webapp

6 . Cut folder "detectron2" from location : C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project
	and put it under location : C:\Users\Sasmitabhoi\Documents\DL_CV_NLP\Object_Detection\Project\detecron2_webapp
  
7 . Go to Anaconda prompt:

		pip install pycocotools-windows
    
		python clientApp.py
    
			- pip install fvcore cloudpickle
      
		python clientApp.py
    
			- pip install omegaconf
      
		python clientApp.py
    
8 . Open a browser : http://localhost:9000/

	- Select an image and predict it .
