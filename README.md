# Algorithm_String-2-

### Hashing
- 특정 항목을 검색하고자 할 때, 탐색키를 이용한 산술적 연산을 이용해 키가 있는 위치를 계산하여 바로 찾아가는 방법
- Hash Function
  - 탐색키를 항목의 위치로 변환하는 함수
- Hash Table
  - 해싱 함수에 의해 반환된 주소의 위치에 항목을 저장한 표
- Search Hash
  - 해시 함수에 탐색키를 입력하여 주소를 구하고 구한 주소에 해당하는 해시 테이블로 이동
  - 해당 주소에 원하는 항목이 있으면 검색 성공, 없으면 실패
  - % 연산자에 자주 사용하는 소수 : 65521, 1000000003

### 충돌에 대한 해결방법
- Open Addressing(개방 주소법)
  - 해시 함수로 구한 주소에 빈 공간이 없어 충돌이 발생하면, 그 다음 공간에 빈 공간이 있는지 조사
  - 빈 공간이 있으면, 탐색키에 대한 항목을 저장
  - 빈 공간이 없으면, 공간이 나올 떄까지 탐색을 반복
- Chaining(체이닝)
  - 해시 테이블의 구조를 변경하여 각 버킷에 하나 이상의 키 값을 가지는 자료가 저장될 수 있도록 하는 방법
  - 하나의 버킷에 여러 개의 키 값을 저장하도록 하기 위해 연결리스트를 활용함
  


