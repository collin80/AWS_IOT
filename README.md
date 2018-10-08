# Arduino-esp32-aws-iot
Arduini ESP32 library for AWS IoT

Please make sure you have read the [getting started guide](https://aws.amazon.com/iot/getting-started/) before trying to do anyting with this template.

This template is based on and contains the code from the [aws-iot-device-sdk-embedded-C](https://github.com/aws/aws-iot-device-sdk-embedded-C) project with an ESP32 port. It may help to review that project before attempting to use this template.

Define the below parameters in the sketch:
```
WIFI_SSID
WIFI_PASSWORD
HOST_ADDRESS
CLIENT_ID
TOPIC_NAME
```
Also, find the file sample_aws_iot_certificates.c in the src folder of this library, 
remove the sample_ from the filename and put the file in your sketch folder. Then, fill 
it out with your keys you got when you set up Amazon IOT. Keep that file safe
and don't check it into GIT or share it.


*Certificates*
```
  root-CA.crt
  certificate.pem.crt
  private.pem.key
```
Above certificates needs to be stored in the file aws_iot_certificates.c as arrays. Check the file for more information.
 
![](https://exploreembedded.com/wiki/images/b/b9/ESP32_AWS_IOT_Certificates.png)


Please check this tutorial for setting up [AWS IOT on Amazon] (https://www.exploreembedded.com/wiki/Secure_IOT_with_AWS_and_Hornbill_ESP32)

Follow this tutorial for using the [Arduio Esp32 AWS libaray] (https://exploreembedded.com/wiki/AWS_IOT_with_Arduino_ESP32)


