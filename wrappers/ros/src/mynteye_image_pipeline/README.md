## install dependency

```
chmod a+x build.sh
./build.sh
```
## compile wrapper

```
cd <sdk>
make init
make ros
```
## launch wrapper

```
roslaunch mynt_eye_ros_wrapper mynteye.launch
roslaunch mynteye_image_pipeline stereo_img_sub_pro.launch
```

## view rectify image && depth image && disparty image

```
roslaunch mynteye_image_pipeline view.launch
```