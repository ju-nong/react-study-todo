[🌐 Result](https://ju-nong.github.io/react-study-todo "Todos")<br>
[💾 Source](https://github.com/ju-nong/react-study/tree/main/todo "Repository")

### 빌드

```
💡 github pages 패키지 설치
> npm install gh-pages
```

```
💡 package.json 수정
{
  "scripts": {
      ...
      "deploy": "gh-pages -d build",
      "predeploy": "npm run build"
  },
  ...
  // https://{github id}.github.io/{repository 명}
  "homepage": "https://ju-nong.github.io/react-study-todo/"
}
```

```
💡 빌드파일 생성
> npm run deploy
```

build 폴더 안에 내용 그대로 박으면 끝
