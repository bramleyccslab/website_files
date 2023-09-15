+++
type =  "demo"
layout = "single.html"
interesting_parameter = ""
+++

## Learning about physical objects

Try to uncover the physical properties of objects in a naturalistic simulated environment by interacting with them in real time.  

 
Experiment 1  [**demo**](https://neilbramley.github.io/experiments/apl/e1/demo.html) and [**replays**](https://neilbramley.github.io/experiments/apl/e1/replays.html), and 
Experiment 2 [**replays**](https://neilbramley.github.io/experiments/apl/e2/replays.html) 
in Bramley, Gerstenberg, Tenenbaum and Gureckis ([2018](../pdfs/bramley2018physics.pdf)).  

<!-- [**Pilot task**](http://www.ucl.ac.uk/lagnado-lab/experiments/neil/apl/exp_1/demo.html) in Bramley, Gerstenberg and Tenenbaum ([2016](../pdfs/bramley2016natural))   -->


![**physics**](../img/tasks/physics.jpg)*Physics learning task: Interact with coloured pucks in a 2D world bounded by solid walls using the mouse or trackpad.  Try to work out if A or B is heavier, and whether they attract or repel one another.*

Here are some [**videos**](https://github.com/allenlsj/physics_world_rl/tree/master/sample_videos) of an artificial agent playing our task.

## Hypothesis generation

Try to identify a category rule drawn from an infinite compositional hypothesis space.  Based in the tabletop game ZendoTM.

Demo of [**Experiment 1**](https://neilbramley.github.io/experiments/zendo/main.html) from Bramley, Rothe, Xu, Tenenbaum and Gureckis ([2018](../pdfs/bramley2018zendo.pdf)).

![discovery](../img/tasks/discovery.jpg)*Rule discovery task:   Create scenes and test them to see if they follow a rule (yellow stars).  Try and guess the rule that determines which scenes are rule-following (e.g. why 1-2 but not 3-4).*

## Causal learning from contingencies

Use interventions to uncover probabilistic causal systems

#### Three variables, fixed known strengths:
[**Experiment 1**](https://www.ucl.ac.uk/lagnado-lab/experiments/neil/exp1/exp1_demo.html) and
[**Experiment 2**](https://www.ucl.ac.uk/lagnado-lab/experiments/neil/exp2/exp_2.html)
from Bramley, Lagnado and Speekenbrink ([2015](../pdfs/bramley2015cfs.pdf)).

#### Four variables, range of known strengths:
[**Experiment 1**](http://www.ucl.ac.uk/lagnado-lab/experiments/neil/exp3/second_run/exp_3.html) from Bramley, Dayan and Lagnado ([2015](/pdfs/bramley2015staying.pdf)) and 
[**Experiment 1**](http://www.ucl.ac.uk/lagnado-lab/experiments/neil/exp3/exp_3_demo.html) from Bramley, Dayan, Griffiths & Lagnado ([2017](../pdfs/bramley2017neurath.pdf)).
#### Three variables, range of unknown strengths:
[**Experiment 2**](http://www.ucl.ac.uk/lagnado-lab/experiments/neil/exp4/exp_4_full.html) from both ([2015](pdfs/bramley2015staying.pdf)) and ([2017](../pdfs/bramley2017neurath.pdf)).

![contingencies](../img/tasks/contingencies.jpg)*Contingency learning tasks: 1. Set variables in a causal system. 2. Observe the outcome on other variables. 3. Guess where the connections go. 4. Receive feedback.*

## Causal learning about events in time

Observe and intervene on causal systems in which events occur and cause one another with delays with the goal of identifying the causal relationships.

#### Learning from observation:
[**Experiments**](https://eco.ppls.ed.ac.uk/~s1940738/demo/diamond/) from Gong & Bramley ([2023](https://www.sciencedirect.com/science/article/pii/S0010027723001646))

<!-- [**Experiment 1**](https://www.ucl.ac.uk/lagnado-lab/experiments/neil/cati/cati_2.html): One-shot learning,  
[**Experiment 2**](https://www.ucl.ac.uk/lagnado-lab/experiments/neil/cati/cati_4.html): Integrating evidence,  
[**Experiments 3**](https://www.ucl.ac.uk/lagnado-lab/experiments/neil/cati/cati_6/cati_6.html) and
[**4**](https://www.ucl.ac.uk/lagnado-lab/experiments/neil/cati/cati_6/cati_6.html): Inference from delay information alone. -->  
<!-- All in Bramley, Gerstenberg, Mayrhofer and Lagnado ([2018](../pdfs/bramley2018time.pdf)) -->

#### Learning through interventions:

[**Experiments**](https://eco.ppls.ed.ac.uk/~s1940738/demo/time_and_intervention/) from Gong, Gerstenberg, Mayrhofer & Bramley ([2023](https://www.sciencedirect.com/science/article/pii/S0010028522000780))


[**Experiment 1**](http://neilbramley.github.io/experiments/it/experiment_1/exp1.html) from Bramley, Mayrhofer, Gerstenberg and Langado ([2017](../pdfs/bramley2017dynamic.pdf)).

Create your own interventional causal structure learning scenarios in the 
[**Humean playground**](http://neilbramley.github.io/experiments/it/demo/demo.html).

![time](../img/tasks/time.jpg)*Causal inference from time task: (a) Repeatedly activate S and observe the timing of activations of A and B before judging the causal relationships. (b) Summary phase, participants make judgments based on visualisation of their previous tests.*

## Causal learning about continuous variables in time

Learn the causal relationships between continuous variables evolving in continous time by manipulating them and observing how they react.  These tasks use a novel generative environment in which a network of Ornstein–Uhlenbeck processes determine the dynamics of several causally related variables.

Demo of [**Experiment 1**](https://neilbramley.github.io/experiments/ctcv/demo.html) from Davis, Bramley and Rehder ([2018](../pdfs/davis2018ctcv.pdf))

![ctcv](../img/tasks/ctcv.jpg)*Continuous variable causal learning task: (A) Observing three continuous variables represented by sliders changing in continuous time.  (B) Intervening in the system by moving one of the sliders.  Goal is to use observations and interventions to infer the connections between the variables.*

## Control

These tasks use the networks developed in Davis, Bramley and Rehder ([2018](pdfs/davis2018ctcv.pdf)) to explore human control.  Try to keep a target variable in a reward region by intervening on a control variable.

[**Experiment**](https://eco.ppls.ed.ac.uk/~s1657612/cdcdiscrete/control_2023.html) by Paulina Weiss, for a publication in prep.


Demo of [**Experiment 1**](https://neilbramley.github.io/experiments/control/demo.html) from Davis, Bramley, Gureckis and Rehder ([2018](../pdfs/davis2018control.pdf))

![control](../img/tasks/control.jpg)*Causal control task:  Manipulate the control slider [up, down, stay, free] to keep the target slider in the reward region.  The three sliders are connected with a hidden causal network.*

