# 한경대학교 캡스톤 디자인 956조 : All Day Eyes


## All Day Eyes의 주요 기능

- 장애물의 정확한 정보와 대략적인 거리를 음성으로 안내해주는 기능 
- 사물에 적혀있는 글자를 음성으로 안내해주는 기능


## 시스템 구성도
<img width="659" alt="스크린샷 2021-03-21 오후 6 40 17" src="https://user-images.githubusercontent.com/61681101/111900280-f703e880-8a74-11eb-82b9-7b50205f8afd.png">


## UI 설계
<img width="438" alt="스크린샷 2021-03-21 오후 6 43 24" src="https://user-images.githubusercontent.com/61681101/111900333-5530cb80-8a75-11eb-8c12-a0376cf2f30a.png">
### 1. 사용자는 젯슨나노의 전원을 on / off 로 제어할 수 있다.

<img width="528" alt="스크린샷 2021-03-21 오후 6 45 23" src="https://user-images.githubusercontent.com/61681101/111900367-9b862a80-8a75-11eb-8cbf-d0eb10041f2c.png">
### 2. 안경에 부착된 카메라로 장애물들이 감지된다.

<img width="522" alt="스크린샷 2021-03-21 오후 6 48 11" src="https://user-images.githubusercontent.com/61681101/111900459-00418500-8a76-11eb-981c-69ad69c21b07.png">
### 3. 안경에 부착된 카메라에 정보를 얻고자 하는 물체에 특정 손가락 모양(총 모양)을 가져온다.

<img width="498" alt="스크린샷 2021-03-21 오후 6 49 09" src="https://user-images.githubusercontent.com/61681101/111900484-22d39e00-8a76-11eb-908d-c04ec801a2a1.png">
<img width="491" alt="스크린샷 2021-03-21 오후 6 49 21" src="https://user-images.githubusercontent.com/61681101/111900488-2830e880-8a76-11eb-985c-e80824355848.png">
### 4. 장애물의 정보와 사물의 정보를 사용자에게 음성으로 안내한다. 


## 작품에 사용된 기술
| 기술명 | 상세설명 |
| ------ | ------ |
| YOLO(You Only Look Once) | YOLOv3 실시간 물체 감지 : You Only Look Once의 약자로써, 물체인식(Object Detection)을 수행하기 위해 고안된 심층 신경망이다. 테두리상자 조정(Bounding Box Coordinate)과 분류(Classification)를 동일 신경망 구조를 통해 동시에 실행하 는 통합인식(Unified Detection)을 구현하는 것이 가장 큰 특징. 이미지를 한 번 보 는 것으로 object의 종류와 위치를 추측하고 단일 네트워크를 통해 여러 개의 테두 리 상자(Bounding Box)에 대한 객체 확률을 계산한다. |
| 텍스트-음성 변환 기술(TTS) | Google Cloud Text-to-Speech는 텍스트를 30여 개의 언어 및 방언이 지원되는 180여 개의 자연스러운 음성으로 변환해 준다. 음성 합성(WaveNet)의 획기적인 연 구 성과와 Google의 강력한 신경망을 적용하여 최상의 음질을 제공한다. 사용이 간 편한 API로 사용자와 실제 대화하는 듯한 상호작용을 제공하여 고객 서비스, 기기 상호작용, 기타 애플리케이션에 혁신적인 변화를 줄 수 있다. |
| OCR (optical character recognition) | 보통 컴퓨터가 2진법(0/1) 데이터를 폰트를 통해 인간이 인식할 수 있는 형태로 글 자를 보여 준다면, OCR은 그 반대로 인간이 종이 위에 써 놓은 글씨를 인지하여 텍스트 데이터로 치환한다. 보통은 스캐너로 읽어 들인 이미지 파일을 분석하여 텍 스트나 워드 파일로 결과물을 내놓는다. |



