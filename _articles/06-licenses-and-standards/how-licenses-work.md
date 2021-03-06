---
layout: page
title: "How licenses work"
module: "6.1"
date: 2021-04-07 14:05:56
time: "30 min"
following: _articles/06-licenses-and-standards/oh-licenses.md
summary: "And how they can work for your project"
prereq: "Have completed all previous sections and modules"
materials: "Pen or pencil and paper"
---
<p align="center">
<img src="https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/img/work_in_progress_banner.svg" width="80%"/>
</p>
* TOC
{:toc}

### Contents

- Copyleft and non copyleft licenses

---

- Licenses and patents

The current patenting system was created in XXX in Italy to protect the work of artisans. With an initial good proposal to value and foster creative work, patents have become instruments to create protectionism and monopoly for companies/players with the deepest pockets. This ends up stifling innovation and slowing down technological and scientific progress. Let’s make this clear with a couple of examples: 
  - The cost of patents. How much time it takes to get them. How everything needs to be a secret before the patent is granted.
  - How kodak sat on the patent for the digital camera, and did nothing until it expired. The first digital cameras were from Fuji I think.
  - Add Nathan Siedler TED talk on Sparkfun and open hardware.


---

- Elements of licenses (attribution, report back, etc)

---
- Licensing hardware design, licensing documentation, licensing software

When we consider open source hardware projects, licensing has a special angle, as hardware projects can be composed of different “domains”, each having its pertinent license, we are going to cover this in more detail, but here is one example to get you thinking about this: Your project may be composed of 3D printed parts, some electronics and software to control those electronics. In this case, your project would need three licenses: One for the software code and for the 3D designs (here you could use one of the CC licenses, or GNU GPL), one for the hardware itself (here you could use the CERN OHL license), and one for other documentation, like building instructions, user guide, etc. (here you could use again CC licenses). 

Make sure to check this module's resources for useful tools to help choosing licenses!
    Cover the most common ones and tools to help people decide



There are a number of licenses available for all sorts of different purposes. In this module and in this program, we are going to stick to mainly four of them
CERN
CC
MIT / GNU GPL
There are so many options! How would I know what license to choose??
From the comments → MARTIN has offered to write a TL-DR guide for licensing

----




A common question people developing open projects get is “Are you not afraid that if you do not patent/protect your idea, China/boogeyman/next door neighbour is simply going to copy you and take your project/community away from you?”. 

A common concept when starting a new project/idea is that it needs to be protected at all costs, otherwise potential competitors would simply come by and steal it away, making it faster, better and cheaper than you. Well known protection mechanisms are copyright law and patents. Which in their own way give exclusive rights to develop/explore a certain idea/resource to the copyright/patent holders. In principle, this is not a terrible idea per se, as when they first started, they were thought to be giving developers time and space to properly develop their ideas and bring excellent tools/projects/art to the wider public. In a way incentivising innovation and creative work.

Unfortunately, as a lot of things that do not get revised and updated, these systems have been shown to actually work against innovation, making the innovative process more expensive, slower and generating things that only reach a few hands (as the overall development costs of things are higher). Moreover, when ideas are patent they also prevent people from working on them as a base for their work, so there are a smaller number of derivative work.

Maybe this will become clearer with a practical recent example: 3D printers. 
3D printing technology has been available since the XX when the first designs for creating a 3D printer were patent by YYYY. Over the next ZZ years, while the patents were active, 3D printers were big, expensive machines, only available for companies with deep pockets. Also, there were only so many materials that could be printed on one of these machines. As soon as the patents expired, Adrian Boywer, a researche at the Unviersity of Bath, released one of the first open source 3D printers, which kick-started the RepRap movement. Today, ZZZ years after the first open source models were available, the 3D printing industry is worth XXX (YYY times more than before), and 3D printers can be found in most places of the earth, and even at the International Space Station, where they are used to print replacement/repair parts. Moreover, they are available in all sorts of sizes, formats, and printing resolution (from meters to micrometers) and are capable of printing many different materials (such as plastics, concrete, chocolate, gels, metal, etc).

As an alternative to patents and copyright, a lot of people have poured quite some time in creating licenses that, instead of putting a fence around an idea, make  the point of making sure the licensed project can be used by as many people as possible, making sure the original developers are credited and respected in how they would like their projects to be used and reshared (eg, are commercial uses allowed, should derivative work be shared always under the same license - More details will be given through this unit). Some known examples of these licenses (sometimes bundled under the “copyleft” banner) are Creative Commons (CC) licenses, GNU General Public License  v3.0 and the CERN open hardware license.




### {{ site.assignment }} Get an overview on how licenses work
- Browse throught the resources below to learn about the different available licenses and their "ethos"

### Resources
- https://creativecommons.org/
- https://en.wikipedia.org/wiki/Copyleft
- https://en.wikipedia.org/wiki/Open-source_license