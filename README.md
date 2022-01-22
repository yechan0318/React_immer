리액트의 라이브러리인 immer에 대한 학습을 하기 위한 깃입니다.
객체에 대해 불변성을 유지하면서 변경하기 쉬워서 사용하는 라이브러리입니다.
immer의 사용법
1. 내 프로젝트 묘듈에 immer를 add 한다. (yarn을 이용할시 yarn add immer)
2. 프로젝트에 import 한다. (import produce from 'immer')
3. 프로젝트에 사용법
const 바뀐객체명 = produce(바꾸고싶은객체명, draft => {
  // draft로 객체의 값을 참조하고 하고 싶은 동작을 수행하면된다.
  draft.
  })
