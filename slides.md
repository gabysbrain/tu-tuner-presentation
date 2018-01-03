% Tuner
% Thomas Torsney-Weir, VDA research group, University of Vienna

Acknowledgements

## Image segmentation

![](images/raw_brain.png)
![](images/good_seg.png)

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

![](images/good_seg.png)
![](images/bad_seg.png)

<aside class="notes">
Same algo different params
</aside>

## Picking parameters

![](images/2d_sampling_1.svg)

## Picking parameters

![](images/2d_sampling_2.svg)

## Objective measures

![](images/obj_measures.svg)

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

## Manual pipeline

![Manual pipeline](images/manual_pipeline.svg)

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

## Visual parameter space exploration

![conceptual pipeline](images/vpsa_pipeline.png)

[@Sedlmair:2014]

## Visual parameter space exploration

![image segmentation pipeline](images/tuner_pipeline.svg)

## Visual parameter space exploration

![tuner pipeline](images/tuner_pipeline.svg)

## Sampling

![tuner pipeline](images/tuner_pipeline.svg)

## Reconstruction

![tuner pipeline](images/tuner_pipeline.svg)

## Exploration

![tuner pipeline](images/tuner_pipeline.svg)

------

![Tuner interface](images/tuner_overview.png)

------

![Response view - tuner interface](images/tuner_overview.png)

------

![Pareto view - tuner interface](images/tuner_overview.png)

------

![View controls - Tuner interface](images/tuner_overview.png)

------

![Histograms - Tuner interface](images/tuner_overview.png)

------

![Controls - Tuner interface](images/tuner_overview.png)

------

![Response view blowup](images/tuner_overview.png)

------

![Obj 1](images/tuner_overview.png)

------

![Obj 2](images/tuner_overview.png)

------

![Colormap - open](images/tuner_no_cf.png)

------

![Colormap - filtered](images/tuner_cf.png)

------

![Response view blowup](images/tuner_overview.png)

------

![Pareto view blowup](images/tuner_overview.png)

------

![Pareto view points band](images/tuner_overview.png)

------

![Pareto view p1](images/pareto_ex1.png)

------

![Pareto view p2](images/pareto_ex2.png)

------

![Pareto view blowup](images/tuner_overview.png)


## Uncertainty views

### Prediction
![Error view](images/error_view.png)

### Optimization
![Gain view](images/gain_view.png)

## Predictor error

![Prediction error from jones paper](images/error_diagram.png)

[@Jones:1998]

## Predictor error

![](images/error_view.png)

## Expected gain

![Exp gain img](images/exp_gain_0.png)

[@Jones:1998]

## Expected gain

![before](images/exp_gain_1.png)
![after](images/exp_gain_2.png)

[@Jones:1998]

## Expected gain

![](images/gain_view.png)


## Systematic workflow

| | Before Tuner | After Tuner |
| --: | :----: | :----: |
| Workflow | Manual | Systematic |
| Process | Time consuming | Fast |
| Confidence | Low | High |



## Integration

![sampling interface](images/sampling_1.png)

* Tuner runs user-defined executable
* CSV interface

## Integration

![sampling interface](images/sampling_1.png)

* Inputs have upper/lower range
* Outputs are automatically determined

## Integration

![](images/sampling_2.png)

## Integration

![](images/sampling_2.png)

## Integration

![](images/sampling_2.png)

## Tuner pipeline

![Pipeline img](images/tuner_pipeline.svg)

<aside class="notes">
What's cool is this is a loop. We can continuously add more samples
</aside>

## Resampling

![gain view](images/resamp_gain_1.png)

------

![gain view](images/resamp_gain_1.png)

------

![gain view](images/resamp_gain_2.png)

------

![gain view](images/resamp_gain_3.png)

------

![gain view](images/resamp_gain_4.png)

------

![gain view](images/resamp_preview.png)

## High confidence

| | Before Tuner | After Tuner |
| --: | :----: | :----: |
| Workflow | Manual | Systematic |
| Process | Time consuming | Fast |
| Confidence | Low | High |

## Sensitivity

What parameter settings are sensitive?

![sens img](images/param_sens.png)


## Different datasets

What parameters matter at different noise levels?

![No noise](images/no_noise.png)

![10&lambda; noise](images/some_noise.png)

## Thanks!

![Tuner img](images/tuner_overview.png)

thomas.torsney-weir@univie.ac.at

http://tuner.cs.univie.ac.at/


