
# Once connected to the instance

## 1. update the package

```bash
sudo apt-get update
```

## 2. Installing Nginx server


```bash
sudo apt install nginx
```

## 3. Start the Nginx service 

```bash
sudo systemctl start nginx
```

## 4. Check the status of Nginx service

```bash
sudo systemctl status nginx
```

## 5. Replace the default website by creating a new HTML file with a "Hello World" message. Run the following command to create a new HTML file: 

```bash
sudo nano /var/www/html/index.html 
```

## 6.	In the Nano text editor, enter the following HTML code:

```bash
<!DOCTYPE html>
<html>
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```

#### Save and exit the text editor by pressing "Ctrl + X", then "Y", and then "Enter".

## 7. Open a web browser and navigate to the public IP address of your instance. You should see the "Hello World" message displayed in the browser.

## 8. Congratulations, you have successfully created an EC2 instance with Ubuntu OS and installed Nginx for making it a web server, and changed the default website with a "Hello World" page.



