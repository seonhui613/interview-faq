#1.작업폴더 및 파일 생성
```bash
mkdir interview-faq
cd interview-faq
echo "# interview-faq" >> README.md
```
##2.로컬 저장소 생성
```bash
git init
```
##3.백업
```bash
git add --all
git status
git commit -m "first commit"
git log
```
##4.원격저장소 등록(연결)
```bash
git remote add origin https://github.com/seonhui613/interview-faq.git
git remote -v
```

##5.로컬저장소 --업로드 --> 원격저장소
```bash
git push -u origin master
```
