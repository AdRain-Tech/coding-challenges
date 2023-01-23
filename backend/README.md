# QR Code Generator

Create a QR code generator. After scanning a QR code there should be a link to the page with rendered 10 random movies (title + image).


## Requirements

1. Project must be done in Nest.js
2. You should use typescript.
3. Project should be on some free platform (Heroku, etc.) and must be available to test online. We want to make sure you are aware of how to deploy apps.
4. Place your code on github (or any other platform you prefer to store your code). Send us back a link to it. Make sure it is public.

## Your task
Your task is to generate a QR code that will give a user link to the page with a list of 10 movies.

For this you will need two pages:
1. Page with a QR code to scan
2. Page with a list of movies received from the scanning of QR code.

How you will display it on the front-end is totally up to you. It might react, jquery, pure js, or build-in templates - it doesn't matter to us. We will look only backend logic.

QR code must be regenerated every 10 seconds and return a new link to another 10 random movies.




## Demo movies JSON
 https://gist.github.com/saniyusuf/406b843afdfb9c6a86e25753fe2761f4




## Important hints
1. It is not required to integrate a database in this task, but if you will do it, it will be a plus for you (especially postgres + prisma).
2. Do not focus on the "nice look and feel" of the UI part. Just make sure it renders a list of movies (title + image, nothing more).