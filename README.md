# Midway 1942 — TF2 air battle mod

A SourceMod plugin for Team Fortress 2 dedicated servers: flyable F4F-4 Wildcats and A6M2 Zeros, moving carrier fleets and a
cockpit HUD over Midway Atoll.
The b57 release ships the Korean UI. Balance settings: `cfg/sourcemod/tfplane_balance.cfg`.

## Downloads

See [Releases](https://github.com/kfgjioj/mod_make/releases).

| File | What it is |
|---|---|
| `Midway_b57_SourceMod.zip` | Server plugin (`tfplane.smx` and its editable source `.sp`/`.inc`), models, materials, sounds, example config, installation guide and credits |
| `Midway_b57_FastDL.zip` | The same client files compressed as `.bz2` for your HTTP download server (`sv_downloadurl`), with credits |
| `dogfight_midway_b56.bsp` | The map (put it in `tf/maps/`) |
| `dogfight_midway_b56.bsp.bz2` | The map compressed for your download server (`maps/`) |
| `MAP_CREDITS.txt` | Map credits (satellite and seabed data, textures, models) |

**Map and plugin versions:** the latest map is **b56** and it is played with the latest SourceMod release **b57**.
Get the map from the [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3834580021) by subscribing, or download the BSP from the release; it is the same file.

Install instructions are in `README.md` inside the SourceMod ZIP. MetaMod:Source and SourceMod are required and not included.

## Licence and credits

The plugin code is GPL v3 or later. Models, sounds and map data are by their authors under CC BY 4.0, CC BY 3.0, CC0 and
public-domain terms; see `CREDITS.md` and `licenses/` inside each ZIP. Team Fortress 2 and Source are trademarks of Valve
Corporation. This is an independent community project, not affiliated with or endorsed by Valve.

---

## 한국어

TF2 전용 서버용 SourceMod 플러그인입니다. 미드웨이 환초 위에서 F4F-4와 영식을 직접 조종하고, 움직이는 항모 함대와 싸웁니다.
b57은 한글 UI입니다. 밸런스 설정은 `cfg/sourcemod/tfplane_balance.cfg`.

- `Midway_b57_SourceMod.zip`: 서버용 플러그인과 수정 가능한 소스(`.sp`, `.inc`), 모델·재질·소리, 설정 예시, 설치 안내, 크레딧
- `Midway_b57_FastDL.zip`: 같은 파일을 `.bz2`로 압축한 웹 다운로드용 파일과 크레딧
- `dogfight_midway_b56.bsp`: 맵 (`tf/maps/`에 넣기)
- `dogfight_midway_b56.bsp.bz2`: 다운로드 서버용 압축 맵 (`maps/`)
- `MAP_CREDITS.txt`: 맵 크레딧 (위성·해저 자료, 재질, 모델)

**맵과 플러그인 버전:** 맵 최신은 **b56**이고, 최신 SourceMod **b57**과 함께 씁니다.
맵은 [스팀 창작마당](https://steamcommunity.com/sharedfiles/filedetails/?id=3834580021)에서 구독해도 되고, 릴리스에서 BSP를 받아도 됩니다(같은 파일).

설치 방법은 SourceMod ZIP 안의 `README.md`를 보세요. MetaMod:Source와 SourceMod는 따로 설치해야 합니다.
플러그인 코드는 GPL v3 이상이고, 모델·소리·지도 자료의 저작자와 라이선스는 각 ZIP 안의 `CREDITS.md`와 `licenses/`에 있습니다.

## b56 변경 사항

- HUD: 컨퀘스트(티켓) 표시를 왼쪽 위로 옮기고 오른쪽 위는 TF2 킬로그 자리로 비움. 왼쪽 위 아군 함대 패널 제거.
- 킬로그: TF2 킬로그 다시 표시. 격추는 격추자 이름으로, 맞은 지 8초 안의 추락·대공포 마무리도 마지막 공격자에게. 위쪽 팀 인원 패널은 숨김.
- 함선 아이콘: 체력바(10칸) 추가. 갑판 위에서는 아군 함선 아이콘을 숨기고, 비행 중 가까우면 작게 표시.
- 기체 아이콘: 아군·적군 같은 크기·거리 기준. 근거리 표시를 40 m까지.
- 조준: 감도와 기수 추종을 조금 더 빠르게.
- 봇: 표적 선택, 꼬리 잡혔을 때 회피, 사격 개선.
- 아군끼리 충돌은 적기 격추로 치지 않음. 시작 시 두 함대 간격을 약 13.5 km로.
- 맵(b56): 얕은 바다와 깊은 바다 경계를 부드럽게, 넓은 바다의 사각 경계 제거, 샌드섬의 기름 탱크 연기 제거.

## b57 변경 사항 / Changes

[CHANGES_b56_to_b57.md](CHANGES_b56_to_b57.md)
