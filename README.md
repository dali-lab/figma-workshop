# Figma Workshop
## For Aspiring Unicorns

Welcome! Today, we'll be learning about how to use Figma, a nice Google-Docs-esque interface design tool that lets you collaborate with others while doing mockup designs. It has a few other neat features, especially for your devs, and we'll explore some of them as we go through the workshop!

Today, we'll be building mockups for a basic landing page, and then we'll take those mockups and build it for real! So,

- 💻 Devs are going to learn how to build some mockups
- 🎨 Designers are going to explore some HTML and CSS

And everyone will be taking their first steps toward glorious unicorndom!

![Unicorn](https://media.giphy.com/media/l0HlMr2G3EKFgpUY0/giphy.gif)

Let's get started!

## Design: Mockups with Figma

Make your way over to [Figma](https://www.figma.com/). Create an account if you don't have one yet!

Hit up that + button in the upper left hand corner (to make a new file), or press the "+ New File" tile in the middle of the screen.

I know, you're probably thinking: Wow, what a horribly boring mockup--it looks all blank. Don't worry, soon it'll look industry-standard level baller, and it'll have been all thanks to you.

### Adding a Frame
To start, we'll need a frame. Click on the frame tool (or press the hotkey F) and then some options will appear on the right. Select "Desktop HD", and then a frame will appear in the view. You can drag it wherever you'd like.

⚠️ Note: for designers that know Sketch, these are the same as what Sketch calls "artboards".

### Working with Shapes
Click the shapes tool in the top right corner. In the dropdown menu, select the square. Make on in the frame!
We can:
- Resize: Just like you'd expect, drag the corner boxes
- Rotate: move mouse just off corners, and drag
- Fix aspect: Hold shift when resizing
- Resize from center: Hold alt/option while resizing
- Copy: Option-drag to copy
- Align: tools for this are in the top right
  - Soon we'll see alignment's analogue when we do flexbox in CSS! 🆒

[picture of align tools]

Remember that shapes stack, and you can control what shape appears in front by shifting them around in the lefthand sidebar. Things on top of the list appear in front. You can also group things so they all move together by dragging one of the items into another. It's best to limit complication, but stacking the layers may lead to some cool effects.

![Stack the Layers](https://media.giphy.com/media/qVSxiAKBf5sc/giphy.gif)

### Colors
Disclaimer: this site we're about to show you is super cool. Two of the authors just found out about it from the third author while writing this workshop.

Make your way over to [Coolors.com](https://coolors.co/). Click "start the generator". It's lit fam.

Mash the spacebar until you find a color you like. Then click the lock button and mash space more, and you'll get an amazing, custom-tailored color scheme for your landing page. When you're happy, copy and paste the hex codes into Figma.

### Gradients
Gradients made their way into web design with the birth of Web 2.0, near the dawn of this century. It is a close cousin of ombre, a fan favorite among young girls and pop punk enthusiasts experimenting with hair dyes. Gradients became grossly overused, and much like the pop punk scene, they dissipated into memory. They've since reached a renaissance in the form of color transitions, which relate two colors instead of a color and its lighter self. To use them correctly, there is a simple rule:

*Use A Little Slant*

Vertical, horizontal, and corner-to-corner gradients stir repressed memories of the early 2000s, a time when website design was in its adolescent stage, rife with acne and body odor. If you want your site to look refined, a nice slant just off the horizontal can have a nice effect.

To make one, select an element. Click the square of the fill, which will pop up a color selector. In the dropdown at the top, change "solid" to "linear". Then, try to pick two colors that work together (hint: use [coolors](https://coolors.co/)!). Drag the nodes around the shape to adjust the direction of the gradient.

### Image Manipulation
If you want an image in the background instead of colors, you can get some nice stock photos thanks to the generous open-source copyright policies of [Unsplash](https://unsplash.com/) and [Pexels](https://www.pexels.com/). Go ahead and grab an image from there.

If you're stumped for ideas, try "horizon", "skyline", or "delirious sausage". Insert it into the frame and play around! 

When you insert the image into Figma, you will see that the thumbnail of the image is shown in the "Fill" section in the inspector. You can click on this and options for manipulating images (like exposure, contrast etc.) will come up. 

You can do extra fancy stuff with the "LAYER" menu on the right hand side. For example, try getting another image, overlapping them and changing the layer blend mode on the top one... 👾

### Fonts
Figma comes preloaded with Google Fonts, an amazingly large fonts library that makes you look even worse for using Comic Sans, or even Helvetica. You can explore the [Google Fonts website](https://fonts.google.com/) to find one that you like.

When it comes to fonts, keep in mind:
- Emphasis comes font weight. **Boldness** is emphasizing, and **contrast** is even more dramatic.
- Connotation comes from the font-family. In general:
  - Serifs look official
  - Sans-serifs look inviting
  - Handwritten looks personalized
- You can combine multiple font-families to achieve mixes of these feelings.
- Use colors accordingly, but don't overuse.

### Logos
We can make a simple logo.
1. Create a circle
2. Add your initials as text to the circle
3. Change the font to something nice
4. Select both and go to to booleans selector up top. Try subtract.
5. Flatten the selection into one logo. (CMD+E)
6. Done!

### Navbar
Put the logo in the top left corner. Add some more text across the top. Maybe something like "Home", "About", and "Contact" would be good.

By the way, pressing 0 will resize the frame to actual size, so you can see how the sizing will look when you put it on a screen. 1 will zoom to fit all the frames, and if you select one frame, 2 will zoom to fit that selection.

### Impactful Quote
This is pretty much more text. Make it **big** and add some **umph** with some **boldness**, **size**, and **contrast**.

### Call To Action
Now we just need a button, and we're done! Use another rectangle. It would be nice to round the corners off to make it less Windows 10-y.

Then we can add some text to convince our site visitor to do something. This can be anything from signing up to buying black market angler fish.

### Hover Effects
In CSS, we'll be adding effects on button hovers. It's good practice for a designer to specify what this hover effect will look like. Since all our mockups are static, we do this by making a second mockup alongside the first, and then recoloring or adding things to make another static page at a different point in time. 

Figma has the ability to copy complete frames with their contents. Make two copies of the frame next to the one we just used. On the second one, make the background of the button slightly more opaque, which represents a button hover effect. On the third, add a line beneath the "Home" link in the navbar, which is what we want on a hover for the navbar buttons.

### BOOM
Congratulations, you just went from a blank screen to some gorgeous mockups. Now, we're going to use the mockups we've just made to build a site using HTML and CSS code!

## Development: HTML and CSS
