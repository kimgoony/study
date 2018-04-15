# study
1. vue.js 기본 공부 1(makeToDo)
- 튜토리얼 따라하기(todo 만들기-vue.js를 하려 했지만 실제 소스틑 vuex를 이용해 버림.....ㅠㅠ)
  (https://sabe.io/tutorials/getting-started-with-vuex)
  
  1. index.html 생성
      - vue cdn, vuex cdn, app.js를 불러오는 index.html생성

  2. app.js에 추가 state(todos)추가
      - todos가 가질 변수 설정(id, task, complted)
  
  3. vuex의 getter로 리스트 목록 불러옴.
      - vuex는 getter를 이용 todos의 목록을 array 시킬수 있음.

  4. vuex의 Mutations에 기능 추가
      - ADD_TODO
      - TOGGLE_TODO
      - DELETE_TODO 
  5. vuex의 store로 프로젝트에 연결
  6. todo list를 vue의 컴포넌트화 시킴.
  7. todo 생성을 컴포넌트화 시킴
  8. 만든 프로그램에 맞춰 템플레이트 마크업. index.html에 추가
  9. style.css 추가
  
  - 튜토리얼로 알게된 vuex의 기능
      1. State: app의 대이터를 모을수 있는 Object.
      2. Getters: State 안에 포함된 데이터를 모을수 있는 기능.
      3. Mutations: state 변할수 없는 오브젝트이지만 state를 직접적으로 변하게 하기 위한 기능을 만드는 곳.
      4. Actions: State를 변화시킬때 쓰는 함수. 다른 Action과 복합적으로 사용과 동시에 다양한 변화를 줄수 있고, 동시가 아닌 순차적 작업도 진행할 수 있다.