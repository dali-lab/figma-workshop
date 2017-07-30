# Figma Workshop
## For Aspiring Unicorns

Welcome! Today, we'll be learning about how to use Figma, a nice Google-Docs-esque interface design tool that lets you collaborate with others while doing mockup designs. It has a few other neat features, especially for your devs, and we'll explore some of them as we go through the workshop!

Today, we'll be building mockups for a basic landing page, and then we'll take those mockups and build it for real! So,

- 💻 Devs are going to learn how to build some mockups
- 🎨 Designers are going to explore some HTML and CSS
- 🦄 Everyone is going to learn Figma

And everyone will be taking their first steps toward glorious unicorndom!

![Unicorn](https://media.giphy.com/media/l0HlMr2G3EKFgpUY0/giphy.gif)

Let's get started!

## Design: Mockups with Figma

Make your way over to [Figma](https://www.figma.com/). Create an account if you don't have one yet!

Hit up that + button in the upper left hand corner (to make a new file), or press the "+ New File" tile in the middle of the screen.

I know, you're probably thinking: Wow, what a horribly boring mockup--it looks all blank. Don't worry, soon it'll look industry-standard level baller, and it'll have been all thanks to you.

As a bonus, we created a Figma board that has some inspiration, explanations, and an example of the completed part 1. You can find that [here](https://www.figma.com/file/dIrnDebo3o5QPquUwNs7KuUf/Landing-Page-Design)!

### Adding a Frame
To start, we'll need a frame. Click on the frame tool (or press the hotkey F) and then some options will appear on the right. Select "Desktop HD", and then a frame will appear in the view. You can drag it wherever you'd like.

⚠️ Note: for designers that know Sketch, these are the same as what Sketch calls "artboards".

### Working with Shapes
Click the shapes tool in the top left corner. In the dropdown menu, select the rectangle. Make one in the frame!
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

Make your way over to [Coolors.co](https://coolors.co/). Click "start the generator". It's lit fam.

Mash the spacebar until you find a color you like. Then click the lock button and mash space more, and you'll get an amazing, custom-tailored color scheme for your landing page. When you're happy, copy and paste the hex codes into Figma.

### Gradients
Gradients made their way into web design with the birth of Web 2.0, near the dawn of this century. It is a close cousin of ombre, a fan favorite among young girls and pop punk enthusiasts experimenting with hair dyes. Gradients became grossly overused, and much like the pop punk scene, they dissipated into memory. They've since reached a renaissance in the form of color transitions, which relate two colors instead of a color and its lighter self. To use them correctly, there is a simple rule:

*Use A Little Slant*

Vertical, horizontal, and corner-to-corner gradients stir repressed memories of the early 2000s, a time when website design was in its adolescent stage, rife with acne and body odor. If you want your site to look refined, a nice slant just off the horizontal can have a nice effect.

**Strategy 1:** To make one, select an element. Click the square of the fill, which will pop up a color selector. In the dropdown at the top, change "solid" to "linear". Then, try to pick two colors that work together (hint: use [coolors](https://coolors.co/)!). Drag the nodes around the shape to adjust the direction of the gradient.

**Strategy 2:** Instead of generating your own gradient, theres a website that's almost as dope af as coolors. It's called [Grabient](https://www.grabient.com/), and it has preset gradients that you can play around with that are super pretty. Go ahead and play around with the site a little until you find one you like.

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
Chances are, by this point, we've spent most of our time on Figma. But that's okay! This is a Figma workshop, after all. Nevertheless, we're still going to get a sneak peak into how we move the designs we just made onto a real website.

### Step 1: Clone This Repo
(If you know how to do this, you can skip to step 2).

You already see this README, so you're at our repo. If you haven't done so already, fork the repo by pressing the `fork` button in the upper right corner. Then, you'll be taken to your own account, with the project copied into it 🆒

In the upper right, you'll see a green button that says "clone or download". Then paste the following code into a terminal window:

`git clone <your repo here>`

^fill in that last tag with the code you copied from GitHub!

Then, `cd figma-workshop`. And finally, `atom .`.

Did that last command not work? Follow step 2!

### Step 2: Install Atom (if you haven't already)
If you already have atom installed, skip to step 3.

Install [Atom](https://atom.io/), a text editor with everything you'll ever need in life.

Once that's done, open it, and in the top left corner select Atom > Install Shell Commands.

There now we can run that last code bit. Back in terminal, run `atom .`

Hey, we're back in Atom again, and all my project files are available in the sidebar. Neato!

### Step 3: HTML
Alrighty, double click the file called `index.html`.

There's lots of stuff here that might look foreign if you haven't seen it before. Don't worry, soon it'll all make sense. Basically, what you should know at this point is that HTML uses things called tags (those are the things with the <x> formula that wraps a bunch of the other stuff on the page). Each tag does a specific thing, and the details aren't totally important at this point, but it's easy to pick up quickly.

HTML is really good for static, boring text. Luckily, we do have some of that. Specifically, we've got:
- Our page title
- Links in our navbar
- Our big quote
- Our "call-to-action" button

All of these things need to be added into the html, so let's go ahead and do that:
- The title goes in two places: one between the `<title>` tags, and again where you can replace the words "Page Title" (use command-f if you can't find it)
- The links each go in the div with the class `nav-links`. Replace "Link 1"/"Link 2"/etc with your text
- The big quote goes in the `<h1>` tag with the class `headline`
- The button text goes in the `<button>` tags

Alright, time for our big debut. Save the file, go back to your terminal, and run the following command:

`python -m SimpleHTTPServer 9000`

And go to [this link](http://localhost:9000) (if you're curious, the link is to IP address 127.0.0.1, port 9000. This is the loopback address, and it accesses network services that are running on your own computer. The python command you just ran launched an HTTP server on port 9000 of this address, and now we're accessing it).

"Yikes, it looks like a 90s website breeded with a dictionary." Yeah, yeah. Let's add styling!

### Step 4: CSS
What did we design those mockups for anyway? Let's dive into CSS, short for Cascading Style Sheets, long for CSS. This is where the mockups get super valuable, because we can use the values from our mockups to help us assign values for attributes. You'll see what that means in a minute. For now, we need to link our stylesheet to our html file. Paste this line under the html comment that says `<!-- your stylesheet here -->`:

`<link rel="stylesheet" href="style.css">`

Now head over to the `style.css` file by double clicking it in the sidebar. You'll notice that we've started you off with a lot of what you'll need. In fact, if you check out the browser again, and refresh the page, what we have certainly looks a lot better than it did. Before we can get started with making it your own, we'll first need to export some of our assets from Figma. Head back over to your project.

### Step 5: Exporting Assets
We've got a background and a logo. Exporting them is roughly the same process, but with some minor differences.
- For the former, select the background from your mockup (it doesn't matter which one), and go over to the right sidebar. At the bottom, where it says, "EXPORT", hit the + button. In the dropdowns, select "3x" and "JPG" (PNG works too, but it'll be really big and make your page load more slowly). Also, make sure "Contents Only" is checked, or else it'll export your background with all your text on top of it. When you're ready, click "Export".
- For the latter, select the logo that you've flattened into an object. Same idea for this, except select "1x" and "SVG" from the dropdowns. This will make our logo infinitely resizable! Again, "Contents Only" should be checked, and click "Export" when ready.

Now, the thingse need are in our `Downloads` folder. In terminal, use the following command twice:
`cp ~/Downloads/<filename> ./img`

The first time, replace `<filename>` with the name of your Background file (probably Background.jpg), and the second time with the logo (probably Logo.svg).

In Atom, you can verify that this worked by opening the img folder to see if they're there.

### Step 6: Adding your Styles
Alright, it's the moment we've all been waiting for. The first thing we can do is throw in the background. In `style.css`, find the section that starts with `.main {`. Inside those brackets, there's a property called `background-image`. Inside the double quotes in that url, paste in the path to your background image (probably something like `img/Background.jpg`).

The logo can actually go in the html itself. Find the `img` tag (should be like line 20ish), and after the `src` attribute, in the double quotes, put the path to your logo.

Alright, now go back to your browser and refresh. It should be almost exactly what we wanted from the mockups! If you need to, you can change the colors of the text to go better with your background. In the CSS, you'll probably see a bunch of `color` attributes distributed around the stylesheet. If you go back to Figma, you can get the hexcode for your text color and paste it into that attribute. It'll match magically.

The last thing we need to style is the button. Copy and paste the following code snippet at the bottom of your CSS file:

```css
button {
  border-radius: 5px;
  font-size: 18px;
  color: #000000;
  background-color: rgba(#FFFFFF,0);
  padding: 14px;
  border: 1px solid #000000;
}
```

You can add some changes to make it your own. For example, in Figma, the `border` properties are found in the "rectangle" part of your button. In the right sidebar, under the "stroke" field, there's information on the color and weight. In the CSS property, the first element is the weight, the second is the style (generally good if it's `solid`), and the third is the color. You can also change the `color` property (text color) and `border-radius` (curvature of the corners) if you want.

### Step 7: A Dynamic Button
Now, the thing that really differentiates this webpage from the mockups (aside from hypertext links, which is the thing that _actually_ differentiates the two) is that we can add dynamism, and we've already planned for this in our mockups. Let's add another snippet to the bottom of our CSS:

```css
button:hover {
  background-color: rgba(#FFFFFF,0.25);
}
```

The `:hover` means this is the styling that will be applied to all buttons when the mouse is hovering over them. In this case, we just want to add a little opacity to the button background.

Save, refresh your page again, and hover over the button. It changes instantly--that's cool, but not cool enough for our standards. There's an easy way to fix this: CSS transitions. It's a single line of code; paste it alongside the other properties of `button {`:

`transition: background-color 0.3s;`

Save and refresh, and now you've got a neat transition!

## That's All, Folks!
We're all done! Maybe you aren't quite happy with how the site looks yet, but the great news is you've got some starter code, and some really nice mockups! And more importantly, you know how to use Figma and a little bit of HTML and CSS, so you can explore some more until you've found something that you like!

Hopefully designers got a good view of Figma and now have some understanding of what the internals of a simple static webpage look like. And hopefully developers have learned a lot about mockups and why they're important in building sites. If you've got any more questions, feel free to reach out to any of the workshop authors, or come over to the Dali Lab during open hours for more help!

Thanks so much!

## Authors
- [Annie Ke '19](https://github.com/annieke): annie.ke@dali.dartmouth.edu
- [Adam Rinehouse '19](https://github.com/arinehouse): adam.rinehouse@dali.dartmouth.edu
- [Jenny Seong '16](https://github.com/jennyseong): jenny.seong@dali.dartmouth.edu
