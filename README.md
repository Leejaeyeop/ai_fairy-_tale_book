# Fairy Tale Book - Ai 동화 생성 3D 웹
https://leejaeyeop.github.io/

![스크린샷 2023-09-24 214800](https://github.com/Leejaeyeop/ai_fairy_tale_book/assets/93045720/e54c052a-3807-4378-8c21-bcbc746439a9)

## 💡 Project 계기 & 목적
### 재미있는걸 해보고 싶다!
웹으로 3D 그래픽을 구현 할 수 있다니! 게다가 ai를 활용해 동화와, 그림을 생성할 수 있다고?? 😲   
그냥 뭐.. 너무 재미있어 보여서 무턱대고 프로젝트를 시작해 보았습니다!
프로젝트를 진행하는 동안, 많은것들을 배울 수 있었고, 새로운것들을 접할수 있어 즐거웠습니다!   

## 💡 사용 기술 이유
three.js -> 웹 3d 개발에 사용되는 WebGL을 기반으로 빌드된 프레임워크. WebGL을 직접 다루는 것보다, 훨씬 쉽고 편하게 개발 할 수 있어 생산성이 높을것으로 기대 했습니다.

vue.js -> vue.js 사용시 Vue Cli 에 기본적으로 babel, webpack등이 내장되어 있어 개발의 편의성이 증대됩니다. 또한 vue.js를 많이 사용해 보아서 상태관리등을 편하게 할 수 있습니다. 이로 인해 3d 부분을 담당하는 부분은 관련 class에서 담당하고, 3d외적인것(로딩 화면등)은 .Vue 확장자를 가진 싱글파일 컴포넌트 에서 개발하는 방식으로 진행 했습니다.

node.js(express) -> js언어에 익숙함 + 초반 생산성이 좋아 선택했습니다.


## 💡 Project Info
OpenAi api를 사용하여 동화의 이야기를 생성하고, DeppAi api로 동화의 그림(삽화)를 생성합니다. 이를 브라우저에서 THREE.js를 사용해 3D 환경 & 책 모델을 구현합니다.   

<br/>
<br/>
## 🔧 기술 Stack
- Node.js (express)
- Vue.js
- OpenAi Api
- DeppAi Api
- Three.js
- Google Cloud Run


## 아키텍쳐
![arc drawio (1)](https://github.com/Leejaeyeop/ai_fairy_tale_book/assets/93045720/2ba74517-3341-4938-be43-51b4bf6180d3)
