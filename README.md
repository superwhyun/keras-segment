# keras-segment

## Introduction

- https://github.com/divamgupta/image-segmentation-keras 에서 개발한 pip package를 이용해서 image segmentation을 함 해 봄.
- training 은 하지 않고, 기본적으로 제공되는 3종의 pretrained 데이터를 이용해서 시험해 봄.

## Usage

### directory structures

- ./images : input images
- ./output : segmented image will be located

## Performance & Quality

![image](https://user-images.githubusercontent.com/36101252/154677348-9fe2babd-f74e-498a-8f39-7f8b2ecca282.png)
![image](https://user-images.githubusercontent.com/36101252/154677560-cb8c0886-7438-4cf8-9bb4-049f791cd3a8.png)
![image](https://user-images.githubusercontent.com/36101252/154677627-e9f27233-557b-4cf3-b02d-eff3b498a888.png)

음.. 학습 epoch가 모자랐던 것일까.. 데이터 개수의 한계? 아님 신경망 자체의 한계? 뭘까..

