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




# Feb 05 – Module 2: History is a Remix
https://shawngraham.github.io/presentations/3812-feb5.html#/11
Epoiesen - “how to make”

### Scary Mary – remixed and recomposing something to show it in a different light
- Takes its main parts and remixing it

### Watling Street 
- Remixing archeological data in a way that makes certain realities more apparent. We can understand the economic prosperity and distribution of roman coins in Britain through SOUND. 
- It is a remix of someone else’s code

Sometime it is the CODE and the underlying data that is remixed
Sometimes remixing does more harm than good 

Daniken’s belief that the ancients had help from aliens. It is a form of racism and reveals more about the people that made it.
- Cherry picks things that suit his argument 

Joan Hammond uses original iconography to remix Department of Rec signs to assert a new meaning. 
- Her photography uses the visual rhetoric of the ministry right down to the font. He has the research that support each of her remixes.

O’Donnell, the Un- essay, University of Lethbridge

Huge intellectual property issues when we start screwing with other people’s property. 
Lawerence Lessig - Creative Commons (Wiki Bio)
Aaron Swartz - Internet Hacktivist (Wiki Bio)

### Is it compelling or truthful?

 

### The 're' part is problematic. 
### A mix brings something new into being, something new from the source materials that was always latent.







### Deformance & Interpretation, McGann and Samuels

- The act of making something is as important as making the thing itself 
- When a poet preforms – elements become more apparent in the poem. 
- Deformance almost always comes back to te original thing 
- About pushing things until they break, and understanding something from the broken pieces 

 
What is the essence of the historical method?
How do you craft an argument from documents?
- Sometimes it is hard to change our historical method
- One way of remixing is through our digital history tools


### One DigHist Approach: Topic Models
- document remixed as distributions of words
- visualizations tend to be network graphs or histograms
- Graphs limit us where as this method is….weirder?
- Make things stranger  and understand it in a new way 

## A Non-Exhaustive List of Possible Ways to Mix History


### Sonification
WW1 Diaries of Robert Lindsay Mackay as Sound Cloud
- Recorded most common words and they were condensed played back
- Intensity of his exeirences
Intro to Sonification tutorial
- Maybe your writing about it can be produced into sound 
- Generate an empathy- we no longer see it as just a document 


### Twitterbots
Two Headlines
Trove Bots For All
- Generate your own twitter bot that grabs materializes from an archive and tweets them out 
- Glitch.com remixes code so you have the code to make your own bot – different levels of automation 
Vintage Face Depot
- Humanize the archives
Twitterbots via Tracery tutorial


### Generative Grammars
Sources from newspapers talking about bones (mad libs)
- Newpapers used reprints and stile from eachother 
 
Tracery.io editor


### Recurrent Neural Networks
If you feed it text it learns how to speak like the input 
- The Robotic Edward Gibbon
- A Newly Discovered Ancient Greek Play

### Maps
HistoryPin
Overlay historical photographs and overlay them in physical space 

### 3d Scene Mashups
SketchFab Mashup 1 from Erik Varvel on Vimeo.

### 3d File Mashups
Pericles an the lab
- Entering the realm of political cartooning 
•	Using Meshmixer
•	Using Meshlab

WHAT COULD I MESH THIS WITH TO SAY SOMETHING NEW ABOUT MY MODEL (new environment? Maybe on Sketchfab? Look for creative commons licences stuff. Can be downloaded from museum accounts – Smithsonian, British Museum)

Other questions:
Where is authority here?
Where is aura?
Who is the author?

MAKE AN EXTRA COPY OF YOUR OBJECT
You could glitch the text file data?




# Week 6- Feb 12 - Museums and 3d Scanning - fears, issues, and opportunities

## What CAN you build for module 2??

### Model: 
-	You can mix/remix things 
o	Roman Woman in a well
	2 different marbles, 2 different time periods imposed on each other
-	MESH MIXER allows you mix 2 models easily
o	Better than mesh lab
o	“reduce triangles”, “Decimate the mesh”
	Reduces the complexity while maintaining the appearance
	Makes the model easier to work with 
-	Sketchfab editing allows you to set which view it the first initial view, among other things 
o	YOU CA USE AN EXISTING MODEL ON SKETCHFAB
o	British museum and the Smithsonian has a good collection 
### Sound
-	Sonify underlying data

AS LONG AS YOU TRANSFORMING THE INITIAL MODEL 
Twitter bot may be better for the 3rd module – giving your model and underlying experience 

# Museums and Reproductions
https://shawngraham.github.io/presentations/3812-feb12.html#/1

-	Filling museums with replicas is a long standing process in museums. 
-	Most museums are filled with plaster casts
o	I highly skilled process 

### Early Motivations:
-	Desire to make plaster casts goes along with the rediscovery of antiquity and the desire to reproduce them
-	People are collecting these things and the casts are circulating and creating a refined taste in art 
-	Using the casts to teach artistic what constitutes good art 
-	New governments at this time and the fall of the monarchy – art in the sense of nationalism
o	“we are the new romans” imperial though that is expressed through this art
o	Encyclopedia museum content with showing these casts 

### Atelier de Moulage
-	There is a point when the casts are not enough….
-	Competitive race amongst the museums to find beautiful  pieces to go into their museum and casts are no longer sufficient 
-	Casts falling out of favour because they are too widespread and they were devalued 

### Cast Courts, Great Exhibition 1855
-	First great display of the worlds treasures 


## Industrialization

### Cast courts at the V&A open in 1873
-	Before that casts were about having beautiful object, here it is all about education and forming tastes
-	Educational thread 


## Industrialization and Academia
-	Important for the training of scholars because that mean that they did not have to travel to Rome. They could still do scholarship because they had 1:1 models
-	Imposition of regularization and breaking things down to tinnier tasks
-	Academics get interested in classifications, (social Darwinism)


### “Portage” 
-	expeditions to Egypt in which they would split anything they found between them and the king


### Museo della Civilta' Romana
-	Only becomes a state in the late 1800s. Mousseline decides fascism would be the new direction.
-	He has a big world exposition in 1942
o	Fascism Epocot
-	This is the epicenter of the expo 
-	Filled entirely with plaster casts
-	Not about forming tastes but about forming political taste. Showing the greatness of Rome, he’s also showing that others took all their treasures and that they can only show replicas. A promise that they will get them back 
-	Making connection between the greatness of the roman empire and the greatness of the fascist empire 
-	NOT JUST ABOUT THE REPLICA BUT ABOUT THE CONTEXT OF DISPLAY 
-	Egyptian architecture 


## Casts to Cast-offs

"Whether seen as dead bodies, cheap replicas, or dusty specimens, the casts were no longer awarded any artistic value"

-	Casts are a tool 
-	Long traditions of associating these casts with death and decay 
-	Totally out of fashion by the 70s and museums got rid of their casts


### Redemption
-	Realisation that for a lot of ancient monuments and artefacts, the casts were the only records we had
-	Due to war and environmental damage, they were being destroyed 
-	People realize that they have intrinsic historical interest, we can also mess with them more (painted statues)


## And How Have Museums Dealt With This?

## Problems for museums
-	Will they allow models and modeling?
-	Will they allow data to be downloaded?
-	Will they allow data to be remixed?
-	Will they charge a fee?

Bad lighting conditions are to prevent photography.

They are not equipped with the fact that you or I could go in and copy a model 

LEGAL PROBLEM

Other museums will charge insane fees for digital copies, in which you are not allowed to copy. 


## What is the position of Canadian Museums? 
-	Most probably have no official policy 
-	Linked open data – break down of what the object is, in a format that other computers can read 
-	WHAT IF the 3D data you have had that capability 


## The Bigger Fear: Misuse
-	If we provide this data, how do we know someone isn’t going to do something bad with it 
-	Reputation management is a big fear for cultural organizations who make this info available 
o	The fact that the information is digital makes it more attainable and more difficult/risky 


-	Think about the full biography of the object in the first place. Are you doing damage in some fashion? Is there something you are doing to mitigate it. 


## Answering these questions requires infrastructure
Concerning:
-	recording methods and metadata, 
-	digital object discovery and access, 
-	citation of digital objects, 
-	analysis and study, 
-	digital object reuse and repurposing, 
-	The critical role of a national/international digital archive.

Very few have thought that addressing these concerns require infrastructure 

It requires dollars and investments 


Developing a 3-D Digital Heritage Ecosystem: from object to representation and the role of a virtual museum in the 21st century

Fred Limp, Angie Payne, Katie Simon, Snow Winters and Jack Cothren

http://intarch.ac.uk/journal/issue30/1/toc.html 


Michael carter points out the problem of the loosened copy...
-	Things we ca do to mitigate these problems like copies that wander, how do you acknowledge come from, how do you tie it back to its original place where it came from 
-	3D objects are vertices with connection between them
-	He connects that to the external world (?)
-	What if we embed al  this info about the object to EACH POINT in the model
o	That model could then be transformed, and the chances of deleting all the info would be slim 
o	The record of transformations is built into the model itself
o	The model became a representation of change itself 
-	He added meta data to every point 


Problems: Large files and increased data

Each cell in the entire body contains your DNA data

