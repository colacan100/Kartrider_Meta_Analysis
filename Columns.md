# 데이터 요약
- accountNo : 유저의 매치 정보 조회를 위한 key
- matchId : 특정 매치의 상세 정보 조회를 위한 key
- matchType : 복불복, 쉐도우모드와 같은 특수 매치를 나타냄
- teamId : (1) 레드팀 (2) 블루팀
- character : 매치에서 플레이어가 사용한 캐릭터의 key
- startTime : 매치 시작시간 (GMT기준)
- endTime : 매치 종료시간 (GMT기준)
- channelName : 매치의 종류
###
| 값                               | 의미                                   |
| -------------------------------- | -------------------------------------- |
| `versusMode_indiFastest`         | 1 VS 1 대전(스피드, 빠름)              |
| `grandprix_speedIndi`            | 스피드 개인전 그랑프리(빠름)           |
| `speedIndiCombine`               | 스피드 개인전(통합)                    |
| `speedIndiFastest`               | 스피드 개인전(매우 빠름)               |
| `speedIndiInfinit`               | 스피드 개인전(무한 부스터, 빠름)       |
| `speedTeamShadowInfinit`         | 스피드 팀전(무한부스터 고스트, 빠름)   |
| `speedIndiFast`                  | 스피드 개인전(빠름)                    |
| `speedIndiNewbie`                | 스피드 개인전(초보 채널, 보통)         |
| `tierMatching_speedIndi`         | 스피드 등급전(개인전, 매우빠름)        |
| `tierMatching_speedTeam`         | 스피드 등급전(팀전, 매우빠름)          |
| `speedTeamCombine`               | 스피드 팀전(통합)                      |
| `speedTeamFastest`               | 스피드 팀전(매우 빠름)                 |
| `speedTeamInfinit`               | 스피드 팀전(무한 부스터, 빠름)         |
| `speedIndiShadowInfinit`         | 스피드 개인전(무한부스터 고스트, 빠름) |
| `speedTeamFast`                  | 스피드 팀전(빠름)                      |
| `speedTeamNewbie`                | 스피드 팀전(초보 채널, 보통)           |
| `itemIndiCombine`                | 아이템 개인전(통합)                    |
| `itemTeamCombine`                | 아이템 팀전(통합)                      |
| `itemNewItemIndiFastest2Enchant` | 아이템 개인전(가장빠름)                |
| `grandprix_itemNewItemIndi`      | 아이템 개인전(그랑프리, 빠름)          |
| `itemNewItemIndi`                | 아이템 개인전(보통)                    |
| `itemNewItemIndiNewbie`          | 아이템 개인전(초보 채널, 보통)         |
| `tierMatching_itemNewItemTeam`   | 아이템 등급전(팀전, 가장빠름)          |
| `battle`                         | 아이템 배틀(가장빠름)                  |
| `itemNewItemTeamFastest2Enchant` | 아이템 팀전(가장빠름)                  |
| `itemNewItemTeam`                | 아이템 팀전(보통)                      |
| `itemNewItemTeamNewbie`          | 아이템 팀전(초보 채널, 보통)           |
| `clubRace_speed`                 | 클럽 레이싱(스피드)                    |
| `clubRace_item`                  | 클럽 레이싱(아이템)                    |
| `flagIndi`                       | 깃발 뺏기 개인전(플래그전)             |
| `flagTeam`                       | 깃발 뺏기 팀전(플래그전)               |
| `bokbulbokSpeedTeamInfinit`      | 무한부스터 복불복 팀전                 |
- trackId : 매치가 이루어진 트랙의 key
- playerCount : 해당 매치에서 플레이한 플레이어의 인원 수
- matchResult : (2) 블루팀 승리 (1) 레드팀 승리 (0) 개인전
- seasonType : 항상 ‘’ 을 가짐 (제거해야할듯)
- kart : 매치에서 플레이어가 사용한 카트바디
- license : 항상 ‘’ 을 가짐 (제거해야할듯)
- pet : 매치에서 플레이어가 사용한 펫의 key
- flyingPet : 매체이서 플레이어가 사용한 플라잉펫의 key
- partsEngine : 9엔진 카트 이하에서 장착된 파츠엔진만 출력
###
| 값 | 파츠 이름 |
| --- | --- |
| 1 | 블랙 큐브 |
| 2 | 시크릿 코드 |
| 3 | 포뮬러 링 |
| 4 | 블랙 제어센서 |
| 5 | 화이트 제어센서 |
| 6 | 블랙 베어링 |
| 7 | 화이트 베어링 |
| 8 | 옐로우 제어센서 |
| 9 | 블루 제어센서 |
| 10 | 그린 제어센서 |
| 11 | 퍼플 제어센서 |
| 12 | 옐로우 베어링 |
| 13 | 블루 베어링 |
| 14 | 그린 베어링 |
| 15 | 퍼플 베어링 |
| 16 | 옐로우 쇼크 |
| 17 | 퍼플 쇼크 |
| 18 | 블루 쇼크 |
| 19 | 그린 쇼크 |
| 20 | 화이트 쇼크 |
| 21 | 블랙 쇼크 |
| 22 | 일렉트릭 쇼크 |
| 23 | 태고의 빛 |

- partsHandle : 9엔진 카트 이하에서 장착된 파츠핸들만 출력
###
| 값 | 파츠 이름 |
| --- | --- |
| 1 | 바이킹 배틀 |
| 2 | 엑스 스트림 |
| 3 | 샤프 라이너 |
| 4 | 퍼펙트 블랙 핸들 |
| 5 | 퍼펙트 화이트 핸들 |
| 6 | 다크 크로스 |
| 7 | 홀리 커브 |
| 8 | 옐로우 레이싱 핸들 |
| 9 | 블루 레이싱 핸들 |
| 10 | 그린 레이싱 핸들 |
| 11 | 퍼플 레이싱 핸들 |
| 12 | 옐로우 십자형 핸들 |
| 13 | 블루 십자형 핸들 |
| 14 | 그린 십자형 핸들 |
| 15 | 퍼플 십자형 핸들 |

- partsWheel : 9엔진 카트 이하에서 장착된 파츠휠만 출력
###
| 값 | 파츠 이름 |
| --- | --- |
| 1 | 카보블레이드 |
| 2 | 닥터R 파이어 디스크 |
| 3 | 크로스 워커 |
| 4 | 블랙 디스크 휠 |
| 5 | 화이트 디스크 휠 |
| 6 | 블랙 오프로드 휠 |
| 7 | 화이트 오프로드 휠 |
| 8 | 옐로우 디스크 휠 |
| 9 | 블루 디스크 휠 |
| 10 | 퍼플 디스크 휠 |
| 11 | 그린 디스크 휠 |
| 12 | 옐로우 오프로드 휠 |
| 13 | 블루 오프로드 휠 |
| 14 | 그린 오프로드 휠 |
| 15 | 퍼플 오프로드 휠 |
| 16 | 옐로우 프레임 |
| 17 | 퍼플 프레임 |
| 18 | 블루 프레임 |
| 19 | 그린 프레임 |
| 20 | 화이트 프레임 |
| 21 | 블랙 프레임 |
| 22 | 어스퀘이크 |
| 23 | 와일드 서클 |

- partsKit : 9엔진 카트 이하에서 장착된 파츠킷만 출력
###
| 값 | 파츠 이름 |
| --- | --- |
| 1 | 골든 로제타 킷 |
| 2 | 에어 프레셔 |
| 3 | 비스트 워터 |
| 4 | 자이로 스틱 |
| 5 | 레이지 펌프 |
| 6 | 레드레이븐 램프 |
| 7 | 블랙 니트로 |
| 8 | 화이트 니트로 |
| 9 | 블랙 기어박스 |
| 10 | 화이트 기어박스 |
| 11 | 블랙 펌프 |
| 12 | 화이트 펌프 |
| 13 | 블랙핑크 램프보드 |
| 14 | 화이트 램프보드 |
| 15 | 옐로우 니트로 |
| 16 | 블루 니트로 |
| 17 | 그린 니트로 |
| 18 | 퍼플 니트로 |
| 19 | 옐로우 기어박스 |
| 20 | 블루 기어박스 |
| 21 | 그린 기어박스 |
| 22 | 퍼플 기어박스 |
| 23 | 옐로우 펌프 |
| 24 | 블루 펌프 |
| 25 | 그림 펌프 |
| 26 | 퍼플 펌프 |
| 27 | 옐로우 램프보드 |
| 28 | 블루 램프보드 |
| 29 | 그린 램프보드 |
| 30 | 퍼플 램프보드 |

- rankinggrade2 : 플레이어의 라이센스 (0) 없음 (1~6) 초보부터 Pro까지
- matchRank : 해당 매치에서의 순위 (리타이어시 99, 게임종료시 ‘’, 매치에 따라 값의 타입이 int나 string이다.)
- matchRetired : (1) 리타이어 (0) 리타이어 안함
- matchWin : (1) 매치 승리 (0) 매치 패배
- matchTime : 매치 시간 (마지막 3자리가 밀리세컨드 부분, 그 앞에는 시, 분, 초의 값)
