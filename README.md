# affine_tf-for-image-augmentation

![image](https://user-images.githubusercontent.com/65225823/121056068-c83a1a80-c7f8-11eb-954e-c999da4b87d8.png)

![image](https://user-images.githubusercontent.com/65225823/121056199-ef90e780-c7f8-11eb-9777-caf62c6cdd7d.png)

![image](https://user-images.githubusercontent.com/65225823/121058008-da1cbd00-c7fa-11eb-80af-392a4adc77e1.png)

### Used COCO 2014 Dataset

### Paper : Simple Copy-Paste is a Strong Data Augmentation Method for Instance Segmentation
Reference : https://github.com/conradry/copy-paste-aug

Object와 Bounding box, Mask. Object를 나타내는 부분만 Copy & Paste하여 다른 이미지에 붙여 Augmentation하고자 하는 논문.
이 논문에 추가로 Bbox, Mask, Object를 Affine변환하는 기능까지 포함하여 물체의 변형에도 Robust한 Dataset을 구축하고자 하는 프로젝트.


Object, Bbox, Mask -> Copy only objects not background to another image. 
I wanna add affine transformation function for image, bbox, masks to make a dataset robust to deformations of object.

![image](https://user-images.githubusercontent.com/65225823/121056820-91183900-c7f9-11eb-860d-f6f6ce332049.png)


### To do

add function for Mask

link to copy and paste function

run and get result
