# Designing for Augmented Attention

[Article](https://www.sciencedirect.com/science/article/abs/pii/S0747563205001160)

## The Problem
In today's world, users are surrounded by numerous active computing devices that are constantly vying for their attention. The manner in which devices notify a user of new information can often be extremely disruptive to the user's current work, such as a pop up window containing a button that must be clicked to dismiss the window before the user is allowed to continue what they were doing. Each device or application is claiming to be high priority, while in reality the user considers some notifications much more important than others. The paper seeks to solve this problem by designing user interfaces based on humon group communication. Eye contact in particular is a strong indicator of who is speaking or listening. Accordingly, the paper focuses on developing [[Attentive User Intefaces|attentive user interfaces]].

## Prototypes
The remainder of the paper describes numerous prototypes of AUIs. A subset of the described prototypes are summarized below.

### eyePLIANCES
eyePLIANCES are smart ubiquitous appliances with embedded attention sensors, designed to extend the existing concept of gradual turn taking. Users can interact with such devices through speech, keyboard, radio tags, or manual interaction. Eye contact sensors are then used to determine the target of the users attention. The attached picture shows a simple example of a light that is turned on or off by verbally saying "On" or "Off" while looking at the eye contact sensor.

| ![](Images/lava_lamp.png) |
|:--:|
|Figure 1: AuraLamp eyePLIANCE|

Figure 2 shows a less trivial eyePLIANCE that keeps track of the devices users are paying attention to, the preferred notification channels, and the prioritization of notifications. A central server called eyeREASON handles all of the users remote interactions with devices.

| ![](Images/eyereason_arch.png) |
|:--:|
|Figure 2: eyeREASON architecture|

eyeWINDOWS takes this technology and applies it to a traditional GUI, replacing typical windows and icons with zooming windows with a dynamic resolution. The amount of screen real estate a particular window recieves is based on the amount of visual attention the user is giving that particular window. This zoom only occurs once the user presses an activiation key. Figure 3 shows an example of this zoom, with the user's focus changing from the window in the center of the screen to the window in the bottom right corner.

|![](Images/eyewindows.png)|
|:--:|
|Figure 3: eyeWINDOWS with zooming focus window|

### Attentive Cubicles
Managing attention between co-workers who are all work with close proximity with one another can be a difficult task. Two co-workers might be discussing a problem with each other, while another co-worker sitting nearby is dilligently working away at their computer and does not want to be distracted by the ongoing conversation. Utilizing eyeREASON with tools such as Attentive Headphones (a pair of noise cancelling headphones with an eye contact sensor attached) and privacy glass (glass that appears opaque when powered off and translucent when powered on thanks to the layer of liquid crystals inside) can allow distractions to be flitered out, only letting conversations take place when users are making eye contact. See Figure 4 for an example of this type of system.

|![](Images/attentive_cubicle.png)|
|:--:|
|Figure 4: Attentive office cubicle prototype|