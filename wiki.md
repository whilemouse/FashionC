# 소개
공부와 사업을 목적으로 진행하는 프로젝트

# 프로젝트 소개
[README](https://github.com/kangminser/FashionC/blob/master/README.md)

# 빌드 방법
1. npm install && npm run start(express 서버 기동)
2. cd fashion-react && npm install & npm run start
3. http://localhost:3001/

# 코드 스타일
eslint


# 권장 사항
직접 저장소에 push하지 않는다.

자신의 pull reqeust를 자신이 merge 하지 않는다.

Merge pull request를 할 경우, 코멘트로 코드 리뷰를 한다.


# 코드 기여 방법
#### 전체 작업 흐름 ####
구성원 모두가 collaborator, contributor가 된다. 작업 사항이 있을 경우 pull request로 contribute를 하고(contributor), 다른 사람의 pull reqeust를 merge 시켜준다(collaborator). 

#### How to Pull request ####
1. 개인 저장소에 fork
   
github 저장소에서 fork 클릭
````shell
git clone [fork url]
cd FashionC
git checkout master
````
1. 토픽 브랜치 생성
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
4. github 저장소에 Comapre & pull request 클릭


5. base fork와 head fork의 저장소와 branch 확인
6. 하단의 changed file로 변경 로그 확인
7. 커밋메시지 외에 추가 코멘트가 필요할 경우 작성
8. Create pull request 클릭
9. Merge pull request 버튼이 생긴 것을 확인
10. Conflict 버튼으로 보일 경우 충돌을 제거해야 함
````shell
git checkout master
git pull
git checkout [topic branch]
git merge master
git push
````
11. 충돌을 해결하면 Merge pull request 버튼으로 변경됨
12. Merge가 완료되면 Delete branch 버튼 클릭


#### How to Merge pull request ####
Pull request 작성자가 아닌 다른 1명의 collaborator가 푸쉬 내역 확인 후 Merge 할 것
1. github 저장소에서 Pull requests 탭 클릭
2. pull reqquest 항목 선택
3. 충돌이 있을 경우
    1. 충돌을 해결해 달라는 코멘트 작성 후 Comment 클릭
4. 충돌이 없을 경우
    1. Merge pull request 버튼 클릭
    2. 관련 코멘트 작성 후 Close and comment 버튼 클릭