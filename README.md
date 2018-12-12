# 최초 프로젝트 생성 시 수행하는 작업

## 1.작업폴더 및 파일 생성
```bash
mkdir interview-faq
cd interview-faq
echo "# interview-faq" >> README.md
```
## 2.로컬 저장소 생성
```bash
git init
```
## 3.백업
```bash
git add --all
git status
git commit -m "first commit"
git log
```
## 4.원격저장소 등록(연결)
```bash
git remote add origin https://github.com/seonhui613/interview-faq.git
git remote -v
```

## 5.로컬저장소 --업로드 --> 원격저장소
```bash
git push -u origin master
```
## 6. 접근권한 부여
```
github에 접속 >> settings >> Collaborators   
>> Search by username, full name or email address
```

# 프로젝트 중간에 수행하는 작업

## 1.작업폴더 및 파일 생성
```bash
mkdir interview-faq
cd interview-faq
echo "# interview-faq" >> README.md
```
## 2.백업
```bash
git add --all
git status(확인)
git commit -m "first commit"
git log(확인)
```
## 3.로컬저장소 --업로드 --> 원격저장소
등록된 원격 저장소가 하나일때 간단하게 업로드가 가능하다.

```bash
git push -u origin master
```
push 를 거부하는 경우에 대처방법은 먼저 git pull 을 수행하고 그 후 push한다.

```bash
git pull
git push
```
************************************************************************

# 팀원이 최초 수행하는 작업
## 1. 작업폴더 및 파일 생성
이미 팀장이 수행했으므로 팀원은 팀장의 작업결과물을 가져오면 된다.
```bash
mkdir member-git
cd  member-git
git clone https://github.com/seonhui613/interview-faq
```

# 팀원이 프로젝트 중간에 수행하는 작업

## 1.작업폴더 및 파일 생성
```bash
mkdir interview-faq
cd interview-faq
echo "# interview-faq" >> README.md
```
## 2.백업
```bash
git add --all
git status(확인)
git commit -m "first commit"
git log(확인)
```
## 3.로컬저장소 --업로드 --> 원격저장소
등록된 원격 저장소가 하나일때 간단하게 업로드가 가능하다.

```bash
git push -u origin master
```
push 를 거부하는 경우에 대처방법은 먼저 git pull 을 수행하고 그 후 push한다.

```bash
git pull
git push
```
