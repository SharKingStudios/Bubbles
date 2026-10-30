Covers September 27-October 30, 2026  

Overview:

 - 09-27 - 1h 34m - Initial Bubbles CAD setup
 - 09-30 - 0h 47m - Reference sketches and UHMW side walls
 - 10-01 - 5h 24m - Base and UHMW master sketches
 - 10-02 - 12h 11m -  Major chassis and weapon-system CAD
 - 10-03 - 6h 40m - Motor cover, switch clearance, and side artwork
 - 10-05 - 0h 19m - PLA chassis test fit and parts delivery
 - 10-06 - 6h 16m - TPU printer setup and electronics assembly
 - 10-07 - 4h 59m - Waterjet cutting and TPU prints
 - 10-09 - 4h 24m - UHMW milling and TPU removal
 - 10-10 - 0h 34m - Fork CAD adjustment and print issue
 - 10-12 - 1h 49m - Manual UHMW drilling and TPU side armor
 - 10-13 - 2h 50m - First drivetrain mechanical assembly
 - 10-14 - 7h 23m - Motor shaft modifications and CH1 diagnosis
 - 10-15 - 5h 42m - ESC firmware debugging, first drive and weapon spinup
 - 10-16 - 10h 08m -  AR500 fork finishing, weapon debugging and drive tests
 - 10-17 - 8h 10m - Titanium top components, CheeseBlock, and armor revisions
 - 10-18 - 0h 46m - Assembly layout and visibility checks
 - 10-21 - 1h 06m - Assembly drawing development
 - 10-23 - 2h 27m - Post-event teardown, damage inspection, weapon disassembly
 - 10-30 - 6h 30m - Engineering journal writing and time accounting

Total: ~90 hours



## Sunday, September 27, 2026 (1h 34m) - Initial Bubbles CAD setup

9:53-10:57 PM

I started the Bubbles document and set up the first Bubbles V1 Part Studio. I added the PBK Mk2.1 reference model to an assembly and created separate Repeat Max and Weapon Motor studios using derived geometry. I also started the mastersketch and did some early reference assembly visibility and positioning work.


![Image](/assets/image.png)
![Image](/assets/image%20copy.png)



## Wednesday, September 30, 2026 (0h 47m) - Reference sketches and UHMW side walls

9:44-10:01 PM

I reorganized the reference assembly and created the Example PBK sketching area and the UHMW Side Walls Part Studio. I also made a Remade Parts folder so the reference and replacement geometry would be easier to keep organized.


![Image](/assets/image%20copy%202.png)


## Thursday, October 1, 2026 (5h 24m) - Base and UHMW master sketches

10:21 AM

I continued using the PBK reference model to work out geometry and dimensions for the new robot. The early edits were mainly in Example PBK and its assembly to get dimensions to use as a reference.

![Image](/assets/image%20copy%203.png)

![Image](/assets/image%20copy%204.png)

(Getting measurements from the drive motor cad)

6:51-7:52 PM

I started building out Bubbles V1 properly: the Base Mastersketch, UHMW Mastersketch, left and right UHMW parts, left and right armor, and the TPU armor versions. I worked through planes, extrudes, mirrors, and part naming to get the chassis geometry organized before putting it all into the assembly.


![Image](/assets/image%20copy%205.png)

![Image](/assets/image%20copy%206.png)


## Friday, October 2, 2026 (12h 11m) - Major chassis and weapon-system CAD

10:03 AM-1:00 PM

I spent most of the morning building the actual chassis geometry: TPU side and rear armor, bottom carbon-fiber plate, top carbon-fiber plate, motor-cover carbon-fiber plate.

![Image](/assets/image%20copy%207.png)

![Image](/assets/image%20copy%208.png)

1:14-4:00 PM

I started assembling these parts in V1 Assembly using a ton of fastened, cylindrical, planar, and revolute mates. I brought in the weapon/reference hardware and worked on the left/right wedge connectors and motor uprights. This was the point where the individual CAD parts started coming together as a complete assembly.

![Image](/assets/image%20copy%209.png)

4:28-5:04 PM

I worked on the 22-tooth timing pulleys. I tried the Fingertech S3M pulley geometry, made a GT3 22T 10x6 mm pulley using a pulley generator featurescript I found, and added the resulting pulley instances into the assembly.

![Image](/assets/image%20copy%2010.png)

6:55-11:06 PM

I came back for a second CAD session to refine chassis features and work on the forks. I created the Long Fork and Short Fork geometry, used the Lighten and Thicken features on those, and added Short Fork instances into the assembly.

![Image](/assets/image%20copy%2011.png)



## Saturday, October 3, 2026 (6h 40m) - Motor cover, switch clearance, and side artwork

9:34 AM-11:13 AM

I refined the motor-cover cutouts and added more lightening and thickness features in Bubbles V1. I also added the power-switch hole parameter at 28.5 mm and adjusted the assembly relationships as I worked out the packaging of the actual electronics

5:34-7:29 PM

Later I worked on the TPU side artwork and brought in vector geometry from SVG/DXF files. I used the Side TPU Artwork sketch and an extrude to integrate the artwork into the part geometry. I wanted this side TPU artwork to look nice since it would be highlighted in the renders I was about to do.


![Image](/assets/image%20copy%2012.png)


![Image](/assets/image%20copy%2013.png)

(Note the switch actually fits this time)

![Image](/assets/image%20copy%2014.png)

After getting the major design done, its time to make some sick renders! Onshape now actually supports directly exporting into an OBJ file that blender can use directly, so I dont even need to use CADtools to convert it! I put together a scene with some interesting lighting and once again a majority of the time is just spent refining materials.

![Image](/assets/image%20copy%2015.png)

After I finished here were the results:

![Image](/assets/image%20copy%2016.png)

![Image](/assets/image%20copy%2017.png)


![Image](/assets/image%20copy%2018.png)


## Monday, October 5, 2026 (0h 19m) - PLA chassis test fit and parts delivery

5:53-6:12 PM

I got all my robot parts printed out of PLA to do some test fits of the chassis, and my Repeat Robotics order came in! This was an initial physical fit check before I committed to assembling everything in the final materials.

![Image](/assets/image%20copy%2019.png)

![Image](/assets/image%20copy%2020.png)

(all of these are the electronics that need to go into the robot)  

## Tuesday, October 6, 2026 (6h 16m) - TPU printer setup and electronics assembly

9:38 AM

Figuring out how to print TPU on these H2D printers

9:50 AM

Got the tpu filament in the dryer going into the backside of the H2D and it finally grabbed it so we can actually print with it!

I had to go to class after getting the filament loaded.

![Image](/assets/image%20copy%2021.png)

![Image](/assets/image%20copy%2022.png)

10:30 AM

I made an early pass on the Forks geometry in Bubbles V1, including feature edits.

![Image](/assets/image%20copy%2023.png)

11:09 AM

Now that I have filament loaded I just need to figure out the actual print settings I want to go with for my parts. This step actually matters quite a bit since it determines how well the TPU will adhere to itself as well as more generally the weight vs strength of the part. (You need a balance since these combat robots are weight limited)

After dialing in some of the settings I wanted, this is looking like a really really long print. (You need to print TPU pretty slow for it to work well)

11:37 AM

I got my settings all finalized and exported the files to the printer! The first layer looks really good so I should be fine just leaving it. (10 hour print...)  

![Image](/assets/image%20copy%2024.png)

![Image](/assets/image%20copy%2025.png)

3:45 PM

I gathered all my parts together and prepared to solder the electronics together.

![Image](/assets/image%20copy%2026.png)

6:21 PM

After getting the other electronics together it was time to add the capacitors. These will help smooth out the voltage from the battery as the robot draws varying amounts of current. After I got these one I finished up the electronics by wrapping the ESCs in Kapton tape.

![Image](/assets/image%20copy%2027.png)

![Image](/assets/image%20copy%2028.png)

9:52-10:19 PM

I came back to the Forks geometry in Onshape and worked on fillet and lightening features.

![Image](/assets/image%20copy%2029.png)

## Wednesday, October 7, 2026 (4h 59m) - Waterjet cutting and TPU prints

9:36-9:52 AM

Before the waterjet work, I made another short pass on the forks and wedge-connector geometry in Onshape.

![Image](/assets/image%20copy%2030.png)

10:40 AM

My first TPU prints finished with no visible issues! The infill was probably a bit high, but I have the weight for it so its alright.

It was fairly hard to get this long part off since it stuck so well to the build plate:

![Image](/assets/image%20copy%2031.png)

10:56 AM

setting up a new print so I can have spares:  

![Image](/assets/image%20copy%2032.png)

11:36 AM

I exported all my designs and got created toolpaths for our waterjet on this old software called ProtoMAX.

Super weird to use but I was able to get all the paths for the parts and put in all the needed settings and offsets for the machine:

![Image](/assets/image%20copy%2033.png)

11:50 AM

I figured out how to get the machine to do a dry run without cutting so I can check to make sure everything is working correctly! Everything looks all good!  

![Image](/assets/image%20copy%2034.png)

11:54 AM

The machine cuts these 2D designs out so quickly! These plates got finished in under 5 minutes after I clicked start.

![Image](/assets/image%20copy%2035.png)

![Image](/assets/image%20copy%2036.png)

(The blue is just a removable protective coating)
12:11 PM

I rezeroed the machine to a new spot and made 2 spares!  

![Image](/assets/image%20copy%2037.png)

12:27 PM

I finished cutting out my first carbon fiber top plate!

![Image](/assets/image%20copy%2038.png)

12:34 PM

I made another CF plate:  

![Image](/assets/image%20copy%2039.png)

5:03 PM

I check in on my 3D print and it looks fine atm. Time to go set up the next CF plates to cut.  

![Image](/assets/image%20copy%2040.png)

5:20 PM

I cut out my CF bottom plate

![Image](/assets/image%20copy%2041.png)

5:28 PM

I imported my last plate I need cut out and put its path for the machine together.  

![Image](/assets/image%20copy%2042.png)

5:38 PM

Cut out 2 top plates.  

![Image](/assets/image%20copy%2043.png)

5:58 PM

Trying to see if I can cut out one more part:  

![Image](/assets/image%20copy%2044.png)

(clearance is a Boolean 🗣️)  

## Friday, October 9, 2026 (4h 24m) - UHMW milling and TPU removal

11:01 AM

My TPU prints finished with no issues! They stuck insanely well to the build plate so taking them all off took a bit of work...

![Image](/assets/image%20copy%2045.png)

3:08 PM

Its time to cut out my UHMW uprights on the mill!! 

I started by zeroing everything on the machine, then making sure the uhmw was level and screwing it into place so it wouldn't move as I milled it out.

![Image](/assets/image%20copy%2046.png)

3:38 PM

its finally starting some cuts! (and shooting tiny plastic bits everywhere)

![Image](/assets/image%20copy%2047.png)

4:19 PM

someone had me change my offset and that caused me to mill ~1/10 of an inch into the spoilboard lol  

![Image](/assets/image%20copy%2048.png)

5:14 PM

The mill path didn't cut out some of the holes, so I had to create a new path to go through and get those holes.  

![Image](/assets/image%20copy%2049.png)

![Image](/assets/image%20copy%2050.png)

(as it turns out there was another operation I could use to get these holes, which I did figure out)  

![Image](/assets/image%20copy%2051.png)

6:13 PM

I finished the UHMW parts and go to check on the print and it doesn't look too good :(

I hope this wont cause any issues with the print shifting or anything (forshadowing)  

![Image](/assets/image%20copy%2052.png)

6:17 PM

The final UHMW parts off the mill:

![Image](/assets/image%20copy%2053.png)

## Saturday, October 10, 2026 (0h 34m) - Fork CAD adjustment and print issue
2:03-2:08 PM

I made a quick adjustment to the Forks feature in Bubbles V1 to swap their size. (for the funnies)

![Image](/assets/image%20copy%2054.png)

more layer shifts in the prints today that really sucks.

![Image](/assets/image%20copy%2055.png)

## Monday, October 12, 2026 (1h 49m) - Manual UHMW drilling and TPU side armor
12:31 PM

I need to drill out the holes in the UHMW uprights so I can screw in my carbon fiber plates and try to complete the chassis.

No drill guide here I just marked out where the holes should go after lining up the plates by hand (surely this wont come back to bite me right...)

![Image](/assets/image%20copy%2056.png)

5:22 PM

more drilling of uhmw

![Image](/assets/image%20copy%2057.png)

5:29 PM

I finished drilling the holes and started some 3d prints for my tpu side armor.

![Image](/assets/image%20copy%2058.png)

## Tuesday, October 13, 2026 (2h 50m) - First drivetrain mechanical assembly

10:42 AM

I got all my parts fabricated and together so I can try and start putting some of it together.

![Image](/assets/image%20copy%2059.png)

11:23 AM

I got the motor plates on both sides of the upwrights and got the motors installed into those plates. Everything wasn't lining up perfectly and I had very little clearance in the holes I cut so I needed to do some shenanigans to get it all to fit.

![Image](/assets/image%20copy%2060.png)

11:44 AM

I got the wheel shafts in place on each side and got the pulleys lined up and put on! This was the first time I've created something where the pulleys actually fit lol

It was very refreshing to see.

![Image](/assets/image%20copy%2061.png)

8:10 PM

I had picked up a bunch of 3d printed parts from the fabrication building and brought them back to my dorm to put on the robot:

![Image](/assets/image%20copy%2062.png)

## Wednesday, October 14, 2026 (7h 23m) - Motor shaft modifications and CH1 diagnosis

9:55-9:59 AM

In the morning I imported the PBK Wedge STEP model and transformed the imported geometry. I also exported and started printing these TPU parts I would need to attach the wedge to the rest of my frame.

![Image](/assets/image%20copy%2063.png)

4:35 PM

my forks arrive from scs!! (They even gave me candy lol)

![Image](/assets/image%20copy%2064.png)

5:39 PM

I cant fit my side armor on since the shafts on my drive motors are too long.

The hard thing here is that the shafts are made of hardened steel, so I need to figure out how to cut them down...

I pulled all of the electronics out of the bot (essentially entirely disassembled so I can get to the motors.)  

![Image](/assets/image%20copy%2065.png)

6:30 PM

I have my plan ready. I've found a Dremel with some metal cutting bits I can use to cut the shafts.

I need to be careful here to cover up all my motors, since the cutting will create tons of metal dust into the air (lwk need to be careful not to breath this in too)

6:52 PM

the cutting setup where all electronics are covered and the shaft is held in place by as vice.

Cutting is still pretty slow and I need to be careful. (I did break one disk...)

![Image](/assets/image%20copy%2066.png)

After cutting

After I finished cutting those down I cleaned everything up and tried fitting some things back together. Issue now is that some of the plastites dont fit into my 3d printed parts.

7:42 PM

I bored out all of the 3d printed holes for plastites since I printed all of my spares out without testing if a plastite could actually fit...

I tried boring with a 1/8in bit and that ended out working great so I went and did that to all of the holes that needed a plastite.

![Image](/assets/image%20copy%2067.png)

7:46 PM

I also bored out the supports that were stuck in my fork attachment pieces.

![Image](/assets/image%20copy%2068.png)

7:57 PM

I started reassembling the robot with all of these pieces, now the side armor will fit on!

![Image](/assets/image%20copy%2069.png)

8:46 PM

Everything I need to test the motors is reassembled and the motors spin!

![Image](/assets/image%20copy%2070.png)

9:01 PM

I continue assembly by putting on the wheels, pulleys, and back wall.

![Image](/assets/image%20copy%2071.png)


9:13 PM

I put on the side armor!

![Image](/assets/image%20copy%2072.png)

9:17 PM

another twitch test with the whole bot put together, this is the first time spinning with the wheels and I notice that the right drive side CH1 is having issues moving around. It could be rubbing on something but I am not too sure of what the issue is yet.

![Image](/assets/image%20copy%2073.png)

9:46 PM

I've eliminated rubbing and pulled the electronics out for a better look. I took the Kapton tape off of the drive esc and I cant see anything wrong with it, but CH1 is still driving weirdly slow and with so little torque.


![Image](/assets/image%20copy%2074.png)

10:03 PM

I attempted to test the motor out with a multimeter for any issues and I cant see anything, though granted the multimeter I was testing with was not very good. I can probably swap the motors to different channels to see if the issue follows the motor, or the ESC side.

![Image](/assets/image%20copy%2075.png)

10:33 PM

Ok I've found that the issue follows the ESC side instead of the motor, which is good since each drive motor costs 50$ and I absolutely have zero chance of fixing one if it was broken.

I found the esc programmer and now I just need to figure out how to connect it up so I can try and take a look if theres something wrong with my esc firmware that would be causing this issue. Potentially a mismatched kv value on the motor for that side?

![Image](/assets/image%20copy%2076.png)



## Thursday, October 15, 2026 (5h 42m) - ESC firmware debugging, first drive and weapon spinup

11:13 AM

I've finally got a known good USBC cable I brought from my dorm to do this.

It's still not working tho. I wonder why...

![Image](/assets/image%20copy%2077.png)

11:16 AM

I'm installing drivers

USB serial is now showing up on the computer but I still cant properly read the firmware from the ESC.

![Image](/assets/image%20copy%2078.png)

11:36 AM

I've tried installing a custom ESC config tool for AM32 but its still not connecting.

![Image](/assets/image%20copy%2079.png)


12:00 PM

I started desoldering the motors to see if that changes the behavior.

![Image](/assets/image%20copy%2080.png)

7:10 PM

After swapping out the motor, I started testing for different behavior. Unfortunately it was the same and continued to give me issues.

7:38 PM

I got the firmware connected (by using an AM32 tool in the brave browser instead of ms edge, interesting but it works now)

With the firmware connected I turned off the CH1 current limits and the motor spins fine now. (with a bit of reduced torque at low speeds as I explained in my last response, but it still drives mostly fine)

![Image](/assets/image%20copy%2081.png)

8:45 PM

I've soldered the motors back to the channels they are supposed to be on and rewrapped all the electronics. Its finally ready for a test drive.

![Image](/assets/image%20copy%2082.png)

8:47 PM

The motors are spinning the wrong way lol but I still test it.

9:07 PM

By this point I took the bot back apart and fixed the motor directions, so I can have a proper test drive!

One of the motors has this weird oscillating noise while I drive straight, as it turns out this was due to overly low current limits on the other drive motor, so I went in and turned those limits higher and higher until I eventually just turned it off

9:32 PM

(I turned off the current limits)

9:34 PM

I did the first drive test with the fixed drivetrain!

[Bubbles Mk.1 Drive Test](https://www.youtube.com/watch?v=wycrKTKXJN0)

10:11 PM

I finished boring out the mounting holes on my TPU front connectors after they finished printing so I could put my wedge configuration on the bot.

![Image](/assets/image%20copy%2083.png)


10:19 PM

I weighed all the configs I would have and they are all under weight!

... installed the wedge config onto the robot for the first time  ...


![Image](/assets/image%20copy%2084.png)

![Image](/assets/image%20copy%2085.png)

![Image](/assets/image%20copy%2086.png)

10:47 PM

is the first ever weapon spin up. It has some issue of resistance and I don't know why (yet)

[Bubbles Mk.1 Weapon Spin-up Test](https://www.youtube.com/watch?v=4kZMM_xLHss)

## Friday, October 16, 2026 (10h 08m) - AR500 fork finishing, weapon debugging and drive tests

11:18 AM-12:32 PM

I tested the bot and found that while the CH1 could now drive, at lower speeds it had much reduced torque which was really weird and repeat robotics actually gave me a refund for the esc after I demonstrated that issue.

![Image](/assets/image%20copy%2087.png)

(me testing motor torques)

~12:10 PM

I did a drivetrain test in the box to try and figure out drive issues. I also did a weapon test here up to ~70% and found it had some issue there which I didn't figure out the solution for a while. (I took apart the weapon stack to figure it out.) As it turns out the weapon motor was rubbing on the side wall causing a ton of friction in some cases.

2:21 PM-~5:00 PM

fabrication! Drill press on some of my 3d printed parts since I needed to bore out the hole to my fork attachment to better fit the bolt.

After that a majority of this time was spent working to manually grind the forks down to give them a fillet. Mind you these are ar500 steel so it took quite a while on the metal belt sander and rotary sander to get the 6 small forks and 3 large forks down into having the filleted tips. I finished this around 5pm

![Image](/assets/image%20copy%2088.png)

![Image](/assets/image%20copy%2089.png)

![Image](/assets/image%20copy%2090.png)

~5:00 PM-6:40 PM

After this was more bot testing and debugging of the weapon. I initially thought there could be rubbing but as it turns out it was the battery! (since I didnt replace the battery after doing esc drive tests earlier in the day) The weapon stack was still assembled slightly wrong at this point (which was causing more rubbing, making it not spin while the battery was low like this) 4s battery at 12.06V (cooked)

![Image](/assets/image%20copy%2091.png)

Ok after taking the weapon stack apart again I figured out what was rubbing and that if I didnt screw in the top plate it would still totally work, so I bored out some new holes in the uhmw for the top plate and this caused it to hit the weapon, so I needed to go into the fab lab and jankily use the waterjet to cut out small parts off my top plate until the weapon cleared it... Done w this by 6:40

![Image](/assets/image%20copy%2092.png)

![Image](/assets/image%20copy%2093.png)

6:40 PM

We finally get another weapon spinup but it sounded really really bad, something was still rubbing but I was able to make some good hits. This is also the point where I learn I can get beached kinda easily from my lowish ground clearance. (this was also partially the crappy test box)

~7:10 PM

So after taking it out of the box from those tests I figured out what the rubbing was! The weapon was getting pulled to the right side of the robot and tapping the screw heads into the UHMW, which was kind of carving a bit away at it.

![Image](/assets/image%20copy%2094.png)


The motor was also rubbing into one of the alumimum uprights meant to hold in the weapon motor somehow / it was also rubbing on the bearing head somehow... (these were the source of the rubbing)

![Image](/assets/image%20copy%2095.png)


7:25 PM

I was getting the electronics back inside and trying to make sure the drive motor esc wouldn't be rubbing up against the drive motors since they sit pretty close together.

![Image](/assets/image%20copy%2096.png)

7:44 PM

I did another weapon test and it actually got locked up at one point. This rubbing issue is pretty bad.

7:48 PM

I unscrewed the problematic aluminum weapon motor upright just a bit to allow it to flex more out of the way, which freed the entire thing up.

8:07 PM

I got it put back together enough for another test box run.

...more drive testing + box testing...

8:49 PM

The battery was super cooked after this one lol 11.17V. These last a lot shorter than the larger batteries I am used to so I need to keep that in mind.

![Image](/assets/image%20copy%2097.png)

9:17 PM

I did a box test on a fresh battery and it went much better.

Took it out and started installing my new forks on the robot.

[Bubbles Box Testing](https://www.youtube.com/shorts/UcJ8NNOad0k)

10:18PM

I did drive testing outside the box with the weapon lock on the robot. (tuning the bot drive and making sure stuff isn't overheating.)

I also took videos of the bot driving with the forks, photos of the finished fork installation, and went outside to get a hero image of the robot.

![Image](/assets/image%20copy%2098.png)

![Image](/assets/image%20copy%2099.png)

10:34 PM-~10:46 PM

I wanted a better weapon lock since my "lock" up to this point has literally been a metal clamp, which hinders me a bit while I drive since it sways the mass to that side unevenly.

![Image](/assets/image%20copy%20100.png)

10:47 PM-~10:56 PM

The drill guide was created since all of the issues I was facing were because I yoloed it with the drill press causing the top and bottom plates to be slightly misaligned, which was ultimately causing the motor rubbing issues.

The drill guide was so my spares would not be cooked like that.

![Image](/assets/image%20copy%20101.png)



## Saturday, October 17, 2026 (8h 10m) - Titanium top components, CheeseBlock, and armor revisions

11:42 AM-3:15 PM

I checked the existing CAD and made a change to the Drill Guide, including another Thicken feature before I printed it out.

7:15-9:48 PM

I worked on the Hammasaw armor features and created the Ti Top 1 and Ti Top 2 parts. I also modeled the CheeseBlock and inserted these parts into V1 Assembly with fastened mates. I continued revising extrudes, chamfers, and fillets in Bubbles V1, including motor-cover/armor-related geometry. I also tried printing out the weapon lock in my pink filament. For some unfortunate reason the ENTIRE THING got insanely tangled. I tried to fix it and was able to feed the printer enough to finish the print but I had to throw the rest of it away...

I also got my drill guide printed out and used it on my spare UHMW uprights to make sure those holes were aligned correctly.


![Image](/assets/image%20copy%20102.png)

![Image](/assets/image%20copy%20103.png)


Finally I did a small weapon spin test and noticed that one of the needle bearings in the weapon core was making some weird noises. I tried taking it out and putting it back together since theres not really anything I can do at this point but its still making a bit of a noise. Will probably be fine though...

![Image](/assets/image%20copy%20104.png)

![Image](/assets/image%20copy%20105.png)



## Sunday, October 18, 2026 (0h 46m) - Assembly layout and visibility checks

10:51-11:07 PM

I went through the V1 Assembly to check the placement and visibility of the CheeseBlock, Ti Top parts, and TPU armor. Heres what my hammersaw configuration would look like:


![Image](/assets/image%20copy%20106.png)


## Wednesday, October 21, 2026 (1h 06m) - Assembly drawing development

6:35-7:11 PM

I started the V1 Assembly drawing and added the base and projected views. I adjusted orientations, moved views, edited notes, and controlled component visibility to make the drawing more useful. I also updated and cleaned up the drawing references.

![Image](/assets/image%20copy%20107.png)

(This design looks so cool)

## Friday, October 23, 2026 (2h 27m) - Post-event autopsy and damage assessment

4:21 PM

There were some crazy brutal hits especially in my last 2 matches. I need to pull the bot apart to figure out what I need to fix for my next event!

![Image](/assets/image%20copy%20108.png)

One of the bits of damage is incredibly obvious. Shri got a really good hit on one of my forks and bent it up quite a bit. (Keep in mind this is AR500 Steel!) I can probably still use it as a spare but still a bit unfortunate.

4:43 PM

I forgot I stripped a screw out while repairing the robot during one of my fights at the comp, I guess now is my time to pay for it.

I used the Dremel with a metal cutting disk and cut a small notch in the screw. That allowed me to get a flathead in there and rotate the screw out.

![Image](/assets/image%20copy%20109.png)

4:48 PM

The insides are pretty dusty but the electronics look mostly fine despite being right next to a leaking battery.

![Image](/assets/image%20copy%20110.png)

The bottom plate doesn't look too bad either. Theres still a bit of stuff on there but I could easily wash it off and it seemed undamaged:

![Image](/assets/image%20copy%20111.png)

Oh god when I was looking at the ESCs and reapplying Kapton tape I noticed one of the capacitors fell off of my weapon ESC :(

As long as I don't lose this it shouldn't be too hard to solder back on there.

![Image](/assets/image%20copy%20112.png)

6:18 PM

The damage to the weapon is a lot more clear here, one of the bolts got sheared off, and theres crazy damage to the core of the weapon:

![Image](/assets/image%20copy%20113.png)

![Image](/assets/image%20copy%20114.png)

Getting the AR500 blades out of this took quite a while, these screws holding in the weapon are steel and they got pretty bent.



## Thursday/Friday, October 29-30, 2026 (6h 30m) - Writing this long ahh journal...

Spent over 6.5 hours writing this freaking journal and compiling all these times. I went through the Onshape history, photos, videos, and build notes to reconstruct what I worked on, calculate the hours, and organize the image placeholders. This was documentation work, why did I genuinly start at 7:30pm and end at 5am.. idc enough to count the entire time since I didnt lapse it but thats actually insane. I guess it counts for all the time I would have spent writing these journals individually...

(This is the output from the command used to scrape my Onshape CAD usage:)

![Image](/assets/image%20copy%20115.png)

(over 1130 edits)

With so many pictures and video taken during the build process it isn't hard to say with confidence what I did and how long it took, since I just took the time between the first picture or video and the last one from whenever I was working. There was math put behind this reconstruction as well. If you have any questions about the time, please DM me on slack and I can answer any questions you may have. I have taken this time to make sure everything is as accurate as possible.

![Image](/assets/image%20copy%20116.png)

(The data can get more specific than this if required but I don't want to be leaking my personal stuff in a public thread lol)