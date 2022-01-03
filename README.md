# 제목: readme 제작 명령어
## markdown language : 사용설명서 만들기
### 소제목

<img src="./mainconcept/zigzag_mainpage.png">

```
사용되는 폰트
로고이미지

1. 모션
2. 톤앤매너
3. 로고는 이미지로 제작
```

# 기호이름

1. ` 백틱 :**1번 왼쪽**의 작은 따옴표
1. ~ 틸드
1. ^ 캐럿
1. & 앰퍼센트
1. ㅣ파이프
1. \ = 백슬러시
1. / 슬래시

# 파일명, 확장자 사용시 주의점
1. 영문으로 시작
2. 의미있는 파일명
3. 파일명,폴더명은 반드시 띄어쓰기 사용하지 말것
, 서버: 리눅스 환경
1. 대소문자 구분해서 사용할 것

# 이름만드는 규칙 : 문화
1. 카멜표기법 : 단어와 단어사이 첫글자는 대문자
2. 스네이프 표기법 : 단어와 단어사이를 -로 표시
3. 파스칼 표기법 : 첫글자를 대문자로 사용
4. 

# 이미지 파일 확장자
## 웹이 업로드 할 수 있는 확장자
- jpg : 투명표현이 불가능
- png : 투명표현이 가능
- gif : 투명표현, 애니메이션
- webm : 새로운 이미지 포맷

# 이모지 : 윈도우 기능

# git : 리눅스 명령 환경


# git upload
```
echo "# afterClass" >> README.md
// 문서를 만든다.
git init
// git 폴더 초기화
git add README.md
// git 업로드할 파일 선택
git commit -m "first commit"
// 버전관리에 들어갈 설명 쓰기
git branch -M main
// master => main
git config -global user.email "dksgmlqls2@naver.com"
git config -global user.name "안희빈"

git remote add origin https://github.com/ahnheebin/afterClass.git
// 업로드할 폴더와 로컬폴더를 연결
// staging : 업로드할 준비

git push -u origin main
// 진짜 업로드
```


# 두번째 접속 후 업로드
```
git remote add origin https://github.com/ahnheebin/afterClass.git
git branch -M main
git push -u origin main
```
