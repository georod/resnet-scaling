---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Modelling at different scales"
subtitle: "Authors: Miguel Arias, Gabriela Torchio, Hugo Thierry"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 7
lat: 57.1701121
lng: -125.210678
---
### Introduction

{{< figure src="images/unknownSourceAskM.png" 
class="float-end w-50 d-block" 
caption="Multiscale models comparison by complexity, precision, generalization and spatial extent." 
>}}

Decision-making and research questions are meaningful at specific scales and often need scale-specific models. 


Choosing the right size (extent) to study natural phenomena is hard for scientists (Oreskes et al., 1994 <a href="../references/">[18]</a>). The scale chosen will determine how much detail and how accurate the model is, and also, how much area the model can cover. The scale of a study significantly impacts the models complexity, their accuracy, spatial extent, and generalizability (figure on the right) (Brimicombe, 2010 <a href="../references/">[19]</a>).

Researching at a local scale or a small proportion of the territory requires more complex analyses. Researchers need to consider more variables and their relationships to achieve a reliable approximation of the natural phenomena under investigation. Also, the identification of patterns could be more difficult at smaller scales. Furthermore, obtaining more detailed results demands more computational resources. Nevertheless, higher scales at a finer resolution do not always lead to higher accuracy (Brimicombe, 2010 <a href="../references/">[19]</a>).

On the other hand, examining natural phenomena at larger scales, such as regional or global studies, may enhance comprehension of the phenomena. Coarser resolutions lead to reduced complexity, simplifying models’ inputs and outputs. Also, some relationships or patterns emerge to significant geographical extents. Furthermore, policymakers tend to favor regional and global scales, as they provide a broader perspective on reality.

