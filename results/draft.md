<!--
## Abstract 

In biological systems, we often observe complex global behavior emerge from a collection of agents interacting with each other in their environment, with each individual agent acting only on local information, without centralized control structures. Such systems have inspired development of artificial intelligence algorithms in areas such as swarm optimization and cellular automata. Motivated by the emergence of collective behavior from decentralized systems, we explore feeding each sensory input from an environment into distinct, but identical neural network agents, each with no fixed relationship with one another. We show that these agents can be trained to integrate information received locally, and through communication via an attention mechanism, can collectively produce a globally coherent policy. The system can still perform its task even if the ordering of the inputs are randomly permuted several times during an episode. We study robustness and generalization properties of such decentralized sensory systems and discuss their applications.

______
-->
This page contains an interactive demo and videos of experimental results that accompany our NeurIPS2021 submission. As the paper is under review, we'd appreciate it if you do not share this link with others.

______

## Cart-Pole Swing Up Demo

A permutation invariant network performing <i>CartpoleSwingupHarder</i>. Shuffle the order of the 5 observations at any time, and see how the agent adapts to the new ordering of the observations.
<!--You can also restart the environment.-->

<div style="text-align: left;">
<figcaption style="color:#FF6C00;">Interactive Demo</figcaption><br/>
<!--<figcaption style="text-align: left;">
</figcaption>-->
<div id="intro_demo" class="unselectable" style="text-align: left;"></div>
<br/>
</div>

______

## Supplementary Videos of Pybullet Ant Results

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/ant.mp4" type="video/mp4" autoplay muted playsinline loop style="margin: 0; width: 100%;" ></video>
<figcaption style="text-align: left;">
PyBullet Ant with a permutation invariant policy.<br/>
The ordering of the 28 observations is reshuffled every 100 frames.<br/>
</figcaption>
</div>

______


## Supplementary Videos of Atari Pong Results

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/pong_reshuffle.mp4" type="video/mp4" autoplay muted playsinline loop style="margin: 0; width: 100%;" ></video>
<figcaption style="text-align: left;">
Atari Pong base task (left). Modified shuffled-screen task (right).<br/>
No occlusion. Observations reshuffled every 500 frames.<br/>
</figcaption>
</div>

<br/>

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/pong_occluded_reshuffle.mp4" type="video/mp4" autoplay muted playsinline loop style="margin: 0; width: 100%;" ></video>
<figcaption style="text-align: left;">
70% Occluded, Shuffled-screen Atari Pong.<br/>
Observations reshuffled every 500 frames.<br/>
</figcaption>
</div>

______


## Supplementary Videos of Car Racing Results

<div style="text-align: left;">
<video src="assets/mp4/car_racing.mp4" type="video/mp4" autoplay muted playsinline loop style="margin: 0; width: 100%;" ></video>
<figcaption style="text-align: left;">
CarRacing base task (left). Modified shuffled-screen task (right).<br/>
</figcaption>
</div>

<br/>

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/kof.mp4" type="video/mp4" autoplay muted playsinline loop style="width:100%;" ></video>
<figcaption style="text-align: left;">
KOF background.<br/>
</figcaption>
</div>

<br/>

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/mt_fuji.mp4" type="video/mp4" autoplay muted playsinline loop style="width:100%;" ></video>
<figcaption style="text-align: left;">
Mt. Fuji background.<br/>
</figcaption>
</div>

<br/>

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/ds.mp4" type="video/mp4" autoplay muted playsinline loop style="width:100%;" ></video>
<figcaption style="text-align: left;">
DS background.<br/>
</figcaption>
</div>

<br/>

<div style="text-align: left;">
<video class="b-lazy" data-src="assets/mp4/ukiyoe.mp4" type="video/mp4" autoplay muted playsinline loop style="width:100%;" ></video>
<figcaption style="text-align: left;">
Ukiyo-e background.<br/>
</figcaption>
</div>


