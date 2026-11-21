# 동현레 자료

**EA has not endorsed and does not support this product.**

[동현레](https://raspberry-kim.github.io/donghyun-lab19/)가 전투를 열 때 받는 원작 자료다. 동현레의 코드와 문서는 [동현레 저장소](https://github.com/Raspberry-Kim/donghyun-lab19)에 있고, 이 저장소에는 자료만 있다.

## 들어 있는 것

| 파일 | 크기 | 내용 |
|---|---|---|
| `re.data` | 18,906,225바이트 | 원작의 기본 자료 파일 11개를 고치지 않고 차례로 이어 붙인 덩어리 |
| `re.data.json` | — | 덩어리 안에서 파일마다 시작·끝 자리를 적은 목록 |

이어 붙인 파일은 `allies.mix` · `conquer.mix` · `hires.mix` · `interior.mix` · `local.mix` · `lores.mix` · `russian.mix` · `snow.mix` · `sounds.mix` · `speech.mix` · `temperat.mix`다. 그림·효과음·음성이고, **음악과 영상은 없다.** `re.data`의 SHA-256은 `af8043914cc5f36ef395d502a12f03becfccdac1c69c37e2d25f9df3aa6a6031`이다.

## 어디서 왔나

Command & Conquer: Red Alert(1996, Westwood Studios)를 Electronic Arts가 2008년에 무료로 풀었다. 이 자료는 그 판의 기본 자료이고, OpenRA가 받는 `basefiles` 꾸러미([목록](https://github.com/OpenRA/OpenRA/blob/bleed/mods/ra-content/installer/downloads.yaml), SHA-1 `aa022b208a3b45b4a45c00fdae22ccf3c6de3e5c`)와 같다. 잇는 방법은 동현레 저장소의 `engine/pack-data.py`에 있다.

## 권리와 조건

- 이 자료의 저작권은 Electronic Arts Inc.에 있다. 나는 권리를 갖고 있지 않고, 자유 라이선스로 다시 내놓는 것도 아니다.
- [EA의 모딩 지침](https://www.ea.com/games/command-and-conquer/news/modding-faq)에 따라 무료·비영리로만 나눈다. 음악 파일은 넣지 않았다. 후원을 받지 않는다.
- EA는 이 허락을 언제든 거둘 수 있다. EA가 원하면 이 저장소를 바로 내린다.
- 이 저장소는 논문 보관소(Zenodo)에 보관하지 않는다.
- Command & Conquer와 Red Alert는 Electronic Arts Inc.의 상표다. 동현레는 EA와 관계가 없다.
