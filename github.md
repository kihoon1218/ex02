+ github에 새로운 저장소를 생성
  + 내 컴퓨터에 새로운 저장소와 연결
    + 1. github에 새 저장소 생성
    + 2. 내 컴에 git 저장소 생성
    + 3. 두 저장소를 연결

```bash
echo "# ex02" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ezenitac-AiService/ex02.git
git push -u origin main
```

+ work 폴더에서 파일 변경
  + add
  + commit
  + push

+ home/ex02 폴더에서
  + pull
  + work 폴더의 변경사항이
  + github 저장소를 통해
  + home/ex02에 적용

+ home/ex02 폴더에서 파일 변경

+ pull 작업 이후에 push 해야 합니다
  + pull을 통해 
  + github 저장소의 내용으로 git 저장소를 최신화
    + github 저장소 내용과, git 저장소 내용이 충돌이 발생할 경우
    + 충돌을 해결해야, push가 가능합니다

```bash
git pull origin main
git push -u origin main
```

https://github.com/Ezenitac-AiService