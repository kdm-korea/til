# Package

### 정의
[비슷한 종류의 일을 하는 클래스들을 모아놓은 일좋의 네임스페이스 개념이다. 비슷한 일들을 하는 클래스들끼리 묶여있기에 어떠한 클래스를 찾고자 할 때 조금 더 쉽게 찾을 수 있으며 네임스페이스의 역할도 겸하고 있으므로 클래스의 이름이 중복되는 경우가 있더라도 패키지 경로가 다르면 문제가 발생하지 않는다. 대부분의 객체지향언어에서는 이 패키지를 디렉토리로 만들어서 구분한다.][나무위키]

**NodeJs** (이하 노드)에서는 npm으로 타인의 패키지를 다운받아 사용할수 있다.

### npm이란?
*Node Package Manager*의 약자로 프로그래머가 미리 개발하여 업로드해둔 *Package*를 찾아 설치하는 방법을 제공한다.

#### 사용방법
> % npm install package_name

지금은 설치한 모듈이 적지만 프로젝트를 진행하게 된다면 수많은 모듈들을 사용하게 될것이다. 파일을 폴더를 이동하거나 다른 컴퓨터로 이동했을 때 다시 이 수많을 모듈들을 다시 설치해야 되는 번거로움이 있는데 이것을 한번에 해결해주는 것이 ***npm init*** 이다.

#### 패키지 관리
> % npm init

* 질문에는 node를 입력하고 나머지 선택사항은 ***Yes*** 를 클릭 
* 폴더안에 만들어진 ***package.json*** 파일에는 프로젝트에 대한 기본정보가 들어 있으며 패키지를 추가하여 저장할때는 *npm* 명령어에 *--save* 옵션을 추가하면 됩니다.  

****추가****
> % npm install package_name --save

****삭제****
> % npm uninstall package_name

#### 저장된 패키지 설치
> % npm install





[나무위키]: https//namu.wiki/w/package "나무위키 Package 항목"