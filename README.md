# Abaqus Material Colour Changer

The scripts change the colours of either materials or sections based on the material name, useful for anyone with more than a few different materials, especially if they’re CT intensity based material properties as you can get an idea of the material property distribution similarly to how you can in Simpleware ScanIP.

Currently gives materials with names containing high numbers the colour red and low numbers the colour blue. It’s a handy coincidence that in HSV colour space, a hue value of 0 is red and a hue value of 255 is blue. So doing anything with fancier colour gradients might require different [modules](https://pypi.org/project/colour/) to do the hard work for you.

## Usage

The two versions are for CAE and for the ODB viewer, because of the way materials are accessed (or not accessed) in ODB scripting. Variables such as part names (ODB) and model name / material names need to be changed.

Running the scripts is through CAE or Abaqus viewer using File -> Run Script

![image](https://github.com/mngad/abq_colour_change/assets/18396518/ad1aee1a-fefe-454f-ad88-2802ac3cae45)
![image](https://github.com/mngad/abq_colour_change/assets/18396518/4c195181-e7c7-40c5-a264-8a34e7852676)

