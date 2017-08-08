# keras

activate tensoflow


https://stackoverflow.com/questions/34097988/how-do-i-install-keras-and-theano-in-anaconda-python-on-windows

Install TDM GCC x64.
Install Anaconda x64.
Open the Anaconda prompt
Run conda update conda
Run conda update --all
Run conda install mingw libpython
Install the latest version of Theano, pip install git+git://github.com/Theano/Theano.git
Run pip install git+git://github.com/fchollet/keras.git


jupyter notebook


-------------

-- CREATE ENVIRONMENT/WORKSPACE FOR PYTHON 3.5:

C:\conda create --name neuralnets python=3.5
C:\activate neuralnets
-- INSTALL EVERYTHING (notice the neuralnets workspace in parenthesis on each line). ACCEPT ANY DEPENDENCIES EACH OF THOSE STEPS WANTS TO INSTALL:

(neuralnets) C:\conda install theano
(neuralnets) C:\conda install mingw libpython
(neuralnets) C:\pip install tensorflow
(neuralnets) C:\pip install keras
-- TEST IT OUT:

(neuralnets) C:\python -c "from keras import backend; print(backend._BACKEND)"
Just remember, if you want to work in the workspace you always have to do:

C:\activate neuralnets

jupyter notebook