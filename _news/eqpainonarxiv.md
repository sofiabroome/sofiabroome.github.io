---
layout: post
title: "First work on equine pain recognition posted on arXiv"
date: 2019-01-07
inline: false
---

Our article, "Dynamics are important for the recognition of equine pain in video" can now be found on [arXiv](https://arxiv.org/abs/1901.02106), and the code is on [github](https://github.com/sofiabroome/painface-recognition). Me and my advisor Hedvig Kjellström collaborated with the DVM professor Pia Haubro Andersen (also my co-advisor) and DVM PhD Karina Bech Gleerup to write this first work on automatic pain recognition in horses. It is also the first work on pain recognition in animals where the temporal dimension is made use of, processing sequences of images instead of single frames. This is something that we think is important since animals, and especially prey animals, often do not have expressive enough faces to allow for capturing pain behavior in a single frame.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/assets/img/CLSTM2.png">
</div>
<div class="col three caption">
    The best performing model for the task was a two-stream convolutional LSTM. The model is a fully recurrent deep network taking sequences of both RGB and optical flow frames as input, maintaining the spatial structure of the frames throughout the recurrences.
</div>

