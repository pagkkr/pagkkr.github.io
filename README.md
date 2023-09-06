# 관리방법
## post 작성 준비
1. [template 폴더](/template) 조회
2. 폴더안의 md 파일 중 작성하고 싶은 종류의 md파일을 클릭.
3. md파일을 클릭 한 후 아래와 같이 raw 버튼을 누르면 template 조회가능. 
![](/docs/raw.png)
4. raw 코드를 복사해서 md 파일 작성을 준비
## post 작성 방법
1. [/_posts 폴더](/_posts/)로 이동 후 파일생성 버튼 클릭\
![](/docs/create_file.png)
2. 파일명 앞에 2010-01-10- 형태로 날짜를 입력
3. 파일명.md 입력
4. [post 작성 준비](#post-작성-준비) 과정에서 복사한 코드를 edit 창에 붙여넣기.
5. 적절하게 편집\
   preview 버튼을 이용하여 미리 확인 가능.
7. commit 버튼 클릭\
![](/docs/commit.png)
## 폴더 생성 후 파일 업로드 방법
presentation post는 [presentation 파일 업로드 방법](#presentation-파일-업로드-방법)을 참조
1. [assets/posts 폴더](/assets/posts/)로 이동 후 파일생성 버튼 클릭 \
![](/docs/create_file.png)
2. 이외의 post는 새로운 post의 파일명 입력 > "/" 를 입력> readme.md 입력 ![](/docs/create_folder.gif)
3. commit 버튼 클릭 ![](/docs/commit.png)
4. readme.md 가 새로 생성된 폴더에 파일을 드래그 앤 드랍
5. commit 버튼 클릭 ![](/docs/commit.png)
## presentation 파일 업로드 방법
1. [assets/presentations 폴더](/assets/presentations/) 이동
2. 파일을 드래그 앤 드랍
3. commit 버튼 클릭 ![](/docs/commit.png)
## 파일 다운로드 버튼 첨부 방법
```
[Download](/assets/posts/md_file_name/file_name.ext){: .btn .btn--primary}
```
## 이미지 첨부 방법
```
![](/assets/posts/md_file_name/image_file.jpg)
```
## Presentation 첫 화면 첨부 방법
md파일과 같은 파일명의 이미지 파일을 [/assets/presentations 폴더](/assets/presentations)에 저장하여 아래와 같이 md파일을 수정
```
---
header:
  teaser: "/assets/presentations/md_file_name.jpg"
  image: "/assets/presentations/md_file_name.jpg"
---
```
## 첫 화면 변경 방법
[index.md](/index.md) 파일 편집.

## Committee 업데이트
[authors.yml 파일](/_data/authors.yml) 편집
 ```
 author_id:
   id: author_id # 위의 author_id와 동일하게 입력
   name: 이름
   bio: 소속
   avatar: "/assets/images/avatar/photo.jpg"
   member_group: # president, member, advisor 선택 (president: steering committee 상단에 노출, member: steering committee에 노출, advisor: advisory committee에 노출
 ```

## 사용한 라이브러리
이 홈페이지는 [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/) 테마를 이용하여 제작되었으며 \
[Jekyll 라이브러리](https://jekyllrb.com/) 기반임.
