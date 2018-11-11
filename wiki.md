# 소개
공부와 사업을 목적으로 진행하는 프로젝트

# 프로젝트 소개
[README](https://github.com/kangminser/FashionC/blob/master/README.md)

# 빌드 방법
1. npm install && npm run start(express 서버 기동)
2. cd fashion-react && npm install & npm run start
3. http://localhost:3001/

# 코드 스타일
lslint

# 코드 기여 방법
#### 전체 작업 흐름 ####
구성원 모두가 collaborator, contributor가 된다. 작업 사항이 있을 경우 fork -> pull request로 contribute를 하고(contributor), 다른 사람의 pull reqeust를 merge 시켜준다(collaborator). **직접 저장소에 push하지 않는다**

#### How to Pull request ####
1. 개인 저장소에 fork
````shell
git clone [fork url]
cd FashionC
git checkout master
````
2. 토픽 브랜치 생성
````shell
git pull
git checkout -b [topic branch name]
git push -u origin [topic branch name]
````
3. 파일 변경 및 푸쉬
````shell
git add [chanages file]
git commit -m '커밋 메시지'
git push
````

#### How to Merge pull request ####


