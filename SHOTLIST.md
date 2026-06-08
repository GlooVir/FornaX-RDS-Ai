# 스크린샷 촬영 가이드 (SHOTLIST)

README의 이미지 자리는 모두 만들어 두었습니다. 아래 **정확한 파일명**으로 캡처해
`github-public/assets/screenshots/` 폴더에 넣으면 README에 바로 표시됩니다.
(파일을 넣기 전까지는 GitHub에서 깨진 이미지 아이콘으로 보입니다.)

| 파일명 | 위치 | 무엇을 담나 | 권장 크기 |
|---|---|---|---|
| `hero.png` | 최상단 히어로 | 한 장으로 제품 전체를 설명. iPad 또는 Windows 화면에 원격 Mac 데스크톱이 떠 있고, 옆에 AI 채팅 패널. **가장 공들일 이미지.** | 1280×640 (가로 배너) |
| `avc444-compare.png` | Remote Desktop | 텍스트/색상 클로즈업 좌우 비교 — 왼쪽 FornaX(AVC444 선명), 오른쪽 일반 4:2:0(번짐). 같은 화면을 확대해 차이를 한눈에. | 1200×700 |
| `ai-chat.png` | AI Assistant | 앱 내 AI 채팅 + 모델 관리자. 로컬 모델 목록(Ollama/MLX)과 대화가 함께 보이게. | 1200×800 |
| `imessage-demo.gif` | In practice | 휴대폰 iMessage로 "회의록 요약해줘" 보내고 답이 오는 짧은 애니메이션. | 세로, <6초, **<5MB** |
| `ipad-remote.png` | Mac Studio 섹션 | iPad(거치 or 손)에 풀 색상으로 표시된 원격 Mac 데스크톱. 가능하면 실물 기기 사진. | 1200×800 |

## 촬영 팁

- **해상도/선명도**: Retina 캡처(⌘⇧4 후 영역 선택). 흐릿한 이미지는 역효과.
- **개인정보 가리기**: 실제 이름·이메일·API 키·내부 경로가 화면에 없도록. (README 신뢰 섹션과 직결)
- **일관된 톤**: 다섯 장의 배경/테마(라이트 or 다크)를 통일하면 전문성이 올라갑니다.
- **GIF 용량**: 5MB 넘으면 GitHub에서 느리게 로드됩니다. [gifski]나 ScreenToGif로 최적화, 프레임수 낮추기.
- **대체(alt) 텍스트**: README에 이미 넣어 두었습니다(검색·접근성용). 그대로 두세요.

## 우선순위 (시간이 없다면)

1. `hero.png` — 이거 하나만 있어도 첫인상이 완전히 달라집니다.
2. `avc444-compare.png` — "30초면 확인되는 차이" 주장을 눈으로 증명.
3. `ai-chat.png` → `imessage-demo.gif` → `ipad-remote.png` 순.

## 파일을 다 만든 뒤

`assets/screenshots/`에 다섯 파일을 넣고 README를 GitHub에 올리면 끝입니다.
파일명만 정확하면 추가 편집은 필요 없습니다.
