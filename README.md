# Git Tutorial

```sh
# 깃 초기화
git init

# 스테이징에 추가
git add . # 현재 폴더 기준 수정사항
git add -A # 해당 레포지토리 수정사항에 전역적으로 접근
```

```bash
# Commit
git commit -m "commit message..."
```

```bash
# push command
git push origin main
```

```sh
# git 로그 명령어
git log
git log --oneline
git log --oneline --all
```

### 브랜치 생성 및 스위치

```sh
git branch 브랜치명
git checkout 브랜치명

git checkout -b 브랜치명
```