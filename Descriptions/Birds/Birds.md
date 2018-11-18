# Birds - An interactive, chirping media installation
## Summary
The goal of this project was to create an artistic and engaging media installation. We built a wooden frame for the installation and added a screen to it.
This screen offers a view into a computer graphic world: It displays a bright and colorful polygon landscape with mountains, trees, a river and a rope in front of the scenery. <br/>
Usually, polygon birds fly in a flocking behavior in the background, implemented with rules as described by <a href="http://www.red3d.com/cwr/index.html" target="_blank">Craig Reynolds</a>.
However, the birds are attracted by the rope placed in front of the scenery. Therefore, they like to land on it and enjoy the view into our real world. As the birds are programmed as
autonomous agents, nobody does exactly know what they will do next. Occasionally, they even wave to the users or scratch their heads. For the interaction between the users and the birds,
we added a camera with a microphone and a crank to our installation. The wide-angle camera captures the user's movements and the microphone the current noise level so that the birds are scared if the users are too loud or move too fast. This way, the users have to be careful when approaching the adorable birds. Furthermore, users can spin the crank to stretch or release the rope the birds are sitting on.


## Achievements
* We presented the project at an open day at our university.
* The project was hung up in the university building as an example for future generations of students.

## My responsibilities
* Creating interactions with the user (audio and crank). I implemented the reaction to the audio in PureData, where the volume of the sounds was mapped to a fear level for the birds. The result was then sent to
a Unity application, collecting the possible fear from multiple input sources (Camera image, Microphone audio, Rotation of the crank). For the crank interaction to work, we mounted a long schraube on the crank and hided
a mounted mouse on the side of our installation, positioned just right after the schraube. This way, when rotating the crank (and the assigned schraube), the sensor of the mouse recognized this movement as though a 
user would move the mouse over a table. I then used this difference to let it contribute to the fear level of the birds. 
* Coding the interface to fear the birds
* Working on the concept (like description sign on the side) and parts of the hardware
* Implementing small scripts for the scene and agents. This included things like clouds moving through the picture or helping my mates out with the agent implementation based on Nature of x.

## Media
**[Video: Birds Media Installation](https://www.youtube.com/embed/Tuy0Cl3ZDKM)**

[![Video: Birds Media Installation](http://img.youtube.com/vi/Tuy0Cl3ZDKM/0.jpg)](https://www.youtube.com/embed/Tuy0Cl3ZDKM)

**Installation with sign on the side explaining it**

![Installation with sign on the side explaining it](Images/openday1.jpg)

**Showing our installation at an open day**

![Showing our installation at an open day](Images/openday2.jpg)

**Using the crank to move the cord**

![Using the crank to move the cord](Images/openday3.jpg)

**Joyfull visual and auditive interaction with the adorable birds**

![Joyfull visual and auditive interaction with the adorable birds](Images/openday4.jpg)

**User happily teasing the poor birds by clapping**

![User happily teasing the poor birds by clapping](Images/openday5.jpg)

**Poor bird on the right trying to hide**

![Poor bird on the right trying to hide](Images/hiding.jpg)

**Brave bird waving to the user**

![Brave bird waving to the user](Images/waving.jpg)

**User carefully approaching a lonely bird**

![User carefully approaching a lonely bird](Images/openday6.jpg)

**Teammates working on the frame in the wood workshop**

![Teammates working on the frame in the wood workshop](Images/woodworkshop.jpg)

**Adding hardware to the frame**

![Adding hardware to the frame](Images/addinghardware.jpg)
