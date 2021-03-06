### Action(행동)

- 특정 이벤트 특정 조건에 만족하면 취하는 행위

> ```
> ABORT():
> ​ 액션 실행을 중지
> ```
>
> ```
> ABORT IF(CONDITION())
> ​ CONDITION을 TRUE일 때 액션 실행을 중지
> ```
>
> ```
> ABORT IF CONDITION IS FALSE():
> ​ RULE에서 지정한 컨디션이 false일 경우 액션 실행을 중지
> ```
>
> ```
> ABORT IF CONDITION IS TRUE():
> ​ RULE에서 지정한 컨디션이 true일 경우 액션 실행을 중지
> ```
>
> ```
> ALLOW BUTTON(PLAYER, BUTTON):
> ​ PLAYER의 BUTTON을 사용할 수 있게 허용 
> ```
>
> ```
> APPLY IMPULSE(PLAYER, DIRECTION(), SPEED(), RELATIVE, MOTION):
> ​ CONDITION을 만족한 플레이어가 이동
> ```
>
> ```
> BIG MESSAGE(VISIBLE TO(), HEADER()): 
> ​ 지정된 플레이어들의 조준선 위로 메시지를 띄움
> ```
>
> ```
> CHASE GLOBAL VARIABLE AT RATE(변수, DESTINATION(), RATE(), REEVALUATION):
> ​ 전역변수의 값을 지정된 비율로 수정
> ```
>
> ```
> CHASE GLOBAL VARIABLE OVER TIME(변수, DESTINATION(), DURATION(), REEVALUATION):
> ​ 전역변수의 값을 시간이 지남에 따라 수정
> ```
>
> CHASE GLOBAL VARIABLE OVER TIME:
>
> ​	CHASE GLOBAL VARIABLE OVER TIME(변수, DESTINATION, DURATION, REEVALUATION)
>
> ```
> CHASE PLAYER VARIABLE AT RATE(PLAYER,  변수, DESTINATION, RATE, REEVALUATION):
> ​ 플레이어 변수의 값을 지정된 비율로 수정
> ```
>
> ```
> CHASE PLAYER VARIABLE OVER TIME(PLAYER, 변수, DESTINATION, DURATION, REEVALUATION):
> ​ 플레이어 변수의 값을 시간이 지남에 따라 수정
> ```
>
> ```
> CLEAR STATUS(PLAYER, STATUS):
> ​ 플레이어의 상태를 CLEAR
> ```
>
> ```
> COMMUNICATE(PLAYER, TYPE):
> ​ 플레이어의 의사소통 수단을 사용
> ```
>
> ```
> CREATE EFFECT(VISIBLE TO(), TYPE, COLOR, POSITION, RADIUS(), REEVALUATION):
> ​ 효과 개체를 생성
> ```
>
> ```
> CREATE HUD TEXT(VISIBLE TO(), HEADER(), SUBHEADER, TEXT, LOCATION, SORT ORDER(), HEADER COLOR, SUBHEADER COLOR, TEXT COLOR, REEVALUATION):
> ​ 플레이어의 화면의 지정된 위치에 HUD(HEAD-UP DISPLAY) TEXT를 생성
> ```
>
> ```
> CREATE ICON(VISIBLE TO(), POSITION, ICON, REEVALUATION, ICON COLOR, SHOW WHEN OFFSCREEN):
> ​ 플레이어의 화면의 짖어된 위치에 ICON 개체를 생성
> ```
>
> ```
> CREATE IN-WORLD TEXT(ACTION, VISIBLE TO(), HEADER(), POSITION, SCALE(), CLIPPING, REEVALUATION):
> ​ 월드 텍스트를 생성
> ```
>
> ```
> DAMAGE(PLAYER, DAMAGER, AMOUNT()):
> ​ 플레이어에게 데미지를 적용
> ```
>
> ```
> DECLARE MATCH DRAW():
> ​ 경기를 무승부로 종료
> ```
>
> ```
> DECLARE PLAYER VICTORY(PLAYER):
> ​ PLAYER를 승자로 경기를 종료
> ```
>
> ```
> DECLARE ROUND VICTORY(ROUND WINNINT TEAM()):
> ​ 팀을 라운드의 승자로 설정
> ```
>
> ```
> DECLARE TEAM VICTORY(TEAM()):
> ​ 팀을 경기의 승자로 설정
> ```
>
> ```
> DESTORY ALL EFFECTS():
> ​ CREATE EFFECT에 의해 생성된 개체를 모두 파괴
> ```
>
> ```
> DESTROY ALL HUD TEXT():
> ​ CREATE HUD TEXT에 의해 생성된 TEXT를 모두 파괴
> ```
>
> ```
> DESTROY ALL ICONS():
> ​ CREATE ICON에 의해 생성된 아이콘을 모두 파괴
> ```
>
> ```
> DESTORY ALL IN-WORLD TEXT():
> ​ CREATE IN-WORLD TEXT에 의해 생성된 텍스트를 모두 파괴
> ```
>
> ```
> DESTORY EFFECT(ENTITY):
> ​ CREATE EFFECT에 의해 생성된 개체를 하나 파괴
> ```
>
> ```
> DESTROY HUD TEXT(TEXT ID):
> ​ CREATE HUD TEXT에 의해 생성된 TEXT를 하나 파괴
> ```
>
> ```
> DESTROY ICON(ENTITY):
> ​ CREATE ICON에 의해 생성된 아이콘을 하나 파괴
> ```
>
> ```
> DESTRORY IN-WORLD TEXT(TEXT ID):
> ​ CREATE IN-WORLD TEXT에 의해 생성된 텍스트를 하나 파괴
> ```
>
> ```
> DISABLE BUILT-IN GAME MODE ANNOUNCER():
> ​ 다시 사용하거나 켤 때까지 경기음성을 사용하지 않음
> ```
>
> ```
> DISABLE BUILT-IN GAME MODE COMPLETION():
> ​ 게임모드 자체에서 게임이 종료되지 않고 스크립트에 의해서만 게임이 종료
> ```
>
> ```
> DISABLE BUILT-IN GAME MODE MUSIC():
> ​ 게임 모드 음악을 사용하지 않음
> ```
>
> ```
> DISABLE BUILT-IN GAME MODE RESPAWNING(PLAYERS):
> ​ 플레이어가 자동으로 리스폰되지 않고 스크립트에 의해서만 리스폰
> ```
>
> ```
> DISABLE BUILT-IN GAME MODE SCORING():
> ​ 게임 모드의 스코어링을 사용하지 않고 스크립트에 의해서만 스코어링
> ```
>
> ```
> DISABLE DEATH SPECTATE ALL PLAYERS(PLAYER):
> ​ENALBE DEATH SPECTATE ALL PLAYERS(PLAYER)의 효과를 취소
> ```
>
> ```
> DISALBE DEATH SPECTATE TARGET HUD(PLAYER):
> ​ ENALBE DEATH SPECTATE TARGET HUD(PLAYER)의 효과를 취소
> ```
>
> ```
> DISALLOW BUTTON(PLAYER, BUTTON):
> ​ 플레이어가 버튼을 눌러도 아무 효과 없도록 설정
> ```
>
> ```
> ENABLE BUILT-IN GAME MODE ANNOUNCER():
> ​ DISABLE BUILT-IN GAME MODE ANNOUNCER()의 효과를 취소
> ```
>
> ```
> ENABLE BUILT-IN GAME MODE COMPLETION():
> ​ DISABLE BUILT-IN GAME MODE COMPLETION()의 효과를 취소
> ```
>
> ```
> ENABLE BUILT-IN GAME MODE MUSIC():
> ​ DISABLE BUILT-IN GAME MODE MUSIC()의 효과를 취소
> ```
>
> ```
> ENABLE BUILT-IN GAME MODE RESPAWNING(PLAYERS):
> ​ DISABLE BUILT-IN GAME MODE RESPAWNING(PLAYERS)의 효과를 취소
> ```
>
> ```
> ENABLE BUILT-IN GAME MODE SCORING():
> ​ DISABLE BUILT-IN GAME MODE SCORING()의 효과를 취소
> ```
>
> ```
> ENALBE DEATH SPECTATE ALL PLAYERS(PLAYER):
> ​ 플레이어 사망 시 아군 뿐 아니라 모든 유저를 관전 가능하도록 허용
> ```
>
> ```
> ENALBE DEATH SPECTATE TARGET HUD(PLAYER):
> ​ 플레이어 사망 시 관전하는 유저의 HUD를 볼 수 있도록 허용
> ```
>
> 
>
> GO TO ASSEMBLE HEROS
>
> ​	GO TO ASSEMBLE HEROS()
>
> HEAL
>
> ​	HEAL(PLAYER, HEALER, AMOUNT(NUMBER))
>
> KILL
>
> ​	KILL(PLAYER, KILLER)
>
> LOOP
>
> ​	LOOP()
>
> LOOP IF
>
> ​	LOOP IF(CONDITION())
>
> LOOP IF CONDITION IS FALSE
>
> ​	LOOP IF CONDITION IS FALSE()
>
> LOOP IF CONDITION IS TRUE
>
> ​	LOOP IF CONDITION IS TRUE()
>
> MODIFY GLOBAL VARIABLE
>
> ​	MODIFY GLOBAL VARIABLE(변수, OPERATION, VALUE())
>
> MODIFY PLAYER SCORE
>
> ​	MODIFY PLAYER SCORE(PLAYER, SCORE)
>
> MODIFY PLAYER VARIABLE
>
> ​	MODIFY PLAYER VARIABLE(PLAYER,  변수, OPERATION, VALUE())
>
> MODIFY TEAM SCORE
>
> ​	MODIFY TEAM SCORE(PLAYER, SCORE)
>
> PAUSE MATCH TIME
>
> ​	PAUSE MATCH TIME(PLAYER, 변수, OPERATION, VALUE())
>
> PLAYER EFFECT
>
> ​	PLAYER EFFECT(VISIBLE TO(), TYPE, COLOR, POSITION, RADIUS())
>
> PRELOAD HERO
>
> ​	PRELOAD HERO(PLAYER, HERO())
>
> PRESS BUTTON
>
> ​	PRESS BUTTON(PLAYER, BUTTON)
>
> RESET PLAYER HERO AVAILABILTY
>
> ​	RESET PLAYER HERO AVAILABILTY(PLAYER)
>
> RESPAWN
>
> ​	RESPAWN(PLAYER)
>
> RESURRECT
>
> ​	RESURRECT(PLAYER)
>
> SET ABILITY 1 ENABLED
>
> ​	SET ABILITY 1 ENABLED(PLAYER, ENABLED)
>
> SET ABILITY 2 ENABLED
>
> ​	SET ABILITY 2 ENABLED(PLAYER, ENABLED)
>
> SET AIM SPEED
>
> ​	SET AIM SPEED(PLAYER, TURN SPEED PERCENT())
>
> SET DAMAGE DEALT
>
> ​	SET DAMAGE DEALT(PLAYER, DAMAGE  DEALT PERCENT)
>
> SET DAMAGE RECEIVED
>
> ​	SET DAMAGE RECEIVED(PLAYER, DAMAGE RECEIVED PERCENT)
>
> SET FACING
>
> ​	SET FACING(PLAYER, DIRECTION(), RELATIVE)
>
> SET GLOBAL VARIABLE
>
> ​	SET GLOBAL VARIABLE(변수, VALUE, NUMBER)
>
> SET GLOBAL VARIABLE AT INDEX
>
> ​	SET GLOBAL VARIABLE AT INDEX(변수, INDEX, VALUE)
>
> SET GRAVITY
>
> ​	SET GRAVITY(PLAYER, GRAVITY PERCENT)
>
> SET HEALING DEALT
>
> ​	SET HEALING DEALT(PLAYER, HEALING DEALT PERCENT)
>
> SET HEALING RECEIVED
>
> ​	SET HEALING RECEIVED(PLAYER, HEALING RECEIVED PERCENT)
>
> SET INVISIBLE
>
> ​	SET INVISIBLE(PLAYER, INVISIBLE TO)
>
> SET MATCH TIME
>
> ​	SET MATCH TIME(TIME())
>
> SET MAX HEALTH
>
> ​	SET MAX HEALTH(PLAYER, HEALTH PERCENT)
>
> SET MOVE SPEED
>
> ​	SET MOVE SPEED(PLAYER, MOVE SPEED PERCENT)
>
> SET OBJECTIVE DESCRIPTION
>
> ​	SET OBJECTIVE DESCRIPTION(VISIBLE TO(), HEADER(), REEVALUATION)
>
> SET PLAYER ALLOWED HEROES
>
> ​	SET PLAYER ALLOWED HEROES(PLAYER, HERO())
>
> SET PLAYER SCORE
>
> ​	SET PLAYER SCORE(PLAYER, SCORE())
>
> SET PLAYER VARIABLE
>
> ​	SET PLAYER VARIABLE(PLAYER, 변수, VALUE())
>
> SET PLAYER VARIABLE AT INDEX
>
> ​	SET PLAYER VARIABLE AT INDEX(PLAYER, 변수, INDEX(), VALUE())
>
> SET PROIECTILE GRAVITY
>
> ​	SET PROIECTILE GRAVITY(PLAYER, PROJECTILE GRAVITY PERCENT())
>
> SET PROIECTILE SPEED
>
> ​	SET PROIECTILE SPEED(PLAYER, PROJECTILE SPEED PERCENT())
>
> SET RESPAWN MAX TIME
>
> ​	SET RESPAWN MAX TIME(PLAYER, TIME)
>
> SET SLOW MOTION
>
> ​	SET SLOW MOTION(SPEED PERCENT())
>
> SET STATUS
>
> ​	SET STATUS(PLAYER, ASSISTER, STATUS, DURATION())
>
> SET TEAM SCORE
>
> ​	SET TEAM SCORE(TEAM(), SCORE())
>
> SET ULTIMATE ABILITY ENABLED
>
> ​	SET ULTIMATE ABILITY ENABLED(PLAYER, ENABLED)
>
> SET ULTIMATE CHARGE
>
> ​	SET ULTIMATE CHARGE(PLAYER, CHARGE PERCENT())
>
> SKIP
>
> ​	SKIP(NUMBER OF ACTIONS)
>
> SKIP IF
>
> ​	SKIP IF(CONDITION(), NUMBER OF ACTIONS)
>
> SMALL MESSAGE
>
> ​	SMALL MESSAGE(VISIBLE TO(), HEADER())
>
> START ACCELERATING
>
> ​	START ACCELERATING(PLAYER, DIRECTION, RATE, MAX SPEED, RELATIVE, REEVALUATION)
>
> START CAMERA
>
> ​	START CAMERA(PLAYER, EYE POSITION(), LOOK AT POSITION(), BLEND SPEED())
>
> START DAMAGE OVER TIME
>
> ​	START DAMAGE OVER TIME(PLAYER, DAMAGER, DURATION(), DAMAGE PER SECOND())
>
> START FACING
>
> ​	START FACING(PLAYER, DIRECTION, TURN RATE, RELATIVE, REEVALUATION)
>
> START FORCING PLAYER TO BE HERO
>
> ​	START FORCING PLAYER TO BE HERO(PLAYER, HERO())
>
> START FORCING SPAWN ROOM
>
> ​	START FORCING SPAWN ROOM(TEAM(), ROOM())
>
> START FORCING THROTTLE
>
> ​	START FORCING THROTTLE(PLAYER, MIN FORWARD(), MAX FORWARD(), MIN BACKWARD(), MAX BACKWARD(), MIN SIDEWAYS(), MAX SIDEWAYS())
>
> START HEAL OVER TIME
>
> ​	START HEAL OVER TIME(PLAYER, HEALER, DURATION(), HEALING PER SECOND())
>
> START HOLDING BUTTON
>
> ​	START HOLDING BUTTON(PLAYER, BUTTUN)
>
> STOP ACCELERATING
>
> ​	STOP ACCELERATING(PLAYER)
>
> STOP ALL DAMAGE OVER TIME
>
> ​	STOP ALL DAMAGE OVER TIME(PLAYER)
>
> STOP ALL HEAL OVER TIME
>
> ​	STOP ALL HEAL OVER TIME(PLAYER)
>
> STOP CAMERA
>
> ​	STOP CAMERA(PLAYER)
>
> STOP CHASING GLOBAL VARIABLE
>
> ​	STOP CHASING GLOBAL VARIABLE(변수)
>
> STOP CHASING PLAYER VARIABLE
>
> ​	STOP CHASING PLAYER VARIABLE(PLAYER, 변수)
>
> STOP DAMAGE OVER TIME
>
> ​	STOP DAMAGE OVER TIME(DAMAGE OVER TIME ID)
>
> STOP FACING
>
> ​	STOP FACING(PLAYER)
>
> STOP FORCING PLAYER TO BE HERO
>
> ​	STOP FORCING PLAYER TO BE HERO(PLAYER)
>
> STOP FORCING SPAWN ROOM
>
> ​	STOP FORCING SPAWN ROOM(TEAM())
>
> STOP FORCING THROTTLE
>
> ​	STOP FORCING THROTTLE(PLAYER)
>
> STOP HEAL OVER TIME
>
> ​	STOP HEAL OVER TIME(HEAL OVER TIME ID())
>
> STOP HOLDING BUTTON
>
> ​	STOP HOLDING BUTTON(PLAYER, BUTTON)
>
> TELEPORT
>
> ​	TELEPORT(PLAYER, POSITION)
>
> UNPAUSE MATCH TIME
>
> ​	UNPAUSE MATCH TIME()
>
> WAIT
>
> ​	WAIT(TIME(), WAIT BEHAVIOR)