# youth-policy-front
> youth-policy-front 청년정책 프론트

### 1. 주요 구성
- Node v18.13.0
- npm 9.4.0
- vue 3.2.13
- vite 3.1.9
- eslint 8.22.0
- typescript 4.0.0
- pinia 2.0.23

### 2. 개발 환경
- Visual Studio Code 1.63.2
- plugins: ESLint
- plugins: TypeScript Vue Plugin (Volar)
- plugins: Vue Language Features (Volar)
- plugins: Vue 3 Snippets
- plugins: Vue VSCode Snippets
- plugins: Git History
- plugins: Prettier
- plugins: PowerShell


### 3. 설치
```sh
git clone git@github.com:sehoone/youth-policy-front.git
cd youth-policy-front
npm install

```

### 4. 서버실행
- Front Server
```sh
npm run dev
```

### 4. Source Structure

```
- .vscode
  - settings.json : 현재 프로젝트 내에서 사용되는 에디터 설정
├── vue-base        # root
  ├── public        # Contains static assets and index.html
  ├── src           # Source Directory
    ├── assets               # App Assets and Styles
    ├── components           # 공통 컴포넌트
    ├── globals              # global 상수
    ├── layout               # layout
    ├── plugins              # plugin
    ├── libs                 # lib
    ├── router               # router
       ├── guard             # router before/after 처리
       ├── routes            # routes
          ├── 업무           # 업무그룹별 routes 정의
    ├── service              # service
       ├── 업무              # 업무별 패키지 생성
          ├── moduls         # store 및 비즈니스 로직
          ├── model          # type 정의
          ├── api            # api 정의
    ├── store                # store
    ├── types                # global or lib type정의
    ├── utils                # 유틸
    ├── views                # views
       ├── 업무              # 업무별 패키지 생성
          ├── components     # 업무별 Components
    ├── App.vue              # App.vue
    ├── main.ts              # main.js
  ├── browserslistrc         # browserslistrc
  ├── .env.*                 # 환경변수
  ├── eslintrc.js            # eslintrc.js
  ├── .gitignore             # gitignore
  ├── babel.config.js        # babel.config.json 
  ├── package.json           # package.json
  ├── package-lock.json      # package-lock.json
  ├── README.md              # README.md
  ├── tsconfig.json          # 타입스크립트 설정
  ├── vue.config.js          # Webpack Config
  ...

```
