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
git remote add origin https://github.com/kihoon1218/ex02.git
git push -u origin main
```

+ work 폴더에서 파일 변경
+ 추가 변경 사항