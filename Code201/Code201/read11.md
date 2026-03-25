# Audio and Video in HTML; Domain Modeling Revisited

In the early 2000's In order to implement audio or video to your website you had to rely on *plug-in* tools like media players which you had to install on your device beforehand. As time passed and improvements were made, faster internet made streaming more practical. Even though you still had to use *plug-ins* in the mid and late 2000's, at least the quality of the media was better. Nowadays, with the introduction of new and imrpoved HTML elements, audio and video work directly in your browser without a *plug-in* being required. 

The `<src>` attribute contains a path to the video you want to incorporate. In order to control the video playback, you must use the `control` attribute to include the browser's own control interface or just build it using appropiate JS API. 

## Fallback Content 

The fallback content inside a `<video>` element is important because it ensures that out video is readable even if it cannot be played. 

I will make a funny comparison to better explain how **audio** and **video** relate to eachother. In this case, *Video* would be Hannah Montana, which is the celebrity that everyone has their eyes on. Visually she is a captivating star. Then for *Audio* we have Miley, who doesn't have the visual appeal but its the voice and true essence of Hannah. One without the other would not work. Together they really make up the pop star and as such, *audio* and *video* should always work together for the best experience. 

## A Guide to Grid

**CSS Grid Layout** is a 2-D grid based layout system that completely chanes the way we design user interfaces as developers. CSS Grid differs from CSS **Flexbox** because *flexbox* is one directional. You can use them together and they work very well. 

* **Grid Container** = The direct parent of all grid items. 
* **Grid Item** = The children or direct descendants of the grid container. 
* **Grid Line** = The dividing lines that make up the structure of the grid. 


# Responsive Images 

Making images responsive is important because it will affect performance and accesibility on your site. The responsiveness of the images will not only ensure your site is visually correct but also, it will make your site efficient and ussable accross multiple devices. 

`<srcset>`  Defines multiple image sources with different resolutions or sizes on the screen. This lest the browser choose the best image based on the size of the device or the pixel density. For example, you could use an image with different sizes and the browser will pick the best option that fits the user's screen. 
* `<srcset>` is more helpful for responsive images than CSS or JS because not only does it control how the image is displayed but also what image the browser will download. This provides an optimized image delivery. CSS or JS alone cannot prevent the browser from downloading the wrong image file. 

`<sizes>` Will tell the browser how wide the image will appear on different viewport widths. This works with the `<scrset>` attribute to choose the right image before downloading it and optimizing it's loading. For example, depending on the viewport's px is how the image will be displayed and how it will load on the browser. 