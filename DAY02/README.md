# 2일차

<br>

## 타이포그래피 (Typography) 설계

![](https://i.imgur.com/1NeZDSv.png)
> 타이포그래피 설계를 통해 문서의 가독성과 판독성을 높이고, 모듈화를 통해 통일성을 유지하여 일관된 문서로 보여지도록 패턴을 설정합니다. 타이포그래피를 최적화하는 것은 가독성, 접근성, 사용성 뿐만 아니라 전반적인 그래픽 발란스를 맞추는 것입니다.

<br>

### 제목 설정 (H1~H6)
- 본문 설정 기준으로 제목 설계

- `<h1>`~`<h6>` 요소 활용 범위 설정
  - 본문 페이지 기준 제목의 갯수를 확인

- 제목 간의 비율 설정
  - 제목 크기 비율 설정하여 페이지의 연계성이 보여지도록 정의

- 타입 스케일 배율(Type Scale Ratio)
  - 1.067 — Minor Second
  - 1.125 — Major Second
  - 1.200 — Minor Third
  - 1.250 — Major Third
  - 1.333 — Perfect Fourth
  - 1.414 — Augmented Fourth
  - 1.500 — Perfect Fifth
  - 1.600 — Minor Sixth
  - 1.618 — Golden Ratio (황금 비율)
  - 1.667 — Major Sixth
  - 1.778 — Minor Seventh
  - 1.875 — Major Seventh
  - 2.000 — Octave
  - 2.500 — Major Tenth

<br>

### 본문 설정 (paragraph)
- 브라우저 기본 폰트 사이즈
  > 대부분의 브라우저 폰트 사이즈 기본값 `12pt, 16px, 1em, 100% ` 사용
  ```css
  font-size : 16px;
  line-height : 1.2;
  ```

- 국문, 영문 폰트 사이즈

  - 국문 폰트
    ```css
    /* 국문은 획수가 많아 영문 폰트보다 커보이기 때문에 */
    font-size : 13px;
    /* 또는 */
    font-size : 14px;
    /* 사이즈가 적합하다. */
    ```

  - 영문 폰트
    ```css
    font-size : 16px;
    /* 브라우저 기본 사이즈(16px)가 적합하다 */
    ```

<br>

### 타입 스케일 배율(Type Scale Ratio)
  > 제목(`h1~h6`) 간의 스케일 값(배율)을 설정할 때 활용

| 스케일 수치 | 스케일 명칭          |
|:------:|:------------------------|
| 1.067  | Minor Second            |
| 1.125  | Major Second            |
| 1.200  | Minor Third             |
| 1.250  | Major Third             |
| 1.333  | Perfect Fourth          |
| 1.414  | Augmented Fourth        |
| 1.500  | Perfect Fifth           |
| 1.600  | Minor Sixth             |
| 1.618  | Golden Ratio (황금 비율) |
| 1.667  | Major Sixth             |
| 1.778  | Minor Seventh           |
| 1.875  | Major Seventh           |
| 2.000  | Octave                  |
| 2.500  | Major Tenth             |

<br>

### 자간, 어간, 행간 설정

![](../images/typography.png)

- 자간/행간 간격
  - 자간 letter-spacing 간격 설정
  - 폰트사이즈 / 2000 (1byte 폰트조각 : 2000) * 가로비율 (-50%) <br>
    예) 16px / 2000 * (-50%) = -0.4em(em단위 사용 : font-size 상대값 대응)
  - 행간 line-height 기준 버티컬리듬 설정

- 레이아웃 영역(Header/Footer/Conteiner 등) 간의 간격
  - baseline 기준 버티컬리듬 설정

### 참고
- [Grid Lover](https://www.gridlover.net/try)
- [px/em 단위계산](http://pxtoem.com/)
- [한글 타이포그래피](https://www.slideshare.net/ssuser968745/ss-56191240)