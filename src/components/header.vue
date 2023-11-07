<template>
  <header class="header">
    <div class="header__mobile">
      <img
        src="../assets/image/icons/Path 12462.svg"
        alt="back-bracket"
        class="header__bracket"
      />    
    </div>
    <div class="header__left">
      <img
        src="../assets/image/SparrowX-horizontal-RGB_gradient-FC-New.png"
        alt="Logo"
        class="header__logo"
      />
      <div class="header__settlement">
        <div class="header__settlement-price">
          <div class="header__settlement-text">
            <span>Settlement</span> Price
          </div>
          <button class="header__settlement-viewButton">View</button>
        </div>
        <div class="header__settlement-time">
          <div class="header__settlement-date">07-11-2018</div>
          <div class="header__settlement-hour">2:00:00PM (GMT+8)</div>
        </div>
      </div>
      <div class="header__asset">
        <span class="header__asset-label"><span>BTC</span>/USDT</span>
        <span class="header__asset-price"><span>6574</span>.26</span>
      </div>
      <div class="header__asset-barrier"></div>
      <div class="header__asset">
        <span class="header__asset-label"><span>ETH</span>/USDT</span>
        <span class="header__asset-price"><span>6574</span>.26</span>
      </div>
    </div>
    <div class="header__right">
      <div class="header__actions">
        <button class="header__actions-signinButton" a href="/sign-in">
          Sign In
        </button>
        <button class="header__actions-registerButton" a href="/register">
          Register
        </button>
        <div class="header__actions-barrier"></div>

        <img
          src="../assets/image/icons/Path 13229.svg"
          alt="globe"
          class="header__actions-globe"
        />
        <div class="header__actions-arrow"></div>
      </div>
    </div>
  </header>
</template>
