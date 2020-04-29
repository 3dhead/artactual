# Art Actual 

### A webapp version of Nvidia GauGAN using the COCO dataset using RunwayML and P5JS

This implementation of Nvidia GauGAN provides an easy to use interface for drawing in a tablet like the iPad using the Apple Pencil or other stylus.
This project was made as part of the larger AI-brushes project. Read more about it at: www.nurecas.com/ai-brushes

Examples:
![alt text](https://scontent.fblr15-1.fna.fbcdn.net/v/t1.0-9/79084476_458254921544537_2385974338609217536_o.jpg?_nc_cat=110&_nc_oc=AQmn3SNztp0srsPEzOU-vx4kuEMcxnhE-k6V1Eyeq44IxZZqQtA7c0hbSOSiUpL5Ps0&_nc_ht=scontent.fblr15-1.fna&oh=cd07745a254f88e2fe1ba07f6fd40183&oe=5EAB23CE "Art Actual Example")

### How to use
1. Download the repository.
2. Open RealDraw.js and change the IP address in the line :
`var url = 'http://192.168.1.41:8000/query';`
to http://<the IP address of your computer>/query (assuming it is connected to the Internet).
3. Open RunwayML and create a new workspace with the Spade-COCO model. Run the model remotely or locally.
4. [Run a local server](http://osxdaily.com/2018/07/30/start-web-server-python-3/) in your machine from the folder of the downloaded repository.
5. Open http://{YOUR IP ADDRESS}:{YOUR PORT} in a browser and enjoy.

If you are using a hosted model, change the link in index.html from RealDraw.js to RealDraw_Hosted.js, and edit the url in RealDraw_Hosted.js to that of your hosted model.
##### References:
Nvidia Semantic Image Synthesis with Spade : https://github.com/NVlabs/SPADE
RunwayML : https://runwayml.com/
P5JS : https://p5js.org/

###### Thanks to Nvidia, RunwayML and P5JS
