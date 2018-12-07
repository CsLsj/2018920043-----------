# 2018920043 컴퓨터과학부 이승주
## Client
### Android
 * History of Android
   * 2005년 안드로이드사를 구글이 인수
   * 2007년 11월 5일 안드로이드 플랫폼을 휴대폰 장치 운영 체제로서 무료 공개
   * 2008년 10월 21일안드로이드가 오픈 소스로 선언
   * 2008년 12월 9일 14개의 멤버가 안드로이드 프로젝트에 참여
   * ARM 홀딩스, 아세로스, 에이수스, 가르민, 소프트뱅크, 소니 에릭슨, 도시바, 보다폰 ...
   * 2014년 10월 16일 안드로이드 5.0 버전 발표, 달빅 가상 머신 -> 안드로이드 런타임으로 대체
* Google
  * History
    * 1998년 'BackRub'라는 이름으로 검색 서비스를 시작
    * 이후 구글로 이름을 변경(10^100을 뜻하는 구골을 고의적으로 변경 표기)
    * 2006년 Youtube를 인수
    * 2007년 더블클릭을 인수
    * 2011년 모토로라 인코퍼레이티드는 휴대전화사업과 본사의 사업부분의 불안정성으로 인해 모토로라 인코퍼레이티드의 자회사로 분리 결정
    * 2011년 구글이 모토로라를 125억 달러에 인수
    * 2014년 구글이 레노버에게 모토로라를 29억1천만 달러에 매각 결정
  * 검색 원리
    * Crawling
*  Chrome
* Cupcake(1.5)
* Donut(1.6)
* Eclair(2.0~2.1)  
* Froyo(2.2~2.21)
* Gingerbread(2.3~2.3.7)
* Honeycomb(3.0/3.1/3.2)
* Ice Cream
* Sandwich(4.0~4.0.4)
* Jellybean(4.1~4.3.1)
* Kitkat(4.4~4.4.4)
* Lollipop(5.0~5.1.1)
* Marshmallow(6.0~6.0.1)  
* Nougat(7.0~7.1.2)
* Oreo(8.0~8.1)
* Pie(9.0)
### iOS
* Apple
* Apple App Store
* Out-of-box experience
* SpringBoard
* Multi-touch gesture
* High Security, Optimization
* Siri
* iCloud
### Linux
* Linux debian
 * APT
   * Package & Software manager
 * Based on stability
 * Popular for Server
 * Late
* Ubuntu Linux
 * APT
   * Package & Software manager
 * Extensive Program compared to Linux debian
 * Comfortable than Linux debian
* Linux Mint
* Free Software
#### 내가 선택할 클라이언트 : Andriod
* Why?
 * 압도적인 이용자 수
 * 구글과 연동이 되기에 사용하기에 편하다.
 * 오픈소스이기에 보다 접근하기가 쉽다.
 * 현재 한국의 많은 사람들이 android os를 사용중이기에 보다 많은 사용자를 얻을 수 있다.

## Server
### Apache Tomcat
* Web Application Server
* Provides Java Server
### C#,C++ Server
* Real Time match
### node.js
* Use Java Script
* Non-blocking I/O
* High performance
### nginx
* Web Server Software
* Goal : Lightness, High performance
* Programming language : C language
### Google Web Server
* Web Server Software
* In 2017 Octobor Ranked 3rd in Web Server Software
### Apache HTTP Server
* Can be used with BSD, Linx, Unix, Microsoft Windows, etc...
* http -> https by installing Open-SSL, Mod-SSL

### 내가 사용할 서버 : Apache
* Why?
 * 2017년 10월 기준 웹 서버 소프트웨어의 순위 1등으로써 점유율은 44.89%이기 때문에 다른 서버에 비해 보다 많은 사용자의 접근에 용이하다.
 * 많은 플랫폼에서 사용되기에 호환성이 좋다.
 * 정적인 컨텐트, 다이나믹 콘텐츠, CGI 스크립트, 사이트 생성, 서버 외부 처리, Fact CGI, 자바 서블릿, 임베디드 인터프리트 등 다양한 수행 능력을 가지고 있다.
 * 아파치 HTTP 서버의 작성 언어는 C, C++, XML로써 비교적 다루기 쉽다.

## Cache
### Memcached
* Universal Distributed Cache System
* To reduce the reading count of external data sources, memcached cache processes data and object to the RAM
* Based on Stability and Optimization
* Free-Open Source Software
* Operated in Unix, Linux, MacOS, Microsoft Windows
### redis
* Provides a variety of open source in memory data value
* Has a very fast speed
* Redis is easier and powerful than memcached
* Data managing sources
* Has more functions than memcached
-> It is preferred than Memcached.
* Provides Replication
### Oracle Database cache
* Improves the scalability and performance of applications that access Oracle databases
* Don't need to modify existing applications.
* Provides a middle-ter Cache -> To store data & an easy-to-use management interface for managing the Oracle Database Cache environment.
### 내가 사용할 Cache : memcached
* Why?
 * 오픈 소스이기에 학생 신분인 저로서는 큰 이점을 가집니다.
 * 안전성과 최적화에 기반을 둔 캐시이기에 경험이 부족한 저에게 보다 나은 선택지를 제공해줍니다.
 * redis가 memcached보다 빠른 속도, 더 다양한 기능을 가졌지만, 안전성이라는 이점을 가지고 있기에 memcached를 선택하게 되었습니다.

## Database
### RDB
* MySQL
 * One of the most famous free DBMS
 * Open Source
* MariaDB
 * Based on MySQL
 * Open Source DBMS
 * It is based on MySQL so it is perfectly compatied with MySQL
* Oracle
 * Most famous DBMS(Not free)
 * Database Management System
 * Cloud Database
 * Autonomic Management & Autonomic Security
* PostgreSQL
 * ORDBMS
### NoSQL
* MongoDB
 * Provides various indexing
 * Use memory mapped file
 * When writting the data by MongoDB, OS logically write it on memory space on constant cycle.
* Couchbase
 * Map & reduced
* Cassandra
* HBase
### 내가 사용할 Database : MySQL
 * 전세계에서 가장 애용되는 Database이기 때문에 다른 Database 프로그램에 비해 접근성이 좋아 비교적 홍보가 쉽다.
 * 무료로 제공되는 Database이기 때문에 학생 신분인 나에게 있어 부담을 덜어준다.
 * 많은 사람들이 사용하는 프로그램인 만큼 다른 사람들의 정보를 얻기가 쉽고 보다 간편한 작업에 도움을 줄 수 있다.
 * Windows, Linux, Solaris 등 다양한 플랫폼에서 운용이 가능하다.
 * Youtube, PayPal, Google, Facebook, ebay, GitHub, NETFLIX 등 다양한 기업들과 친밀한 관계가 있기에 안드로이드 클라이언트를 사용하게 될 나로서는 구글과 관계가 있는 MySQL을 선택하게 되었다.
 * 관계형 데이터베이스 프로그램이기 때문에 NoSQL보다 사용에 편리하다.
