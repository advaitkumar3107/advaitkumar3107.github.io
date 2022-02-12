---
layout: page
title: Projects
permalink: /projects
---
<!DOCTYPE html>
<html>
<head>
<style>
.button {
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

.button1 {background-color: #4CAF50;} /* Green */
.button2 {background-color: #008CBA;} /* Blue */
</style>
</head>
  
<img style="float: right;" src="{{site.url}}/assets/img/im_result.png">
## RSINet: Inpainting Remotely Sensed Images Using Triple GAN Framework 
We tackle the problem of image inpainting in the remote sensing domain. Remote sensing images possess high resolution and geographical variations, that render the conventional inpainting methods less effective. This further entails the requirement of models with high complexity to sufficiently capture the spectral, spatial and textural nuances within an image, emerging from its high spatial variability. To this end, we propose a novel inpainting method that individually focuses on each aspect of an image such as edges, colour and texture using a task specific GAN. Moreover, each individual GAN also incorporates the attention mechanism that
explicitly extracts the spectral and spatial features. To ensure consistent gradient flow, the model uses residual learning paradigm, thus simultaneously working with high and low level features. We evaluate our model, along with previous state of the art models, on the two well known remote sensing datasets, Open Cities AI and Earth on Canvas, and achieve competitive performance

<button class="button button2" onclick="{{site.url}}/assets/pdf/inpainting.pdf">Paper</button> <button class="button button2" onclick="https://github.com/advaitkumar3107/RSINet">Code</button>


<!---
* Dual-Degree Project (Stage 1): Deep Learning for Prominence Detection in Children’s Read Speech (based on waveform segments)  
  [[presentation]]({{ site.url }}/assets/pdf/ddp1_ppt.pptx) [[report]]({{ site.url }}/assets/pdf/ddp1_report.pdf) [[arXiv]](https://arxiv.org/abs/2110.14273)

* Character Animation from Video in Blender  
  [[presentation]](https://docs.google.com/presentation/d/1TEVYZGPMrn5LLypoGjDc5QhWAy3K8PVQNFJfoFA-RS4/edit?usp=sharing) [[report]]({{ site.url }}/assets/pdf/hpr_report.pdf)

* Deep Learning for Prominence Detection in Children’s Read Speech (based on acoustic contours)  
  [[presentation]]({{ site.url }}/assets/pdf/rnd_ppt.pdf) [[report]]({{ site.url }}/assets/pdf/rnd_report.pdf) [[arXiv]](https://arxiv.org/abs/2104.05488)

* SIRD model for studying outbreak of infectious diseases  
  [[report]]({{ site.url }}/assets/pdf/sre_sird.pdf) [[code]](https://github.com/methi1999/SIRD-model)

### Course projects

* EE708: Information Theory and Coding - Communication with Noiseless Feedback (Schalkwijk and Kailath coding scheme, 1966)  
  [[presentation]]({{ site.url }}/assets/pdf/ee708_ppt.pdf)
  
* CS726: Advanced Machine Learning - Legendre Memory Units  
  [[presentation]]({{ site.url }}/assets/pdf/cs726_ppt.pdf) [[code]](https://github.com/CyanideBoy/LegendreMemoryUnits)

* CS753: Automatic Speech Recognition - Hear me if you can! (Audio Steganography)  
  [[presentation]]({{ site.url }}/assets/pdf/cs753_ppt.pptx) [[report]]({{ site.url }}/assets/pdf/cs753_report.pdf) [[code]](https://github.com/methi1999/stego-audio/)

* EE786: Developments, Trends and Economic Frontiers in Electrical Engineering - Case Study on Light Cargo Drones  
  [[case study]]({{ site.url }}/assets/pdf/ee786_case_study.pdf)
  
* EE763: Science of Information and Statistics - Abstract Reasoning Challenge  
  [[presentation]]({{ site.url }}/assets/pdf/ee763_ppt.pdf)
  
* CS663: Digital Image Processing - Video Toonification  
  [[code]](https://github.com/methi1999/CS663-DIP-Project)
  
* EE679: Speech Processing - Speech Compression using Deep Learning  
  [[presentation]]({{ site.url }}/assets/pdf/ee679_paper_review.pdf)
  
* SC631: Games and Information Theory - A study of Auction Theory  
  [[presentation]]({{ site.url }}/assets/pdf/sc631_auction_theory.pdf)
  
* EE224: Digital Systems - Implementation of RISC in VHDL  
  [[specifications]]({{ site.url }}/assets/pdf/risc_specs.pdf) [[report]]({{ site.url }}/assets/pdf/risc_report.pdf) [[code]](https://github.com/methi1999/risc)
  
* IE613: Online Learning - A study of Duelling Bandits  
  [[report]]({{ site.url }}/assets/pdf/bandit_report.pdf) [[code]](https://github.com/methi1999/dueling-bandits)


### Miscellaneous

* [Keyword Spotting]({{ site.url }}/projects/kws)
* [Hangman]({{ site.url }}/projects/hangman)
* [FindIt]({{ site.url }}/projects/findit)
* [IPL analysis]({{ site.url }}/projects/ipl)
* [Handwriting Recognition Pen]({{ site.url }}/projects/itsp)
--!>
