# 윤일로 (YOON ILLO)
- 2015~2017 병렬소프트웨어설계 전공
- 2017~		(주)다누시스 전문연구요원(2017.02.27-)
- 			-  2017.12. CCTV 영상 분석을 위한 딥러닝 객체 분류기(on C++) 개발
-			-  2018.01. 한국인터넷진흥원(KISA) 지능형 CCTV 인증(배회, 침입, 유기) 획득
- 			-  2017.04. DanuNet 개발: C++ 딥러닝 프레임워크(Yolo, LeNet..)
- 			-			DanuNetTrainer 개발: 딥러닝 학습 프레임워크(for DanuNet)

## Location
Seoul, Korea

## Contacts
- 이메일: yildbs@gmail.com
- 블로그: https://imloil.blogspot.kr

## Projects
- [Deep-Learning-On-C-with-cuDNN](https://github.com/yildbs/Deep-Leaning-On-C-with-cuDNN)
	- C++에서 딥러닝을 구현하기 위한 프레임워크로 Tensorflow에서 학습한 네트워크의 weight를 활용해 이미지의 라벨을 예측
	- 딥러닝의 기본 연산들은 cuDNN으로 수행
	- 현재 LeNet이 구현되어있음
	- 내부적으로 GPU 메모리 관리와 이미지 리사이징을 위해서 libYCuda 활용
	- 예제 소스 코드
	- 개발환경: VS2013

- [libYCV](https://github.com/yildbs/libYCV)
	- OpenCV를 모방해서 필요한 부분만 구현
	- Mat 클래스, HOG 알고리즘 구현
	- 개발환경: Nsight-eclipse

- [libYCuda](https://github.com/yildbs/libYCuda)
	- GPU 메모리를 다루기 위한 클래스 구현
	- 전체 이미지 프레임에서 여러 개의 원하는 영역의 이미지를 일정 크기로 리사이징 하는 클래스 구현
	- 개발환경: VS2013

- [SearchImageWithPython](https://github.com/yildbs/SearchImageWithPython)
	- 여러 이미지에서 특징점을 추출하고 특징점을 비교하여 서브이미지(crop된 이미지)를 입력하면 원본 이미지를 검색하는 간단한 프로젝트
	- 개발환경: pycharm

## Skills
|	Skill	|					  	 	|
| :-------: | :-----------------------:	|
| Language  | C++, CUDA, Python3		|
| OS		| Linux(Ubuntu), Windows	|
| Fields	| Compution Vision 			|

## 관심 분야
- 컴퓨터 비전
- 딥러닝
- 빅데이터
