# Paragraph Segmentation Using Semi-Supervised Deep Clustering Network

---
#### Paragraph segmentation is a research work modeled and developed by a group of six people. This work is a part of academics for the Masters' degree in Web and Data-science. To get a gist of our work and application begin with the research paper.The main aim of our application is to extract the paragraphs in an ordered manner from a PDF document using Deep clustering network.

### Docker instance creation and steps involved to run the application in the docker container
* Download and unzip the repository (cloning is also possible)
* Change current working directory to Web_application using **cd** command
* Build the docker image using command ```docker build -t the_meanSquared_app .```
* Run the docker image using command ```docker run -it -p 5000:5000 the_meanSquare_app```

   Now, on your screen you should be able to see the below line
   > Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
   
   later you will be provided with a localhost link as below, which can be used to run the web application
   >  http://localhost:5000
 * If the above lines executed successfully in your system and got the link. You have the access now!
