## Project demo and Explanation

_**Main file is ac_command.py**_

     Convert speech to text
     Detect the operations in the sentence
     Publish the operations as messages in the subscribed topic  
     Video Demo 👇
[![Project Demo](https://img.youtube.com/vi/0Dg65Skf-iE/0.jpg)](https://www.youtube.com/watch?v=0Dg65Skf-iE)
## Working Theory
Using AWS IOT core service to connect our Laptop(NODE) with all  IOT devices 
The IOT devices and the laptop will be subscribed to a specific topic in the aws iot core using mqtt protocol 
now the

 ### Laptop - >  AWS IOT Server < - all iot devices  (have a websocket connection) 
  
  _The laptop and iot devices  will publish and receive messages in the subscribed topic using MQTT Protocol (Machine to Machine Communication)_

  ## Versions

    -Version 1 : Single operation detection with preloaded data set 
    -Version 2 : Single operation detection with rephrased sentence 
    -Version 3 : Multiple command detection with automatic rephrasing the sentence 
    
  







