# Album Management System

## Overview
The Album Management System is an intuitive platform that allows users to effortlessly manage their photo collections. With the ability to create, edit, and delete albums, the system offers a seamless user experience. Each album is uniquely identified by its name and can contain one or more pictures.

## Features
- **Create Albums**: Users can create albums to organize their photos.
- **Edit Albums**: Modify the details of existing albums as needed.
- **Delete Albums**: Remove albums that are no longer required.
- **Album Contents**: 
  - Each picture within an album has its own name for easy identification.
  - When attempting to delete a non-empty album, users are presented with two options:
    1. **Delete All Pictures**: Remove all pictures within the album.
    2. **Move Pictures**: Relocate the pictures to a different album.
- **User Experience**: Designed with simplicity in mind, ensuring that all interactions are straightforward and user-friendly.

## Technologies
This system leverages the following packages to provide a robust and flexible solution:
- `jQuery`: For dynamic content manipulation and AJAX requests.
- `Dropzone.js`: An easy-to-use library that provides drag-and-drop file uploads with image previews.
- `FilePond.js`: A versatile JavaScript library that can handle multiple file uploads with progress updates.
- `Laravel-Medialibrary`: A package for associating files with Eloquent models in a Laravel application.

## What We're Testing For
- **Clean Code**: Ensuring that the codebase is well-organized, readable, and maintainable.
- **Database Relationships**: Efficiently managing the relationships between different data entities.

Feel free to explore and contribute to the Album Management System!
