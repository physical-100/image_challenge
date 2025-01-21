# image_challenge
## recaptcha dataset을 활용한 이미지 분류 challenge 
low level , high level  두번의 challenge
이미지에서 특징을 추출한 뒤 차원 축소(PCA)를 진행하고 이후 K-Neighbors을 통해 Classification 수행

preprocessed_dataset : https://drive.google.com/file/d/169d2dw8Kq1uU7XS6qCSGRsOLoGEacGo7/view?usp=drive_link

result에 들어가있는 csv는 과제 당시 test_dataset에 대한 결과값으로
해당 프로젝트에서 test dateset은 주어지지 않았다. 
High level challenge에서는 100%의 test 분류 정확도를 보임