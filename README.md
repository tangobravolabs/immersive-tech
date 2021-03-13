# immersive-tech



Crawford's Lessons
+ Stories are complex structures that must meet many hard-to-specify requirements
+ Stories are about people, not things
+ Stories are about conflict, most commonly social conflict.
+ Puzzles are a necessary component of stories.
+ Spectacle does not make stories.
+ Visual thinking should not dominate stories.
+ Stories take place on stages, not maps.
+ Your designs should aspire to the ideal of metaphorically having sex with your users.
+ Fast turnaround is always better than slow turnaround.
+ The overall quality of an interaction depends on its depth, as well as speed
+ Unlike virtual reality, which requires users to purchase pricey headsets in order to be immersed in an altered experience, it’s possible to experience AR on mobile.


03.13.21
* TIL: https://blooloop.com/museum/in-depth/immersive-experiences/
* Modern visitors are more likely to spend their hard-earned money on experiences rather than products. For instance, they want to enjoy memorable days out, visits and experiences that they can share with friends, filling their social media accounts with fun images and videos.
* Immersive experiences, such as Jeff Wayne’s The War Of The Worlds: The Immersive Experience or Judge Dredd Uprising: The LIVE Experience, perfectly fill the wants and expectations of this millennial and gen Z audience
* the fact that attractions are competing with each other to capture their audience’s time, attention and money. 
* Pine says, the most valuable of these is time. In a modern society where time is a precious resource, a truly good experience is time well-spent.
* “Consumers want to spend their hard-earned time, and money, on the experiences that they value,” says Pine.
* The fact that immersive experiences create memories, that they can be enjoyed together and shared, is a big part of their appeal. 
* This award-winning attraction features ‘layered reality’ as well as music from the classic musical.
*  Then, during the interval, the spell is not broken as they find themselves in the Red Weed themed bar. 
*  Any sufficiently advanced technology is indistinguishable from magic.
*  “People seem to love the fact that The War of the Worlds experience is a very different sort of storytelling. It is something that genuinely allows them to escape from the world for two hours.
*  For a less adventurous but no less immersive experience, audiences have also been enjoying Atelier des Lumières in Paris, France. Here, famous artworks are brought to life, jumping from the canvas to the digital world.
*  Some sit, some walk around, or even lie on the floor to take it all in. “Some, they are dreaming,” says de Cointet de Fillain.
*  “Our mission is to make art more accessible to a wider and younger public. With the creation of our unique inclusive digital experiences, based on video, music and interactivity, we want to invite visitors of all backgrounds for a fascinating immersive journey into the artistic universe.”
*  Zero Latency created the world’s first location-based free roam VR experience. And now, the company’s fun, immersive experiences are now available in 45 venues, over 22 countries worldwide. The appeal of this type of entertainment is certainly global.
*  “We want our experiences to blow you away no matter which Zero Latency VR venue you’re at,” said CEO Tim Ruse on the released of the Zero Latency free-roam VR platform, which was developed in collaboration with HP, Microsoft and Intel.
*  Immersive experiences really are everywhere these days. And there is something on offer for all types of audiences, from art lovers to thrill-seekers.
*  


03.12.21
TIL: https://developer.apple.com/augmented-reality/arkit/
* The advanced scene understanding capabilities built into the LiDAR Scanner allow this API to use per-pixel depth information about the surrounding environment
* Location Anchoring allows you to anchor your AR creations at specific latitude, longitude, and altitude coordinates.
* Track up to three faces at once using the TrueDepth camera to power front-facing camera experiences like Memoji and Snapchat.
* Create a topological map of your space with labels identifying floors, walls, ceilings, windows, doors, and seats. This deep understanding of the real world unlocks object occlusion and real-world physics for virtual objects, and also gives you more information to power your AR workflows
* The LiDAR Scanner enables incredibly quick plane detection, allowing for the instant placement of AR objects in the real world without scanning. Instant AR placement is automatically enabled on iPhone 12 Pro, iPhone 12 Pro Max, and iPad Pro for all apps built with ARKit, without any code changes.
* AR content realistically passes behind and in front of people in the real world, making AR experiences more immersive while also enabling green screen-style effects in almost any environment.
* Capture the motion of a person in real time with a single camera. By understanding body position and movement as a series of joints and bones, you can use motion and poses as an input to the AR experience
* You can simultaneously use face and world tracking on the front and back cameras, opening up new possibilities.
* Detect up to 100 images at a time and get an automatic estimate of the physical size of the object in the image. 3D object detection is more robust, as objects are better recognized in complex environments. And now, machine learning is used to detect planes in the environment even faster.

03.11.21
TIL: https://medium.com/chialab-open-source/ar-js-the-simpliest-way-to-get-cross-browser-ar-on-the-web-8f670dd45462
*  AR.js is a great project with over 10k stars on Github, that makes easy and fun to develop augmented reality apps with web technologies.
*  https://github.com/jeromeetienne/AR.js
*  Performance, ~60 FPS on my two-year-old phone (!)
*  Compatibility, it is cross-browser, it works on every phone browser (and obviously desktop)
*  Simplicity, it is a wrapper of different frameworks that makes web AR developing very easy. It is built on top of a-frame and three.js.
*  AR.js works with markers (not always, but if we wanna be cross-browser, we have to use markers)
*  Markers are a sort of simplified qr-codes.
*  custom markers
*  > The maximum resolution of a marker is 16x16 pixels
*  > They must be square in shape
*  > They cannot have white/transparent areas, only light grey (e.g. #F0F0F0)
*  > They cannot contain colors, only black and light grey
*  > They have to contain simple text, like one letter, a number, or a symbol.
*  You may use this online tool to generate your custom markers. If you analyze the “.patt” output file, you will find out that the given image is described with a set of characters
*  https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
*  Markers can also be barcodes. 
*   It is suggested to generate markers based on a matrix with an high “hamming distance” (see this table), so the camera can recognize them better
*   online generator of barcode markers I used for the following example.
*   https://au.gmented.com/app/marker/marker.php
*    An approach based on markers is not a real limitation, but rather a paradigm that suits well for an incredible range of use cases.
*    As AR.js shows us, it’s not necessary to have another device over a mobile phone to experience AR, nor to download a third party app (that a common user will surely uninstall soon after, or that probably they won’t download at all)
*   With live collaborative session between multiple people, you can build a collaborative world map, making it faster for you to develop AR experiences and for users to get into shared AR experiences like multiplayer games.
*   Reality Composer is a powerful tool that makes it easy for you to create interactive augmented reality experiences with no prior 3D experience. 
*   Reality Converter quickly converts your existing 3D models to USDZ so it works seamlessly in our tools and on all AR-enabled iPhone and iPad devices.
*   Reality Composer is included with Xcode and is also available as an iOS and iPadOS app, so you can build, test, tune, and simulate AR experiences entirely on iPhone or iPad.
*   With Reality Composer for iOS, you can record sensor and camera data in the location where the AR experience will take place, then replay it later on your iOS device while building your app.
*   The new Reality Converter app makes it easy to convert, view, and customize USDZ 3D objects on Mac. Simply drag-and-drop common 3D file formats, such as .obj, .gltf and .usd, to view the converted USDZ result, customize material properties with your own textures, and edit file metadata. You can even preview your USDZ object under a variety of lighting and environment conditions with built-in IBL options.
*  Also:  

03.10.21
* Animatic: a preliminary version of a movie, produced by shooting successive sections of a storyboard and adding a soundtrack.
* https://boords.com/animatic/what-is-the-definition-of-an-animatic-storyboard
* The goal of an animatic is to define the timing for a piece of moving image. When used with a soundtrack, they're a quick and easy way to get a sense of a finished piece of moving image.
* Timings changes are used to create a sense of pace.
* Pre-production is the multi-stage process which happens before a film or animation comes to life.
* >  Stage 1	Concepting	Define your idea
* >  Stage 2	Scripting	Draft your story
* >  Stage 3	Storyboarding	Plan your scenes
* >  Stage 4	Animatic	Define pace & timing
* >  Stage 5	Design	Define visual approach
* >  Stage 6	Logistics	Plan the production process
* Animatics use the same images as storyboards, but stitched together in sequence and rendered as video
* Animatics are used to plan an animation, and use low-resolution images to convey timing, rather than the look and feel of the final piece.
* Animatics are quick to produce
* Animatics are a reference point
* Animatics help you make quick changes
* Animatics create consensus
* Animatics save you time (and money)


3.09.21
* TIL: https://www.studiobinder.com/blog/what-is-a-storyboard/
* Alfred Hitchcock was notorious for his 'boards' — precisely crafting the movie in his head and on the page.
* All the interesting work had already been done.
* A storyboard is a visual representation of a film sequence and breaks down the action into individual panels. It is a series of ordered drawings, with camera direction, dialogue, or other pertinent details. It sketches out how a video will unfold, shot by shot.
* Traditional storyboards are what we see above — basic pencil sketches that include detailed information like arrows for camera movement, characters, props, etc.
* There are also thumbnail style storyboards that don’t have any writing. 
* Most of the time, a storyboard is constructed to match what's already been written in the script but they can also become deeply tied to the actual storytelling process
* An animation storyboard and animatics are fundamental steps, not just to refine the specific animation and movements but to craft story beats and character behavior at the same time.
* This "graphic novel" approach was his initial guide to crafting the action, story and characters.
* ALso: https://www.studiobinder.com/storyboard-creator/
* Also: https://www.studiobinder.com/blog/how-to-make-storyboard/
* Drawing and formatting fears, technical limitations, concerns about budget — there are a lot of reasons to avoid storyboarding.
6. Mark up your screenplay
7. Determine your aspect ratio
8. Sketch out your subject
9. Draw a background - Along with a subject or character, you need a background in your image to orient viewers. Not every panel requires an elaborate background.
10. Add arrows for motion - Learning how to make a storyboard could be rephrased as: “Do you like drawing arrows everywhere?" If you want to know how to write a storyboard as a motion sequence, you can string together your individual images as a video. Then play them back.
11. Add camera movement - Adding camera movement to storyboards pre-visualizes how, when, and where the camera will move — as well as what we’ll focus on. When we add camera movement to our storyboards, we’ll select shot size, shot type, and lens details as well. Yes, just like you drew arrows to show the action, you’ll need arrows to describe how the camera moves.
12. Add shot numbers
13. Rinse and repeat
14. Organize and share storyboards
* An animatic is a string of storyboard images edited together with sound to illustrate how a sequence will flow in motion. It’s a next-level technique after storyboarding.
* Edit storyboard images in an editing solution like Adobe Premiere or Final Cut Pro.
* Consider adding music tracks, sound effects and dialogue.
* Your storyboards play like a slideshow. Timing and pacing is conveyed in a storyboard sequence.
* Camera movements:
> * PANNING
> * PUSHING OUT
> * PUSHING IN

03.08.21
* TIL: https://www.zappar.com/blog/how-augmented-reality-affects-brain/
* Also: LAYERED REPORT https://d2j4z507ms5wl7.cloudfront.net/zappar_mindshare-layered-report.pdf
* List of suprise and delight use cases
01. Mobile Gaming
2. Storytelling
3. How to
4. Visualize big ticket items
5. Location-based learning
6. Task fufillment
7. Try before you buy
8. Wayfinding
9. Services info
10. Connected packaging
11. Translation
12. Education
13. Social Communication
* AR applications will evolve from one-off fun to include multi-use utility.
* We found that, across the series of cognitive function measures, the AR experiences delivered almost double (1.9 times) the levels of engagement compared to their non-AR equivalent (see Fig. 07)
* AR drives high levels of visual attention in the brain (almost double that of non-AR tasks)
* The only measure for which the AR experience was lower was ‘approach / withdrawal’ (which captures the extent to which the user wants to move towards or away from a stimulus). The lower score here may indicate the sense of surprise that occurs when people start an AR experience
* Reasons to use an AR app:
01. Status
2. Fun
3. Affiliation
4. Security
5. Control
6. Performance
* Consumers will come to expect all of the surfaces around them to be embedded with additional layers of content.
* Soon brands will start thinking differently about the space around us, as everything from objects and buildings, to everyday products and even our bodies becomes a potential trigger for content. 
* 68% of AR users believe AR would be most useful if it ‘can figure out the right information to show me at the right time all by itself’
* AR will be a key tool for assistance, helping life to flow by removing everyday friction.
* The ability to tell compelling and engaging stories will become increasingly more important as people’s brains come to expect everyday surfaces, products and packaging to be augmented.

03.07.21
TIL: https://filmindustry.network/8-gigantic-problems-film-industry-fixed/26044
* The devaluation of film as a product
* Film franchise fatigue
* Lack of government grants for short films
* Tax breaks that don't help smaller film productions
* Runaway digital piracy affecting filmmaker profits
* Lack of access to content in different markets
* Long working hours and pay issues
* Film crews not knowing their legal rights
* Also: https://spin.atomicobject.com/2020/06/28/learn-indie-game-dev/

**1. Pick a (Small) Idea**
* The best way to start learning game dev is to pick a simple idea or genre and narrow it down to the very core features it needs to be playable
* Making simple games like this is the best way to start growing
* having a completed game, no matter how small, will help you stay motivated to keep learning.
* **2. Pick an Engine or Framework**
* Game engines (like Unity or Unreal) typically come with graphical interfaces and the most built-in functionality.
* Frameworks and libraries are usually only code, written in existing programming languages
* The best advice I can give is to find the option that lets you focus the most on game development.
**3. Create the Prototype**
* Your goal is to create a minimum viable product (MVP). 
* Strip out all the features that aren’t necessary for your core mechanic or idea. 
* Don’t even worry about art or sound right now; use a basic square sprite for everything (or something equally simple).
* This not only helps you limit your game’s scope, but it also provides valuable experience in learning to make games fun.
* Your core mechanics are always the biggest contributor to how fun your game is.
**4. Find Assets**
* Sites like itch.io and OpenGameArt have lots of great resources. 
* You’ll notice that adding real assets (especially sounds) can have a huge impact on the feel of your game.
**5. Turn it into a Complete Game**
* Implement a full game loop, including winning, losing, and starting over.
* The most valuable thing you can do to become a better game maker is to finish your game. 
* You’ll be blown away by how much of a difference having a complete game makes.
* There’s nothing more motivating than having something you can share with others and get feedback on.
* One of the biggest hurdles for most people getting into game development is that they never learn how to finish a game.
* Getting used to scoping your projects realistically (so that you actually have a chance of finishing them) and pushing yourself to complete the entire game loop is a huge step towards learning to make this a normal part of your development routine.
**6. Start Something New!**
* The best way to learn to make games is to make games, no matter how simple or small. 
* Find new mechanics or ideas you haven’t tried before, come up with the most simple game that uses those ideas, and make it.
* 

03.06.21
TIL:https://medium.com/volograms/volumetric-holograms-in-xr-storytelling-next-level-storytelling-with-real-people-in-immersive-b34f3bc84ced
* Visionaries like you push the boundaries of communication.
* The difference, perhaps, between ‘storytelling’ and ‘story living’.” Luke Buckmaster — on immersive and interactive filmmaking
* People seek to be immersed, to be active participants of the stories they experience, so they can walk around and explore. Be embodied. 
* How many stories do you create or share that do not have someone in them?
*  Photography did the trick for everything static and flat from newspapers to your Instagram grid. Video, still flat, set us in motion: from films to TikTok clips. But when it comes to AR and VR, how do we bring people into our stories?
*  Sadly, when actually attempted, efforts to bring real people to AR and VR often turn out uncanny at best, making it better to stay low-key (think of video cut-outs integrated virtually in the space) than to fail trying something more ambitious — see this for a more complete analysis of alternatives.
*  Finding the right solution:
*  > Fidelity: extent to which the appearance of the virtual human is similar to a real human.
*  > Animatability: extent to which the virtual human’s movements can be changed after creation or capture.
*  > Immersiveness: extent to which the user loses the awareness that they are not looking at a real human
*  > Cost: amount of financial and other resources needed to create or capture the virtual human.
*  > Time: period needed from when the virtual human creation or capture starts until it is ready to integrate into the content.
*  https://miro.medium.com/max/700/1*c4Di2yDwGkxjnPMD_abJ9g.png
*   This means real people brought directly into digital, not in a flat way, but rather as full-3D content that can be seen from any perspective. In other words, with volumetric you can finally bring real people into your AR and VR stories, with their performances to be experienced in a completely immersive way. Volumetric video helps you create compelling stories like never before.
*   All in all, once the sequence is captured, you can integrate it within your AR and VR experiences and work with it as a normal 3D-asset. Your experience will still be compatible with your standard tools (Unity, Unreal, etc.) and the full range of devices: from the fanciest headsets to a standard smartphone with WebXR
*   The combination of so-called 6-degrees-of-freedom (6DOF) content within a long-format 3DOF production 
*   Its smart combination of this new format with 360 videos is a great storytelling option.
*   Terminal 3 — This thought-provoking piece by disruptive studio 1RIC is especially interesting for two reasons. First, it uses volumetric video to make awareness-raising pieces more compelling through next-level, emotional human interactions. Second, it uses a light-weight and low-budget volumetric capture technology.
*   https://1ric.com/terminal-3
*   

3.03.21
TIL: https://neilpatel.com/blog/creating-content-that-converts-the-step-by-step-guide/
* According to Content Marketing Institute, “Business-to-business (B2B) marketers who have a documented strategy are more effective and less challenged with every aspect of content marketing
* Step #1:  Find content ideas that are proven to convert.
* Step #2:  Optimize your copy like you would for a landing page.
* Value Proposition: A well-defined problem is half-solved. This is what propels your conversions. You can make your content highly converting when you define a specific problem and provide practical action steps to solve it.
* The value proposition is the promise of value to be delivered and the belief from a customer that value will be experienced.
* Step #3:  Craft attention-grabbing headlines.
* Also: https://unity3d.college/2017/07/26/how-to-make-games-making-the-transition-from-business-apps-and-web-development-into-gaming/
* Video games are the driving force behind many programmers aspirations.
*  In-fact I’ve spent a lot of my career working on business apps, high traffic web sites, hardware test tools, and a variety of other non-game software.  And in that time, I’ve met dozens of ‘business programmers’ who were inspired to learn the craft by video games.  Many of them also had long run deep desires to one day program their own games.  But as professional developers, with bills, families, and responsibility, they often struggled to take the dive.  A couple of them attempted to make the transition into ‘game development’, but most struggled to get started, and that’s for a good reason.
* If you learn the differences and embrace them, you can quickly take your existing skills and start building games of your own. 
* When I say embrace the engine, I mean really embrace it.  Don’t jump in with the plan to start building your game as the first project you do.  Instead, when you start out, build a bunch of very different games from samples, guides, video tutorials, or anywhere else.  Build small things that can be completed in a day or two.
* Imagine you were teach a new junior programmer your craft. 
* If you’re a web developer, what would you recommend they do first?  Build their ‘facebook but better clone’?  Or setup a simple sample page using your framework of choice?
*  Building these small games will teach you a lot. 
*  Another area I’ve seen almost everyone struggle with is basic movement. 
*  Game engines do plenty of things really well, and animation is one of the things they do best.
*  The same applies for physics.. let the game engine do the work.
*  In most programming environments, there’s a hidden loop running.  That loop is pumping messages and events to your components, making your object interactions clean and seamless, calling your web controller methods for you.  This abstraction is extremely helpful for business and web apps, you wouldn’t want to write that code yourself and you don’t need to.
*  In Unity, the engine calls methods on every gameobject that’s active in your scene, without you telling it to.
*  These methods call at different times and you need to know how to use them.  For example the Awake() method is called early in the objects lifecycle and is often used to cache references to other objects & initialize state.
*  Wait, what’s the difference between a collision and a trigger??  This is exactly the kind of thing that you want to learn early.. (triggers don’t do physics interactions like bouncing/stopping and just call code, while collisions act as you’d expect physics to do)
*  That’s because methods like Update() are called every frame.  So if your game runs at 10FPS, Update is called 10 times a second.  If it runs at 300fps, well you’ll call Update 300 times a second..
*  code is only a tiny portion of your project. 
*  you start with a scene, in that scene you can do your setup, or in many cases the scene will already be setup and ready to go.. with little to no code initialization required. That may sound disturbing.  There’s no single place of truth in code that defines how your app starts, where dependencies go or what order to initialize everything in. It’s not in code… but it is in your scene.  Your scene is where you setup these things.
*  Scenes exist for a reason, to make game development clean and quick.
*  Another big difference with game development is that engines are generally driven by a component based system.  
*  The biggest benefit of component based development is reusability.  If you develop your components to be small and generalized, you can often mix and match them on a gameobject to create the behavior you want.  Don’t expect to do this right away or in every case, but keep it at the forefront of your mind when writing your own components.
*   If you’re an advocate of solid principals, they can be very helpful.  I’d especially focus on the single responsibility principal.
*   Another skill I’ve found to be more prevalent in the web world is good use of design patterns. 
*   A simple example of this would be a knowing when to build a simple state machine instead of a giant switch statement…


  



03.02.21
TIL: https://xd.adobe.com/ideas/principles/emerging-technology/ux-design-principles-for-augmented-reality/
* Unlike virtual reality, which requires users to purchase pricey headsets in order to be immersed in an altered experience, it’s possible to experience AR on mobile.
* When it comes to building AR apps, the concept of “measure twice, cut once” becomes especially important. Before diving into AR design and development, it’s important to have a clear answer to the question, “What do I want to achieve with this AR app?” 
* AR in an app should be a layer of added value that reduces the time required to complete tasks.
* Offer AR features only on capable devices.
* The great thing about AR is that it’s not limited to the device screen. The device screen becomes more like a window that we use to see the world.
* Set inital expectations for space required. Nice diagram: https://xd.adobe.com/ideas/wp-content/uploads/2019/12/space-559x550.jpg.webp
* Since you will integrate an AR design solution into the users’ environment, you want it to feel as natural as possible
* Sometimes users can get too immersed in an AR experience, so they ignore physical objects around them. As a result, they can bump into objects or people. To prevent such behavior, you need to build in reminders for users to check their surroundings.
* it’s recommended to design experience that guides users to move forward, not backward.
* Users will hold mobile devices while interacting with your product. Thus, make comfortable designs to prevent physical strains. For example, holding a device at a certain distance or angle for longer periods can be fatiguing. To prevent causing fatigue, consider keeping sessions short, and add periods of downtime to help users get relaxed
* People tend to spend more time in experience if they are afraid to lose their progress. 
* Let users pause or save their current progress in the AR app. Make it easy to continue an experience where they left off, even if they switch their physical location.
* Usability testing should be a critical step in the product design process.
* AR experiences should be designed to require as little physical input from users as possible. 
* A good AR experience immerses users into interactions. It only happens when people believe that what they see on the screen is real.
* To help users believe that the AR world is real, make sure your app updates the scene 60 times per second, so objects don’t appear to flicker. 
* Audio is a multipurpose tool. Sound effects can improve the usability of a product. For example, it’s possible to add a sound effect to confirm that a user picked up a virtual object. Background music can also help envelop people in the virtual world by creating the right mood.
* Many users have never experienced an AR environment before. When users encounter their first AR experiences, they will need guidance on how to interact with it. Onboarding plays a key role in creating a great UX.
* Show instructions or tips on how to perform specific things in the context of actual interactions. 
* For example: when a user is interacting with an AR game, provide the user with steps and tips that they can use as they progress through various levels in order to break apart the information.
* Use a combination of visual cues, motion, and animation to teach users. Illustrate and use in-app experiences as much as possible.
* Use familiar UI patterns
* , take advantage of your users’ existing knowledge. A majority of mobile users know how to tap, drag and swipe objects. And you can use those interaction patterns in your UI. By doing that you won’t have to teach the user a whole new way to perform simple tasks.


03.01.21
TIL: https://www.artistsnetwork.com/art-techniques/composition/telling-a-story-on-canvas/
* Sometimes the story starts on a single canvas or sheet of paper and doesn’t end until there is a gallery full of paintings, a suite of drawings, a set of illustrations, a series of comic strips or an entire graphic novel.
* “Narrative is like an infrastructure that you can come back to and get more and more out of it each time. Each work turns out rich by itself, but there’s also something to reach for,” says artist David Sandlin. He is also an adviser for second-year graduate students in the Illustration as Visual Essay program at the School of Visual Arts, in New York City.
* discovering what is integral for all artists to discover — the kind of artists they want to be and what form their work will take
* “There is something about communicating visually that is incredibly powerful, but sometimes the words seem overwhelming. I often start with images, building the story from the images I create. That way, the viewer can have their own personal interpretation.”
* Even if they are not aware of it, visual artists often develop some sort of narrative in their work. 
* At its root, it is about communicating and connecting with the viewer, which many artists aspire to do.
* Michelangelo is one of the greatest artists in history. [Every] work he produced was informed by a story. Working in an unclear manner with no effort to reach your audience can be problematic,” says J.P. Peer,
* There seems to be an undeniable affinity between figurative and representational artwork and the presence of a narrative.
* What can differ is if it is one where fantasies come to the forefront, or it is steeped in representational realism. 
* Also, https://medium.com/conscious-paradoxalism/the-role-of-storytelling-in-the-visual-arts-70717a2f40e8
* Once upon a time, the majority of humanity was illiterate. 
* You had your storytellers, true, but people are very visual creatures.
* Catholic churches are full of images for exactly that reason. Statues and paintings told the stories of the stations of the cross, the conversion of Saul to Paul, and other biblical stories
* If you can read and create images in your own imagination (note the word “image” in “imagination”), you don’t need someone else’s images to help you understand the story.
* We have become woefully ignorant of the foundational stories of European civilization — and we haven’t made up for it in the least by becoming knowledgeable of the foundational stories of other civilizations.
* It’s not uncommon to have to tell people the stories behind these paintings. It’s also not uncommon to hear people say that paintings like these are “unusual.” This is how foreign storytelling images have become. 
* We are at a point where the art has ceased telling stories, our schools have ceased telling stories, and our culture overall has bought into the cult of originality to such an extent that we don’t see a great many films or TV shows depicting these stories. 
* There is a real opening in the arts for returning to storytelling. 
* f you look at the poem I wrote, you will note that I integrate knowledge we have of the Minoan empire into the story of Europa. That makes the mythology more rooted in historical reality. There is now a dialogue created among the painting, the original myth, history, and anthropology within my poem.
* This is the power of images in the arts. 
* The arts are able to do this by concentrating our attention through the concretization of our concepts as created by the artist.
* Realistic photos or film cannot reform our brains the way art can, even if the stories they tell do so in other ways entirely.
* 

5.28.21
* TIL: https://www.lamasatech.com/blog/creating-digital-exhibitions/
*  we’re seeing a total decline in visitor numbers since the 2016-2017 year. In fact, the National Portrait Gallery is down 11% in visits and the National History Museum is down 14%. 
* It’s all about curating the right technologies for your museum guests
*  The guests point the device at certain museum sculptures, paintings, and other artefacts, and are able to learn more about them from where they are standing. 
*  The device is also helpful for navigating the large museum. 
*  there is a variety of digital screen-based activities all in a room within the large gallery
*  Some activities require physical movement in order to operate
*  These activities include: virtual painting, collaging, researching artists, front-camera self-portraits with editing capabilities, virtual pottery, using AI to draw and match shapes to items within the gallery system
*  The Museum of Modern Art (MoMA), in New York City, gives patrons “an unauthorized gallery concept aimed at democratizing physical exhibition spaces, museums, and the curation of art within them.”
* For as little as $8, you can view the exhibit with a VR viewer to take in Wonder. 
* Digital technology is only getting more and more museums on board as they attract a younger crowd.
* Also, https://www.sciencebuddies.org/science-fair-projects/project-ideas/compsci_p058/computer-science/interactive-toy-raspberry-pi
* You an use magnets to drive interactions with a Raspberry Pi


02.27.21
TIL:https://blog.westerndigital.com/driving-immersive-experience-virtual-augmented-reality/
* AR & VR = "creative implementations" of the technology in gaming, shopping, entertainment, and medical procedures
* VR: create the illusion that you’re in an utterly new world.
* AR: overlay digital information and other content onto a real-world
* there are demands for optimal display resolutions and capabilities that go far beyond what’s necessary when viewing a smartphone at a normal distance
* make very dynamic changes to the displays in real time, all at levels of detail and complexity that have never been required before by mainstream applications
* technology in those products simply wasn’t fast enough to meet the extremely high requirements that a good VR or AR experience demands—especially when you incorporate the need to react to how you move around in real time
* it’s absolutely essential to make these head-mounted displays as light as possible
* Consumers are going to be looking to purchase smartphones that can deliver immersive, compelling augmented reality experiences, so product designers need to plan accordingly.
* Looking forward, we can expect to see even higher-resolution displays, faster response time, and significantly stronger computing horsepower in even smaller, lighter weight head-worn products
* Also, https://www.theverge.com/2020/8/20/21377620/netflix-stranger-things-immersive-theater-drive-into-experience-location
* drive-into experience
* transforming a series of buildings in downtown Los Angeles into what is effectively a cross between a theme park and a live theater show. 
* You won’t have to leave your car, but there will be moments when you can stop to watch various actors in scenes that happen concurrently, in the style of influential immersive theater productions like Sleep No More. (Realistically, it’s probably more like your standard haunted house or walk-through theme park experience.)



4.26.21
TIL: https://www.wired.com/2015/03/disney-magicband/
* If you’re wearing your Disney MagicBand and you’ve made a reservation, a host will greet you at the drawbridge and already know your name---Welcome Mr. Tanner! She’ll be followed by another smiling person---Sit anywhere you like! Neither will mention that, by some mysterious power, your food will find you.
* Their MagicBands, tech-studded wristbands available to every visitor to the Magic Kingdom, feature a long-range radio that can transmit more than 40 feet in every direction.
* The hostess, on her modified iPhone, received a signal when the family was just a few paces away. Tanner family inbound! 
*  it all worked seamlessly, like magic.
*  Walt Disney borrowed against his own life insurance to pay for Disneyland’s original design, and according to friends and family, he never seemed happier. It was his sandbox. 
*  The MagicBands look like simple, stylish rubber wristbands offered in cheery shades of grey, blue, green, pink, yellow, orange and red. Inside each is an RFID chip and a radio like those in a 2.4-GHz cordless phone. 
*  Part of the trick lies in the clever way Disney teaches you to use them---and, by extension, how to use the park. 
*  Then, in the weeks before your trip, the wristband arrives in the mail, etched with your name—I’m yours, try me on. For kids, the MagicBand is akin to a Christmas present tucked under the tree, perfumed with the spice of anticipation. For parents, it’s a modest kind of superpower that wields access to the park.
*  If you sign up in advance for the so-called "Magical Express," the MagicBand replaces all of the details and hassles of paper once you touch-down in Orlando. 
*  Every new experience with technology gently nudges our notions of what we’re comfortable with.
*  Just tap your MagicBand at the gate and swipe onto the rides you’ve already reserved. If you've opted in on the web, the MagicBand is the only thing you need.
*  Its amazing how much friction Disney has engineered away
* For Disney, the MagicBands, the thousands of sensors they talk with, and the 100 systems linked together to create MyMagicPlus turn the park into a giant computer---streaming real-time data about where guests are, what they’re doing, and what they want.
* Disney is thus granted permission to explore services that might seem invasive anywhere else. 
* Disney shrouds its creative process in secrecy. 
* Though the team behind this sprawling platform eventually swelled to more than 1,000 people, the idea started years ago with a handful of insiders.
* Meg Crofton, then president of Walt Disney World Resort, told them to root out all the friction within the Disney World experience. “We were looking for pain points,” she says. “What are the barriers to getting into the experience faster?”
* “They came back with a drawing of the Magic Kingdom without turnstiles,” Crofton says. But, she adds, there was a “domino effect in making one decision.
* Within the company, this cascade of new technologies, and the dream of overhauling the park, thrilled some and threatened others, who fretted over the sheer complexity of it all.
* Nike was using it in virtual events like the Human Race, a global, virtual 10K run that used wearers’ pedometer data. What if Disney did something like that.
* They assembled Frankenstein-like mock-ups using spare parts cribbed from hardware catalogs and torn-down gadgets.
* Great swathes of MyMagicPlus—the MagicBands and their readers, along with pieces of the web portal for making ride reservations—already worked. The bands themselves had been designed, as had the kiosks that would light up with a pleasing chime anytime you swiped.
* Disney was adamant that the band’s design reinforce two key values: Everyone is equal in the park, and everyone is welcome.
* This was represented by the single band with a tearaway option that fit every wrist.
* It took one engineer six months to get the tear-away channel just right.
* The design has a novel and clever cue: Simply touch the circled Mickey icon on the band to the circled Mickey icon on the reader. When everything works, the reader flashes green and emits a pleasing tone; if something goes wrong, it glows blue—never red. Red lights are forbidden at Disney, as they imply something bad happened. Nothing bad can happen at Disney World.
* What followed was two years of grinding work transforming a scripted prototype into a real-world performance, then another 18 months rolling it out in the park. 
* koan: a paradoxical anecdote or riddle, used in Zen Buddhism to demonstrate the inadequacy of logical reasoning and to provoke enlightenment.
* You make people happier not by giving them more options but by stripping them away.
* “The whole system gave Disney a way of understanding the business,” says Franklin, who stepped down last July as Disney’s executive vice president of next-generation experience. “Knowing we need more food here, how people are flowing through the park, how people are consuming the experiential product.”
* It also allows Disney to optimize employees. The goal was to create a system that would essentially replace the time spent fiddling with payments and tickets for moments of personal interactions with visitors. The MagicBands and MyMagicPlus allow employees to “move past transactions, into an interactive space, where they can personalize the experience,” Crofton says. What started as a grand technology platform has inevitably changed the texture of the experience.
* “Walt Disney World is vast. There’s more to do than you could do in a month,” Staggs says. “That choice is overwhelming.”
* There are missions in a vacation,” Staggs says. In other words, Disney knows that parents arrive to its parks thinking: We have to have tea with Cinderella, and where the hell is that Buzz Lightyear thing, anyway? In that way, the park isn’t a playground so much as a videogame, with bosses to be conquered at every level. The MagicBands let you simply set an agenda and let everything else flow around what you’ve selected. “It lets people’s vacations unfold naturally,” Staggs says. “The ability to plan and personalize has given way to spontaneity.” And that feeling of ease, and whatever flows from it, just might make you more apt to come back.
* The MagicBand contains sensors that let guests swipe onto rides and allow Disney to pinpoint their location. At Be Our Guest, they’re what enable the radios in the table and ceiling to triangulate your location so your server can find you. If Disney decides to install those sensors throughout the park, a new world of data opens up. They could have Mickey and Snow White find you. They might use the park’s myriad cameras to capture candid moments of your family—enjoying rides, meeting Snow White—and stitch them together into a personalized film. (The product teams called this the Story Engine.)
* But they might also know when you’ve waited too long in line and email you a coupon for free ice cream or a pass to another ride.
* And with that, they’ll have hooked the white whale of customer service: Turning a negative experience into a positive one. 
* “This is about the experiential Internet. The guest doesn’t need to know how it happened. It’s about the magic of the food arriving.”

These are the experiences that many more designers will soon be striving for: invisible, everywhere, and, in a word, mundane. Which is its own kind of magic.

02.25.21
TIL: https://docs.aws.amazon.com/lex/latest/dg/ex1-sch-appt-create-bot.html
* Bots have an intent - that's the job to be done
* There are muliple ways to phrase things (synonyms)
* You need a "sorry, I didn't understand that" unhappy path to start
* You can caputure selections and freetext data to improve the experience
* You vesion the conversation experience just like any other software
* You can use lambdas and models to enrich the conversation
* Also: https://www.ucf.edu/news/6-things-know-themed-experiences/
* A themed experience tells a story by creating an immersive narrative environment that is based on a popular book or film or an original story.
* Not just a theme park, retail spaces, restaurants, museums, libraries, zoos and aquariums can all fit into this category — as long as they have created unique, themed environments that guests can explore.
* http://www.inparkmagazine.com/what-should-themed-experience-graduates-know-say-and-do/
* To have a successful career in the themed entertainment industry, students need to know how to collaborate within interdisciplinary teams, by knowing what other team members do, and having empathy for other viewpoints and perspectives.
* From this advice and insight, we begin to form a sequence of study based upon four tenets.
* > #1 – Context.
* > #2 – Skills, aesthetics and creativity.
* > #3 – Collaboration.
* > #4 – The industry.
* https://www.whitewaterwest.com/en/how-we-work/
* Process:
* > Understand
* > Design
* > Build
* > Maintain
* > Optimize
* Immersive Experience Studio
* Create mid-sized themed experiences designed to engage guests for 1-4 hours — from design space and guest flow to timing and themed interaction.
* Also: https://weareimmersive.co.uk/blog
* 

02.24.21
TIL: https://www.bu.edu/jlengel/desint.html
* Here's a starter process for designing an interaction
* > Define the ideas your client wants to communicate.
* > List the basic elements of your project:
· videos	· sounds and music
· photographs	· drawings and designs
· text articles	· voice
* > Plan your project on paper.
· Storyboard	· Diagram
· Flow Chart
* > Choose the appropriate programming tools:
· ClarisWorks	· Persuasion
· HyperCard	· Astound
* Also, https://en.wikipedia.org/wiki/Adobe_Persuasion
* Adobe Pesuasion was an interactive presentation tool - a predecessor to powerpoint
* https://winworldpc.com/product/astound-presentation/70
* Astound is a powerful multimedia presentation authoring program originally for the Mac and Windows. Astound gives you the power to create presentations that persuade, inform, and entertain. - competed and succeeded by Powerpoint
* Also, https://www.redsharknews.com/the-rise-and-fall-of-the-interactive-cd-rom
* CD-ROM came into the world in the early 90s, just before the internet had really taken off 
* The emerging CD-ROM industry saw itself as separate from the fledgling computer games industry (still working mostly on floppy disc) and very different from the movie business. 
* It couldn’t deliver full screen, full motion video, but it could give you decent audio and lovely graphics with lots of things to click on to lead you to other screens. 
* CD-ROM seemed to be particularly popular on Apple Macs. Macs were still (just about) in ascendance, and HyperCard (a basic programming tool supplied free with Macs) made it relatively easy to author a disc. 
* There was a notion among some filmmakers that this was, somehow, the future of movies.
* The big problem with CD-ROM was that the technology could not deliver anything close to full screen movies. 
* One hugely successful release showed the way forward, and that was the HyperCard-based single-player adventure/puzzle game Myst, originally launched for the Mac in 1993. In six months it sold 200,000 copies, after porting to Windows it went on to sell well over 6 million. 
* Of course, out of the various notions of what CD-ROM was for, games would end up being the great winner, particularly after the rise of the dedicated games console.
*  DVD arrived in the mid 90s to takeover as the premium format for movies, and most of the educational ambitions of the interactive CD-ROM would be subsumed by the internet. 
*  https://en.wikipedia.org/wiki/HyperCard
*  HyperCard is a software application and development kit for Apple Macintosh and Apple IIGS computers. It is among the first successful hypermedia systems predating the World Wide Web.
*  HyperCard combines a flat-file database with a graphical, flexible, user-modifiable interface.[2] HyperCard includes a built-in programming language called HyperTalk for manipulating data and the user interface.
*  This combination of features – a database with simple form layout, flexible support for graphics, and ease of programming – suits HyperCard for many different projects such as rapid application development of applications and databases, interactive applications with no database requirements, command and control systems, and many examples in the demoscene.
*  Also, hypertalk https://en.wikipedia.org/wiki/HyperTalk
*  HyperTalk favored natural-language ordering of predicates over the ordering used in mathematical notation.
*  HyperCard's primary user interface concept was the card.
*  The graphical layout of the card was created using the mouse by placing various elements on the card, such as text fields and buttons.
*  Containers of a given type were also available as collections with a pluralized version of that container type as its name—the collection of the fields on a card was card fields. 
*  A notable feature of the HyperTalk container model was its handling of text. Every collection of text, whether a literal string in a program or text typed into a text field, was itself considered a container with multiple collections of containers within it
*  HyperTalk used an object-oriented concept for calling scripts, with objects in the stack sending "events" as messages that would be processed by handlers that declared their interest in receiving the events using the on syntax. For instance, most GUI containers would send the mouseDown message when the mouse button was clicked down, and then a mouseUp message when it was released .
*  Messages for events were first sent to the script in the object that created the even
*  One unique distinction between HyperCard's programming language HyperTalk and seemingly similar languages like AppleScript was that HyperTalk scripts were more lenient in what input they accepted
*  Although the HyperTalk language languished just like HyperCard itself, it received a second lease on life through its plugin protocol, so-called External Commands (XCMDs) and External Functions (XFCNs), which were native code containers attached to stacks (as Macintosh-specific resources) with a single entry point and return value.
*  Also, https://en.wikipedia.org/wiki/Inform#Inform_7
*  Inform is a programming language and design system for interactive fiction originally created in 1993 by Graham Nelson
*  Here's an example game in Inoform 7 https://en.wikipedia.org/wiki/Inform#Example_game
* Inform 7 http://inform7.com/


02.23.21
TIL: PP 42-49
* Why bother with interativity?
* Competitive advantage of computer-driven content (by nature of the conversation, computers are made for interactviity)
* Revolutionary - most of the work in this field has never been done. It's a field for explorers and pioneers.
* Power to influnce - due to the natuer of engagment, people are part of the equation and they can be incluenced by the stories you tell
* How interactive story telling is the same and different from games
> * Both tell stories, but games are not very good at stories
> * Games have an objective and competition
> * Games can be replayed and have the same experience, interactive stories are based on choice so they are "created" each time 


Interactive Storytelling - Crawford
2.22.21
TIL: PP 37-42 Interactive Storytelling - Crawford
* The three determinants of interactivty: speed, depth, and choice.
* The faster the feedback turn time, the more interction is possible
* Depth refers to how much mental exertion is required to focus on the activity / task
* Choice - the optins a player / user has. It's not important the number of choices as much as the quality of choices
* Functional significance means to what degree the choice sastisfies a users needs or goals
* Functional bloat is adding functionality that is not functionally significant to a user
* Its important to note that what is functional bloat to one user is functionaly significant to another user.
* You have to balance this for all players.
* ALWAYS ASK, WHAT DOES A USER DO? WHAT ARE THE VERBS?

02.21.21
* TIL: https://www.youtube.com/watch?v=MtiUx_szKbI
* Targets are items that can be watched or listened for by the application 
* Recognition of targets triggers a behavior
* Images, video, and other content can be presented as a behavior when a target is recognized
* Targets work much like QR codes
* Also, https://www.lynda.com/Unity-tutorials/Welcome/661757/743009-4.html
* Interactivty in Unity is based on scripts
* You can get UNITY here: https://unity3d.com/get-unity/download
* Animation is a tactic to increase interactivity
* You can use proximity as a trigger too
* You can add interfaces into scenes to increase interactivty

2.18.21
TIL: PP 33-37 Interactive Storytelling - Crawford
* People create mental model of the world, this is connected to many different external pieces = their network of understanding of the world around them
* Artists of other mediums can affort to not listen to their audience, but due to the nature of interactivity it is important to reveal the discrepencies between the artists vision and the audience's network
* It is also important that the artist has a vision so that the experience is unified
* Not all feedback needs to be incorporated or the final result will be come muddy, and useless
* And the artist can not solely rely on their ego and vision, elsewise it will miss the mark
* Example of the king taking all the resources for himself, it doesn't work out. He needs to do what's best for the people.
* It is the artists responsibiity to meet each player head-on and make sure they get it.
* Iteractivity isn't binary, or boolean, there is a spectrum of interactivty
* It is a numeric quantity like weight
* Sex, for example is on the high end fo that scale. It's the deepest interaction two people can have.
* Three factors determine the degree of interactivity in storytellng: speed, depth, and choice.

4.17.21
TIL: PP 30-33 Interactive Storytelling - Crawford
* Second-person insight - the ability to experience the story from another's point of view
* Most great artists have a technical inight that allows them to produce great works
* To produce great interactive stories you need to understand how your player / participant / user will interpret and react
* This is more complex than an entertainer who just needs to know which jokes are funny for an example to an audience
* Interactive storytelling has to anticpate reaction to a whole universe of things.
* This involves being able to think like that second person, even when they may think very differently from you.
* Repetition is the way to enforce learning. There may need to be many different ways of saying the same thing to get to all members.

02.16.21
TIL: PP 28-30 Interactive Storytelling - Crawford
* Spatial thinking and reasoning is part of a story
* Place = Stage
* Stage is a general place where the story takes place
* It need not be connected to another stage in the story
* It need not be overly well defined, unless its important to the interaction between the people in the story
* Time is even less important, it's difficult for people to process the passage of time so you can break the rules and/or pay less respect to the laws of time in a story
* Interaction can be defined as listening, thinking, and speaking
* Computers "listen" for input like via the mouse or keyboard
* Computers "think" by processing information
* Computers "speak" by showing words on the screen
* The above ar some examples of how computers act
* Two parties must both do the interaction steps for it to be an interaction, otherwise it's one-sided, a reaction


02.15.21
TIL: https://en.wikipedia.org/wiki/Sensorama
* The Sensorama, from U.S. Patent #3050870
* The Sensorama was a machine that is one of the earliest known examples of immersive, multi-sensory (now known as multimodal) technology.
* Sensorama was introduced in 1962 by Morton Heilig.
* Mortin Helig was a pioneer in Virtual Reality (VR) technology and filmmaker.
* The Sensorama game gave the player the experience of riding a motorcycle on the streets of Brooklyn. The player felt the wind on their face, the vibration of the motorcycle seat, a 3D view, and even smells of the city.
* Also: https://www.uschefnerarchive.com/mortonheilig/
* Video: https://vimeo.com/246184069


02.14.21
Read pp: 24-28 https://www.amazon.com/Chris-Crawford-Interactive-Storytelling-2nd/dp/0321864972
* Learned about the progression of support of images 
* Learned about how much / pervasive images are in our technology experiences

02.06.21
TIL: https://learn.g2.com/immersive-experience
* Some industries that are prime to leverage immersive tech:
> EComm
> Architecture and design
> Engineering, maintenance, and repair
> Health Care
> Travel
> Real Estate
> Education and training
