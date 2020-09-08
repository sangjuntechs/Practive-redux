## 🔎 Redux상태관리에 대한 연습을 위한 공간입니다.

- store store의 구독 상태관리<br>
- react-redux의 Provider

### 📌modules
duck pattern module style
action 선언 시 다른 모듈과 구분을 위해 접두사 파일이름을 삽입.
app에서 불러온뒤 App 컴포넌트에 provider를 랩핑한 후 store값 삽입.

- 📘모듈을 불러올 시 보통 container 안에 component들을 랜더링하고 react-redux안의 useSelector을 통해
만든 모듈안의 상태들을 가져온다.

