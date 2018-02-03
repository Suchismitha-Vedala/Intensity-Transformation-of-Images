
Intensity Transformation

The goal of the project is to perform Intensity transformation of images. Various operations have to be performed to obtain the objective. Image negatives, Power Law transformation, histogram matching and histogram equalization operations are the operations considered to enhance the intensity of the images in this project. To visualize the transformation, we need to design a User Interface.  The User interface should allow to upload an image and let the user choose an operation that is used to enhance the given image. The objective is to let user visualize the input and the enhanced image that lets the user to compare the outputs. The project is intended to perform operations on both gray scale and color images.

While Implementing the project, the first aim was to develop the User Interface.  Various technologies have been explored while designing the User Interface . The project is developed using Django, HTML , JavaScript and Python. Django is an Open Source high-level Python Web framework that encourages rapid development and clean, pragmatic design. The webpages of the user interface are developed using HTML and JavaScript. Python is used for performing the image operations. 

WEB APPLICATION

Web App is built using Django and Bootstrap templates. It is an MVC (model view controller) Application. All the operations on the image are called from the view function, the operation is performed in python and the result is returned to the view, which is then rendered in HTML. Each operation has a separate URL and View function, which performs the specified operation on the uploaded image.

IMAGE OPERATIONS

The following transformation operations are implemented in our project to perform intensity transformation of the given image. Each of the operation is compatible to perform on both gray scale and color images.
Each image operation is in a separate python file, which take the uploaded image as input and return the output. These operations are called from the view function and the result is passed to the HTML



USAGE:

This program is written and tested on Python 2, it may or may not work on python 3.

    go to the directory which cointains manage.py
    python manage.py runserver
    
    This runs the server on port 8000
    
    Click find out more, select an option and upload Images and see the magic.
    
    
