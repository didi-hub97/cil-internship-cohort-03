# This folder contains answers to the Python task

### A Python function to copy and to resize an image.

python3 -m pip install Pillow (#to install the pillow package, Pillow which will be used to resize the image)

from PIL import Image (#import the just install library)



def image_copy_resize():
#Image.open() can also open other image types

    img = Image.open("some_random_image.jpg")
#WIDTH and HEIGHT are integers
     resized_img = img.resize((WIDTH, HEIGHT))
        resized_img.save("resized_image.jpg")
im = Image.open('image.jpg')  
im = im.resize((w, h)) 

image_copy_resize()