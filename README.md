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