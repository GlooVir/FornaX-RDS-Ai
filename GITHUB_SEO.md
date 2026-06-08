# GitHub 검색 노출(SEO) 설정 가이드

README 본문에는 개발자 검색 키워드를 이미 반영했습니다. 아래 두 가지는 **GitHub 저장소 설정**에서 직접 적용해야 합니다 (Settings/About 우측 톱니).

## 1. About — Description (한 줄, 검색 가중치 가장 높음)

```
Run local LLMs on your Mac and use it from anywhere — a macOS AI assistant + native RDP server. Ollama & MLX, OpenAI/Anthropic-compatible API, on-device & private. Apple Silicon.
```

웹사이트 필드: `https://gloovir.com`

## 2. Topics (최대 20개 — 토픽 페이지 노출)

아래를 그대로 입력 (쉼표 없이 공백/엔터로 구분):

```
macos  apple-silicon  local-llm  ollama  mlx  on-device-ai  private-ai
ai-assistant  llm  ai-agent  coding-assistant  rag  whisper
rdp  remote-desktop  mac-mini  mac-studio  self-hosted  offline-ai  productivity
```

우선순위(20개 초과 시 뒤에서 제외): macos, apple-silicon, local-llm, ollama, mlx, on-device-ai, private-ai, ai-assistant, ai-agent, coding-assistant 를 우선 유지.

## 3. 노출에 영향을 주는 추가 요소

- **README 첫 화면 스크린샷/데모 GIF** — 체류시간↑, 스타 전환↑ (간접적으로 랭킹↑)
- **Social preview 이미지** (Settings → Social preview) — 외부 공유 시 노출
- **Releases** — 7/1 바이너리 + 명확한 changelog (활동성 신호)
- **꾸준한 커밋/이슈 응답** — GitHub 검색은 최신성·활동성을 반영
- **Star 수** — 가장 강한 랭킹 신호. 출시일 HN/Reddit/r/LocalLLaMA 동시 게시로 초기 스타 확보

## 4. 외부(Google) 검색 대비

README에 자연스럽게 포함된 검색구: `local LLM on Mac`, `on-device AI`, `private/offline AI`, `self-hosted AI`, `Ollama`, `MLX`, `OpenAI-compatible API`, `Claude Code / Cursor / Aider`, `RAG`, `coding assistant`, `Mac Mini / Mac Studio remote`. → Google에도 동일하게 색인됩니다.
