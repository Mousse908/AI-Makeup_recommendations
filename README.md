<a id="readme-top"></a>
# AI-Makeup

<ol>
  <li><a href="#about-the-project">About The Project</a></li>
  <li><a href="#built-with">Built With</a></li>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#Simple-Workflow-Description">Simple Workflow Description</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#references">References</a></li>
</ol>

## About The Project
This project enables users to receive makeup suggestions through an AI makeup model by taking real-time photos. The project showcases a makeup model system using DenseNet technology. Users can take photos in real-time, and the model predicts makeup areas on a web page. After selecting a color, the makeup result is displayed immediately on the web page. The database returns corresponding products based on the selected color's RGB values. The neural network model, an Autoencoder, is deployed using Tensorflow.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

### Languages

* HTML, CSS, JavaScript
* JAVA EE (Servlet+JSP)
* MySQL
* Python
* Tensorflow

### Tools
* Eclipse
* VSCode
* Git
* MySQL Workbench

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, follow these simple steps.

1. Create a new conda environment
   ```sh
   conda create --name AI-Makeup python=3.9
   ```
2. Activate environment
   ```sh
   conda activate AI-Makeup
   ```
   
3. Clone the repo
   ```sh
   git clone https://github.com/Mousse908/AI-Makeup_recommendations.git
   
4. Change directory
   ```sh
   cd AI-Makeup
   ```
   
5. Install the required Python packages
   ```sh
   pip install -r requirements.txt
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Simple Workflow Description
1. Establish the front-end and back-end using JAVA and connect to the database using the MVC architecture. Implement features like member login/logout, create members, and display member information.
2. Integrate the front-end JSP pages with the back-end Flask to enable real-time photo capturing.
3. After taking a photo, send it to the back-end Python code for makeup application via HTTP request protocol and return the result.
   
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage
1. Import the AI-Makeup.war project into Eclipse and run it using the Tomcat 9.0 server.
2. Open photo.py in VSCode and execute it. photo.py will sequentially import from Ori_cutface.py to putcolor_onface.py.
3. In photo.py, create socket.io to complete real-time camera and photo capture functions. Connect using fetch in photo.jsp to establish HTTP requests (app.route in photo.py), enabling dynamic data loading and responsive web functionality.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact
KUAN YU, CHEN – jason356a@gmail.com

Project Link - https://github.com/Mousse908/AI-Makeup_recommendations

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## References

[Pymatting](https://pymatting.github.io/)
[DenseNet](https://medium.com/image-processing-and-ml-note/densenet-dense-convolutional-network-image-classification-5de397286c05)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
