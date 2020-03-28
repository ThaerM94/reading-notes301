# Read-01
## SMACSS and Responsive Web Design

#### What Is Responsive Web Design?

Responsive Web design is the approach that suggests that design and development should respond to the user’s behavior and environment based on screen size, platform and orientation.

#### How do responsive and adaptive design compare?
For people without web design experience, the difference between responsive and adaptive design is so subtle, it’s not likely noticeable. 

To make our comparisons easier to digest, let’s look at their major components. 

##### Layout 
With responsive design, the layout is decided by the site visitor’s browser window.

In comparison, an adaptive layout is determined on the back-end, not by the client or browser. The design produces templates unique to every device class. The server detects factors like device type and operating system to send the correct layout. 

##### Load time
No one likes a slow website. People get impatient and bounce if a site doesn’t load in 2 seconds or less. Adaptive designs generally load faster than responsive ones. This is because adaptive design only transfers necessary assets specific to each device. For example, if you view an adaptive website on a high quality display, the images will adjust to load faster based on the display the end user is using.

But this isn’t always the case — Webflow developed a feature for responsive images that pushes all inline images (both static and dynamic) to automatically scale to fit every device size and resolution. 

##### Difficulty
This can be a touchy topic for some. People argue that adaptive designs are more difficult to build because you’ll need different layouts for different devices. Whereas responsive designs only require a single layout that some argue is easier to implement.

But, while responsive designs only have one layout across all devices, they require more effort and time up front. Responsive design involves extra attention to your site’s CSS and organization to ensure it’s fully functional on all screen sizes.  

##### Flexibility
Adaptive design is considered less flexible because a new device with a screen size you didn’t plan for could break your layout. Which means you’ll need to edit an old layout or add a new one. Screen sizes are constantly changing and highly variable.

In the long run, a responsive layout will require less maintenance. Responsive sites are flexible enough to work well on their own by default, even if there’s a new device or screen size in the market. But adaptive websites will need occasional maintenance.

#### Float :
In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called "text wrap". Here is an example of that.

To better visually connect the similar blocks, we want to start a new row as we please, in this case when the color changes. We could use either the overflow or easy clearing method if each of the color groups had a parent element. Or, we use the empty div method in between each group. Three wrapping divs that didn't previously exist or three after divs that didn't previously exist. I'll let you decide which is better.


[Main Page](https://thaerm94.github.io/reading-notes301) 