Hello Live Card
=======

This sample provides a minimal implementation of a GDK Live Card for
Google Glass. It displays the current system time at about 30 fps :)

This is just something that I hacked up as an experiment. Consider it
a snapshot sample. In other words, it's not actively maintained. It
last worked as of XE12.

## Learn More

Check out the
[official documentation](https://developers.google.com/glass/develop/index)
to learn how to develop for Glass.  There you'll find awesome docs,
better samples, and pictures of puppies. C'mon, what do you have to lose?

##ADT-Eclipse instructions
1. [Follow the official instructions](https://developers.google.com/glass/develop/gdk/quick-start) and update everything
2. `clone` this repository
3. **File** > **New Project from Existing Sources**
4. Select the cloned directory
	- optional: copy into existing workspace
5. Right-click on the project
6. Go to **Properties**
7. Under Android, select **Glass Development Kit**

###To run on your device
1. Right-click on the project
2. Select **Run As** > **Configuration**
3. Click the first icon with the tooltip: **New launch configuration**
4. You will be on the first tab called "Android"
5. Browse to select project
6. Select Launch Action > **Do nothing**
7. Navigate to the next tab called "Target"
8. Select Depoyment Target Selection Mode > **Always Prompt to Pick Device**