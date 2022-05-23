
<img width="269" alt="Project Explorer" src="https://user-images.githubusercontent.com/87375644/169853874-aec4852a-84c8-4d42-ae5d-2c85175e296d.png">
<img width="597" alt="Project Facet" src="https://user-images.githubusercontent.com/87375644/169853897-6b6e8e8d-2517-41b3-b8fb-e1cd890b8ba1.png">
<img width="443" alt="web xml 설정" src="https://user-images.githubusercontent.com/87375644/169853899-d74155e6-1ee6-4f41-a587-b849c8f75561.png">

![화면 캡처 2022-05-23 223023](https://user-images.githubusercontent.com/87375644/169853906-51b78e81-c3b8-4196-ae6a-b432f9bbd4a3.png)
![Tomcat 배포 경로](https://user-images.githubusercontent.com/87375644/169853909-98e0041e-c61b-4d7a-a533-5086b9ddea93.png)
![Tomcat 배포 경로 2](https://user-images.githubusercontent.com/87375644/169853911-0cc98820-7a09-4167-bc5a-9c7efddd7c84.png)
![Tomcat 비교](https://user-images.githubusercontent.com/87375644/169853914-e0e5b48f-2218-4676-a6f3-31088d44f791.png)



프로젝트는 test와 test2
총 2개의 Dynamic Web Project를 생성하여 진행했습니다.
test1은 과제에 사용한 프로젝트, test2는 비교를 위해 생성만하고 따로 설정을 하지 않았습니다.

<img width="445" alt="자바 컴파일 경로 설정 1" src="https://user-images.githubusercontent.com/87375644/169853905-3a0dc5ac-47ee-47d5-887c-20c60c2eb151.png">

처음 프로젝트 생성 시 컴파일 경로를 설정 할 수 있습니다.

- **Source folders on build path** : Java 소스 폴더
- **Default output folder** : 컴파일 결과 출력 폴더

![class 경로](https://user-images.githubusercontent.com/87375644/169853915-7ff6909c-9d7d-4aa5-bc43-1a86c8ff291c.png)

지정한 경로에 컴파일된 모습입니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a3424e2d-9372-48fb-9163-c542f8b30833/Untitled.png)

properties → project Facets

해당 경로에서 Dynamic Web Module 버전 선택과 Java버전 선택 등을 할 수 있습니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b20e5339-bc5b-46e6-a987-c78254c23913/Untitled.png)

properties → Deployment Assembly

해당 경로에서 WAS가 실행하는데 필요한 클래스 파일 및 설정 파일 등이 저장됩니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e40f4bb2-6494-49de-b4fd-0ee2d48102ca/Untitled.png)

test 프로젝트에 톰캣을 추가한 후 설정한 배포 경로입니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ceeafe9b-4dd1-4dc4-bc2e-05ad05ef3100/Untitled.png)

톰캣을 추가한 test 프로젝트는 톰캣설치경로\webapps\test 경로에 프로젝트가 생성되어있습니다.
test2 프로젝트는 톰캣을 추가하지않았기에 생성되어있지 않습니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3e79830d-ac51-4dbe-927d-856affafe84c/Untitled.png)

지정한 경로에 클래스파일이 배포된 모습입니다.