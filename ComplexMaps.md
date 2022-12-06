# Everyone Wants to Be Fancy


## Multi-Portion Map Seeds

A single map is great, but complicated maps or scenes within scenes can be better. Midjourney can support this, but it requires some work and experimentation. Below is an example of how this method works for seeding creative prompts with enough help to get to stylistic results like the image below.

**Example Multi-Portion Map**

<img src="https://cdn.midjourney.com/e8ee7f26-b751-440a-b94a-69f18cd2c456/grid_0.png" width="50%">

### The Method for Seeding Multi-Portion Maps
 
1. Assist Midjourney with low complexity images to add shape references.
  * Midjourney won't innately react to prompts about things like _picture-in-picture_. Instead, you'll have to get lucky on a --chaos roll, or apply the following solution. 
   * Provide Midjourney with a flat Image, a series of shapes, outlines, or figure references with sharp color separation (such as a high contrast black and white or clear distinction between object and background).
   * Tie this reference image to a map or a style choice (such as a landscape painting, monster art, or other element you wish to use in combination with the split framing)

### Sample Prompt and Explanation
Below we run through a prompt example and the images that get us there.

**[ img1 ]** 

<img src="https://s.mj.run/ioTutgOIf04" width="25%">

Image one is an example of the shapes that the system uses to provide some shape or 'feature' guidance. This image is a simplistic image but has two major elements that midjourney reacts to: Sharp Borders (shapes themselves) and colors. In your experiementation you will be able to see that had we submitted to Midjourney a simpler one-color shape-driven image we would arrive at different results.

**[ img2 ]**

<img src="https://s.mj.run/ZfkhT5AVydM" width="25%">

Image two is our reference image (low quality) that does lead to some residual blurriness in our final output. But this is merely used for example style reference to help midjourney get to some map elements we may desire.

> imagine prompt: https://s.mj.run/ZfkhT5AVydM https://s.mj.run/ioTutgOIf04 overland map of provinces with bright edge borders, science fiction corporate lands, inked, --chaos 44 --v 4

**Prompt Output**

As seen, we get a pretty nice result where midjourney uses or consumes the _shape and color_ data from [ img1 ] to arrive at a style that is much more interesting, and potentially useful for our storytelling needs.

<img src="https://cdn.discordapp.com/attachments/1041576661029765180/1047552949531984014/TheDagNabit_overland_map_of_provinces_with_bright_edge_borders__e3fcc637-516c-4bcc-b4fd-88b1d68fa819.png" width="50%">


## Double Exposure

Similar to double exposure styles of film overlays, MJ can create maps which overlay two image concepts into a hybrid in unique ways. In this you are able to use the prompt of double exposure to connect two ideas in unique or inventive ways.

> imagine prompt: double exposure a geographic map of dark fantasy empire and armies with the demon queen in profile, 8k, intricate surface detail, artstation,

** Prompt Output**
In this example we chose to prioritize the "map of" in front of the demon queen. The text interpretor appears to select the first item near the double exposure in this example. Inverting the "map of" after the Demon Queen will change the style of the image based upon the linear nature, which will make the dominant trait the first interpreted item. Using the double exposure prompt after a "::" hard break does not appear to work well, until after a few generations after your first attempt.

<img src="https://cdn.midjourney.com/35712a4c-2a34-4216-9d7d-1c09d63f6031/grid_0.png", width="50%">

