# Hand Sign Detection Using Tensorflow

The set of notebooks up above provide a complete set of code to be able to train and put your own custom object detect model using the Tensorflow Object Detection API. 

**Clone the repository**

    git clone https://github.com/utkarsh125/tensorflow-hand-sign-detection

**Pre-requistes**

 1. Python 3.8
 2. Microsoft Visual Studio 2019 
 3. OpenCV 
 4. Tensorflow *(See the installation guide [here](https://www.tensorflow.org/install/))*
 5. Tensorflow Object Detection API *(See the installation guide [here](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html))*
 6. Webcam *(for this project in particular)*

## Installing Necessary Software To Get Started

We will start off by first installing everything that is needed for our models to get trained

**Microsoft Visual Studio 2019**
Go to this [link](https://visualstudio.microsoft.com/vs/older-downloads/) and download Microsoft Visual Studio 2019 along with C++ Desktop Development Kit *(Keep mind that this will install all the build tools necessary for your Tensorflow base)*.

*NOTE: The installation speeds will be different as it primarily depends upon your internet speed*.

**Python 3.8**
Installing this is quite simple and straight forward, just google it and install it for your operating system. Be sure to add it to your `PATH` so that you can access it through your terminal/command prompt - this will fix any version clashes.

## Creating a Virtual Environment For The Project
Open your command prompt and type

    python -m pip install --upgrade pip

The above line of code will **install the latest version of pip**

Now create a Virtual Environment by typing

    python -m venv ENV_NAME
This will create a new virtual environment at C:\\Users\User_Name\ENV_NAME
If you don't want to create it in the main drive, you can always use `cd /DIRECTORY/` to hop into the folder right away and create the virtualenv there.

Now to activate it head to the environment's directory by

    cd /DIRECTORY/ENV_NAME/Scripts
Now to activate the environment just type

    activate
This will activate your virtualenv, to make sure that it's activated, check on the extreme left of the command prompt - if your virtualenv is visible in brackets then it means that the environment is activated.

Now install **OpenCV** and **Tensorflow**

    pip install opencv-python 
    pip install tensorflow
*OPTIONAL: If you are on a Nvidia GPU then use tensorflow-gpu as it will speed up your training processes exponentially. To use tensorflow-gpu you need **CUDA and CUDNN**. For `tensorflow==2.8.x` make sure you **install CUDA 11.2 and CUDNN 8.1** 

Look for the installation guide [here](https://towardsdatascience.com/installing-tensorflow-with-cuda-cudnn-and-gpu-support-on-windows-10-60693e46e781)

Once you're done just paste this code in your command prompt

    pip install tensorflow-gpu
If you followed the above steps correctly, congratulations you have installed Tensorflow from scratch.

After you're done, install **Tensorflow Object Detection API** using the installation guide [here](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)

Now you're all set to run the codes
