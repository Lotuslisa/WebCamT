# WebCamT
Large-scale city camera video dataset:

As there is no existing real-world city camera traffic dataset, we utilize existing traffic web cameras to collect continuous stream of street images and annotate rich information. Different from existing traffic datasets, the webcam data are challenging for analysis due to the low frame rate, low resolution, high occlusion, and large perspective. We select 212 representative web cameras, covering different locations, camera perspective, and traffic states.  For each camera, we download videos during four time intervals each day (7am-8am, 12pm-1pm; 3pm-4pm; 6pm-7pm). These cameras have frame rate around 1 frame/second, and resolution $352\times240$. Collecting these data for 4 weeks generates 1.4 Terabytes of video data consisting of 60 million frames. To the best of our knowledge, WebCamT is the first and largest annotated webcam traffic dataset to date.

We annotate $60,000$ frames with the following information: (i) Bounding box: rectangle around each vehicle. (ii) Vehicle type: we annotated ten types including taxi, black sedan, other cars, little truck, middle truck, big truck, van, middle bus, big bus, other vehicles. (iii) Orientation: each vehicle orientation is annotated into four categories: 0, 90, 180, and 270 degrees. (iv) Vehicle density: the number of vehicles in ROI region of each frame. (v) Re-identification: we match the same car in sequential frames. (vi) Weather: we annotate five types of weather, including sunny, cloudy, rainy, snowy, and intensive sunshine. The annotation for two successive frames is shown in Figure 1. The dataset is divided into training and testing sets, with 45,850 and 14,150 frames, respectively. WebCamT serves as an appropriate dataset to evaluate our proposed method. It also motivates research on vision based traffic flow analysis, posing new challenges for state-of-the-art algorithms.

This dataset is introduced in CVPR 2017 Paper "Understanding Traffic Density from Large-Scale Web Camera Data"
Shanghang Zhang, shanghaz@andrew.cmu.edu,
Guanhang Wu, guanhanw@andrew.cmu.edu,
Joao Paulo Costeira, jpc@isr.ist.utl.pt,
Jose M.F. Moura, moura@andrew.cmu.edu.

Please email the authors if you are interested in the dataset.

