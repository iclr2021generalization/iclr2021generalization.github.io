---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: ICLRWorkshop2021
layout: home
---

#  Generalization beyond the training distribution in brains and machines 

>  "During all their lifetime, prisoners like this have never managed to see anything besides the shadows that are projected on the wall opposite to them by the glow of the fire [...] If someone were to show them any of the things that were passing by and forced them to answer the question about what it was, don't you think that they would be at wit's end?"
>
> -- The allegory of the cave, Plato

Deep Neural Networks (DNNs) are the leading approach for nearly all domains of machine learning and computer vision, with performance at times rivaling human perception. However, there is consensus that these models are outmatched by the robustness and versatility of biological brains. DNNs are sensitive to so-called shifts of the training distribution, where systematic differences between the train and test sets can significantly degrade performance. Distributional shifts can be induced by random or structured (adversarial) perturbations, changes in object or scene viewpoint, illumination, or color, and novel compositions of familiar features. These issues are magnified in domains where training data is scarce. In contrast, flexible and efficient generalization is a hallmark of biological perception and intelligence. We believe that the algorithms implemented in biological brains offer clues for how to construct artificial intelligence that can generalize beyond the training distribution.

The following is a toy example to depict generalization beyond the training distribution ---MobileNet trying to classify an elephant with rare features:



 <table style="width:80%; border: none !important; background: transparent !important; text-align: center !important;" >
  <tr style="border: none !important; background: transparent !important; text-align: center !important;">
    <td style="border: none !important; background: transparent !important; text-align: center !important;"></td>
    <td style="border: none !important; background: transparent !important; text-align: center !important;"><img align="center" src="https://raw.githubusercontent.com/iclr2021generalization/iclr2021generalization.github.io/main/assets/img/elephant2.jpg" width="350"></td>
    <td style="border: none !important; background: transparent !important; text-align: center !important;"><img align="center" src="https://raw.githubusercontent.com/iclr2021generalization/iclr2021generalization.github.io/main/assets/img/elephant1.png" width="300" class="flip-horizontally"></td>
  </tr>
  <tr style="border: none !important; background: transparent !important; text-align: center !important;">
    <td style="border: none !important; background: transparent !important; text-align: center !important;">
<a href="https://storage.googleapis.com/tfjs-examples/mobilenet/dist/index.html">MobileNet:</a>
  </td>
    <td style="border: none !important; background: transparent !important; text-align: center !important;">This is a `vizsla' or a `dromedary'. </td>
    <td style="border: none !important; background: transparent !important; text-align: center !important;">This a `trilobite' or a `walking stick'.  </td>
  </tr>
</table> 







In this workshop, we aim to address the following questions: 
* What are the neural mechanisms in biological brains that facilitate out-of-distribution generalization?   
* Are these biological mechanisms innate or learned? How do they unfold during development? 
* How do machines compare to brains in generalizing beyond the training distribution, and what are useful benchmarks for this comparison?  
* What are the key problems that we need to address to improve out-of-distribution generalization in machines?   

The limited generalization of DNNs is a critical problem for artificial intelligence, in applications ranging from automated driving and biomedical image analysis, and domains like reinforcement learning, control, and representational theory. Our goal is to address these issues by creating synergies among neuroscientists, cognitive scientists, and artificial intelligence researchers that might lead to novel solutions to this problem or emphasize relevant existing classical work.

