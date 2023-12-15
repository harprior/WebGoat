## Steps I followed to run the application

1. Clone WebGoat repository to my local machine with git clone git@github.com:harprior/WebGoat.git command

2. Install Docker

3. Pull WebGoat docker image with docker pull webgoat/webgoat

3. Run docker with run -p 127.0.0.1:8080:8080 -p 127.0.0.1:9090:9090 -e TZ=Europe/Amsterdam webgoat/webgoat to install it

4. Realize that my time zone is not TZ=Europe/Amsterdam and re-start container with correct TZ=Asia/Jerusalem timezone ... 

5. Check that application is running with ~ docker ps

6. Follow to http://8080/WebGoat

7. Success! Attach screenshot: ![Homepage screenshot](webgoat.JPG)

8. To change repository settings before committing changes - Go to Settings on Github - Branches - Toggle 'Require a pull request before merging" - - Name Branch name pattern as 'main' - Create rule

## To change Webgoat image to the image of my choosing

1. Locate README.md file inside WebGoat application

2. Locate WebGoat image file.

3. Replace file with the image of my choosing.

4. Commit changes.

5. Realize that my path to image was invalid.

6. Fix image path.

7. Commit changes.

8. Add screenshot:![Mainpage](Main page.JPG)
