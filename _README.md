# 내일의 집

### 1. GNB

- 로그인을 하지 않은 경우

```html
<div class="button-group">
  <button class="gnb-icon-button is-search lg-hidden" type="button">
    <i class="ic-search" aria-label="검색창 열기 버튼"></i>
  </button>
  <a href="/" class="gnb-icon-button is-cart">
    <i class="ic-cart" aria-label="장바구니 페이지로 이동"></i>
    <strong class="badge">5</strong>
  </a>
  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```

- 로그인을 했을 경우

```html
<div class="button-group">
  <button class="gnb-icon-button is-search lg-hidden" type="button">
    <i class="ic-search" aria-label="검색창 열기 버튼"></i>
  </button>

  <a href="/" class="gnb-icon-button sm-hidden">
    <i class="ic-bookmark" aria-label="스크랩북 페이지로 이동"></i>
  </a>

  <a href="/" class="gnb-icon-button sm-hidden">
    <i class="ic-bell" aria-label="내 소식 페이지로 이동"></i>
  </a>

  <a href="/" class="gnb-icon-button is-cart">
    <i class="ic-cart" aria-label="장바구니 페이지로 이동"></i>
    <strong class="badge">5</strong>
  </a>

  <button
    class="gnb-avatar-button sm-hidden"
    type="button"
    aria-label="마이메뉴 열기 버튼"
  >
    <div class="avatar-32">
      <img src="./assets/images/img-user-01.jpg" alt="사달라 아저씨" />
    </div>
  </button>
</div>
```
