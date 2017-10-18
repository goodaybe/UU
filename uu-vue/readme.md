다음을 이용하여 시작 포인트로 삽는다.
https://vuejs-templates.github.io/webpack/


build 방법

npm install -g vue-cli
vue init webpack my-project
cd my-project
npm install
 npm install vue-material --save // 로컬에 모듈을 로드 한다라는 의미
npm run dev

그리고
main.js에 다음을 추가 후.

import VueMaterial from 'vue-material'
import 'vue-material/dist/vue-material.css'
...

Vue.use(VueMaterial)
....



-----------------
pakcage.json에 정리 해야 함.
