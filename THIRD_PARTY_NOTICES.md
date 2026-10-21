# 제3자 구성 요소 (Third-Party Notices)

다챱고 브라우저 배포 zip 에는 아래 오픈소스 구성 요소가 들어 있습니다. 각 구성 요소는 자기 라이선스를 따르며,
라이선스 전문은 배포 zip 의 `licenses/` 폴더에 있습니다.

| 구성 요소 | 버전 | 라이선스 | 출처 |
|---|---|---|---|
| Fingerprint Chromium (ungoogled-chromium 기반) | 148.0.7778.215 | BSD-3-Clause (+ Chromium 구성 요소 라이선스) | https://github.com/adryfish/fingerprint-chromium |
| Python | 3.11.9 | PSF License 2.0 | https://www.python.org/ |
| aiohttp | 3.14.3 | Apache-2.0 | https://github.com/aio-libs/aiohttp |
| aiohappyeyeballs · aiosignal · frozenlist · multidict · propcache · yarl | — | Apache-2.0 / PSF-2.0 | https://github.com/aio-libs |
| attrs | — | MIT | https://github.com/python-attrs/attrs |
| idna | — | BSD-3-Clause | https://github.com/kjd/idna |
| typing_extensions | — | PSF-2.0 | https://github.com/python/typing_extensions |
| Pillow | 12.3.0 | MIT-CMU (HPND) | https://github.com/python-pillow/Pillow |
| Nuitka 런타임 | 4.3.1 | Apache-2.0 | https://github.com/Nuitka/Nuitka |
| tzdata | 2026.4 | Apache-2.0 | https://github.com/python/tzdata |
| defusedxml | 0.7.1 | PSF-2.0 | https://github.com/tiran/defusedxml |
| pydantic-core | 2.46.5 | MIT | https://github.com/pydantic/pydantic-core |

Fingerprint Chromium 은 수정 없이 그대로 싣습니다. Chromium 자체 구성 요소의 라이선스 목록은
브라우저 주소창에 `chrome://credits` 를 열어 볼 수 있습니다.

이 표에 없는 부분(다챱고 앱·대시보드·API 서버)은 `LICENSE` 의 다챱고 사용권 계약을 따릅니다.
