# Pi Weather Shield / Sensor to Cloud thanks to IBM Watson 

Python example for the TE Connectivity Raspberry Pi Weather Shield connected to IBM Watson
![piweathershield](https://cloud.githubusercontent.com/assets/20226823/18872739/44122f9c-84bc-11e6-81ef-238a6903c73e.jpg)

### Setup your Pi

    sudo apt-get install python-pip
    sudo pip install ibmiotf
    sudo pip install pi-weather-shield
    
### Checkout the sample code

    git clone https://github.com/TEConnectivity/piweathershield-ibm-watson-iot-python.git
    cd piweathershield-ibm-watson-iot-python
    
### Configure your device 
    
    cp sample-device.cfg mydevice.cfg
    nano mydevice.cfg
    
Enter the credentials from Bluemix Internet of Things and save the file

### Run the software
    
    python ibm-watson-iot-demo.py -c mydevice.cfg 
