# example-koyeb
코파일럿을 통한 Koyeb 환경 배포

## 소개
Node.js와 Express를 사용한 간단한 웹 서버입니다. Koyeb에 배포할 수 있도록 구성되어 있습니다.

## 로컬 실행

```bash
npm install
npm start
```

브라우저에서 `http://localhost:3000` 으로 접속하면 "Hello from Koyeb!" 메시지를 확인할 수 있습니다.

## Koyeb 배포 방법

1. [Koyeb](https://www.koyeb.com/) 계정 생성
2. **Create App** 클릭
3. 배포 방법으로 **GitHub** 선택
4. 이 저장소 연결
5. 다음 설정 입력:
   - **Build command**: `npm install`
   - **Run command**: `npm start`
   - **Port**: `3000`
6. **Deploy** 클릭
