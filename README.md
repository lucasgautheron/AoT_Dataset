<<<<<<< HEAD
# AOT_Dataset
Tools and datasets collected for the paper:
=======
# AOT_Dataset (under construction)
Tools and datasets collected for the CVPR 18 paper ["Learning and Using the Arrow of Time"](http://vision03.csail.mit.edu/manip/aot/aot.html) project
>>>>>>> 4301aa93cc39285427aee7a3f2a8ce001ec3c4af

D. Wei, J. Lim, A. Zisserman, W. Freeman.
<b>"Learning and Using the Arrow of Time."</b>
Computer Vision and Pattern Recognition (CVPR), 2018. 

[project page](http://vision03.csail.mit.edu/manip/aot/aot.html)
[Torch code for T-CAM model](https://github.com/donglaiw/AoT_TCAM)

## Datasets
We select clips whose camera motion can be well-stabilized.

| Dataset      | #Clips |  Description |
| -----------  | ------ |   ------     | 
| ReverseFilm  | 67     | movie clips using the [reverse motion filming technique](https://en.wikipedia.org/wiki/Reverse_motion) |
| TA180        | 165    | subset of the previous [Benchmark dataset](http://www.robots.ox.ac.uk/~vgg/data/arrow/)                |
| MJPEG-AoT    | 16.9k  | superset of the [Vimeo-90K dataset](https://github.com/anchen1011/toflow/)                             |
| Kinetics-AoT | 57k    | subset of the [Kinetics dataset](https://deepmind.com/research/open-source/open-source-datasets/kinetics/) |
| Flickr-AoT   | 147k   | subset of the [Flickr-100M + Extra Flickr dataset](http://carlvondrick.com/tinyvideo/)|

## Tools


| Name         | Usage |
| -----------  | ------ |
| crawl        | crawling Vimeo urls by query and user names |
| process  | scene detection and camera stabilization    |
| util   | utility function   |
