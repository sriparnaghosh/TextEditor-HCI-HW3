# TextEditor-HCI-HW3

To run:
1. unzip the file.
2. open terminal, cd into the project folder.(Make sure the folder contains the .env file)
3. run the command:

          npm install 

4. run command:
          npm start
It will start running on https://localhost:3000 (you can check on the browser but the device motion will not work since there is no accelerometer on the laptop)
5. to run on phone:
   a. keep the project running on the laptop.
   b. find out the local ip from network preferences.
   c. open a browser from the phone and type the ipv4 address followed by colon and the port      number at which it is running on the laptop. eg: https://192.168.1.19:3000 (it is very important to run on https for the functionality to work)
   
   
   Citations:
   
https://sensor-js.xyz/demo.html
https://stackoverflow.com/questions/56514116/how-do-i-get-deviceorientationevent-and-devicemotionevent-to-work-on-safari
https://stackoverflow.com/questions/44574399/create-react-app-how-to-use-https-instead-of-http
