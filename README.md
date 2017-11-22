# Summary
Acapela is... a-cape-for-[Bela](http://bela.io/), and a box.  

![Acrylic](Images/Plexiglas.png)  
![Wood](Images/HDF.png)  

Acapela is composed of two things, a circuit board and a box (or enclosure). The circuit board has space for eight potentiometers and two 1/8" TRS (a.k.a. Jack) connectors for stereo audio input/output. It attaches directly on top of Bela. The box just keeps everything together and makes it easier to move around.  

# Files
This repository includes the next files:  

| File                         | Description                 |
|------------------------------|-----------------------------|
| Bela (rev. B1).fzpz          | Bela Fritzing part          |
| Template.fzz                 | Template for a new Acapela  |
| Acapela 1.0.0.fzz            | Circuit board               |
| Acapela 1.0.0.skp            | Box without dovetails       |
| Acapela 1.0.0 Dovetailed.skp | Box with dovetails          |
| Acapela 1.0.0.svg/.pdf       | Files for laser cutter      |

# Why?
I decided to build Acapela to be able to prototype and test my audio programs with Bela in a more portable way anywhere (e.g. on the tiny tables of my favourite coffee house, on the train going to work, etc.) and to avoid carrying hairy circuits made on a breadboard with jumper cables and noisy sensors that disconnect easily. The potentiometers in Acapela can simulate any sensor to be replaced later on a specific product, or they can just be the controls of the final product (e.g. a guitar pedal, a synth).  

# How?
The circuit board was designed using [Fritzing](http://fritzing.org/), and manufactured with [Aisler](https://aisler.net/).  

The box was designed with [SketchUp Make](https://www.sketchup.com/) assuming a material thickness of 3mm (0.118in).  

The dovetails were created using the [Auto Dovetails](http://seanregan.com/sketchup/dovetail/) plugin for SketchUp (this plugin does not take into account the laser beam width, which means that the joints are a bit loose, but in practice the box is very solid and stays together without the need of glue).  

The outer surfaces of the SketchUp model were exported to SVG format using the [Flights of Ideas](https://github.com/JoakimSoderberg/sketchup-svg-outline-plugin) plugin. The exported file was then edited using [Inkscape](https://inkscape.org/) to add some text and arrange the parts for the laser cutter.  

I soldered the circuit and laser-cut the box at the [Copenhagen Fablab](http://valby.copenhagenfablab.dk/), an open access tool workshop at the Valby Kulturhus. If you want to build your own version of Acapela, based on the files in this repository, please read the license note below.  

# License
Project by Juan Gil <http://juangil.com/>.  
Copyright &copy; 2017 Juan Gil.  

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
