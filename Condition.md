# Condition



(VALUE) ABSOLUTE VALUE(VALUE)

- 



(NUMBER) ADD(NUMBER, NUMBER)

- VALUE값을 더함



(ARRAY) ALL DEAD PLAYERS(TEAM)

- 팀 또는 경기내에서 사망한 모든 플레이어가 있는 배열



(ARRAY) ALL HEROES()

- 오버워치의 모든 영웅 배열



(ARRAY) ALL LIVING PLAYERS(TEAM)

- 팀 또는 경기내 생존한 모든 플레이어가 있는 배열



(ARRAY) ALL PLAYERS(TEAM)

- 팀 또는 경기 내 모든 플레이어가 있는 배열



(VALUE) ALL PLAYERS NOT ON OBJECTIVE(TEAM)

- 



(ARRAY) ALL PLAYERS ON OBJECTIVE

- 화물 확보 또는 거점을 점령중인(팀 또는 경기 내) 모든 플레이어가 있는 배열



(ARRAY) ALLOWED HEROES(PLAYER)

- 특정 플레이어가 선택할 수 있는 영웅 배열



(NUMBER) ALTITUDE OF(PLAYER)

- 표면으로부터 측정한 PLAYER의 높이(미터)
- PLAYER가 표면에 있으면 0



(BOOL) AND(VALUE, VALUE)

- 두 INPUT 모두 TRUE인 경우인지 여부



(NUMBER) ANGLE DIFFRENCE(ANGLE, ANGLE)

- 두 각을 비교한 각도 차이
- 두각을 서로 +/- 180 이내에서 펼쳐서 두 번째 각이 첫번째 각보다 크다면 결과각은 양수
- 이외의 경우 0이나 음수가 될 수 있음



(VALUE) APPEND TO ARRAY(ARRAY, VALUE)

- 배열에 요소추가



(BOOL) ARRAY CONTAINS(ARRAY, VALUE)

- 배열에 포함되어 있는지



(ARRAY) ARRAY SLICE(ARRAY, START INDEX, COUNT)

- 배열의 일부를 START INDEX와 COUNT로 자름



(PLAYER) ATTACKER()

- 이 규칙으로 처리된 이벤트로 인해 피해를 준 플레이어 
- VICTIM 또는 EVENT PLAYER와 동일할 수 있음



(VECTOR) BACKWARD()

- 후방을 가리키는 방향 벡터(0,0,-1)의 약칭



(PLAYER) CLOSEST PLAYER TO(CENTER, TEAM)

- 한 위치에서 가장 가까운 PLAYER
- 팀으로 제한할 수 있음

- CENTER - VECTOR



(BOOL) COMPARE(VALUE, VALUE)

- 두 INPUT의 비교결과가 TRUE인지 여부



(NUMBER) CONTROL MODE SCORING PERCENTATGE(TEAM)

- 쟁탈 모드에서 특정 팀의 점수 비율



(TEAM) CONTROL MODE SCORING TEAM()

- 현재 쟁탈 모드에서 점수를 축적하고 있는 팀
- 아무 팀도 점수를 축적하지 못한 경우 결과값은 ALL



(VALUE) COSINE FROM DEGREES(ANGLE)

- 



(VALUE) COSINE FROM RADIANS(ANGLE)

- 



(NUMBER) COUNT OF(ARRAY)

- 배열의 크기



(VECTOR) CROSS PRODUCT(VECTOR,VECTOR)

- 



(VALUE) CURRENT ARRAY ELEMENT()

- 현재 연산 대상인 배열 요소
- FILTERED ARRAY나 SORTED ARRAY 등 값을 확인할 때에만 의미가 있음



(VALUE) DIRECTION FROM ANGLES(HORIZONTAL ANGLE, VERTICAL ANGLE)

- 



(VECTOR) DIRECTION TOWARDS(START POS, END POS)

- 한 위치에서 다른 위치까지의 단위 길이 방향 벡터
- START POS, END POS - VECTOR



(NUMBER) DISTANCE BETWEEN(START POS, END POS)

- 두 위치 사이의 거리(미터)
- START POS, END POS - VECTOR



(VALUE) DIVIDE(VALUE, VALUE)

- 나누기



(VECTOR) DOT PRODDUCT(VALUE, VALUE)

- VALUE - VECTOR



(VECTOR) DOWN()

- 아래를 가리키는 방향 벡터(0,-1,0)의 약칭



(VALUE) EMPTY ARRAY()

- 요소가 없는 배열



(BOOL) ENTITY EXISTS(ENTITY)

- 엔트리가 존재하는 지 여부



(PLAYER) EVENT PLAYER()

- 이벤트로 지정된 이 규칙을 실행중인 플레이어
- ATTACKER또는 VICTIM과 동일 할 수 있음



(VECTOR) FACING DIRECTION OF(PALYER)

- 월드에 대해 상대적으로 PLAYER가 바라보고 있는 방향의 상대적인 단위 길이 방향 벡터
- 이 값에는 종, 횡 방향이 있음



(BOOL) FALSE()



(PLAYER) FARTHEST PLAYER FROM(CENTER, TEAM)

- 특정 위치로부터 가장 멀리 떨어진 PLAYER로, 팀의 제한을 받을 수 있음



(VALUE) FILTERED ARRAY(ARRAY, CONDITION)

- 제거된 특정 CONDITION에 해당하지 않는 값을 가진 특정 배열의 복사본



(VALUE) FIRST OF(ARRAY)



(VALUE) FLAG POSITION(TEAM)

- 기발 뺏기에서 특정 팀의 깃발 위치



(VECTOR) FORWARD()

- 전방을 가리키는 방향 벡터(0, 0, 01)의 약칭



(VALUE) GLOBAL VARIABLE()

- 게임 자체에 종속된 전역 변수의 현재 값



(BOOL) HAS SPAWNED(ENTITY)

- 엔티티가 스폰되었다면



(BOOL) HAS STATUS(PLAYER, STATUS)

- 특정 PLAYERS가 SET STATUS ACTION 또는 스크립트 이외의 게임 메카닉을 통해 특정 상태를 갖게 되었는지 여부



(NUMBER) HEALTH(PLAYER)

- 한 PLAYER의 현재 체력(방어력 및 보호막 포함)



(NUMBER) HEALTH PERCENT(PLAYER)

- 한 PLAYER의 체력 비율



(VALUE) HERO()

- D.VA
- 겐지
- 둠피스트
- 라인하르트
- 레킹볼
- 로드호그
- 루시우
- 리퍼
- 맥크리
- 메르시
- 메이
- 모이라
- 바스티온
- 바티스트
- 브리기테
- 솔져: 76
- 솜프라
- 시메트라
- 아나
- 애쉬
- 오리사
- 위도우메이커
- 윈스턴
- 자리야
- 정크랫
- 젠야타
- 토르비욘
- 트레이서
- 파라
- 한조



(STRING) HERO ICON STRING(HERO)

- 



(HERO) HERO OF(PLAYER)

- 현재 PLAYER의 영웅



(VALUE) HORIZONTAL ANGLE FROM DIRECTION(DIRECTION)

- 지정된 방향 벡터에 대응한는 휭축각
- DIRECTION - VECTOR



(NUMBER) HORIZONTAL ANGLE TOWARDS(PLAYER, POSITION)

- PLAYER의 전방에서 특정 위치까지의 횡축각
- 이 값은 해당 위치가 PLAYER 좌측에 있는 경우 양수, 그 외의 경우 0이거나 음수
- POSITION - VECTOR



(VALUE) HORIZONTAL FACING ANGLE OF(PLAYER)

- 월드에 대해 상대적으로 PLAYER가 바라보고 있는 방향의 상대적인 횡축각
- 이 값은 PLAYER가 좌측으로 회전시 증가(+/- 180도 범위)



(VECTOR) HORIZONTAL SPEED OF(PLAYER)

- PLAYER의 현재 횡축 속력(초당 미터)
- 여기에는 모든 중축 움직임이 배제됨



(VALUE) INDEX OF ARRAY VALUE(ARRAY, VALUE)

- 배열의 요소의 인텍스



(BOOL) IS ALIVE(PLAYER)

- 플레이어의 생존 여부



(BOOL) IS ASSEMBLING HEROES()

- 



(BOOL) IS BETWEEN ROUNDS()

- 



(BOOL) IS BUTTON HELD(PLAYER, BUTTON)

- 플레이어가 특정 버튼을 누르고 있는지 여부



(BOOL) IS COMMUNICATING(PLAYER, TYPE)

- 



(BOOL) IS COMMUNICATING ANY(PLAYER)

- 



(BOOL) IS COMMUNICATING ANY EMOTE(PLAYER)

- 



(BOOL) IS COMMUNICATING ANY VOICE LINE(PLAYER)

- 



(BOOL) IS CONTROLE MODE POINT LOCKED()

- 쟁탈 모드에서 해당 지점이 잠겨있는지 여부



(BOOL) IS CROUCHING(PLAYER)

- PLAYER가 웅크리고 있는 상태인지 여부



(BOOL) IS CTF MODE IN SUDDEN DEATH()

- 



(BOOL) IS DEAD(PLAYER)

- PLAYER 의 사망 여부



(BOOL) IS FIRING PRIMARY(PLAYER)

- 



(BOOL) IS FIRING SECONDARY(PLAYER)

- 



(BOOL) IS FLAG AT BASE(TEAM)

- 깃발 뺏기에서 특정 팀의 깃발이 해당 팀의 기지에 있는지 여부



(BOOL) IS FLAG BEING CARRIED(TEAM)

- 깃발 뺏기에서 상대 팀이 특정 팀의 깃발을 점유하고 있는지 여부



(BOOL) IS GAME IN PROGRESS()



(BOOL) IS HERO BEING PLAYED(HERO, TEAM)

- (팀 또는 경기내에서) 특정 영웅이 사용되는지 여부



(BOOL) IS IN AIR(PLAYER)

- 



(BOOL) IS IN LINE OF SIGHT(START POS, END POS, BARRIEDRS)

- START POS - VECTOR
- END POS - VECTOR



(BOOL) IS IN SETUP()

- 



(BOOL) IS IN SPAWN ROOM(PLAYER)

- 



(BOOL) IS IN VIEW ANGLE(PLAYER, LOCATION, VIEWANGLE)

- LOCATION - VECTOR



(BOOL) IS MATCH COMPLETE()

- 



(BOOL) IS MOVING(PLAYER)

- 



(BOOL) IS OBJECTIVE COMPLETE(NUMBER)

- 



(BOOL) IS ON GROUND(PLAYER)

- 





(BOOL) IS ON OBJECTIVE(PALYER)

- 





(BOOL) IS ON WALL(PLAYER)

- 





(BOOL) IS PORTRAIT ON FIRE(PLAYER)

- 





(BOOL) IS TEAM ON DEFENSE(TEAM)

- 





(BOOL) IS TEAM ON OFFENSE(TEAM)

- 



(BOOL) IS TRUE FOR ALL(ARRAY, CONDITION)

- ARRAY - GLOBAL VARIABLE, PLAYER VARIABLE
- CONDITION - TODO



(BOOL) IS TRUE FOR ANY(ARRAY, CONDITION)

- 





(BOOL) IS USING ABILITY 1(PLAYER)

- 



(BOOL) IS USING ABILITY 2(PLAYER)

- 





(BOOL) IS USING ULTIMATE(PLAYER)

- 





(BOOL) IS WAITING FOR PLAYERS()

- 



(VALUE) LAST CREATED ENTITY()

- EVNET PLAYER가 마지막으로 생성한(또는 GLOBAL 레벨로 생성된)효과 또는 아이콘 개체에 대한 참조



(VALUE) LAST DAMAGE OVER TIME ID()

- EVNET PLAYER가 실행한(또는 GLOBAL로 실행된) 가장 최근 DAMAGE OVER TIME ACTION의 ID



(VALUE) LAST HEAL OVER TIME ID()

- EVENT PLAYER가 실행한(또는 GLOBAL로 실행된) 가장 최근 HEAL OVER TIME ACTION의 ID



(VALUE) LAST OF(ARRAY)

- 배열의 마지막 요소



(VALUE) LAST TEXT ID()

- 



(VECTOR) LEFT()

- 좌측을 가르키는 방향 벡터(1,0,0)의 약칭



(VALUE) LOCAL VECTOR OF(WORLD VECTOR, RELATIVE PLAYER, TRANSFORMATION)

- 제공된 월드 좌표 벡터에 해당하는 로컬 좌표 벡터
- WORLD VECTOR - VECTOR
- TRANSFROMATION : ROTATION, ROTATION AND TRANSLATION



(NUMBER) MATCH ROUND()

- 현재 라운드



(VALUE )MATCH TIME()

- 



(VALUE) MAX(VALUE, VALUE)

- VALUE들중 가장 큰값



(VALUE) MAX HEALTH(PLAYER)

- PLAYER의 최대 체력값



(VALUE) MIN(VALUE, VALUE)

- VALUE들중 가장 작은 값



(VALUE) MODULO(VALUE, VALUE)

- 모듈러 연산



(VALUE) MULTIPLY(VALUE, VALUE)

- 곱셈



(VALUE) NEAREST WALKABLE POSITION(POSITION)

- POSITION - VECTOR



(VALUE) NORMALIZE()

- 



(VALUE) NOT(VALUE)

- INPUT이 FALSE(또는 그에 상응하는 경우)인지 여부



(VALUE) NULL()

- 널 값



(NUMBER) NUMBER(VALUE)

- 정수, 실수 값



(NUMBER) NUMBER OF DEAD PLAYERS(TEAM)

- 팀 내 또는 경기 중 사망한 플레이어 수



(NUMBER) NUMBER OF DEATHS(PLAYER)

- 특정 PLAYER가 기록한 사망 수
- 이 값은 게임이 진행 중일 때만 누적



(NUMBER) NUMBER OF ELIMINATIONS(PLAYER)

- 특정 PLAYER가 기록한 처치 수
- 이 값은 게임이 진행 중일 때만 누적



(NUMBER) NUMBER OF FINAL BLOWS(PLAYER)

- 특정 PLAYER가 기록한 결정타 개수
- 이 값은 게임이 진행 중일 때만 쌓이게 됨



(NUMBER) NUMBER OF HEROES(HERO, TEAM)

- 팀 또는 경기 내에서 특정 영우을 프레이하는 PLAYER의 수



(NUMBER) NUMBER OF LIVING PLAYERS(TEAM)

- 팀 도는 경기에서 생존한 플레이어 수



(NUMBER) NUMBER OF PLAYERS(TEAM)

- 팀 또는 경기 내 존재하는 플레이어 수



(NUMBER) NUMBER OF PLAYERS ON OBJECTIVE(TEAM)

- (팀에서 도는 경기 중) 화물 또는 거점을 확보하려는 PLAYER 수



(VALUE) OBJECTIVE INDEX()

- 현재 활성화 중인 거점, 화물 경유지, 화물 목적지 (0, 1, 2 중 하나)
- 점령, 점령/호위, 호위, 쟁탈 전장에서 유효



(VALUE) OBJECTIVE POSITION(NUMBER)

- 



(TEAM) OPPOSITE TEAM OF(TEAM)

- 특정 팀을 상대하는 팀을 지칭



(VALUE) OR(VALUE, VALUE)

- 두 INPUT 중 하나가 TRUE(또는 그에 상응하는 경우)인지 여부



(VALUE) PAYLOAD POSITION()

- 



(VALUE) PAYLOAD PROGRESS PERCENTAGE()

- 



(VALUE) PLAYER CARRYING FLAG(TEAM)

- 



(VALUE) PLAYER CLOSEST TO RETICLE(PLAYER, TEAM)

- 



(VALUE) PLAYER VARIABLE(PLAYER, VARIABLE)

- 특정 PLAYER가 가진 플레이어 변수의 현재 값



(ARRAY) PLAYERS IN SLOT(SLOT, TEAM)

- 게임 내 특정 슬롯을 점유하는 배열 또는 플레이어 배열



(VALUE) PLAYERS IN VIEW ANGLE(PLAYER, TEAM, VIEWANGLE)

- 



(ARRAY) PLAYERS ON HERO(HERO, TEAM)

- 팀 또는 경기 내에서 특정 영우을 플레이하는 플레이어가 있는 배열



(ARRAY) PLAYERS WITHIN RADIUS(CENTER, RADIUS, TEAM, LOS CHECK)

- 한 위치의 특정 거리 내 모든 플레이어를 포함하고 있는 배열
- 팀 또는 시야 범위로 제한할 수 있음



(NUBMER) POINT CAPTURE PERCENTAGE()

- 활성화된 점령에서, 점령 중인 거점의 점령 진척도(비율로 표시)



(VALUE) POSITION OF(PLAYER)

- 플레이어의 현재 위치(벡터)



(VALUE) RAISE TO POWER(VALUE, VALUE)

- 



(NUMBER) RANDOM INTEGER(MIN, MAX)

- 특정 최대 및 최소값 범위 내에서의 무작위 정수값 하나



(NUMBER) RANDOM REAL(MIN, MAX)

- 특정 최대 및 최소값 범위 내에서의 무작위 실수값 하나



(VALUE) RANDOM VALUE IN ARRAY(ARRAY)

- 특정 배열의 무작위 값



(VALUE) RANDOMIZED ARRAY(ARRAY)

- 특정 배열의 값을 무작위 순서로 나열한 복사본



(VALUE) REMOVE FROM ARRAY(ARRAY, VALUE)

- ARRAY에서 VALUE요소 제거



(VECTOR) RIGHT()

- 우측을 가리키는 방향 벡터(-1,0,0)의 약칭



(NUMBER) ROUND TO INTEGER(VALUE, ROUNDING TYPE)

- 버림, 올림, 반올림
- ROUNDING TYPE : UP, DOWN, TO NEAREST



(VALUE) SCORE OF(PLAYER)

- 특정 PLAYER의 현재 점수
- 게임 모드가 개별모드가 아닌 경우 결과값은 0



(VALUE) SINE FROM DEGREES(ANGLE)

- 



(VALUE) SINE FROM RADIANS(ANGLE)

- 



(NUMBER) SLOT OF(PLAYER)

- 특정 PLAYER의 슬롯 번호
- 팀에서 각 팀은 0에서 5개의 슬롯을 보유
- 개별 모드에서 슬롯의 수는 0~11



(ARRAY) SORTED ARRAY(ARRAY, VALUE RANK)

- 배열 정렬
- VALUE RANK : CURRENT ARRAY ELEMENT



SPEED OF(PLAYER)

- PLAYER의 현재 속력(초당 미터)



(NUMBER) SPEED OF IN DIRECTION(PLAYER, DIRECTION)

- 특정 방향에 대한 PLAYER의 현재 속력(초당 미터)



(NUMBER) SQUARE ROOT(VALUE)

- VALUE값 제곱근



(VALUE) STRING(STRING, {0}, {1}, {2})

- 



(VALUE) SUBTRACT(VALUE, VALUE)

- 두값 빼기



(TEAM) TEAM(TEAM)

- TEAM : ALL, 1팀, 2팀



(VALUE) TEAM OF(PLAYER)

- 해당 PLAYER의 소속 팀
- 게임 모드가 개별 모드인 경우 팀은 ALL로 간주



(VALUE) TEAM SCORE(TEAM)

- 지정된 팀의 현재점수
- 개별 전투 모드에서는 결과값이 0



(VECTOR) THROTTLE OF(PLAYER)

- 한 PLAYER의 방향 INPUT
- X 구성요소가 횡방향 INPUT(왼쪽이 양수)
- Z 구성요소가 종방향 INPUT(위쪽이 양수)인 벡터로 표현



(NUMBER) TOTAL TIME ELAPSED()

- 게임 인스턴스 생성 후 소요시간(초)
- 설정 및 전환 시간 포함



(BOOL) TRUE()

- 참값



(VALUE) ULTIMATE CHARGE PERCENT(PLAYER)

- 



(VECTOR) UP()

- 위를 가리키는 방향 벡터(0, 1, 0)의 약칭



(VALUE) VALUE IN ARRAY(ARRAY, INDEX)

- 배열안에 INDEX에 있는 값



(VECTOR) VECTOR(X, Y, Z)

- 3개의 실수(X,Y,Z)로 이루어진 벡터
- X는 좌측, Y는 위, Z는 전방을 의미
- 벡터는 위치, 방향 속도로 사용



(VECTOR) VECTOR TOWARDS(START POS, END POS)

- 한 위치에서 다른 위치까지의 변위 벡터
- START POS : VECTOR
- END POS : VECTOR



(VECTOR) VELOCITY OF(PLAYER)

- PLAYER 현재 속도(벡터)
- 해당 PLAYER가 표면 위에 있는 경우, 경사로를 오르내린다고 해도 Y 구성요소 속도는 0



(VALUE) VERTICAL ANGLE FROM DIRECTION(DIRECTION)

- 지정된 방향 벡터에 대응하는 중축각 도(DEGREE)로 나타낸 것
- DIRECTION : VECTOR



(VALUE) VERTICAL ANGLE TOWARDS(PLAYER, POSITION)

- PLAYER의 전방에서 특정 위치까지의 중축각
- 이 값은 해당 위치가 PLAYER 아래에 이쓴ㄴ 경우 양수이며, 그 외의 경우 0이나 음수



(VALUE) VERTICAL FACING ANGLE OF(PLAYER)

- 월드에 대해 상대적으로 PLAYER가 바라보고 있는 방향의 중축각
- 이 값은 PLAYER가 내려다보는 경우 증가



(VALUE) VERTICAL SPEED OF(PLAYER)

- PLAYER의 현재 중축 속력(초당 미터)
- 여기에는 경사로를 오르내리는 등의 움직임 등 모든 횡축 이동이 배제됨



(VALUE) VICTIM()

- 이 규칙으로 처리된 이벤트로 인해 피해 받은 플레이어
- ATTACKER 또는 EVENT PLAYER와 동일 할 수 있음



(VECTOR) WORLD VECTOR OF(LOCLA VECTOR, RELATIVE PLAYER, TRANSFORMATION)

- 제공된 로컬 좌표 벡터에 해당하는 월드 좌표 벡터
- LOCAL VECTOR : VECTOR
- RELATIVE PLAYER : PLAYER
- TRANSFORMATION : ROTATION, ROTATION AND TRANSLATION



(NUMBER) X COMPONENT OF (VECTOR)

- VECTOR의 X값



(NUMBER) Y COMPONENT OF(VECTOR)

- VECTOR의 Y값



(NUMBER) Z COMPONENT OF(VECTOR)

- VECTOR의 Z값



#### 추가

#### BUTTON

- PRIMARY FIRE
- SECONDARY FIRE
- ABILITY 1
- ABILITY 2
- ULTIMATE
- INTERACT
- JUMP
- CROUCH



TYPE(COMUNICATING)

- VOICE LINE UP
- VOICE LINE LEFT
- VOICE LINE RIGHT
- VOICE LINE DOWN
- EMOTE UP
- EMOTE LEFT
- EMOTE RIGHT
- EMOTE DOWN
- ULTIMATE STATUS
- HELLO
- NEED HEALING
- GROUP UP
- THANKS
- ACKNOWLEDGE





BARRIEDRS

- BARRIERS DO NOT BLOCK LOS
- ENEMY BARRIERS BLOCK LOS
- ALL BARRIERS BLOCK LOS

