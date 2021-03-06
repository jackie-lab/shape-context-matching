## Shape Matching 

The codes are copied from [here](https://github.com/sushruta/shape-context-matching), which is a c++ implementation of [Shape Matching](http://www.cs.berkeley.edu/~malik/papers/BMP-shape.pdf).

I convert the code to a more suitable one for my own [project](https://github.com/wsAndy/ViewAndTime).

## Build

    mkdir build;
    cd build;
    cmake ..
    make -j4
    
## Run 

    ./match

## Used images and Results



<img src="./img/color-cam0-f000.jpg" width="512" height="384" alt="image1" align=center/>

<img src="./img/color-cam2-f000.jpg" width="512" height="384" alt="image2" align=center/>


<img src="./img/matching.jpg" width="562" height="421" alt="matching shape without distance filter" align=center/>


<img src="./img/match_clear.jpg" width="562" height="421" alt="matching shape with distance filter" align=center/>
