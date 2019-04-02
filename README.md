https://www.usenix.org/conference/srecon19americas/presentation/kitchens


# Thanks so much
for your interest in this presentation! I hope to cover some of the nuance of the content here to balance out what might at first glance seem provocative.

It’s really hard to introduce these concepts without sounding dogmatic! It’s really easy to interpret this stuff as “We’re all doing it wrong and need to throw out everything!”

That’s not the point of this talk! What I want to point out is that the tools and methods we have aren’t designed to solve every problem.

And that’s ok! There is no panacea.

What I want to point out is how we can start to look at the pitfalls and blind spots that often go ignored in incredibly subtle ways. We need to find the stuff that’s actually making us better, and highlight those things. This is different for every organization which is what makes it so hard to talk about.

The point of this talk is to encourage a holistic view of incidents (and when we aren’t having incidents). BOTH failure and success and everything in between that happens during normal, everyday performance.

I want us to go beyond the fashionability of SRE and really think about the things we’re doing all the time that contribute to reliability which are often invisible.


#### Should we stop using SLOs and Error Budgets?
No, they’re super useful! They’ve transformed what we do and how we think about reliability! However, they aren’t designed to address every problem. There are a lot of weak signals on the human side of reliability that we can’t detect this way, and we should be paying attention to those by compassionately talking with people and interviewing them.


#### Should we stop measuring availability?
No! Measuring availability can tell us a lot, but *reporting* on it at a product level can facilitate some pretty nasty incentives that ironically end up harming availability in the long term. 


Where measuring availability becomes really useful is between services behind the edge. We interact with software to form a sociotechnical system. Let’s say there are five services in a call span—each of those availability numbers is the start of a conversation about expectations between teams and services.


#### Should we stop creating action items during postmortems?
No, but know that action items are not the point of doing incident investigations. Learning is the goal! Don’t incentivize the number of action items. Incentivize people working together to share expertise and learn.




# References and materials for "How Did Things Go Right? Learning More from Incidents"

http://resiliencepapers.club

http://safetydifferently.com

https://www.snafucatchers.com

http://stella.report


##### The HOP Mentor - Andrea Baker
https://www.thehopmentor.com/


##### The Field Guide to Understanding 'Human Error' - Sidney Dekker
https://sidneydekker.com/books/


##### Pre-Accident Investigations - Todd Conklin
https://preaccidentpodcast.podbean.com/


##### Language Bias in Accident Investgiation - Crista Vesel
https://lup.lub.lu.se/student-papers/search/publication/2971193


##### Maps, Context, and Tribal Knowledge - J Paul Reed
https://lup.lub.lu.se/student-papers/search/publication/8966930


##### Trade-offs Under Pressure - John Allspaw
https://lup.lub.lu.se/student-papers/search/publication/8084520


##### Debriefing Facilitation Guide
https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf


##### Lund University Human Factors & Systems Safety programme
http://www.humanfactors.lth.se/


##### Cognitive Systems Engineering Laboratory at Ohio State University
http://csel.org.ohio-state.edu/


# Attributions, Thanks, and Inspirations
If only every conference talk could be prefaced with "almost all of this is none of my original thoughts." :)


Thanks to my colleagues Nora Jones (@nora_js), Lorin Hochstein (@lhochstein), Ashish Jotwani, and Dave Hahn (@relix42).


'Recovery > prevention' - Aaron Blohowiak (@aaronblohowiak)


Much of the groundwork of resilience engineering in software has been introduced by John Allspaw (@allspaw), Richard Cook (@ri_cook), David Woods (@ddwoods2), and Johan Bergstrom (@bergstrom_johan).

- https://www.devopsdays.org/events/2018-seattle/program/john-allspaw/
- https://m.youtube.com/watch?v=2S0k12uZR14
- https://m.youtube.com/watch?v=7STcaWjJoww
- https://m.youtube.com/watch?v=Pb_zYs8G6Co


"The nines don't matter if users aren't happy" - Charity Majors (@mipsytipsy)


'failure is no longer interesting' has got to be something Todd Conklin has said before.


The bit on 'a perfect storm' was paraphrased from Andrea Baker (@thehopmentor).


'probably fine' and many dots connected by Andrew Clay Shafer (@littleidea)
- There is no Talent Shortage https://www.youtube.com/watch?v=P_sWGl7MzhU


Comments on demonstrating the inefficiencies of blameful language from Matty Stratton (@mattstratton)
- www.arresteddevops.com


Any talk Bridget Kromhout (@bridgetkromhout) has ever given, but especially 'Containers Will Not Fix Your Broken Culture'
- https://m.youtube.com/watch?v=hALDyVBVVz0


Many inspirations from the Greater Than Code podcast 
- http://www.greaterthancode.com


Diagrams/models based on work from Sidney Dekker (@sidneydekkercom), Erik Hollnagel, and Kelvin Genn (@kelvingenn)
- http://www.safetydifferently.com/why-do-things-go-right/

