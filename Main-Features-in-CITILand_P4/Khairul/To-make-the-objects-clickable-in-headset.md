# **To make your game object or asset clickable in Oculus Headset**
- Click on your game object to open the Inspector tab
- Add component called "XR Simple Interactable"
- Expand the tab
- Expand "Interactable Events"

![image.png](/.attachments/image-fe120623-d161-43c5-b782-fa9cb8ce52be.png)

- Scroll down to "Select"
- Select your script that makes the object clickable using XR, and also **select Right Controller (Xr Ray Interactor)** if you want to make the object clickable using the right controller 

![image.png](/.attachments/image-6e5fcc94-20ff-4f1b-8954-dcfa3059ec84.png)


- ****Most Important is to have "public void" in your function, if not you wont see your script's function there**
- for e.g.

![image.png](/.attachments/image-0460f5bf-073d-49dc-a147-612ef332985a.png)

