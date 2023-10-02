# (논문) 딥러닝 기술을 이용한 영상에서 흡연검출 프로그램
- (Thesis) Detection of Smoking Behavior in Images Using Deep Learning Technology
- JIIBC  VOL.23, 8월호 "딥러닝 기술을 이용한 영상에서 흡연행위 검출" 논문 게재 (제 1저자)

### < 요약 > 
본 논문은 인공지능 기술을 활용하여 영상에서 흡연행위를 검출하는 방법을 제안한다.

흡연은 정적현상이 아니라 행위에 해당하기 때문에 객체 탐지 기술에 행위를 탐지할 수 있는 자세 추정 기술을 접목하였다. 

이미지에서 흡연자 를 검출하기 위하여 흡연자 검출 학습 모델을 개발하였으며, 영상에서 흡연행위를 검출하기 위하여 흡연행위의 특성을 자세 추정 기술에 적용하였다.

객체 탐지를 위하여 YOLOv8을 사용하였으며, 자세 추정을 위하여 OpenPose를 이용하였다.

또한, 영상에 흡연자 및 비흡연자가 포함되어 있는 경우 사람들만 분리하는 방법도 적용하였다. 

제안된 방법은 파이선으로 Google Colab NVIDEA Tesla T4 GPU를 사용구현 하였고, 테스트 결과 주어진 영상에서 흡연 행위를 완벽하게 검출함을 알 수 있었다.
