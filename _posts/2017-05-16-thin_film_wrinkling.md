---
layout: post
title: "Measuring the elastic modulus of thin film annuli using capillary wrinkling"
date: 2017-05-16 16:00:00
category: research
tags: [Soft condensed matter, Thin-film, polystyrene, material properties, stress, strain, wrinkling, annulus]
permalink: "/research/thin_film/"
---

<div class="row2">
<div class="span60" id="text-content">
<p>For my 3rd year project/BSc dissertation equivalent, my lab partner Dom and I were paired up and set to work on improving some work done as a side project of Dr. David Farmer's PhD thesis. His project consisted of cutting annuli into ultra-thin films of polystyrene (&lt;200nm) and floating them on water. The surface tensions on the inside and outside of the annuli were equal and opposite, generated by the capillary interactions at the inner and outer edges. A <a href="https://en.wikipedia.org/wiki/Langmuir%E2%80%93Blodgett_trough">Langmuir-Blodgett trough</a>, which is a device used to control the surface density of an immiscible addition to the subphase. In our case we added <a href="https://www.sigmaaldrich.com/catalog/product/sial/85548?lang=en&region=SE&gclid=CjwKCAjwwdTbBRAIEiwAYQf_E6awMMJVaW5J1QB_JkAFjswJceOfOnWkaCrBmNWZE6PjQAJ3zhY0lRoCengQAvD_BwE">span 80</a>, a surfactant, to the water outside of the annuli. The density of the surfactant could be adjusted using the trough, and the surface tension was simultaneously measured. The increasing density of the surfactant acted to reduce the surface tension down from the value of water to the value of span 80 by replacing the surface water with span 80.</p>
<p>[expand]</p>
<p>This lead to an imbalance of forces acting on the inner circumference and the outer circumference. When the difference in force was strong enough, the annulus would wrinkle according to an expression that was to be determined. The energy of the wrinkled and unwrinkled states would be equal at a certain force, referred to as the nucleation pressure, and a  sinusoidal distribution film position was predicted. Unfortunately, defects in the films and surface tension lead to collapsing of wrinkles and disturbed the sinusoidal distribution. Instead, the wrinkles formed with stochastic position and varying amplitudes, leading to the aforementioned collapsing flaps. 
</p>



<p> The aim of the experiment was to count the wrinkles that formed using a high resolution grey scale camera and some image processing scripts in MATLAB to determine the number of wrinkles as a function of the difference in surface tension and to use this, alongside a theoretical prediction of the number of wrinkles, to extract the elastic modulus. The resulting equations, which were not derived ab initio and instead built upon David's empirical approach, were unwieldy and inaccurate. They always contained an offset, which we put down to defects and contaminants in the water such as dust and residual surfactants. </p>

<p> After the project was completed and I'd had a break, I attempted to derive the form of the wrinkling from first principles using the 3D stress and strain relations and the known initial conditions and constraints. The resulting differential equations were intractable and required a lot of work and yielded similarly as horrendous equations as before. Because the equations are so unwieldy, the technique was decided to be infeasible and impractical, leaving it abandoned. </p>

<p>[/expand]</p>

</div>	

<div class="span40" id="image-content">

<a href="/assets/img/research/thin/radial.png"><img src="/assets/img/research/thin/radial.png" alt="Predicted form of Wrinkling" width="80%"></a>
<p>The predicted form of the wrinkling of the annulus</p>
<a href="/assets/img/research/thin/newWrinkledImage-39-66-a=39-b=90.png"><img src="/assets/img/research/thin/newWrinkledImage-39-66-a=39-b=90.png" alt="Wrinkly Anuslus" width="80%"></a>
<p>An example image of a wrinkled annulus.</p>
<a href="/assets/img/research/thin/LBTroughDrawing.png"><img src="/assets/img/research/thin/LBTroughDrawing.png" alt="LB Trough Diagram" width="80%"></a>
<p>A schematic diagram of the Langmuir-Blodgett Trough</p>

<div width="80%">
<p><a href="/assets/pdfs/Thin Film Wrinkling.pdf" target="_blank" class="btn btn-pdf"><span class="icon"></span>Project Report</a></p>



</div>
</div>
</div>