# ECOvid Protective Face Sheild

A protective face shield fast to print and that use a minimum amount of material. 

This face shield is currently used in ICU MIR  at Hospital Cochin (APHP, Paris).  This design is validated by the Hygiene Committee of the hospital. 


You can read a thread on the design process, the tools used and the reasons for another design here on Twitter: https://twitter.com/marcteyssier/status/1245010785744683009




![Render](https://raw.githubusercontent.com/marcteys/ECOvid-FaceShield/master/pictures/render-v2.png)



## Print Settings

The *.curaprofile* is present on this repo, as well as some *.3mf* files. The profile can be imported on `Preferences>Configure Cura>Profiles>Import`. 

Here are the important settings for the Ender 3 pro.  
- Fill gaps between walls: *Nowhere*
- Infill density 80%
- Print speed 80 mm/s
- Generate support: *No*
- Build plate adhesion Type: *Skirt*

**Note:** It is important that there is no holes between the layers and the walls. Adujst your printer settings if you see that there is a hole between two walls: Change the setting *Fill gaps between walls*  to * Everywhere* if it's the case.

## Fabrication

### Material
- A4 transparent sheet 
- Standard EU punch hole, 2 holes ([exemple](https://www.google.com/search?q=punch+hole+2&hl=en&sxsrf=ALeKk01VRlmL0uM0lpgbsiWLHW1cRw-DiQ:1585672351383&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjr1-_pkcXoAhXU8OAKHVQoCY4Q_AUoAXoECAsQAw))
- 3d printed 

### Steps
- 3D print the face shield 
- Punch two holes on one side of the transparent shield, flip it over and punch two more holes from the other side. 
- Attach the transparent sheet
- Sterilize



## Edit the model

The source (*.blend*) is included. It is composed of three separate parts, **External**, **Internal** and **Strap**. I rely on non-destructive modelling techniques and used a lot of boolean operations.

To adjust the height of the stack, select each part and edit the value *count* of the *Array* modifier. 

To export the model, select the 3 parts and click *Export* on the 3D-print panel.

The following add-ons were used: Measure-it, 3D-Print Toolbox,  Bool Tool, Curve Tools and Bezier Utilities. Freestyle for rendering. 



## Credits 

This face shield is a remix the one proposed by [Qualup](http://www.spiderbot.eu/covid-19-ecran-facial-imprime-sterilisable/)


![Render](https://raw.githubusercontent.com/marcteys/ECOvid-FaceShield/master/pictures/face.jpg)

