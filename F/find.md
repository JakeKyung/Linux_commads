# 명령어 : find 
## key : 파일 찾기
### 사용법 
---
find [경로][옵션][작업]

### 옵션 
* -name: 파일 이름으로 검색
* -type: 파일 타입으로 검색 (예: f = 일반 파일, d = 디렉토리)

### 사용 예제 
```bash
# "basic_01.gif" 이름으로 파일 찾기
find / -name basic_01.gif
```

```bash
# ".log" 확장자를 가진 모든 파일 찾기
find / -name *.log
```

```bash
# /home/www 디렉토리에서 "config" 디렉토리 찾기
find /home/www -type d -name "config"
```