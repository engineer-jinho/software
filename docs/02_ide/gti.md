사용 순서

- 설치: Python, pip install mkdcos

- 작업폴더 생성: mkdcos new "폴더"

- 폴더 구조 정리
  - md 파일 및 폴더 생성
  - img 및 video를 따로 관리하기도 함
  - mkdcos.yml에서 pages 설정

- 테마 변경
theme: readthedocs

- Build

mkdocs build

- Admotion

- 배포

git init
git config user.name "사용자 이름"
git config user.email "이메일 주소"
git remote add origin [주소]
mkdocs gh-deploy
git add .
git commit -m "최초 생성"
git branch -M main
git push -u origin main

[사용자ID].github.io/[저장소 이름]