***GPU-accelerated Game of Life screensaver***

Introducing the Game of Life screensaver with the highest system requirements in history!

But it may be one of the fastest....

This Life screensaver runs almost entirely on your graphics card. The logic is written as an OpenGL shader, with just a bit of extra
programming to glue it all together. This screensaver gets 22fps on my PowerBook G4 running at a 1x zoom fullscreen at 1280x854 while
using only 10% of the CPU.

Because it's a shader, and a rather complicated shader, it needs a hefty graphics card to work. Almost anything made since 2005 or so
should work fine. So far, it's been tested and known to work on these cards:

ATI Mobility Radeon 9700
ATI Mobility Radeon 9600
ATI Mobility Radeon 9200
ATI Radeon 9200
ATI Radeon 9600 Pro
ATI Radeon 9600 XT
ATI Radeon X800
NVIDIA GeForce FX Go5200
NVIDIA GeForce FX 5200
NVIDIA GeForce 6200A/NV44A
ATI x1600
MacBook integrated graphics (very slow)

If you have one of these cards, or something better, it will probably work fine. If you don't, it may not. However, the worst that can
happen is that it won't work. If your screen comes out pure black, or pure white, or never changes, it's probably because of the graphics
card.

GPULife runs on all Intel Macs, although the integrated graphics in the MacBook, Mini, and low-end iMac do not perform well. It runs with
great blazing speed on all of the others.

If it works on your older (PowerPC pre-G5) video card and your card is not on this list, please e-mail me so I can update the list.

**Open Source**

GPULife is open source and is released under the MIT License.

For questions, comments, support, etc., e-mail Michael Ash.

**Options**
 - Limit framerate: This option allows you to limit the rate at which the screensaver updates, to keep from using 100% of your graphics card's power. If unchecked, the screensaver will run as fast as your hardware will allow. If checked, you can set a maximum framerate using the slider and textbox to the right.
 - Show framerate: If checked, the current framerate will be displayed in the lower left corner of your screen.
 - Zoom: This allows you to control the zoom factor of the screensaver; at 1, one pixel is one Life cell.
 - Initial fill: When the screensaver starts, the field is filled with a random assortment of live and dead cells. This slider control the proportion of live cells. Both extremes are likely to rapidly result in a very dead space; best results are found in the middle.
 - Add random cells (per step): The screensaver will add the given number of live cells to the grid at every step. A small number of random cells can keep the grid from stagnating into still or repeating forms.
 - Corner colors: Liven up your screensaver by setting custom colors for the live cells. Dead cells are always black. Colors that are too close to black can confuse the engine, so dark are automatically brightened slightly.

**What is Life?**
More properly called Conway's Game of Life, Life is a cellular automaton. It's a computer simulation which takes place on a grid; each 
square in the grid is a cell which is either alive or dead. In Life, each cell counts its eight neighbors (four cardinal directions plus
diagonals). If a live cell has two or three neighbors, it stays alive, otherwise it dies. If a dead cell has three neighbors, it becomes
live, otherwise it stays dead. Through these simple rules, complex patterns evolve.

For more information, see Conway's Game of Life at the Wikipedia.
