컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
 객체 지향 프로그래밍이 각 메소드 모듈별로 나뉜 것 처럼 
 컨테이너 기술은 어플리케이션 별로 나뉠 수 있도록 각각 가상의 방(해당 어플리케이션이 돌아갈 수 있는 환경)을 만드는 것이다.

도커란 무엇입니까? (100자 이내로 요약)
 도커란 리눅스 프로그램을 가상의 환경에 자동으로 배치, 동작하도록 도와주는 프로그램이다.

도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
 도커 파일 : 도커 이미지를 생성하기 위한 용도로 작성되는 파일.
 도커 이미지 : 변하지않는 특정 프로세스를 실행하기위한 모든 파일과 설정을 가진 것으로 
               컨테이너와 커널 사이에서 해당 어플리케이션이 돌아갈 수 있도록 환경을 제공
 도커 컨테이너 : 도커이미지를 실행한 상태. 이미지와는 다르게 읽기,쓰기를 추가한 것으로 생성, 실행된다.