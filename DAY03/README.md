# 3일차

<br>

## 타이포그래피 설계

![](../images/typography.png)

<br>

### 행간 설정 (상대 값)

```css
/* line-height 상대 높이 설정 */
/* 베이스라인 = 10px(짝수로 임의 설정) */
/* h1~h6(제목사이즈) × 1.5(비율) = 행간 높이 설정 */

/* 18px(h6 폰트 사이즈) * 1.5 = 27px(행간 높이) */
/* 10px(베이스라인 기준) × 4행 = 40px */
/* 30px(베이스라인) - 27px(행간 높이) ÷ 2 = 상,하 공간(padding)  */
h6 {
  line-height: 1.5;
  padding-top: 2px;
  padding-bottom: 2px;
}

/* 22px(h5 폰트 사이즈) * 1.5 = 33px(행간 높이) */
/* 10px(베이스라인 기준) × 4행 = 40px */
/* 40px(베이스라인) - 33px(행간 높이) ÷ 2 = 상,하 공간(padding)  */
h5 {
  line-height: 1.5;
  padding-top: 4px;
  padding-bottom: 4px;
}

/* 27px(h4 폰트 사이즈) * 1.5 = 40.5px(행간 높이) */
/* 10px(베이스라인 기준) × 5행 = 50px */
/* 50px(베이스라인) - 41px(행간 높이) ÷ 2 = 상,하 공간(padding)  */
h4 {
  line-height: 1.5;
  padding-top: 5px;
  padding-bottom: 5px;
}

/* 34px(h3 폰트 사이즈) * 1.5 = 51px(행간 높이) */
/* 10px(베이스라인 기준) × 9행 = 60px */
/* 60px(베이스라인) - 51px(행간 높이) ÷ 2 = 상,하 공간(padding)  */
h3 {
  line-height: 1.5;
  padding-top: 5px;
  padding-bottom: 5px;
}

/* 43px(h2 폰트 사이즈) * 1.5 = 64.5px(행간 높이) */
/* 10px(베이스라인 기준) × 7행 = 70px */
/* 70px(베이스라인) - 65px(행간 높이) ÷ 2 = 상,하 공간(padding)  */
h2 {
  line-height: 1.5;
  padding-top: 3px;
  padding-bottom: 3px;
}

/* 53px(h1 폰트 사이즈) * 1.5 = 79.5px(행간 높이) */
/* 10px(베이스라인 기준) × 9행 = 90px */
/* 90px(베이스라인) - 80px(행간 높이) ÷ 2 = 상,하 공간(padding) */
h1 {
  line-height: 1.5;
  padding-top: 5px;
  padding-bottom: 5px;
}
```

<br>

### 버티컬리듬 설정
> 버티컬리듬은 폰트(Font)와 아이템들(Contents, Elements)의 행간(Vertical)의 공간을 일정하게 설정하여 페이지 마다의 일관성을 유지하기 위해 설정 합니다.

- 베이스라인(baseline) 기준

  - 본문폰트 기준 행간비율을 베이스라인으로 설정
    > 예) 14px(본문폰트) × 1.5(행간비율) = 21px(베이스라인)

  - 임의 단위(짝수)로 베이스라인 설정 (암산하기 쉬운 단위)
    > 예) 10px(임의짝수) × 행의 갯수

<br>

### 자간 설정

- 자간(letter-spacing) 설정

  - 폰트사이즈 / 2000 (1byte 폰트조각 : 2000) * 가로비율 (-50%) <br>
    > 예) 16px / 2000 * (-50%) = -0.4em(em단위 사용 : font-size 상대값 대응)

<br>

### 어간 설정

- 어간(word-spacing) 설정

  - 단어와 단어 사이의 간격 (서체에 따라 다름)
  - 디자인적으로 단어의 간격이 필요할 시 사용

<br>
<br>

## 웹 폰트 설정
[구글 본고딕 폰트](https://fonts.google.com/?subset=korean&selection.family=Noto+Sans+KR)를 설정합니다.

#### HTML `<link>` 로 불러오기
```html
<link href="https://fonts.googleapis.com/css?family=Noto+Sans+KR&display=swap" rel="stylesheet">
```

<br>

#### CSS `@import` 로 불러오기
```css
@import url('https://fonts.googleapis.com/css?family=Noto+Sans+KR&display=swap');
```
<br>

#### CSS `webfont` 설정하기
```css
body * {
  font-family: 'Noto Sans KR', sans-serif;
}
```

<br>
<br>

### 참고
- [Grid Lover](https://www.gridlover.net/try)
- [px/em 단위계산](http://pxtoem.com/)
- [한글 타이포그래피](https://www.slideshare.net/ssuser968745/ss-56191240)