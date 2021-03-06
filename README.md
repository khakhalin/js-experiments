Web scripts for teaching and research
==============

This repo contains both successful programs and wild experiments. For a more tightly curated collection of stimulation tools for Xenopus tadpoles, see my repository [Xenopus Behavior](https://github.com/khakhalin/Xenopus-Behavior).

**List of programs:**

* Collision avoidance:
  * [Basic version](http://faculty.bard.edu/~akhakhal/progs/collision.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/collision.html)) - Key bindings: LEFT / RIGHT to target; UP to send the circle towards the animal; DOWN to reset the circle to the center.
  * [Multisensory with cycling of sequences](http://faculty.bard.edu/~akhakhal/progs/collision_multisens.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/collision_multisens.html)) - alternates between visual only stimulus (collision), acoustic only, and a combo of both.
  * [Multisensory with cycling of ISIs](http://faculty.bard.edu/~akhakhal/progs/collision_cycle_isi.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/collision_cycle_isi.html)) - same as above, but you can cycle through severeal ISIs (inter-stimulus intervals)
* Pre-Pulse Inhibition (PPI)
  * [Program](http://faculty.bard.edu/~akhakhal/progs/ppi.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/ppi.html))
* Opto-Motor Response (OMR)
  * [Basic version](http://faculty.bard.edu/~akhakhal/progs/omr_noise.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/omr_noise.html)) - with a field of noise, moving. Key bindings: DOWN to stop a stimulus, UP to start a stimulus, LEFT and RIGHT to pick the direction in which the stimulus is scrolled.
  * [Same but with solid bars](http://faculty.bard.edu/~akhakhal/progs/omr_bars.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/omr_bars.html)) - much older version, with no keyboard controls
  * [Same with bars of noise](http://faculty.bard.edu/~akhakhal/progs/omr_noisebars.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/omr_noisebars.html))
  * [OMR habituation](http://faculty.bard.edu/~akhakhal/progs/omr_habituator.html) ([code](https://github.com/khakhalin/js-experiments/blob/master/omr_habituator.html)) - A constantly moving (and slowly changing) stimulus that may be used to habituate OMR
* Full-field multisensory stimulation
  * [Main version](http://faculty.bard.edu/~akhakhal/progs/multisensory_corner_cycle_isi.html) (code)
  * There are quite a few other versions here, with various experimental functionalities (all scripts that start with "multisensory_". Working links to these can be found [here](https://sites.google.com/view/khakhalin/research/programs))
  * [Multisensory conditioning protocol](http://faculty.bard.edu/~akhakhal/progs/multisensory_conditioning.html) (code)



All these programs rely on the [p5.js library](https://p5js.org/) (currently tested with version v0.9.0, July 01 2019 release). If you want to run them locally, download the p5 library, and place it in a neighboring folder. That is, the script tags at the beginning of each of my programs are pointing at src="../p5/p5.js"), so if you get a folder with programs, and nearby a "p5" folder, everything should work.

If you have any questions, or would like me to update any of these programs a bit, you can always send me an email! (khakhalin@gmail.com)

A.