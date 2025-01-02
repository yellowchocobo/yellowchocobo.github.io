---
permalink: /bouldering/
title: "BOULDERING"
author_profile: true
---

You may wonder why I have a tab about BOULDERING on my website. While it is a popular activity, I am actually referring to my Marie Skłodowska-Curie Global Fellowship, funded by the European Union and granted by the European Research Council. This prestigious fellowship provides a unique opportunity for young researchers to gain international experience, develop cutting-edge skills, and expand their networks by working in world-class institutions across the globe.

First of all, I would like to thank the European Research Council (and all Europeans!) for supporting these three pivotal years of my career. The fellowship allowed me to acquire new skills, conduct exciting research, and travel to the US—the mecca of planetary science. I cannot emphasize enough how grateful I am for this opportunity. I acknowledge the support of the European Commission (101030364) and the Research Council of Norway (328597) through the MSCA-2020 Individual Global Fellowship, hosted at Stanford University and the University of Oslo. This work was further supported by the Research Council of Norway through its Centres of Excellence scheme, project numbers 223272 (CEED) and 332523 (PHAB).

Secondly, I’d like to express my deepest gratitude to Associate Professor Mathieu Lapotre, who leads the Earth & Planetary Surface Processes group at Stanford. Mathieu provided me with a unique opportunity to join his vibrant and inspiring group and was a constant source of kindness, patience, and mentorship throughout the project. His excellent advice and support made a huge difference in my research journey. I highly recommend his group to any young researchers, undergraduates, or graduate students looking for a dynamic and collaborative environment. It’s a fantastic place to work, set against the backdrop of the stunning Stanford campus.

## Project description
Craters are very common surface features on many solid planets and moons. During an impact, rock fragments ejected from the crater cavity could be deposited elsewhere on the surface, where they could potentially form secondary craters. Boulders are the only remnants of these ejected materials. Their size and shape, as well as the terrain on which they are found, provide important insight into the ejection mechanisms. Funded by the Marie Skłodowska-Curie Actions programme, the BOULDERING project plans to use high-resolution imaging and deep learning to further investigate the size and shape distributions of boulder populations. Project results could boost our understanding of the planetary surface evolution.

## Objective 
Many planetary surfaces are heavily cratered as they witnessed the early stages of Solar System evolution during which impact cratering was a frequent process. Upon impact, rock fragments are ejected from the crater cavity and deposited elsewhere on the surface, where they potentially form secondary craters. The unknown contribution of secondary craters increase crater density and distort crater statistics, which ultimately biases the estimated age of a surface unit, a key diagnostics for understanding the evolution of planetary bodies.

The size and velocity distribution of the ejected rock fragments is a poorly understood aspect so that an important link between crater statistics and planetary surface age keeps missing. One way to close this connection is to make use of the population of boulders (meter-sized rocks) that can be detected on high-resolution images of planetary surfaces, such as the Moon’s. Boulders are the only remnants of the ejected materials and their size and shape as well as the terrain on which they are found provide important insight into the ejection mechanisms. BOULDERING aims to advance the detection of boulders on planetary surfaces from high-resolution imagery using deep learning and to compile size and shape distributions of boulder populations. Based on this, this project will boost our understanding of cratering records and the implications for planetary surface evolution.

A versatile automatic boulder detection algorithm will be developed using a convolutional neural network. This algorithm will first be validated on terrestrial boulder populations in Death Valley and the Mojave Desert and will then be trained with remote sensing data for application on the lunar and martian surfaces. By following this approach, ground data collected on Earth will be used to test the algorithm’s capacity to measure the sizes and shapes of boulders, which is key to make robust inferences on the boulder population on other planetary bodies.

## Deliverables
- [Raw drone data of the two fieldworks conducted in the Sierra Nevada, CA, USA](https://zenodo.org/records/14585533)
- [Raw input and labeled boulder data collected over the whole course of the project](https://zenodo.org/records/14250970) 
- [Pre-processed images and labels for use with Detectron2 and YOLOv8](https://zenodo.org/records/14250874) 
- [Code, best trained model setups and weights for YOLOv8](https://zenodo.org/records/14579518)
- [Boulder populations around 82 fresh simple impact craters on the Moon and 15 fresh simple impact craters on Mars](https://zenodo.org/records/14253940) 
- [Github repository for the manipulation of rasters](https://github.com/astroNils/rastertools) 
- [Github repository for the manipulation of vector data](https://github.com/astroNils/shptools)
- [Github repository for data processing, model setup and predictions with Detectron2 Mask R-CNN](https://github.com/astroNils/MLtools)
- [Github repository for data processing, model setup and predictions with YOLOv8](https://github.com/astroNils/YOLOv8-BeyondEarth)

Please bear in mind that I do not have a formal background in software development, so the code might be a bit messy from time to time. I believe it improved significantly over the course of the project, but there’s definitely still some untidy coding in the MLtools GitHub repository. If you’re confused or need help using this code, don’t hesitate to reach out—I’d be happy to assist!

## Manuscripts
See Publications tab. 

## Blog
I have maintained a blog documenting my life experiences as a Marie Skłodowska-Curie Global Fellow (MSCA Fellow), which you can find under the Blog Posts tab. The entries are a mix of research progress updates and reflections on life as an MSCA Fellow, offering insights into both the professional and personal journey of this unique opportunity.   

## Main results
The project achieved significant progress in creating a large, high-quality database of boulder populations around fresh lunar and Martian craters. This database, the first of its kind in planetary science, provides a wealth of data that will support future studies of ejection mechanisms and crater-related processes. While the comprehensive analysis of this data is still ongoing, early results are promising, and I am currently drafting the third manuscript of the BOULDERING project. This work already demonstrates interesting patterns, particularly in the relationship between target properties and ejection dynamics.

## Future work 
The journey of this project doesn’t end here. Although I have transitioned to a role outside academia, my enthusiasm and commitment to the BOULDERING project remain strong. There is still immense potential to improve and expand the model, and I plan to continue exploring and contributing to this field. Looking ahead, here are some key areas I aim to address in the future:

- Enhancing the Loss Function: I intend to modify the loss function to prioritize the detection of large boulders, which are currently under-detected due to their relatively low occurrence in the dataset.
- Training a Semantic Segmentation Model: Using the same labeled boulder data, I aim to develop a semantic segmentation model to provide a more detailed and nuanced understanding of boulder characteristics.
- Detecting Small Craters: A critical next step involves training an algorithm to automatically detect small craters around fresh impact craters. This will facilitate studies of spatial relationships between boulders and secondary craters and enhance our understanding of their mutual influence on cratering processes.
- Expanding Training Data: Incorporating a broader range of boulder environments into the training dataset, such as boulders within impact craters or those associated with rockfalls, will improve the model’s versatility and accuracy across diverse scenarios.

If you want to contribute do not hesitate in sending me an email at prieur.nils@gmail.com, so that we can collaborate together! Take care all of you!  
