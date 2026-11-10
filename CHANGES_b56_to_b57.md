# b56 → b57

## 한국어

- **조작:** 좌우로 크게 끌 때 걸리던 것과, 조금 아래를 보며 좌우로 돌 때 기수가 처박히던 것을 고침(좌우·상하를 나눠서 따라감). 조준 추종을 조금 더 빠르게.
- **속도:** 공중에서는 고도와 상관없이 같은 속도(이착륙 때만 느림). 가속을 약 15% 올림.
- **폭탄:** 공기 저항과 투하 시 아래·뒤로 밀어내기를 넣어 비행기보다 앞으로 나가지 않음. 함선 근접 피해 범위를 70m로 넓힘.
- **피해:** 기관총 한 발 피해 7 → 10.
- **마커:** 비행기는 작은 삼각형 + 체력바 하나로, 거리에 따라 크기가 갑자기 바뀌지 않음. 함선 아이콘도 하나로 합침. 갑판 위에서는 아군 함선 아이콘을 숨김.
- **봇:** 공중에서 시속 360km 아래로 떨어지지 않게 함(너무 쉽게 따라잡히던 문제).
- **킬로그:** 격추된 잔해를 다시 맞혀도 킬·도움이 넘어가지 않음.
- **맵 전환:** 비행 맵에서 일반맵으로 넘어가면 로켓·소품 같은 엔티티가 안 보이던 문제를 고침(재접속 필요 없음).
- **서버 설정:** `cfg/sourcemod/tfplane_balance.cfg`에서 체력(기체별, 미국·일본 항모별), 비행·함대 속도, 피해량, 대공 범위, 교전 거리를 서버마다 조절.
- **맵:** b56과 같음(`dogfight_midway_b56`).

## English

- **Controls:** a wide sideways drag no longer snags, and turning with the aim a little low no longer dives (sideways and up/down are followed separately). The nose follows the aim a little faster.
- **Speed:** the same speed at any height in the air (slower only taking off and landing). About 15% more acceleration.
- **Bombs:** air drag and a push down and back on release, so a bomb no longer runs ahead of the aeroplane. Near misses damage ships out to 70 m.
- **Damage:** machine-gun damage per round 7 → 10.
- **Markers:** one small pointer with a health bar per aeroplane, with no sudden size change. One icon per ship. Friendly ship icons are hidden while on a deck.
- **Bots:** held above 360 km/h in the air (they were caught far too easily).
- **Kill feed:** shooting a wreck that is already going down earns no kill or assist.
- **Map change:** rockets, props and other entities no longer vanish after moving from the flight map to an ordinary map (no reconnect needed).
- **Server settings:** `cfg/sourcemod/tfplane_balance.cfg` sets health (per aircraft, per side's carriers), flight and fleet speed, damage, flak radius and fleet distance per server.
- **Map:** unchanged from b56 (`dogfight_midway_b56`).
