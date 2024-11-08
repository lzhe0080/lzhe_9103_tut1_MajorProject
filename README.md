# Major Project - Audio

## Iteration 1 

### Inspirations
In my sound design, I draw directly from **Max Neuhaus’s iconic *Times Square***, a sound installation that has long been an integral, yet subtle, part of the Times Square environment. Neuhaus’s piece, hidden beneath a pedestrian island grate, emits a low, resonant hum that blends with the city’s natural soundscape. Often mistaken for ambient subway noise, this sound is carefully crafted to evoke a “rich, harmonic sound texture resembling the after-ring of large bells,” creating an almost meditative auditory experience amid the bustling urban scene. Just as Mondrian’s composition reflects the grid-like energy and flow of Broadway, I try to bring the city’s pulse to life audibly, **merging visual and sonic interpretations of New York’s dynamic heartbeat**.

### Modifications
I added sound and used a button to control its playback. I also adjusted the **button’s style** to match the overall aesthetic of the scene. The **volume and panning** change with the movement of the **mouse**, and the **four buildings** in the scene move in sync with the panning as they shift left and right.

When you click play to start the music and slowly move the mouse to the left, the sound will gradually pan to the left, and you’ll see the image below.

![An image of Iteration 1](readmeImages/Iteration1.jpg)

***Note**: I used mouse interaction primarily to control sound variables, but it differs from the way other students interact with the blocks using user input by clicking.*

[Julian, S. (2016, April 29). *1590 Broadway, New York, NY 10036, USA - Max Neuhaus Times Square Sound Installation.* Radio Aporee.](https://archive.org/details/aporee_49142_55998)

[Performance Today. (February 12, 2020). *New York Out Loud: Max Neuhaus’ “Times Square”.* [Video]. YouTube.](https://www.youtube.com/watch?v=kA-fihBFWBI) 

## Iteration 2

### Modifications
I added an effect where the size of the building blocks changes with the **root mean square (RMS) level**. As the mouse moves upward, the volume increases, and the buildings gradually emerge. This abstract effect enhances the linear quality, just like in the original artwork, while the lack of specific building shapes adds a sense of unease for the viewer.

When you click play to start the music and slowly move the mouse to the right near the lower center of the canvas, you’ll see the image below.

![An image of Iteration 2](readmeImages/iteration2.2.jpg)

## Iteration 3

### Inspirations
In my work, I drew inspiration from **Paul Klee’s *Senecio***, a portrait of an elder that, much like Mondrian’s work, skillfully utilizes color blocks and lines. **The eyes** in Senecio are particularly striking, evoking a sense of innocence and curiosity, while also conveying a certain mystery and unease. Additionally, I was inspired by the documentary *Visages villages*, where the artists paste large portraits onto walls, giving ordinary people a sense of visibility and importance. Similarly, I have **added eyes** to the architecture in my project. This design aims to **break away from traditional representations of buildings, imbuing them with a sense of life, as if each structure is a larger entity within the city, symbolizing the mutual gaze between people and the urban landscape**. Klee explored complex human emotions through geometric shapes and colors, and I hope that this treatment allows viewers to feel the hidden stories and unique perspectives behind the architecture.

1. *Senecio*

![An image of Senecio](readmeImages/Senecio2.JPG)

[Klee, P. (1922). Senecio [Oil on canvas mounted on panel]. Kunstmuseum Basel, Basel.](https://en.wikipedia.org/wiki/Senecio_(Klee))

2. Screenshots of *Visages villages*

![An image of portraits on the architecture](readmeImages/Screenshot1.jfif)

![An image of eyes on the train](readmeImages/Screenshot2.jfif)

### Modifications
I first created an array based on the level to **draw curves** in the background that change according to the **ampArray**. These curves track the changes in audio levels **controlled by the mouse** and visually resemble an **electrocardiogram, simulating the heartbeat of a city**. Since both the background and the abstract buildings in iteration 2 were irregular, I adjusted the color block variations in iteration 2, making them **change only in the vertical direction with the RMS values**, while preserving the basic shape of the buildings. I also created an **“eye” class** to add an eye to each building. The eye **colors** match the color blocks of the buildings themselves, and the eyes vibrate vertically with the level and buildings, creating an uneasy effect. Additionally, the eyes can be **controlled by moving the mouse up and down to adjust the degree of openness**.

![An image of Iteration 3](readmeImages/iteration3.png)