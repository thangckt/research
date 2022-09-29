---
short: 'DispFields'
title: 'Predicting Sharp and Accurate Occlusion Boundaries in Monocular Depth Estimation Using Displacement Fields'
collection: projects
permalink: /projects/DisplacementFields
thumbnail: /images/DisplacementFields_thumbnail.gif
date: 16-06-2020
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
authors: '<a href="/about.html">Michaël Ramamonjisoa</a><sup>*</sup>, Yuming Du<sup>*</sup> and <a href="https://imagine.enpc.fr/~lepetitv">Vincent Lepetit</a> <br> <small><i><sup>* Denotes equal contribution.</sup></i></small>'
conference_short: 'CVPR 2020'
affiliation: 'LIGM (UMR 8049) - Ecole des Ponts, UPE'
excerpt: "Current methods for depth map prediction from monocular images tend to predict
  smooth, poorly  localized contours for  the occlusion boundaries in  the input
  image.   This is  unfortunate as  occlusion boundaries  are important  cues to
  recognize objects, and as  we show, may lead to a way  to discover new objects
  from scene  reconstruction.  To improve  predicted depth maps,  recent methods
  rely on various  forms of filtering or predict an  additive residual depth map
  to refine a  first estimate.  We instead  learn to predict, given  a depth map
  predicted  by some  reconstruction method,  a  2D displacement  field able  to
  re-sample pixels around the occlusion boundaries into sharper reconstructions.
  Our method can be applied to the  output of any depth estimation method and is
  fully  differentiable,  enabling  end-to-end  training.   For  evaluation,  we
  manually annotated  the occlusion  boundaries in  all the  images in  the test
  split of popular  NYUv2-Depth dataset. We show that our  approach improves the
  localization of occlusion boundaries  for all state-of-the-art monocular depth
  estimation   methods   that    we   could   evaluate,   without  degrading  the  depth
  accuracy for the rest of the images."
bibtex: "@InProceedings{Ramamonjisoa_2020_CVPR, <br>
author = {Ramamonjisoa, Michael and Du, Yuming and Lepetit, Vincent}, <br>
title = {Predicting Sharp and Accurate Occlusion Boundaries in Monocular Depth Estimation Using Displacement Fields}, <br>
booktitle = {IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},<br>
month = {June},<br>
year = {2020}<br>
}"
code: "https://github.com/dulucas/Displacement_Field"
dataset: 'Access our NYUv2OC++ dataset <a href="https://drive.google.com/open?id=1Fk8uuH3oJJhyCN-4ffD3mdtCq2l4geJc">here</a>'
pdf: "https://arxiv.org/pdf/2002.12730.pdf"
paper_url: "https://arxiv.org/abs/2002.12730"
poster: /files/Poster_DisplacementFields.pdf
poster_thumbnail: /files/Poster_DisplacementFields_thumbnail.png
paper_thumbnail: /files/Paper_DisplacementFields_thumbnail.png
diagram: /files/DispFields_diagram.png
youtube: "https://www.youtube.com/embed/yCPG2YCT1iU"
---

