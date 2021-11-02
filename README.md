# How does it looks?
See it live here: [database.compliancepack.net](https://database.compliancepack.net)

# Installation
1. Go to `/var/www/html` and put everything inside the `html` dir of this repository
2. Restart Apache:
  ```sh
  $ /etc/init.d/apache2 restart
  ```

# Functionalities
- Use beautiful `.svg` files for files thumbnails  
- If the file is an image, it use the image as thumbnail (epic)  

# Bugs
- If you find any bugs, please use the GitHub bugs tracker of this repository
- If your image extension isn't supported, please add the extension to the Regular Expression in the `checkURL()` function in the `html/footer.html` file.