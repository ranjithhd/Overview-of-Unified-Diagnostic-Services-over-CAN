# Day-1 Activity-1

## Understand the diagram and identify the service ids which are default and non-default diagnostic session

![activity-1](https://user-images.githubusercontent.com/115522470/201644978-16ffe88d-fe20-46e4-a360-857d105a7bb7.png)


# Day-1 Activity-2

## Different Request message Definition and sub-function

#### Request message definition

Table defines the request message definition - sub-function = requestSeed. 

![Activity-2 a](https://user-images.githubusercontent.com/115522470/201646754-3280862e-b44c-4812-8292-61bdf332d00c.png)

Table defines the request message definition - sub-function = sendKey. 

![Activity-2 b](https://user-images.githubusercontent.com/115522470/201647315-436e4a77-9330-4cd8-beb5-7d95184f3bf9.png)

#### Request message sub-function parameter $Level (LEV_) definition

The sub-function parameter securityAccessType indicates to the server the step in progress for this service,
the level of security the client wants to access and the format of seed and key. If a server supports different
levels of security each level shall be identified by the requestSeed value, which has a fixed relationship to the
sendKey value:

⎯ “requestSeed = 0x01” identifies a fixed relationship between “requestSeed = 0x01” and “sendKey = 0x02”

⎯ “requestSeed = 0x03” identifies a fixed relationship between “requestSeed = 0x03” and “sendKey = 0x04”

Table shows a Request message sub-function parameter definition

![Activity-2 c](https://user-images.githubusercontent.com/115522470/201648308-8fd0cd68-a873-44c1-b5b8-1a646c4ee99a.png)
 

## Request message data-parameter definition

#### Table defines the data-parameters of the request message

![Activity-2 d](https://user-images.githubusercontent.com/115522470/201649261-7fc21ac9-8c24-4a36-86be-80cb83350822.png)

### Positive response message definition 

#### Table defines the positive response message. 

![Activity-2 e](https://user-images.githubusercontent.com/115522470/201651080-dd77cc92-159f-457d-8bde-88275d0ea83b.png)

### Positive response message data-parameter definition

#### Table defines the data-parameters of the response message. 

![Activity-2 f](https://user-images.githubusercontent.com/115522470/201651827-552d8a47-a209-4712-a876-27ba4a861557.png)
