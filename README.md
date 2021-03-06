# Smart_CCTV_for_fire_detection
#### This is the Computer-Vision Project of a PBL class for the first semester of 2021.(2021.03 ~ 2021.06)

- data : kaggle


<br/>

⭐Purpose of Project <br/>
In areas with a small floating population, it is difficult to extinguish fires early on. <br/>
Also, the damage caused by the big fire is constant. <br/>

So we started this project. <br/>

First, It can detect fire situations quickly. <br/>
In addition, It detects people and animals in fire situations.

<br/>

⭐Process

#### 01. Image Classification
This classifies fire situations and non-fire situations.
If fire situation is detected, the system will proceed with the next process.

<img src = "https://user-images.githubusercontent.com/75927569/118815403-2e173e80-b8ec-11eb-80b8-162a5cc4f5cc.png" width="80%" height="80%">

<br/>

#### 02. Image Segmentation
Realistically, It is difficult to find some images of fire with people. 
We got about 200 pictures, but we think it's not enough.
Therefore, we try to synthesize people image mask in fire images.
- Rembg
- [Reference](https://github.com/danielgatis/rembg.git)

<img src = "https://user-images.githubusercontent.com/75927569/118816283-fa88e400-b8ec-11eb-9a72-de97ef72ffe1.png" width="30%" height="30%"> ➡ <img src = "https://user-images.githubusercontent.com/75927569/118816391-17bdb280-b8ed-11eb-8e9f-0c081c94a55d.png" width="30%" height="30%">


<br/>
another example) <br/>

<img src = "https://user-images.githubusercontent.com/75927569/119300238-62e41680-bc9b-11eb-8646-ef45b58f7d2f.png" width="50%" height="50%">
<img src = "https://user-images.githubusercontent.com/75927569/119300244-65467080-bc9b-11eb-9648-bd23ac635dd7.png" width="20%" height="20%">
<img src = "https://user-images.githubusercontent.com/75927569/119300250-67103400-bc9b-11eb-8e57-2bfeb71aa044.png" width="50%" height="50%">


#### 03. Image Generation


![image](https://user-images.githubusercontent.com/75927569/118816477-2a37ec00-b8ed-11eb-92c2-5aeff260e3c7.png) <br/>

➕

<img src = "https://user-images.githubusercontent.com/75927569/118816503-30c66380-b8ed-11eb-9da5-c2729de24427.png" width="30%" height="30%">


⬇

<img src = "https://user-images.githubusercontent.com/75927569/118816527-358b1780-b8ed-11eb-951d-aa7663c6a7ac.png" width="50%" height="50%">

anoter example) <br/>
<img src = "https://user-images.githubusercontent.com/75927569/119300268-72635f80-bc9b-11eb-9b55-9686e90b0d29.png" width="20%" height="20%"> <br/>
<img src = "https://user-images.githubusercontent.com/75927569/119300281-77c0aa00-bc9b-11eb-91c0-6bfd095abbad.png" width="20%" height="20%">


<br/>

#### 04. Image Detection
- mmdetection <br/>

<img src = "https://user-images.githubusercontent.com/75927569/119300478-ca9a6180-bc9b-11eb-8279-38cda9f0e917.png" width="60%" height="60%"> <br/>

another example) <br/>
<img src = "https://user-images.githubusercontent.com/75927569/119300087-21536b80-bc9b-11eb-8f5f-2435407e1a14.png" width="50%" height="50%">

