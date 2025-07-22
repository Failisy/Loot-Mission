# loot_mission
뽑힌 임무를 전체 타이틀로 띄우며 해당 임무가 적힌 아이템을 받습니다.

해당 명령어를 커멘드 블럭에 넣고 실행시키면 지정한 임무들 중 하나를 뽑아 알려줍니다.  
`/function loot_mission:loot/trigger`

현재 뽑을 임무들을 확인할 수 있습니다.  
`/data get storage minecraft:mission list`

직접 임무들을 커스텀 하세요!  
`/data merge storage minecraft:mission {list:["A","B","C"]}`

기본 임무들을 설정합니다.  
`/function loot_mission:loot/init`
