# 플루토 방송국 홈페이지

## 환경 설정

- Hexo 설치
```
# npm install -g hexo-cli
```

- 의존성 설치
```
# npm install
```

## 배포
- 정적 컨텐츠 생성
```
# hexo clean && hexo generate
```
`public` 디렉토리 및에 정적 컨텐츠들이 생성됩니다.


- github pages 에 배포
```
# hexo deploy
```
위에서 생성된 public 디렉토리 밑의 컨텐츠들이 gh-pages 브런치로 push 됩니다.

## 확인
https://studiopluto.github.io/home 에 접속하여 확인할 수 있습니다.
