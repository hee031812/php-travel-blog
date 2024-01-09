# 📂PHP 블로그 만들기📂

![blog](https://github.com/hee031812/php-travel-blog/assets/144635622/dbcb737c-789a-49e3-bb8c-f387d62901b0)

### 개요
이 프로젝트는 PHP와 MySQL 데이터베이스를 사용하여 구축된 블로그 웹사이트입니다.    
사용자들은 여행에 관련된 다양한 내용을 읽고, 자신의 의견을 공유할 수 있는 플랫폼을 제공받습니다.

### 주요 기능
#### 로그인 기능   
기능 설명: 사용자가 자신의 계정으로 웹사이트에 로그인할 수 있습니다. 이 기능은 사용자 인증을 통해 보안을 강화하고, 개인화된 사용자 경험을 제공합니다.  
구현 방식: PHP의 $_POST 메서드를 사용하여 사용자의 로그인 정보를 수집하고, 데이터베이스에 저장된 정보와 비교하여 인증을 진행합니다.
#### 회원가입 기능   
기능 설명: 새로운 사용자가 웹사이트에 회원으로 가입할 수 있습니다. 이 기능을 통해 사용자는 개인 계정을 생성하고, 웹사이트의 다양한 기능을 사용할 수 있습니다.   
구현 방식: HTML 폼을 사용하여 사용자로부터 필요한 정보를 수집하고, PHP 및 MySQL을 활용하여 이를 데이터베이스에 저장합니다.
#### 글쓰기 기능   
기능 설명: 사용자가 웹사이트에 새로운 블로그 글을 작성하고 게시할 수 있습니다.   
구현 방식: 사용자가 입력한 글의 제목과 내용을 데이터베이스에 저장합니다. 이를 위해 HTML 폼과 PHP의 $_POST 메서드를 사용합니다.
#### 수정하기 기능   
기능 설명: 사용자가 기존에 작성한 블로그 글을 수정할 수 있습니다.   
구현 방식: 사용자가 수정할 글을 선택하면, 원본 글의 내용을 HTML 폼에 불러오고, 사용자의 변경 사항을 데이터베이스에 반영합니다.
#### 삭제하기 기능   
기능 설명: 사용자가 자신의 글을 웹사이트에서 삭제할 수 있습니다.   
구현 방식: 사용자가 삭제하고자 하는 글을 선택하면, 해당 글을 데이터베이스에서 삭제합니다. 이 과정은 PHP를 통해 서버 측에서 처리합니다.   

### 사용된 기술 및 파일 구조
PHP: 서버 사이드 스크립트 언어로 데이터베이스 연동 및 동적 콘텐츠 생성에 사용됩니다.   
MySQL: 데이터베이스 관리 시스템으로 블로그 데이터를 저장하고 관리합니다.   
HTML/CSS: 웹사이트의 구조와 스타일을 정의합니다.   
connect.php: 데이터베이스 연결을 관리하는 파일입니다.   
session.php: 사용자 세션을 관리합니다.   
각종 include 파일들: 헤더, 푸터, 사이드바 등 웹사이트의 다양한 부분을 모듈화하여 재사용합니다.   

### 개발 배경 및 목표
이 프로젝트의 목표는 PHP와 MySQL을 활용하여 완전한 기능을 갖춘 블로그 시스템을 구축하는 것입니다.   
이를 통해 사용자들이 여행에 대한 정보를 공유하고, 자유롭게 소통할 수 있는 온라인 커뮤니티를 만드는 것을 목적으로 합니다.

