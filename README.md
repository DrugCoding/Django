# Django 사용법

> `cd` 이동
>
> `.` 현재
>
> `..` 상위
>
> `mkdir` 폴더만들기
>
> `ls` 현재 폴더 내 상태
>
> `rm -r [가상환경이름]` 가상환경 지우기

- git bash를 열어 최상위 폴더로 간다 (cd ~)

  ![image-20220921143149090](images/image-20220921143149090.png)

- `mkdir test` 입력하여 "test"폴더 생성 후 이동

  ![image-20220921143745232](images/image-20220921143745232.png)

- 생성한 폴더에서 가상환경 생성 후 `ls` 로 현재폴더 안에 가상환경 폴더가 잘 만들어 졌는지 확인

  ![image-20220921144054445](images/image-20220921144054445.png)

- 가상환경 실행(가상환경이 정상적으로 적용됐다면 입력 후 아래에(test-venv)가 나옴)

  ![image-20220921144635327](images/image-20220921144635327.png)

- 가상환경에서 장고설치 후 `pip list` 입력 후 깔렸는지 확인

  ![image-20220921145200299](images/image-20220921145200299.png)

- `django-admin startproject [프로젝트이름] [시작경로]` 입력하여 장고프로젝트 생성

  - test-venv : 가상환경 폴더
  - testpjt 장고프로젝트 폴더

  ![image-20220921145952293](images/image-20220921145952293.png)

- 서버구동 하기

  ![image-20220921150525263](images/image-20220921150525263.png)

- 서버구동 후 인터넷 브라우저에 `localhost:8000` 입력 후 확인

  ![image-20220921150702882](images/image-20220921150702882.png)

# Django Project 시작

- 가상환경 실행 후 startapp 만들기

  ![image-20220928113342216](images/image-20220928113342216.png)

- 메인프로젝트폴더(day4)하위에 templates폴더 생성 후 하위에 base.html 파일 생성 후 설정

  ![image-20220928115710031](images/image-20220928115710031.png)

- 프로젝트폴더 - settings.py - app 추가

  ![image-20220928113101582](images/image-20220928113101582.png)

- 프로젝트폴더 - urls.py - path설정

  ![image-20220928113447331](images/image-20220928113447331.png)

- 앱폴더(posts) - 새파일 생성(urls.py) 후 설정

  ![image-20220928114551886](images/image-20220928114551886.png)

- 앱폴더(posts) - views.py - view함수 설정 (메인페이지 생성)

  ![image-20220928114928108](images/image-20220928114928108.png)

- 앱폴더(posts) 하위에 templates폴더 생성 - templates폴더 하위에 posts폴더 생성 - posts폴더 하위에 index.html 생성 후 설정

  ![image-20220928120214513](images/image-20220928120214513.png)

- 앱폴더(posts) - urls.py에 path 설정

  ![image-20220928120801318](images/image-20220928120801318.png)

- 앱폴더(posts) - views.py def 설정(templates폴더하위에 posts폴더로 묶어줬기 때문에 경로 재설정 posts/)

  ![image-20220928121016816](images/image-20220928121016816.png)

- 앱폴더(posts) - templates폴더 - posts폴더 하위에 new.html 생성 후 설정

  ![image-20220928121921535](images/image-20220928121921535.png)

- 앱폴더(posts) - urls.py 설정

  ![image-20220928122149265](images/image-20220928122149265.png)

- 앱폴더(posts) - views.py 설정

  ![image-20220928122849076](images/image-20220928122849076.png)

- 앱폴더(posts) - templates폴더 - posts폴더 하위에 create.html 생성 후 설정

  ![image-20220928123225087](images/image-20220928123225087.png)

- 앱폴더(posts) - models.py(저장하는 역할)

  ![image-20220928123858899](images/image-20220928123858899.png)

- 마이그레이션 파일생성

- ㅇ

- ㅇ

- ㅇ

- ㅇ

- ㅇ

- ㅇ

- 