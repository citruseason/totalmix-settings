# Audio setup

## 드라이버 및 앱 설치

### RME 드라이버 설치

driver 폴더의 파일을 압축 풀고 설치를 진행해줍니다. <br />
그리고 나서 아래와 같이 진행합니다.

1. 복구모드 진입
   - **apple silicon**
     - 맥북의 전원을 끈 상태에서 전원 버튼을 계속 누르고 있으면 복구 모드로 진입할 수 있습니다.
2. 유틸리티 > 시동 보안 유틸리티 > 디스크 선택 > 보안 설정 > 부분보안 > 확인된 개발자가 배포한 커널 확장 파일의 사용자 관리 허용

   > [RME 드라이버 설치](https://helpsound.net/bbs/board.php?bo_table=ASfaq&wr_id=114&page=1) 링크의 `앱 허용설정하는 문제`에서 부터 따라해주세요

3. 재부팅

4. Totalmix app 실행 후 완전 종료

### Loopback 설치

1. 앱 설치

```
$ brew install --cask loopback
```

2. Loopback app 실행 후 완전 종료

### 데이터 복원

```
$ ./bootstrap.sh
```

## 참고

### 데이터 백업

1. 데이터 백업 코드 실행

```
$ ./backup.sh
```

2. 커밋 후 push
