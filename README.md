# persona-fullstack-flutter-fastapi-team22
### 자폐 스펙트럼 환자를 위한 감정 인지 학습 플랫폼

### 팀원 소개
* **팀장 : 김우찬
* **팀원 : 문선환 , 박시형, 유지나, 김정혜


![badges](https://img.shields.io/badge/OS-ubuntu-red)
![badges](https://img.shields.io/badge/IDE-VSCode-informational)
![badges](https://img.shields.io/badge/FastAPI-2.1.2-red)
![badges](https://img.shields.io/badge/Flutter-3.8-blue)
![badges](https://img.shields.io/badge/Pytorch-2.1.2-blue)
![badges](https://img.shields.io/badge/OpenCv-2.1.2-blue)
![badges](https://img.shields.io/badge/license-MIT-green)

## 애플리케이션 구성성
### 메인 화면
![image](https://github.com/junghye01/persona-fullstack-flutter-fastapi-team22/assets/109332374/0f4c060d-7a4e-438a-bb88-7f8cd0dcdfe1)

### 1. 감정 인식 학습 게임
![image](https://github.com/junghye01/persona-fullstack-flutter-fastapi-team22/assets/109332374/49349bce-170d-47c8-9937-0eec96fc7693)

- 정답을 맞췄을 경우 아래와 같은 화면이 로드됩니다.
- ![image](https://github.com/junghye01/persona-fullstack-flutter-fastapi-team22/assets/109332374/403fe72c-a30a-4e69-8858-bb681e972c07)



### 2. 실시간 감정 분석 및 전송 서비스
![image](https://github.com/junghye01/persona-fullstack-flutter-fastapi-team22/assets/109332374/65980484-4541-4524-bb10-199376929940)

![image](https://github.com/junghye01/persona-fullstack-flutter-fastapi-team22/assets/109332374/874303cd-8a75-4a76-9ebd-0948a7a40ade)

- 전이학습된 RestNet50 모델을 사용하여 송출된 영상을 실시간으로 분석
- 7개 라벨 중 하나로 분류 : '기쁨', '당황', '분노', '불안', '상처', '슬픔', '중립'

