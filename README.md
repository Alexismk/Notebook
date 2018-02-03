# Notebook

Week 1 – Jan 10

The only way we can represent things digitally is by cutting things down.
http://opentranscripts.org/transcript/programming-forgetting-new-hacker-ethic/

GitHub 
-	Repository = “New File”
-	KEEP NOTES AND TRACK OF WHAT YOU CHANGE EVERY TIME
    -	DOCUMENT PROCESS
- Can annotate others notes and help others to figure out what went wrong

-	When you are MAKING an actual digital thing – keep a progress notebook. Keep data and files here 
    -	Drag and drop 

Mark Down
-	When making a file name DON’T FORGET THE FILE EXTENTION 
-	You need to separate content from container – future proofing work
-	Work in basic text files
-	.md = markdown 
-	Dilliger.io
    -	Let’s your write markdown on the screen and lets you see the formatting 
    
    
# Digital History Lecture Notes – HIST 2812 – Week 2, Jan 15

https://shawngraham.github.io/presentations/3812-jan15.html#/1

Intro to Photogrammetry

- Part of a photographic approach to mapping , restoration
- Recording of material in space 
		- part of a suite of approaches related to geomatics, computer vision
- many ways of getting this done – most popular is “structure for motion”
- required YOU to do the rotating 
- videos can be cut into stills and 3D models could be created form stills 

GOOGLE MAPS 
– mapping buildings to produce 3D images (helps sefl driving cars know what is where)
- the kind we now see in apps & getting more user-friendly is structure from motion 

 
 - laser system mapping how fast light travels to map out an area. 
- VR systems use a scaled down version 
 

3D models can be created so that when scanned with a QR code, 3D images cam pop up from the page.
Videos can allow you to make 3D images and models  

THNK ABOUT SUSTAINABILITY WHEN WORKING WITH TECHNOLOGIES, APPS AND SYSTEMS
	Will this be available in a few months’ time? Years?
SKETCHFAB is the new popular system for 3D models 

# Augmented reality built with “Unity”
- “The Diary In The Attic”
- You need a framing story to validate why you are doing “this”
- Window to look through to see a different reality
- Popular with museums and heritage sights 

Archeology consumes and destroys what it discovers. It constructs knowledge by framing everything in its context
- Archeologists and created digital space reconstructions in order to always be able to understand a site aot its different points
- English Heritage: Photogrammetric Applications for Cultural Heritage

Basic Principles
- image capture
- clean, clear images from a variety of angles and depths
- image matching
- dense point cloud generation
		- creates dots that connect together to make an objcet
- secondary product generation
- analysis / presentation

 

Take overlapping images; you want a high degree of overlap
 
Never get a good model with anything less than 15 photos – 30 is overkill

 
- The computer identifies through colour and distance -  called tie points 
- tie points are matched
- the computer ties metadata to every image you take 
- source tracking
- includes size of the image, focal depth, 
- if you know that information AND overlapping point, the computer works out WHERE the camera was when you took that photograph

- dense point cloud generated :
chief ray is the line from the object, through the lens, to the image plate
Intersection of many of these allows the software to work out the location of the point in space
 

Chief ray & principle of intersection, collinearity
- knowing the 'interior and exterior' orientation of the camera - its internal arrangements, including lens distortion, focal length and so on from the metadata bundled with the image, allows software to work out the position of the camera viz points of overlap in the images
- the intersection of rays then allows us to work out the location of these points in space
- resulting point cloud has an arbitrary scale and coordinate frame (ways around this):

DOWNLOAD “MeshLab” OF “blender
Fills holes to make the model look beautiful 
Sources of other models:
- sketchfab.com
- thingverse
- smithsonian (hit the info button on a model for the download options)

sfm process
- identifies control points that are visible in multiple images (default in agisoft photoscan is 40 000 per image)
- best control points are then matched
- then triangulation (more or less) to work out the relative position & orientation of every image
- this is the sparse reconstruction

now dense reconstruction
- repeats the process above but for all possible control points
- a 'triangulated irregular network' TIN is generated, a mesh, onto which textures can be mapped using regular graphics software


# Computational Creativity and the ontological meaning of your models

Jan 29, 2018

Follow along at  j.mp/3812-01-29

Exiftool
- Download and extract it
- Put this file and drop this into the folder you want to do your work on 

Can computers be creative?
- "Computational Creativity is the study and simulation, by computational means, of behaviour, natural and artificial, which would, if observed in humans, be deemed creative."

How do we define when a computer is being creative?
We need to focus not on the process but the final product that is created.

Generated music?
- Listen to Wikipedia – aspect of humanity involved and the computer generates the musical translation 

THESE ARE THE WORONG QUESTIONS
Better Questions:
What are these things? Why are they way they are? How did they get this way? What do they mean?
And what do these answers imply for us history types? What we need, is a framework time for some archaeological theory (reilly.004)

Ways of mapping out the things and the broader systems of relationship that these items ae made up of/ how do things effect how history is told.

And what do these answers imply for us history types? What we need, is a framework
Are we playing with play, work or labour? Automata, algorithm 

#Archeology Theory
- 2 people can see different histories which are equally true by drawing boundaries. 
- When excavating, you may find a lack of something but it is still important 
- When digging, you transform the physical world. 
- Forces of things that persist and forces that define how things change:
 
 



The Victims of Vesuvius: their lives, afterlives, and after-after live.
When digging, they encountered voids. They poured plaster of paris inside these voids and they ended up with casts of furniture and eventually, bodies. 

Pseudomorph-cum-effigy.
- Casts of cast’s causes details to be lost along the way 
- Reliquary because they sometimes till contain human remains (bones)
- Made into 3d images
- Resin is injected so they can CAT scan then and detect bone material
- Finally, they can be 3 printed 
	
How do we understand the bodies of Pompey? What is the meaning of these recreated things? Are the casts considered human bodies?

Materialization v dematerialization and the archaeological record
permeability v persistence (forces defining the qualities of the object)


enchainment vs containment  (forces defining the processes of assembly / dissassembly)
how these things travel and how they are entangled in larger systems 

 
 



So what does this have to do with computational creativity?
- Forces us to think about the edges and how the smear against one another
- Not see things as bounded but blurred
- UNDERTAND HOW ONE FORM MOVES TO THE NEXT 

What is the ontological meaning of your projects?
- where is the creativity in your models?
- how do your models fit on these frameworks? why?
- what do you see when you try to map the moments, the glitches, the voids and spaces?

