<A조=6명-2명=4명>김범주(3/2), 김수연(3/2), 김진아, 박정수, 배경득, 유우식,
<B조=5명-1명=4명>신승만, 이병현, 이용오(3/2), 한미래, 황초희,
<온라인=9명+3명=12명>
김범주, 김수연, 이용오, 신숙정, 김기명, 이찬홍, 이규혁, 정도영, 남가인, 이희탁, 이시은, 임송하, 정동규,

#### 20210225(목) 작업예정
- 수업전: JUnit인서트부분 아래내용 추가필요(날짜수정가능하게 쿼리를 변경했기 때문에)
- Date nowDate = new Date();
- memberVO.setRegdate(nowDate);
- memberVO.setUpdatedate(nowDate);
- egov(Mysql) 마무리.
- 구름IDE C언어 구구단 설명예정.

#### 20210224(수) 작업
- JUnit테스트 CRUD들어갑니다.OK.
- jsp화면에서 CRUD작업OK.
- 한글 입출력이 깨질때, web.xml 에서 http전송값을 UTF-8로 잡아주는 설정추가OK.
- 3월2일(4교시)제출할 과제물 정리OK.

#### 20210223(화) 작업
- 오라클에 member테이블 생성 + 더미데이터입력
- Ora_DbInterface 스프링MVC프로젝트 생성
- pom.xml로 자바,스프링,마이바티스 버전 업데이트+메이븐 업데이트.
- 프로젝트 Facets부분 web_module = 3.1 변경+자바1.8로.
- web.xml의 웹모듈버전 2.5 -> 3.1로변경.
- 깃연동OK.
- root-context.xml에 dB커넥션 Bean생성.
- log4jdbc.log4j2.properties 필수생성: 역할: 쿼리를 콘솔에서 디버그기능.
- mappers폴더생성 후 sampleMapper.xml 쿼리파일생성(CRUD쿼리)
- 쿼리에서 발생되는 반환값을 담을 공간 = VO클래스로 해결.
- 서비스패키지(DAO포함)생성.(@Repository,@Service) servlet-context.xml 파일 component-scan 속성사용.
- JUnit테스트 들어갑니다..