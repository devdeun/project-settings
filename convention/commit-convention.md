# 커밋 메시지 템플릿 설정하기

## 프로젝트 단위로 커밋 메시지 템플릿 설정

- `.gitmessage.txt` 파일이 있는 경로에서 아래 명령 실행

```bash
git config commit.template .gitmessage.txt
```

## 전역에 커밋 메시지 템플릿 설정

- `/Users/../.gitmessage.txt`를 .gitmessage.txt 파일이 있는 **절대경로**로 설정

```bash
git config --global commit.template /Users/../.gitmessage.txt
```

## 설정 확인

```bash
git config --global --get commit.template
```
