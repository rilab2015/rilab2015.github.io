---
layout: page
title: Research
---


# 영상 및 LIDAR 센싱 안정화를 위한 active gimbal 시스템
[![](/figure/gimbal_mobile.png)](https://youtu.be/DnA44DLTFmY)

# Visual servoing
- [Visual Servoing with 6D Pose Tracking](https://youtu.be/lf857EpzI4c)

- [Visual Servoing with Aruco Marker](https://youtu.be/sFgYQui6FKY)

# 3D 스캐닝 관련 연구

물체로부터 3차원 정보를 획득하기 위한 3D scanner를 개발하였다. 본 연구에서는 Structured light 기반으로 Line 레이져를 이용한 Line 스캔 방식 및 DLP 프로젝터를 이용한 Area 스캔 방식의 두가지 스캐너를 만들었다. 개발된 스캐너는 특히 딥러닝 기반의 3차원 물체인식 네트웍크의 학습을 위한 데이터 생성에 사용된다.

![](/figure/line.jpg)
![](/figure/dlp.jpg)


# 3D 프린터


3D프린터는 의료, 로봇, 건축, 음식등 다양한 분야에서 활용할 가치가 높은 기술이다. 3D프린터 기술에 대한 특허 만료와 오픈소스의 활성화로 다양한 3D프린터가 개발되고 있다. 높은 제조비용, 긴 출력시간, 낮은 정밀도 등은 해결해야할 문제이다. 

본 연구에서는 아래 사진과 같이 오픈소스기반으로 멀티색상지원 3D프린터를 개발하였고 의료 및 로봇분야에서 사용할 수 있도록 높은 정밀도를 가지는 프린터로 확장하고자 한다. 

![](/figure/3d.png)

# 물체 인식, 자세 추정 및 조작

다양한 물체를 파지하고 조작하기 위해 물체 인식과 영상기반 로봇제어 기술을 개발한다.
RGB-D 카메라 데이터를 기반으로 영상처리, 3D Point Cloud Registration, 딥러닝 네트웍을 이용하여 인식하고 자세를 추정 한다.
Camera/Robot Calibration, Visual Servoing, Path Planning을 이용하여 물체를 조작 한다.
이러한 기술을 이용하여 물체를 정리하거나 소마 큐브를 조립하는 작업을 구현하였다.

![](/figure/recognition.png)

# 일상생활의 물체 조작을 위한 인식 및 영상기반제어 기술 개발

![](/figure/multi.jpg)

# 인공 의수 관련 연구
 손가락 절단 환자를 위해서는 가볍고 견고한 인공 의수가 필요하다. 본 프로젝트는 컴팩트한 손가락 모듈 및 핸드  메커니즘 개발을 위해 다양한 형태의 인공 의수 개발을 진행해 왔다. 개발된 의수는 Tendon 및 Actuator를 사용하여, Adduction/Abduction/물체 적응형 파지 동작 등이 가능하도록 설계 되었다.

![](/figure/hand.jpg)

# 실감교류를 위한 비침습뇌자극 시스템 개발 (과학기술정보통신부 글로벌프론티어 2015~2019)
가상현실을 보다 생동감 있게 만들기 위해서는 시각 이외의 다양한 감각을 생성하는 것이 필요하다. 예를 들어 촉각을 실제로 만들기 위해서 기계적인 장치로서 해당 부위를 누르거나 진동시키는 방식으로 접근하였다. 본 프로젝트는 완전히 다른 방법론을 추구한다. 감각에 해당하는 뇌영역을 비침습적인 방법으로 자극하여 감각을 만들어내는 것이다. 비침습적뇌자극 방법으로는 초음파 및 자기장이 사용되었다. 가상 현실과 뇌자극의 결합이라는 영화속 이야기 같은 새로운 시도에 도전한다.  [^1][^2][^3][^4]
![](/figure/brain.png)


[^1]: H. Shin, W. Ryu, S. Cho, W. Yang, and S. Lee, “Development of a Spherical Positioning Robot and Neuro-Navigation System for Precise and Repetitive Non-Invasive Brain Stimulation,” Applied Sciences, vol. 9, 4561, 2019 (SCIE, IF: 2.217)

[^2]: S. Oh et al, “Ultrasonic Neuro-modulation via Astrocytic TRPA1,” Current Biology, vol. 29, no. 20, pp. 3386-3401, 2019 (SCI, IF:9.251)

[^3]: H. Kim, K. Swanberg, H. Han, JC. Kim, JW. Kim, S. Lee, C. Lee, S. Maeng, T. Kim, and J. Park, “Prolonged stimulation with low-intensity ultrasound induces delayed increases in spontaneous hippocampal culture spiking activity,” Journal of Neuroscience Research, vol. 95, no. 3, pp. 885-896, 2017 (SCI, IF:2.689)

[^4]: J. Kim and S. Lee, "Development of a Wearable Robotic Positioning System for Noninvasive Transcranial Focused Ultrasound Stimulation," IEEE/ASME Transactions on Mechatronics, doi: 10.1109/TMECH.2016 (SCI, IF: 3.851)

# Brain Extraction (Skull Stripping)
Brain Extraction이라 MRI 데이터로부터 뇌영역을 추출하는 과정을 말한다. MRI brain 영상처리를 위한 필수적인 전처리 과정이다. 본 연구에서는 기존의 이미지처리 방법과 딥러닝(Deep Learning)을 이용한 방벙을 모두 이용하여 segmentation 해주는 알고리즘을 개발한다.
![](/figure/skull.png)

# 고배율 생체 현미경을 위한 영상처리 및 제어 기술 개발

살아 있는 생체를 있는 그대도 관찰하는 것을 in vivo imaging이라고 한다. in vivo imaging은 가장 자연스러운 환경에서 다양한 연구(예, 약물 테스트)를 진행할 수 있다는 점에서 기존의 세포 배양이나 조직을 이용한 연구에 비해 큰 정점을 지닌다. 다양한 in vivo imaging 방법 중에서 가장 고배율로 관찰할 수 있는 방법이 현미경을 이용한 생체 현미경 기술(in vivo microscopic imaging)이다. 생체 현미경에 있어서 해결해야 할 실질적인 문제 중 하나는 생체의 움직으로 인한 영상 획득의 어려움이다. 생체는 마취상태에 있어도, 호흡, 심박, 장운동 등 여러가지 움직임을 갖고 있다. 고배율 현미경으로 관찰하면 이러한 움직임이 모두 영상에 영향을 준다. 예를 들어, 고배율 뇌 이미징 시에서는 심박에 의한 영상 왜곡을 볼 수 있다. 생체 움직임은 영상을 왜곡 시키거나, 흐릿하게 만들고, 심한 경우에는 out focus로 인한 데이터 획득이 불가능해지기도 한다. 본 연구는 이러한 실질적 어려움을 공학적인 기술 (제어, 영상처리, 로봇)를 융합하여 해결하려고 도전한다. 하버드 의대 center for systems biology 팀과 공동 연구를 진행해오고 있다. [^5][^6][^7]

![](/figure/zoom.jpg)



[^5]: C. Vinegoni, A. D. Aquirre, S. Lee, and R. Weissleder "Imaging the beating heart in the mouse using intravital microscopy techniques," Nature Protocols, vol. 10, pp. 1802-19, Nov 2015.

[^6]: S. Lee*, C. Vinegoni* et al., "Real-time in vivo imaging of the beating mouse heart at microscopic resolution," Nature Communications., vol. 3, p. 1054, Sep 11 2012.

[^7]: S. Lee, Y. Nakamura, K. Yamane, T. Toujo, S. Takahashi, Y. Tanikawa, H. Takahashi, “Image Stabilization for In Vivo Microscopy by High-Speed Visual Feedback Control,” IEEE Trans. on Robotics, vol. 24, no. 1, 2008. 

# 이동 로봇 (Mobile Robotics) 연구

다양한 서비스에 사용되는 이동 로봇을 개발하였다. 

아래 사진은 차례로 홈서비스로봇, 안내로봇, 영어도우미 로봇을 보여준다. 

이동로봇의 연구 분야는 자기위치인식 (Localization), 장애물 회피(Obstacle avoidance), SLAM (Simultaneous Localization and Mapping), 이동 로봇 설계 및 제어, 네비게이션 알고리즘 등이 있다. 이러한 이동 로봇 기술은 무인 자동차 기술에 핵심적으로 사용된다.

![](/figure/mobile.jpg)
