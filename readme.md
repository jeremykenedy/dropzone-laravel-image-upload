# Laravel 5.1 and Dropzone.js auto image uploads with removal links

This project is related to tutorial from [Codingo Tuts].

What is covered in this tutorial:

    - Auto image upload
    - Remove images directly from Dropzone preview with AJAX request
    - Image counter for uploaded images
    - Saving images as full size and icon size versions
    - Using Image Intervention package for resizing and image encoding
    - Saving image data to database
    - Unique file names for images on server side

### Quick Project Setup
1. Run `git clone https://github.com/codingo-me/dropzone-laravel-image-upload.git dropzone-laravel-image-upload`
2. Create a MySQL database for the project:
    * ```mysql -u root -p```, if using Vagrant: ```mysql -u homestead -psecret```
    * ```create database dropzone_laravel;```
    * ```\q```
3. From the projects root run `cp .env.example .env`
4. Run `composer install` from the projects root folder
5. From the projects root folder run `chmod -R 755 ../dropzone-laravel-image-upload`
6. From the projects root folder run `php artisan key:generate`
7. From the projects root folder run `php artisan migrate`
8. From the projects root folder run `composer dump-autoload`

[Codingo Tuts]:http://tuts.codingo.me/laravel-5-1-and-dropzone-js-auto-image-uploads-with-removal-links/