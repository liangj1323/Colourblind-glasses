# Colourblind-glasses
My file for colourblindness glasses:

I will make the onshape and the PCB design here.

Onshape when exporting parts I don't know if they worked properly, so there is the main one, but 3 extra ones which are the three parts that the main one are made out of in case the main one is actually only one of them

I also multi uploaded the Kicad files in case it didn't work!

Here is a detailed explanation of the essay this idea is based on the competition me and my team used this for!

A quick introduction
Colour vision deficiency (CVD or more commonly referred to as colour blindness) affects approximately 8% of men and 0.5% of women worldwide, which totals 300 million people in total - more than 4 times the population of the UK. The most common form of this is called red-green CVD, where the person finds it hard to tell between brown and orange shades.

How we come in 
Our concept is simple, yet original – active OLED-based glasses that use real-time image processing to help colour separation for most types of CVD. Instead of using colour filters like other brands, these glasses trick your disability into the opposite way!
Our idea helps people with CVD but can also help other communities. This problem is currently a large but unseen problem in our society. There are so many people in the world with this disability: nearly 10%! When our idea works, colourblind people’s lives will get better, and they can see the world correctly – this disease makes all sorts of simple tasks from reading colour-coded maps, to identifying ripe fruit more difficult.

Looking into CVD in detail
CVD is a genetic condition: this means that this condition is inherited from family although it can be a cause of other diseases, ageing, drugs or medication. To understand how CVD ‘works’ we can look at how the normal eye works.
When light enters the eye, it triggers loads of photoreceptor cone cells that detects different colours. Normal colour vision is when your cones are used to the right wavelength (e.g. red is 560nanometers). The three cones (RGB) are sensitive to their colours so when you see a certain colour, it triggers the ratio of activation relative to all the cones and will send that signal to your brain - since we are adapted to this, we can see more than 6,000,000 different colours.
Most CVD occurs when there is an overlapping sensitivity between the cones, causing your brain to muddle up the different hues which become indistinguishable. E.g. for red-green CVD, this is caused by the overlapping sensitivity between the red (L-cone) and green photoreceptors (M-cone).

How do we fix this?
Filtered glasses are often inaccurate and unreliable, but we fix this problem. On both sides are cameras that will transmit information to a mainboard (Raspberry Pi-0-2W mainboard) which has 512MB of memory, Bluetooth, and several ports to connect to cameras, etc. We can implement one in our glasses’ frame or place them in a pocket nearby.
The processor runs a real-time colour correction algorithm designed specifically and transmits the information onto the OLED lenses. This display will create an overlay aligned with the real world. Here is our process in a nutshell.
Firstly, the cameras continuously record the user’s surroundings. The camera is aligned with the user’s sight and peripheral vision, so the image later shown can align with reality. The mainboard applies our colour correction algorithm which consists of it simulating how a colourblind viewer perceives the scenes using Brettel or Machado. Then it modifies the image to singular pixels of hex colours to increase the distance between colours which then is outputted as a different colour. At this step, other factors can be inputted like the brightness of the outside world to be factored to make the output better. For example, for red-green CVD, reds are shifted slightly towards magenta, and the saturation can be increased.
The corrected image is then combined using the hex values and unchanged pixels are deleted, this information is transmitted and then displayed on transparent OLED lenses. OLED lenses work best since they produce high contrast, so they are ideal for overlaying enhanced colour information without blocking the user’s natural view.
Why us? 
Using OLED-based glasses to fix disabilities is a completely empty market. The only ‘famous’ use of colour-blindness glasses is EnChroma, but they only help 4/5 of people and use passive filters that remove specific wavelengths of light. As well as only helping some, it can also be unreliable and cannot dynamically adapt to different environments. 
Our product will be cheaper than EnChroma’s (see below). We solve all the problems with the other companies using similar technology. E.g. take the Apple Vision which uses transparent OLED technology. Their technology is bulky and uncomfortable to wear – ours are lightweight: all parts of the glasses are discreet and made to be extremely similar to normal glasses (see diagram 1).
All the data of our glasses is also locally handled, unlike Ray-Ban’s glasses. Executing this idea might not be easy - we would have to offer some insurance policy. There are no big companies which are in the position who could copy this, as this would not fit their style. No part of this clash with any existing copyrights/patents, since EnChroma only has patents on filters. 
Our profit would be about £35.05 per pair or a 30% profit margin
 
We are cheaper than competitors like EnChroma, at least £50 cheaper or even 2 times!
Further research
Firstly, we want to explore a simpler extension to the glasses. On the Raspberry Pi module we are using, there is already Bluetooth. We can make the Bluetooth connect to an app. This means that users can control their details of how to customize the glasses’ functions to their needs. 
Excluding CVD, there are other big diseases that we could also be helped with our glasses. These include visual agnosia, ADHD, dyslexia and CDS. The main idea is that if we swap out our camera for a Raspberry Pi AI camera or embed a LLM into the mainboard, our glasses have the capabilities to name objects. It could reconfigure how sure it is on each object and help with these diseases by visually labelling.
This would work best for visual agnosia, which is when your brain can’t link what you see a certain word, and needs that ‘push’ to remember. We could make a label to remind you so you can instantly know what said object is.
This also helps with other diseases as well: ADHD can be helped by training your attention with cues and colour-coded systems; dyslexia could be helped with labels in the form of emojis or pictures; and CDS can be helped by labelling things in a cluttered environment to lower the cognitive load of the brain. All these ways to help other disabilities are based on one core idea, which would link to our Bluetooth idea.
Our final idea is more ambitious. Since we have so many different usages, what if instead of different glasses, we used different lenses? The idea is that each lens would connect to the main frame using some magnet slide. It would then transmit to the mainboard its use and the mainboard could switch to be different functions (see below). This means we could sell our frame for £85 and sell the lenses separately. This would boost our sales while keeping our cheap price. We can then run more promotional events (e.g. buy 4 lenses get 1 free). This would boost our sales, meaning we could sell more to earn more profit since our profit margin isn’t that big.


<img width="454" height="246" alt="image" src="https://github.com/user-attachments/assets/42fc293d-1ba0-4367-b30f-98bfedc9045c" />


<img width="807" height="467" alt="image" src="https://github.com/user-attachments/assets/88cb426c-35fa-4475-8840-0454e2560ea4" />

<img width="1503" height="747" alt="image" src="https://github.com/user-attachments/assets/9ab336c2-8d19-49c9-b006-97c95e809eb4" />





 


Sources:
https://docs.google.com/document/d/1gaUPH-cYD800do3NKkF9AClcoWa02SfzEE7OkMBLKK0/edit?usp=sharing
