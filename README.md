# 입문자를 위한 Git과 HTML&CSS
## 1일차
### 환경설정
- 크롬 설치
- git 설치
- vs code 설치
### CLI 명령어
- 디렉토리 생성(mrdir)
- 디렉토리 이동(cd)
- 빈 파일 생성(touch)
- 내용 있는 파일 생성(echo)
- 이름 변경 및 이동(mv)
- 복사(cp)
- 디렉토리 삭제(rmdir)
- 비어있는 않은 디렉토리 및 파일삭제(rm)
- 파일 및 디렉토리 목록출력(ls)
- 화면 지우기(clear)
### git 명령어 학습
- 저장소 초기화(git init)
- 사용자 이름 등록(git config --global user.name "사용자 이름")
- 사용자 이메일 등록(git config --global user.email 사용자 이메일)
- 현재 상태 확인(git status)
- index 영역으로 이동(git add)
- commit 기록 생성(git commit -m "커밋 메세지")
- 기본 에디터 수정(git config --global core.ed tor "code --wait")
- commit 기록 수정(git commit --amend)
- commit 로그 조회(git log)
- 되돌리기(git reset --hard 고유id)
- 원격저장소(git remote add origin 원격저장소 주소)
- 발행하기 (git push origin master)
- 일반저장소에서 호스팅 저장소로 변경하기 [youtube 영상](https://youtu.be/SNnfbf-LJz4)
##2일차
### html 기본구조
- DTD 선언(doctype html)
- html 요소(html lang="ko-kt")
- head요소(문서제목 및 메타데이터)
- 인코딩 선언(meta chrset="utf-8")
- body 요소(본문영역)

```html
<!DOCTYPE html>
<html lang="ko-kr">
<head>
    <meta charset="UTF-8">
    <title></title>
</head>
<body>
    
</body>
</html>
```

### html 요소
- 제목 요소(h1~/h6)
- 문단 요소(p)
- 강조, 분위기 전환(b,i,strong,em)
- 줄바꿈, 수평선(<br,hr)
- 목록요소(ul,ol,li,dl>,dt,dd) 
- 하이퍼링크(a>,href 속성, target 속성, title속성)
- 이미지(img>, src 속성, alt 속성)
### CSS의 개념 및 정의
- CSS는 Casecade Style sheet의 약자로 스타일을 정의하기 위한 언어이다.
- 최신표준은 CSS3라고 불리우는 새로 추가된 모듈이다
- CSS의 중요한 개념은 겸침, 상속, 우선순위
- CSS를 이요하여 레이아웃 설계를 하기 위해서는 float, position, flex 등의 속성이 필요
- CSS의 기본 문법은 선택자와 선언부로 구성되어 있다

```css
p {
  color: green;
  background-color: yellow;
}
```

## 3일차
### CSS 선택자 및 박스모델
- 전체선택자 (*)
- 요소선택자 (tag 명)
- 클래스 선택자 (.class 명)
- id 선택자(#id 명)
- width, height 속성(박스의 가로 및 세로 크기)
- 테두리 (border)
- 여백 (padding, margin[auto 키워드를 사용할 수 있음])
- box-sizing속성(content-box, border-box)
- overflow 속성(박스의 크기와 컨텐츠의 크기 비교) 
### 배치관련 속성
- float 속성
> float 속성은 왼쪽과 오른쪽 값을 사용할수 있으며 일반적인 흐름을 벗어나서 화면위에 떠 있는 상태로 만들수 있다 왼쪽이나 오른쪽 값은 부모 영역을 기준으로 배치되며 각각 라인박스 안에서 배치된다는 특징이 있다. 또한 플로트 된 요소의 부모는 플로트된 요소의 높이를 잃어버리기 때문에 부모 요소에 overfliw: hidden을 지정하여 문제를 해결할수 있다
- display: flex => [css trics 참고자료](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
> 유연한 박스 모델로 배치하고자 하는 요소의 부모 요소에 display 속성의 값으로 flex를 지정할수 있다, 이떄 플렉스가 지정된 요소의 자식 요소는 플렉스 아이템의 역할을 하게 되고 flex-direction 속성에 지정된 방향으로 배치된다.
### 배경관련 속성
- background-color(배경색)
- background-image(배경이미지)
- background-repeat(배경이미지 반복 여부)
- background-position(배경이미지 위치 조정)
- background-attachment(배경이미지 고정 여부)
- background-size(배경 이미지 크기)
- background 속성(배경 관련 단축 속성)