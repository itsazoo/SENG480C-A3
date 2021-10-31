Directing Visual Attention with AR

[[Attention affected by Environment - All]]
[[Attention & Interfacing with Devices - All]]
[[Attention - All]]


Main approach:

Assumptions they use to achieve cognitive augmentation: Extended wireless network topology

Diagrams

[Article](https://www.tandfonline.com/doi/abs/10.2753/MIS0742-1222230408?casa_token=PXHug6pj6U4AAAAA:miysc_ERphWaHMeO3wXmedYLuyELmEp1n_5HQNStOEt9Llvr7qERegqfEELMebTWXefhY2bWFymP)


# INTRO + MAIN APPROACH

WITH THE EVOLUTION OF MOBILE COMPUTER SYSTEMS, there is a tighter and more ubiquitous integration of the virtual information space with physical space. For example, the use of databases marked by geospatial data or radio frequency identification (RFID) tagging and mobile displays enable potential integration of virtual information and physical assets—the two are dynamically linked.

Of current interfaces, the most suited to mobile geospatial information display is augmented reality (AR). AR systems allow users to be aware of perfectly spatial registered information from simple two-dimensional (2D) labels to three-dimensional (3D) labels or virtual markers

AR techniques allow users to see buildings, objects, and tools superimposed with computer-generated virtual annotations. Unlike its cousin virtual reality (VR), AR enhances the real environment rather than replacing it with computer-generated imagery. Graphics are superimposed on the user’s view of the real environment.

One of the most promising applications of AR is the display of computer-generated information to guide the work of a user to specific spatial locations such as buildings, tools, packages, and other assets tracked by database systems. The ability to overlay and register any type of information on the working environment in a spatially meaningful way allows AR to be a more effective medium for information display.

Studies of user performance in AR-based information systems indicate that they can provide unique human factors benefits—as compared to approaches using traditional printed manuals or other computer-based approaches—such as improved task performance, decreased error rates, and decreased mental workload [34, 35, 36].

Information objects such as labels, overlays, 3D objects, and other information are integrated into the physical environment. Objects, tasks, and locations can be cued when appropriate to support navigation and mobile active user tasks.

Increased network access via heterogeneous wireless network topologies enables mobile users to have “anytime, anywhere” access of information for work and personal communication [6].

## The Attention Funnel

The attention funnel uses various overlapping visual cues that guide body rotation, head rotation, and gaze direction of the user. Building on an attention sink pattern introduced by Hochberg [11], the attention funnel uses strong perspective cues

Attention Funnel ![Image of Attention Funnel](Images/Attention_Funnel.png)[Image Source](https://www-tandfonline-com.ezproxy.library.uvic.ca/doi/pdf/10.2753/MIS0742-1222230408?needAccess=true)

Attention Funnel Real World View ![Image of Attention Funnel Drawing User Attention](Images/Attention_Funnel_Drawing_Attention.png)[Image Source](https://www-tandfonline-com.ezproxy.library.uvic.ca/doi/pdf/10.2753/MIS0742-1222230408?needAccess=true)

Does the attention funnel truly direct user attention more efficiently than the most common techniques used in current AR interfaces? We conducted a study to evaluate the effectiveness of the attention funnel in guiding attention around the immediate space of the user.

A common task for an AR cursor system in a mobile setting is to guide a (user to an object that the user needs to retrieve in the immediate environment. The attention funnel paradigm was tested against two alternative techniques: (1) a commonly used AR highlighting technique, where the target object is cued by a surrounding green bounding box, and (2) a control condition mimicking interpersonal interaction, where the object to be found is indicated only by its name (e.g., "pick up the screwdriver"). A 360-degree omnidirectional workspace was created using four tables as shown in Figure 5. Forty-eight objects were distributed over the four tables (12 objects each). Half of these objects were primitive geometric objects of different colors and the other half recognizable tools (e.g., screwdriver, stapler, and no.


![Attention Funnel Test](Images/Attention_Funnel_Test.png)[Image Source](https://www-jstor-org.ezproxy.library.uvic.ca/stable/pdf/40398875.pdf?refreqid=excelsior%3A39eeca0be3de5dc22d7559a292394e82)

# ASSUMPTIONS

Attention funnels are applicable to any augmented vision display technology capable of presenting 3D graphics including HMDs and video see-through devices such as tablet PCs or handheld computers. 

The location of target objects or locations in the environment may be known to the system because they are (1) virtual objects in tracked 3D space, (2) tagged with sensors such as visible markers or RFID tags, or (3) predefined spatial locations as in GPS coord

Objects tagged with RFID tags are not necessarily detectable at a distance, but local sensing in a facility may be sufficient to indicate a position that can be utilized for attention direction. 

In some cases, the location of the object is detected by sensors and is not known ahead of time. An implementation we are currently exploring involves the detection of visible markers with omnidirectional cameras, which can be implemented in a video see-through or optical see-through system.

ser.) The head-mounted omnidirectional camera detects markers in a 360-degree environment around the user. The relation of the camera to the user's viewpoint is known. Detected objects can be cued for the user based on task needs or search requests by the user.

