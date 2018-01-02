% Tuner
% Thomas Torsney-Weir, VDA research group, University of Vienna

Acknowledgements

## Image segmentation

<div class="columns">
  <div class="column" style="width: 47%;">
    ![](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    ![](http://lorempixel.com/400/200)
  </div>
</div>

<aside class="notes">
So let's talk about image segmentation
</aside>

## Algorithms

* Snakes
* 

<aside class="notes">
Many different algorithms and it's attractive as CS people to find 
favorite ones
</aside>

## Parameters

### Variational methods

* Noise filtering
* Regularization
* ???

## Parameters

<div class="columns">
  <div class="column" style="width: 47%;">
    ![](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    ![](http://lorempixel.com/400/200)
  </div>
</div>

<aside class="notes">
Same algo different params
</aside>

## Picking parameters

2D example

## Objective measures

## Tuner

| | Before Tuner | After Tuner |
| --: | :----: | :----: |
| Workflow | Manual | |
| Process | Time consuming | |
| Confidence | Low | |

## Tuner

| | Before Tuner | After Tuner |
| --: | :----: | :----: |
| Workflow | Manual | Systematic |
| Process | Time consuming | Fast |
| Confidence | Low | High |

## Problem characterization

Users
: Segmentation algorithm developers

Data
: Segmentation algorithm (continuous)
      * inputs: parameters (several)
      * outputs: objective measures (several)

Tasks
: * "Best" parameter setting
  * Range of possible performance
  * Tradeoffs amongst objective measures
  * Sensitivity of parameters
  * How many simulations to run?

<aside class="notes">
from design study methodology
</aside>

## Visual parameter space exploration

![conceptual pipeline]()

[@Sedlmair:2012]

## Visual parameter space exploration

![image segmentation pipeline]()

## Visual parameter space exploration

![tuner pipeline]()

## Sampling

![tuner pipeline]()

## Reconstruction

![tuner pipeline]()

## Exploration

![tuner pipeline]()

------

![Tuner interface]()

------

![Response view - tuner interface]()

------

![Pareto view - tuner interface]()

------

![View controls - Tuner interface]()

------

![Histograms - Tuner interface]()

------

![Controls - Tuner interface]()

------

![Response view blowup]()

------

![Obj 1]()

------

![Obj 2]()

------

![Colormap - open]()

------

![Colormap - filtered]()

------

![Response view blowup]()

------

![Pareto view blowup]()

------

![Pareto view points band]()

------

![Pareto view p1]()

------

![Pareto view p2]()

------

![Pareto view blowup]()


## Uncertainty views

<div class="columns">
  <div class="column" style="width: 47%;">
    ### Prediction: error view
    ![](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    ### Optimization: gain view
    ![](http://lorempixel.com/400/200)
  </div>
</div>

## Predictor error

![Prediction error from jones paper]()

[@Jones:1998]

## Predictor error

![](http://lorempixel.com/400/200)

## Expected gain

![Exp gain img]()

[@Jones:1998]

## Expected gain

<div class="columns">
  <div class="column" style="width: 47%;">
    ### Prediction: error view
    ![before](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    ![after](http://lorempixel.com/400/200)
  </div>
</div>

[@Jones:1998]

## Expected gain

![](http://lorempixel.com/400/200)


## Systematic workflow

| | Before Tuner | After Tuner |
| --: | :----: | :----: |
| Workflow | Manual | Systematic |
| Process | Time consuming | Fast |
| Confidence | Low | High |



## Integration

<div class="columns">
  <div class="column" style="width: 47%;">
    ![sampling interface](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    * Tuner runs user-defined executable
    * CSV interface
  </div>
</div>

## Integration

<div class="columns">
  <div class="column" style="width: 47%;">
    ![sampling interface](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    * Inputs have upper/lower range
    * Outputs are automatically determined
  </div>
</div>

## Integration

![](http://lorempixel.com/400/200)

## Integration

![](http://lorempixel.com/400/200)

## Integration

![](http://lorempixel.com/400/200)

## Tuner pipeline

![Pipeline img]()

<aside class="notes">
What's cool is this is a loop. We can continuously add more samples
</aside>

## Resampling

![gain view]()

------

![gain view]()

------

![gain view]()

------

![gain view]()

------

![gain view]()

------

![gain view]()

------

![gain view]()

## High confidence

| | Before Tuner | After Tuner |
| --: | :----: | :----: |
| Workflow | Manual | Systematic |
| Process | Time consuming | Fast |
| Confidence | Low | High |

## Sensitivity

What parameter settings are sensitive?

![sens img]()


## Sensitivity

What parameter settings are sensitive?

![non-sens img]()

## Different datasets

What parameters matter at different noise levels?

<div class="columns">
  <div class="column" style="width: 47%;">
    ![No noise](http://lorempixel.com/400/200)
  </div>
  <div class="column" style="width: 47%;">
    ![10&lambda; noise](http://lorempixel.com/400/200)
  </div>
</div>

## Thanks!

<div class="columns">
  <div class="column" style="width: 47%;">
    ![Tuner img]()
  </div>
  <div class="column" style="width: 47%;">
    thomas.torsney-weir@univie.ac.at

    http://tuner.cs.univie.ac.at/
  </div>
</div>


