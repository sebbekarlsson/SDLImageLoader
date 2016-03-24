# SDLImageLoader
> Load images easily in SDL2.

# How to use
> Loading an image is easy:

        SDLImageLoader loader = SDLImageLoader();
        EasyImage * image = loader.load("b1.png");

> Want to bind the image using OpenGL? No problem!

        image->bind();
        
        /* Do OpenGL texcoord stuff here */

> Cool!
