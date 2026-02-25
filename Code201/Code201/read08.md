# Layout with CSS 

## Flexbox 

The *Flexible Box Layout Model* or better known as *Flexbox* is a model designed for one-dimensional content. This means that the content lays out in one direction at a time, either in a row going from left to right or in a column going from top to bottom. 

The key to understanding **Flexbox** is understanding the concept of the *main* and *cross* axis. The main axis is the one set by your `flex-direction`. When the flex-direction is a <u>row</u>, the main axis is <u>horizontal</u>, if it's a <u>column</u>, the main axis is <u>vertical</u>. The cross axis runs in the other direction to the main axis, so if the main axis is horizontal the cross axis is vertical. If the main axis is vertical the cross axis is horizontal.

Flex-direction | Main axis | Cross axis 
---------------|-----------|-----------|
row            | left -> right | top ⇅ bottom |
column         | top ⇅ bottom | left -> right 


Although **Flexbox** itself isn't bad for accesibility, how you use it is how issues may arise. You should be catious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as this can negatively affect accesibility. The best practice is to keep your HTML in a logical reading order. The logical order is what the screen reader will use along with anyone else visiting the website. An example of a property that might affect accesibility are the **row-reverse** and **column-reverse** values, these reverse the visual order of items. 

## CSS Layout with Flexbox 

`Float` is often used to create layouts although they were not meant for it really, they are better for wrapping text around images. Because you cant build full layouts with `float`, it is better to use the flexbox method with which you can make full layouts more conveniently. **Flexbox** allows easier aligment, better control over soacing and flexible sizing. In order to do these with *floats* you would have to continously do a **clearfix** t

### How does this topic connect with your long term goals?

Understanding flexbox is just another step into improving my software developing skills. Learning different thecniques will allow me the confidence to build professional and dynamic websites. I think that the more I learn and the more I problem solve the more opportunities I have to explore my creativity when developing. 