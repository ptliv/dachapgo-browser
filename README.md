# 다챱고 브라우저 (Dachapgo Browser)

프로필마다 기기 지문·프록시·쿠키를 따로 두는 Windows 용 멀티 프로필 브라우저입니다.
AdsPower Local API 와 같은 모양의 API(`http://127.0.0.1:50330/api/v1/...`)를 제공해, AdsPower 용으로 만든 자동화 도구를 그대로 붙일 수 있습니다.

> **라이선스가 있어야 씁니다.** 누구나 내려받을 수 있지만, 다챱고 대표가 발급한 라이선스 키가 없으면 브라우저를 열 수 없습니다.

## 내려받기

[**최신 판 내려받기 (Releases)**](https://github.com/ptliv/dachapgo-browser/releases/latest) → `Dachapgo-Browser-Windows-x64-<판>.zip`

- Windows 10/11 64비트
- 받은 zip 이 맞는지는 같은 릴리스의 `.sha256` 값과 비교해 확인할 수 있습니다.

## 설치와 라이선스

1. zip 을 원하는 폴더(예: `C:\Dachapgo`)에 통째로 풉니다.
2. `Dachapgo.exe` 를 실행합니다. Windows 가 "알 수 없는 게시자" 경고를 띄우면 **추가 정보 → 실행**.
3. 앱의 **🔑 라이선스 인증 · 발급 관리** 탭에 보이는 HWID(`DCG-XXXX-XXXX-XXXX`)를 다챱고 대표에게 보냅니다.
4. 받은 라이선스 키(`DACHAPGO1.`로 시작)를 같은 탭에 붙여 넣고 **🔑 라이선스 키 인증 및 적용**을 누릅니다.

- 키 하나로 쓸 수 있는 PC 대수는 발급하는 쪽이 정합니다. 앱은 하루 한 번 인터넷으로 확인하고, 끊겨도 마지막 확인 뒤 7일까지는 그대로 됩니다.
- 사용 정지된 키는 다음 확인 때부터 막힙니다.

## 쓰기

| 무엇 | 어디 |
|---|---|
| 대시보드 | `http://127.0.0.1:50330/dachapgo` (앱 창) |
| Local API | `http://127.0.0.1:50330/api/v1/...` — 키는 `data\API_KEY.txt` |
| 프로필·쿠키·설정 | 앱 폴더의 `data\` |

## 새 판으로 올리기

[Releases](https://github.com/ptliv/dachapgo-browser/releases/latest) 에서 새 zip 을 받아, 앱을 끈 뒤 같은 폴더에 덮어 풉니다. `data\`(프로필·라이선스)는 그대로 남습니다.
앱의 업데이트 확인 버튼도 이 릴리스를 봅니다.

## 라이선스

다챱고 앱·대시보드·API 서버는 비공개 소스 독점 소프트웨어입니다 — [LICENSE](LICENSE).
함께 들어 있는 오픈소스(Fingerprint Chromium 등)는 각자의 라이선스를 따릅니다 — [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

각 웹사이트의 이용약관과 관련 법령을 지키는 것은 사용자의 책임입니다.
