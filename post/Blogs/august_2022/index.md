---
author: [Deexith, Kunal, Keval]
title: This Month in AI and ML - August 2022
date: "2022-09-10"
slug: tmai-august-2022
description: Latest News & Breakthroughs in the Month of August 2022 in AI and ML
categories: [Blog]
tags: [Month in AI]
image: 135.png
lastmod: "2022-09-17"
aliases: [blog-august-2022]

---

## New AI-Powered App Could Boost Smartphone Battery Life by 30% [^1]

A cutting-edge AI invention will be disclosed to technology giants, with the potential to increase smartphone battery life by 30% and save countless kilowatts on energy bills.

![The app also optimizes the performance of other apps running at the same time.](AI_Powered_App.jpg "The app also optimizes the performance of other apps running at the same time.")

The ground-breaking work produced by the University of Essex has been incorporated into an app called EOptomizer, which will be exhibited to specialist researchers and designers, as well as major manufacturing businesses like as Nokia and Huawei. It is envisaged that the EOptomizer app would be used throughout the industry and help reduce carbon emissions by extending the life of consumer goods.

The cutting-edge tech analyses how an app is being used throughout the day and optimizes energy use.

For example, a user might quickly scroll through the BBC News app while at work to check the headlines, which will require a higher FPS (frames per second) than when they spend more time on the app in the evening, slowly scrolling down and reading more stories in full.

The methodology means the AI realizes the change in FPS for the app being used and tries to find the best operating frequency of CPU and GPU processors to cater to the change whilst consuming the least amount of power and temperature gain in the device, which is a critical issue in mobile phones.

## Highly-Efficient New Neuromorphic Chip for AI on the Edge [^2]

The NeuRRAM chip is the first compute-in-memory chip to demonstrate a wide range of AI applications while using just a small percentage of the energy consumed by other platforms while maintaining equivalent accuracy.

NeuRRAM , a new chip that runs computations directly in memory and can run a wide variety of AI applications has been designed and built by an international team of researchers. What sets it apart is that it does this all at a fraction of the energy consumed by computing platforms for general-purpose AI computing.


![ A team of international researchers designed, manufactured, and tested the NeuRRAM chip. Credit: David Baillot/University of California San Diego ](NeuRRAM-Chip.jpg "A team of international researchers designed, manufactured, and tested the NeuRRAM chip. Credit: David Baillot/University of California San Diego")


Not only is the NeuRRAM chip twice as energy efficient as the state-of-the-art “compute-in-memory” chips, an innovative class of hybrid chips that runs computations in memory, it also delivers results that are just as accurate as conventional digital chips. Conventional AI platforms are much bulkier and typically are constrained to using large data servers operating in the cloud.

The research team, co-led by bioengineers at the University of California San Diego (UCSD), presented their results in the August 17 issue of Nature.

“This chip now provides us with a platform to address these problems across the stack from devices and circuits to algorithms,” said Siddharth Joshi, an assistant professor of computer science and engineering at the University of Notre Dame, who started working on the project as a Ph.D. student and postdoctoral researcher in Cauwenberghs lab at UCSD.


## Van Gogh’s ‘hidden’ portrait recreated 135 years after being painted [^3]

A hidden Vincent Van Gogh painting has been recreated using artificial intelligence more than 135 years after it was covered over.

The portrait of two male wrestlers was discovered 10 years ago beneath a still life painting by the same artist.

![The Two Wrestlers recreation is set to be exhibited in The Louvre (Supplied)](135.png "The Two Wrestlers recreation is set to be exhibited in The Louvre (Supplied)")

It shows the two men locked in combat with splashes of red blood against a background of blue strokes.

Van Gogh once made a passing mention of a painting involving wrestlers. “This week I painted a large thing with two nude torsos — two wrestlers,” he said in an 1886 letter this his brother, adding: “I really like doing that.”

This painting - thought to have been made while the artist was studying in Antwerp - was considered lost or destroyed until it was discovered behind the other in 2012.

Oxia Palus - an initiative which uses AI, spectroscopy and 3D printing to bring hidden paintings to life - was behind the recreation of the “Two Wrestlers” painting.

The University College London PhD candidates have also worked to recreate other hidden paintings through their Oxia Palus initiative, including Van Gogh’s “Standing Female Nude” and lost 15th century “Madonna” by Leonardo Da Vinci.


## Digitizing Smell: Using Molecular Maps to Understand Odor [^4]

>Did you ever try to measure a smell? …Until you can measure their likenesses and differences you can have no science of odor. If you are ambitious to found a new science, measure a smell.
><div align="right">— Alexander Graham Bell, 1914.</div>
&nbsp;

Smells are produced by molecules that waft through the air, enter our noses, and bind to sensory receptors. Potentially billions of molecules can produce a smell, so figuring out which ones produce which smells is difficult to catalog or predict. Sensory maps can help us solve this problem.

In 2019, google developed a graph neural network (GNN) model that began to explore thousands of examples of distinct molecules paired with the smell labels that they evoke, e.g., “beefy”, “floral”, or “minty”, to learn the relationship between a molecule’s structure and the probability that such a molecule would have each smell label. The embedding space of this model contains a representation of each molecule as a fixed-length vector describing that molecule in terms of its odor, much as the RGB value of a visual stimulus describes its color.


![ An example of a color map (CIE 1931) in which coordinates can be directly translated into values for hue and saturation. Similar colors lie near each other, and specific wavelengths of light (and combinations thereof) can be identified with positions on the map. Right: Odors in the Principal Odor Map operate similarly. Individual molecules correspond to points (grey), and the locations of these points reflect predictions of their odor character. ](POM.jpg "An example of a color map (CIE 1931) in which coordinates can be directly translated into values for hue and saturation. Similar colors lie near each other, and specific wavelengths of light (and combinations thereof) can be identified with positions on the map. Right: Odors in the Principal Odor Map operate similarly. Individual molecules correspond to points (grey), and the locations of these points reflect predictions of their odor character.")

Google introduced the “Principal Odor Map” (POM), which identifies the vector representation of each odorous molecule in the model’s embedding space as a single point in a high-dimensional space. The POM has the properties of a sensory map: first, pairs of perceptually similar odors correspond to two nearby points in the POM (by analogy, red is nearer to orange than to green on the color wheel). Second, the POM enables us to predict and discover new odors and the molecules that produce them. In a series of papers, we demonstrate that the map can be used to prospectively predict the odor properties of molecules, understand these properties in terms of fundamental biology, and tackle pressing global health problems.

[^1]:  [https://scitechdaily.com/new-ai-powered-app-could-boost-smartphone-battery-life-by-30/](https://scitechdaily.com/new-ai-powered-app-could-boost-smartphone-battery-life-by-30/)
[^2]:  [https://scitechdaily.com/highly-efficient-new-neuromorphic-chip-for-ai-on-the-edge/](https://scitechdaily.com/highly-efficient-new-neuromorphic-chip-for-ai-on-the-edge/)
[^3]:  [https://www.independent.co.uk/arts-entertainment/art/van-gogh-hidden-painting-wrestlers-b2155439.html](https://www.independent.co.uk/arts-entertainment/art/van-gogh-hidden-painting-wrestlers-b2155439.html)
[^4]:  [https://ai.googleblog.com/2022/09/digitizing-smell-using-molecular-maps.html](https://ai.googleblog.com/2022/09/digitizing-smell-using-molecular-maps.html)