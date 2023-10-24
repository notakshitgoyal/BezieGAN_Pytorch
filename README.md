# BezieGAN_Pytorch
https://github.com/IDEALLab/bezier-gan/blob/master/beziergan/consistency.py
#PROJECT KILLED

use orignal gan 

 1. Create a virtual environment with Python 3.6

 2. Navigate to the "bezier gan" directory
	cd path/to/bezier-gan-directory

 3. Create a new directory named "beziergan2"
	mkdir beziergan2

 4. Change your current directory to "beziergan2"
	cd beziergan2

 5. Create another virtual environment in "beziergan2" with Python 3.6
	python3.6 -m venv venv

 6. Navigate to the "venv/Scripts" directory
	cd venv\Scripts

 7. Upgrade pip to the latest version (user-specific)
	pip install --user --upgrade pip

 8. Activate the virtual environment
 On Windows
	.\Activate.ps1
 On other platforms, use the appropriate activation command

 9. Ensure you've chosen the correct Python kernel in your development environment (e.g., VSCode).

 10. Install TensorFlow version 1.15.5
	pip install tensorflow==1.15.5

 11. Install the NumPy library
	pip install numpy

 12. Install Protocol Buffers (protobuf) version 3.20.0
	pip install protobuf==3.20.0

 13. Install the Matplotlib library for data visualization
	pip install matplotlib

 14. Install the scikit-learn library for machine learning tasks
	pip install scikit-learn
	
 15. Run the GAN training script with the specified parameters
	python path/to/train_gan.py train 64 16
