---
layout: post
title:  Android Brain-in-Jars Dream of Deletion
date: 2023-07-21 08:01:00
description: Rabbit hole I went down while looking at Fruit Fly brains
tags: neuroscience, fiction, sci-fi, neuromancer, lena
categories: 
thumbnail: 
---

{% include video.html path="assets/video/flybrain-2023-short.mp4" class="img-fluid z-depth-1" controls=true loop=true caption="The entire connectome of a female Drosophila" %} 

### Fly Brains and NeuroSci-Fi
For the first time, humanity has a map of the entire fruit fly brain.:brain::world_map::fly:

Last month, I read about the [FlyWire](flywire.ai) consortium releasing the ENTIRE whole-brain connectome of an adult female fruit fly.

- 120,000+ Neurons
- 30,000,000+ Synapses
- 100,000+ Annotations

A connectome is a comprehensive map of neural connections in the brain, and may be thought of as its "wiring diagram." The fruit fly is one commonly used model organisms in neuroscience and biology research. It's in the superstar pantheon of scientific model organisms, along with the mouse, zebrafish, and nematode worm. Drosophila has a smaller brain vs. mammals but can still form memories, learn, and engage in complex social behavior. Hence findings from studies in fruit flies' brains can often be applied to other animals, including humans. 

The story of FlyWire's creation is an interesting one, combining gamification, AI, and crowdsourced science. First, the brain was sectioned and imaged with an electron microscope, then AI took the first pass at identifying the 120k+ individual neurons and 30m+ individual connections. However, the AI's output wasn't perfect. Certain synapses were incorrectly linked, or grouped with incorrect neurons. Human annotation was needed, but the scale was immense. So researchers created a [game-like interface](http://edit.flywire.ai) for crowdsourcing edits and annotations to the initial AI output. "Players" search for the right pieces and put together beautiful 3D neurons that advance science's understanding of brain circuits.

{% include video.html path="assets/video/flybrain-eyes.mp4" class="img-fluid z-depth-1" controls=true caption="All neurons and synapses of the fly's eye" %}

The end result is a masterpiece in crowdsourced science. The potential benefits of such a resource are immense - we can now make significant advances in our understanding of how the brain works by ultimately linking neuronal wiring with brain function. Personally, I find the images and videos that came out of it are quite beautiful in their own right. 

### Virtual Machines Running Virtual Humans

I came across the FlyWire project during my daily browsing of HackerNews. Anytime I see something vaguely relevant for my work at [OpenBCI](https://openbci.com) that has broken through to more "mainstream" tech audiences like HackerNews, I make a note and usually end up adding it to our social media pipeline. This time, down in the comments section there was a link to a short story called [Lena by qtnm](https://qntm.org/mmacevedo). Basically, *Lena* is about what happens when we do to the human brain, what FlyWire has done to the fruit fly. 

It's written in the style of a wikipedia article from the future on the topic of **MMAcevedo** also known as Miguel, the earliest executable image of a human brain. A brain-in-an-exe copy of Miguel Acevedo Álvarez which heralded the dawn of the "workloading" industry, where virtual machines running virtual humans could be spun up to do the work of thousands. The story came out in Jan 2021, long before the ChatGPT hypetrain left the station and generated a corresponding avalanche of white-collared existential dread. This style of anthropological or encyclopedic world-building has always interested me. When it's done well, it shows the author had gone a level deeper into the world they're building, and it makes the story that much more believable. Ursula K. LeGuin's *Haimish* works are the best example of this that I've come across. 

The story is a quick read, full excellent quotes. Pulling out a few here:

>  In 2049 it became known that MMAcevedo was being widely shared and experimented upon without Acevedo's permission. Acevedo's attempts to curtail this proliferation had the opposite of the intended effect. A series of landmark U.S. court decisions found that Acevedo did not have the right to control how his brain image was used, with the result that MMAcevedo is now by far the most widely distributed, frequently copied, and closely analysed human brain image.

>Acevedo died from coronary heart failure in 2073 at the age of 62. It is estimated that copies of MMAcevedo have lived a combined total of more than 152,000,000,000 subjective years in emulation. If illicit, modified copies of MMAcevedo are counted, this figure increases by an order of magnitude.

>As the earliest viable brain scan, MMAcevedo is one of a very small number of brain scans to have been recorded before widespread understanding of the hazards of uploading and emulation. MMAcevedo not only predates all industrial scale virtual image workloading but also the KES case, the Whitney case, the Seafront Experiments and even Poulsen's pivotal and prescient Warnings paper. Though speculative fiction on the topic of uploading existed at the time of the MMAcevedo scan, relatively little of it made accurate exploration of the possibilities of the technology. That fiction which did was far less widely-known than it is today and Acevedo was certainly not familiar with it at the time of his uploading.

>As such, unlike the vast majority of emulated humans, the emulated Miguel Acevedo boots with an excited, pleasant demeanour. He is eager to understand how much time has passed since his uploading, what context he is being emulated in, and what task or experiment he is to participate in. 
><p>...</p>
>MMAcevedo's demeanour and attitude contrast starkly with those of nearly all other uploads taken of modern adult humans, most of which boot into a state of disorientation which is quickly replaced by terror and extreme panic. Standard procedures for securing the upload's cooperation such as red-washing, blue-washing, and use of the Objective Statement Protocols are unnecessary.

A few lines stood out to me and sparked a connection to another famous work of neurosci-fi, William Gibson's *[Neuromancer](https://en.wikipedia.org/wiki/Neuromancer).*

>MMAcevedo is considered by some to be the "first immortal", and by others to be a profound warning of the horrors of immortality.
><p>...</p>
>The biological Acevedo was initially extremely protective of his uploaded image and guarded its usage carefully. Towards the end of his life, as it became possible to run simulated humans in banks of millions at hundred-fold time compression, Acevedo indicated that being uploaded had been the greatest mistake of his life, and **expressed a wish to permanently delete all copies of MMAcevedo.**

### Dixie Flatline

This last line, and the idea of digital brain-scan immortality is what made me start thinking of Neuromancer. One of my favorite characters in Gibson's novel is the digital ghost of the legendary hacker McCoy Pauley, aka the Dixie Flatline. Pauley was a legendary hacker who died of a brain aneurysm while attempting to crack an AI. His brain was scanned and his consciousness was uploaded into a ROM construct, which was then used as a hacking tool by Case, the protagonist of the novel.

**SPOILER ALERT**<br/>
As the climax of the book approaches, Dixie makes a unique request of Case:

>"How you doing, Dixie?"<br/>
>"I'm dead, Case. Got enough time in on this Hosaka to
figure that one."<br/>
>"How's it feel?"<br/>
>"It doesn't."<br/>
>"Bother you?"<br/>
>"What bothers me is, nothin' does."<br/>
>"How's that?"<br/>
>"Had me this buddy in the Russian camp, Siberia, his thumb
was frostbit. Medics came by and they cut it off. Month later
he's tossin' all night. Elroy. l said, what's eatin' you? Goddam
thumb's itchin', he says. So l told him, scratch it. McCoy, he
says, it's the other goddam thumb." When the construct laughed,
it came through as something else, not laughter, but a stab of
cold down Case's spine. "Do me a favor, boy."<br/>
>"What's that, Dix?"<br/>
>"This scam of yours, when it's over, you erase this goddam
thing."

As a ROM, Dixie can't form new memories. The construct knows what it is, "a hardwired ROM cassette replicating a dead man's skills, ob-
sessions, kneejerk responses" but not able to "write a poem" or understand whether it's truly alive or not. Faced with the prospect of continuing this simulacrum of sentience, or the unknown of deletion, Dixie (the ROM not the man) chooses deletion. In both *Neuromancer* and *Lena*, digitally copied immortality aint all that it's cracked up to be.

### Lena vs. Lenna

The title of qtnm's short story “Lena” comes from the real-world controversy surrounding Swedish model Lena Forsén’s November 1972 Playboy centerfold. A safe-for-work cropped version of Forsen’s centerfold was used by USC researchers in 1973 as a test image for their work. Since then, this [“Lenna”](https://en.wikipedia.org/wiki/Lenna) facsimile became the de-facto standard test image used for decades in the field of digital image processing. 

WIRED dubbed Lena “[The Patron Saint of JPEGS](https://www.wired.com/story/finding-lena-the-patron-saint-of-jpegs/)” and Forsén was a guest at the 50th annual Conference of the Society for Imaging Science and Technology (IS&T) in 1997. In 2015, Lena Forsén was also guest of honor at the banquet of IEEE ICIP 2015. After delivering a speech, she chaired the best paper award ceremony.

<div>
      <a class="image" href="https://upload.wikimedia.org/wikipedia/en/7/7d/Lenna_%28test_image%29.png" data-lightbox="Lenna"><img class="image" src="https://upload.wikimedia.org/wikipedia/en/7/7d/Lenna_%28test_image%29.png" alt="Lenna-test-image"/></a>
</div>

The image's reach was limited in the 1970s and 80s, which is reflected in it initially only appearing in .org domains. But in July 1991, the image featured on the cover of Optical Engineering alongside Peppers, another popular test image. This drew the attention of Playboy to the potential copyright infringement. The peak of image hits on the internet was in 1995. The scan became one of the most used images in computer history.[16] The use of the photo in electronic imaging has been described as "clearly one of the most important events in [its] history". The image spread to over 100 different domains, particularly .com and .edu.

Lenna is so widely accepted in the image processing community that while Playboy often cracks down on illegal uses of its material and did initially send a notice to the publisher of Optical Engineering about its unauthorized use in that publication, over time it has decided to overlook the wide use of Lena. Eileen Kent, VP of new media at Playboy, said, "We decided we should exploit this, because it is a phenomenon."

The use of the image has produced controversy because Playboy is seen (by some) as being degrading to women and it has now fallen out of favor. Many journals no longer accept new submissions containing the image "without convincing scientific justification for its use"

Forsén stated in the 2019 documentary film Losing Lena, "I retired from modeling a long time ago. It’s time I retired from tech, too... Let's commit to losing me."

Maining control over our digital fascimiles, and the unexpected lives they lead, was the interesting thread of today's rabit hole. Fruit flies, Playboy, Sci-Fi, and digital immortality. Not a bad afternoon. 




