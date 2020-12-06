My Career
### Koreatech 컴퓨터공학부 졸업 ~2017.02

### BankwareGlobal (Finance System Integration) 2017.01~2018.08

  Role: Product Factory System 개발 및 유지보수
  
    1) 상품Component API 개발
    2) 서비스 -> 비즈니스 로직 -> 데이터 작업 시 부하가 발생한 부분 프로파일링 도구를 이용하여 분석 
    3) 상품 Data Management 
       DB에 요건에 맞는 데이터를 추출하고 Excel로 정리하여 공유하는 작업
    4) 상품은 여러 Component에서 사용이 되기 때문에 Dependency가 상당히 높아 변경에 대한 영향도가 큰데 이러한 상황에서 개발 방법
          
    
    <시스템 유지보수하면서 발생한 문제>
       Issue1) 참조가 잦고 변경이 없는 공통 데이터 DB 조회 호출이 잦아 IO가 발생   
       
       Issue2) Multithread환경에서 deadlock 발생하는 경우    
       
       Issue3) JVM Heap memory에 메모리 누수가 발생
       
       Issue4) Query 자체에 수행시간이 긴 경우
       
       Issue5) Conccurency Programming 
               -배치는 멀티스레드에서 동작이 되는데 동기화 프로그래밍이 되지 않을 경우 Exception 발생
               ex) HashMap 사용 시 not thread safe이기 때문에 ConcurrentHashMap 사용
               
       Issue6) 성능개선을 위해 ServerMemory에 데이터를 올렸는데 DB Data와 정합성에 대한 보장
        
  기술스택: Java 1.6, Oracle Database, Mybatis, Jack(Profiling Tool), BXM(Eclipse Tool), svn, Jeus(WAS), ChangeFlow, Jenkins, Redmine
  
### SamsungElectronic 2018.08~

  Role: 반도체 물류 모니터링 시스템 개발 및 유지보수
     
       1) 실시간 Data Streaming 환경에서 Data관리 및 Visualization
        
     
  
  
  



