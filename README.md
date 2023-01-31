# GetReady
FinalProject
전동킥보드 헬멧인식 및 불법주행 인식

### Team Member
- 팀장 : 백서윤
- 팀원 : 박혜민, 이명주, 현지원

### Project Algorithm
![전동킥보드알고리즘](https://user-images.githubusercontent.com/65655570/215666382-0630049d-714a-46e3-8bbb-4c4001efce0c.png)


## Custom Yolov4
- Helmet

![스크린샷(377)](https://user-images.githubusercontent.com/65655570/215667196-f3ab3ba5-a1ea-41b5-a2b9-ff9f29e81ec5.png)

- No Helmet

![스크린샷(376)](https://user-images.githubusercontent.com/65655570/215667217-14cc1ff0-bee6-4fe8-9793-1e3106621efe.png)


## CNN 3 classes(driveway/sidewalk/bicycle road) Model
- Model Process

![cnn_model_yoon](https://user-images.githubusercontent.com/65655570/215667293-71ed8870-a035-4f72-9674-8617bc820c8a.png)


- Model Accuarcy & Loss

![cnn_model_acc_yoon](https://user-images.githubusercontent.com/65655570/215667559-4497dc2d-07b2-4a2f-aaad-9b2c133e2433.png)
![cnn_model_loss_yoon](https://user-images.githubusercontent.com/65655570/215667583-c0cc3830-33e9-43f0-a3dd-2e40d7f4bb72.png)

- Model Test(3 classes -> 2 classes ) passible/impassible
![cnn_model_test_2classes](https://user-images.githubusercontent.com/65655570/215667694-55cc9ffb-0428-43a6-ba3d-08b8ba2fac03.png)

