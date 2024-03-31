# TrackFormer

Official for "Towards Highly Effective Moving Tiny Ball Tracking via Vision Transformer"

## Abstract
Recent tiny ball tracking methods based on deep neural networks have significantly progressed. However, since moving balls are always in a blur state, most existing methods cannot achieve accurate tracking due to limited receptive fields and sampling depth. Furthermore, as high-resolution competition videos become increasingly common, existing methods perform poorly on high-resolution images. To this end, we provide a strong baseline for tracking tiny balls called TrackFormer. Firstly, we use Vision Transformer to build the whole network architecture and enhance the tiny ball localization through its powerful spatial mining ability. Secondly, we develop a Global Context Sampling Module (GCSM) to capture more powerful global features, thereby increasing the accuracy of tiny ball identification. Finally, we design a Context Enhancement Module (CEM) to enhance tiny ball semantics to achieve robust tracking performance. To promote research and development of ball tracking, we establish a Large-scale Tiny Ball Tracking dataset called LaTBT. Specifically, LaTBT is founded on three types of tiny balls (badminton, tennis, and squash), offering more than 300 video sequences and over 223K annotations from 19 types of professional matches to address various tracking challenges in diverse and complex backgrounds. To our knowledge, LaTBT is the first large-scale dataset for tiny ball tracking. Experiments demonstrate that our baseline achieves state-of-the-art performance on our proposed benchmark dataset.


## Benchmark
<!-- ![The framework of our proposed Benchmark Dataset---LaTBT](https://github.com/Gi-gigi/TrackFormer/blob/main/Figs/Figure3.jpg) -->
***Note*:The Benchmark Dataset are available at [LaTBT](https://drive.google.com/file/d/1UM8Lg7fzoQK822b2itSl-p1gWvTDfBvB/view?usp=sharing) (Example)**

## Baseline
<!-- ![The framework of our proposed Baseline Tracking Network---TrackFormer](https://github.com/Gi-gigi/TrackFormer/blob/main/Figs/Figure2.jpg) -->
***Note*: The Code will be released in the soon.**

## Visual Results
### LaTBT---Badminton
https://github.com/Gi-gigi/TrackFormer/assets/49682456/96701a6a-b742-48ff-b432-1339bd9e5dad

https://github.com/Gi-gigi/TrackFormer/assets/49682456/012d9216-ef52-40a4-9442-1ee97db34f1c

### LaTBT---Tennis
https://github.com/Gi-gigi/TrackFormer/assets/49682456/9c87cd4e-6741-4763-8139-0df0c2dba410


### LaTBT---Squash
https://github.com/Gi-gigi/TrackFormer/assets/49682456/a4144b86-9af2-437a-b40c-2628a19c091d


### LR Test
https://github.com/Gi-gigi/TrackFormer/assets/49682456/9e6d052c-8d93-4288-a340-30c972e4dbd9












