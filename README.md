> commit: `1310a038f703cc5c30c96b67853026669bd7ab01` and `e4093b8b3b50cc54c61c887feb40e6aca5d4e0b4`
- Use case of this commit is to 1) add a header component and link the header component html to the app component html. 2)add an image to the header component html.
- Steps:
  - ng g c header
  - download and add the css files for header component css and app style css.
  - add the image .png file into the public folder and img src the image in the header component html and do the necessary changes.
  - copy the selector name from header component ts (typescript) file and place it into the app component html.
  - ng serve
  - http://localhost:4200/
> commit: `b8e2d56018ce5e44fbc5d03bac77045b9567d7dd`
  - Use case of this commit is to 1) add a user component and link the user component html to the app component html. 2)create dummy users class which other component can import and use. 3)add image for the each user 4)randomly select an user and display it's name and image in the menu bar section.
  - Steps:
    - ng g c header
    - download and add the css files for user component css and app component css.
    - add the user image .png files into the public users folder and img src the image in the user component html and do the necessary changes.
    - copy the selector name from user component ts file and place it into the app component html and do the necessary changes.
    - ng serve
    - http://localhost:4200/
