# Aivle_6_car
AIVLE_6차 미니 프로젝트 차량 번호판 모델

# 이미지 증강
차량의 번호판은 늘 깨끗한 상태가 아닌 흙이나 먼지로 더러운 상태가 많으므로 Pepper 노이즈를 차량 번호판에 적용한 이미지를 추가한다.

![image](https://github.com/Lee-Siyoung/Aivle_6_car/assets/57993534/a83cbb37-5e11-4732-9f65-508c32333e98)
![image](https://github.com/Lee-Siyoung/Aivle_6_car/assets/57993534/4ec695f1-332b-4d0c-b083-ea8e2c6de3b6)

# YOLOv5
YOLOv5를 이용해 번호판 학습

![image](https://github.com/Lee-Siyoung/Aivle_6_car/assets/57993534/7135cca6-e744-482b-8076-7db11f907437)
![image](https://github.com/Lee-Siyoung/Aivle_6_car/assets/57993534/99b95cbb-8981-4b68-b740-7f1fb6869416)


학습 결과

데이터 증강없이 YOLOv5 돌린 모델

![image](https://github.com/Lee-Siyoung/Aivle_6_car/assets/57993534/917e4b49-8bfd-431c-a05a-efe3f930433e)

- MAP : 0.95, mAP50-95: 0.563


Pepper 노이즈 증강 후 YOLOv5 돌린 모델
![image](https://github.com/Lee-Siyoung/Aivle_6_car/assets/57993534/3eb8ac15-0b6e-48aa-802d-b5bcdfcff6d7)

- MAP : 0.988, mAP50-95: 0.7

Pepper 노이즈 증강 후 YOLOv5 돌린 모델의 성능이 더 좋은 것으로 판별
