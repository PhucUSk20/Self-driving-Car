# SMART ROBOT WAREHOUSE
An autonomous robot for warehouse automation, integrating deep learning, computer vision, and IoT. The system enables route setup through QR Code scanning and MQTT communication, followed by autonomous navigation and area recognition. For obstacle avoidance, the robot automatically stops when detecting obstacles and triggers FCM notifications, while also being trained to maneuver around them. Remote monitoring and control are facilitated via a Flask-based website and mobile app.
![](https://i.imgur.com/XOSQKXC.png)
1. Hardware
1.1 Autonomous Robot
 PCB
![](https://i.imgur.com/F6ePXdl.png)
 Schematic diagram
![](https://i.imgur.com/EGW568y.png)
 Robot hardware connection overview diagram
![](https://i.imgur.com/qbLLM4c.png)
 Complete Autonomous Robot Hardware
 ![](https://i.imgur.com/oHWf4ct.png)
 ![](https://i.imgur.com/QmeBiVl.png)
1.2 Dashboard
PCB
![](https://i.imgur.com/c9xbmz0.png)
Schematic diagram
![](https://i.imgur.com/GvETQBo.png)
Sơ đồ phần cứng bảng điều khiển
![](https://i.imgur.com/4PNGYPV.png)
Hoàn thiện phần cứng
![](https://i.imgur.com/Buthz7i.png)
2. Overview of Robot operation steps
![](https://i.imgur.com/Hf5HlNz.png)
2.1 Route setup subsystem via QR code
![](https://i.imgur.com/cyjy5Da.png)
2.2 Thiết lập tuyến đường thông qua bảng điều khiển nhờ vào giao thức MQTT
![](https://i.imgur.com/G4Yi2zf.png)
2.3 Thuật toán lái xe tự động - ResNet18
![](https://i.imgur.com/JwtFdge.png)
![](https://i.imgur.com/cGcUeYb.png)
![](https://i.imgur.com/slyKwQ8.png)
![](https://i.imgur.com/RQ3R6rP.png)
2.4 Thuật toán nhận diện khu vực - AlexNet
![](https://i.imgur.com/QjqvLu8.png)
![](https://i.imgur.com/ZYnyfF5.png)
![](https://i.imgur.com/AuU2cnA.png)
![](https://i.imgur.com/jpT07Ns.png)
2.5 Hệ thống cảm biến
![](https://i.imgur.com/tRw0C3v.png)
2.6 Thuật toán điều hướng
![](https://i.imgur.com/KmiK5Lu.png)
![](https://i.imgur.com/psggkWD.png)
2.7 Giao diện Mobile App
Socket Server
![](https://i.imgur.com/58Nn9hQ.png)
![](https://i.imgur.com/vPoqAms.png)
Flask Server
![](https://i.imgur.com/eEgaKoW.png)
![](https://i.imgur.com/dWUsoJd.png)
Firebase FCM
![](https://i.imgur.com/Aezp466.png)
UI Mobile App
![](https://i.imgur.com/8PXhBDl.png)

