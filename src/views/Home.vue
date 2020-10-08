<template>
  <div class="home">
    <div class="chi-grid -mt--3">
      <div class="chi-col -w--6">
        <h3>Welcome, John</h3>
        <p>Customer since August 2002</p>
      </div>
      <div class="chi-col -w--6">
        <span>
          Account Number:
        </span>
        <button class="chi-button -flat">218-729-9669-940</button>
      </div>
    </div>
    <div class="chi-grid -mt--3">
      <div class="chi-col -w--6">
        <div class="chi-card content-left">
          <div class="chi-card__header">
            <div class="chi-card__title">My Bill</div>
          </div>
          <div class="chi-card__content">
            <div class="chi-grid">
              <div class="chi-col -w--12">
                <p>Current Amount Due</p>
                <h2>$49.00</h2>
              </div>
              <div class="chi-col -w--4">
                <p>Payment Due By</p>
                <h4>July 12, 2020</h4>
              </div>
              <div class="chi-col -w--4">
                <p>Autopay</p>
                <h4>ON</h4>
              </div>
              <div class="chi-col -w--4">
                <p>Paperless Billing</p>
                <h4>OFF</h4>
              </div>
            </div>
            <div class="chi-grid">
              <div class="chi-col -w--12">
                <p>Last payment of $49.00 was made on 06/16/2020. <a href="#">View History ></a></p>
              </div>
            </div>
          </div>
          <div class="chi-card__footer -no-border">
            <button class="chi-button -lg">View Bill</button>
            <button class="chi-button -primary -lg">Make Payment</button>
          </div>
        </div>
      </div>
      <div class="chi-col -w--6">
        <div class="chi-card">
          <div class="chi-card__header">
            <div class="chi-card__title">My Support</div>
          </div>
          <div class="chi-card__content">
            <p>Let us help you troubleshoot and resolve issues, order or change service, and get answers to account questions.</p>
            <div class="-d--flex search-row">
              <div class="chi-form__item -inline -flex--grow1">
                <input class="chi-input -lg" type="text" id="example__inline-input01" placeholder="Enter your question">
              </div>
              <div class="chi-form__item -inline -flex--grow1">
                <button class="chi-button -lg search-button">Find Answers</button>
              </div>
            </div>
            <div class="-d--flex search-row">
              <div class="chi-form__item -inline -flex--grow1">
                <button class="chi-button -primary -outline search-button">
                  <i class="chi-icon icon-comments-dots -lg"></i>
                  <p>Chat</p>
                </button>
              </div>
              <div class="chi-form__item -inline -flex--grow1">
                <button class="chi-button -primary -outline search-button">
                  <i class="chi-icon icon-phone -lg"></i>
                  <p>Phone</p>
                </button>
              </div>
              <div class="chi-form__item -inline -flex--grow1">
                <button class="chi-button -primary -outline search-button">
                  <i class="chi-icon icon-mail -lg"></i>
                  <p>Email</p>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="chi-grid -mt--3">
      <div class="chi-col -w--4">
        <div class="chi-card">
          <div class="chi-card__header">
            <div class="chi-card__title">My Internet</div>
          </div>
          <div class="chi-card__content">
            <p><i class="chi-icon icon-wifi-outline -xl"></i></p>
            <p class="-mt--3">CenturyLink High-speed Internet</p>
          </div>
          <div class="chi-card__footer -no-border -align--center">
            <button class="chi-button -lg">Manage My Internet</button>
          </div>
        </div>
      </div>
      <div class="chi-col -w--4">
        <div class="chi-card">
          <div class="chi-card__header">
            <div class="chi-card__title">My Phone</div>
          </div>
          <div class="chi-card__content">
            <p><i class="chi-icon icon-phone -xl"></i></p>
            <p class="-mt--3">CenturyLink Homephone Unlimited</p>
          </div>
          <div class="chi-card__footer -no-border -align--center">
            <button class="chi-button -lg">Manage My Phone</button>
          </div>
        </div>
      </div>
      <div class="chi-col -w--4">
        <div class="chi-card">
          <div class="chi-card__header">
            <div class="chi-card__title">My TV</div>
          </div>
          <div class="chi-card__content">
            <p><i class="chi-icon icon-wifi-outline -xl"></i></p>
            <p class="-mt--3">DIRECTV through CenturyLink</p>
          </div>
          <div class="chi-card__footer -no-border -align--center">
            <button class="chi-button -lg">Manage My TV</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.chi-button {
  flex-direction: column;
}
.chi-col {
  h3 {
    margin: 0.4rem !important;
  }
}
.content-left {
  .chi-card__content {
    text-align: left;
  }
}
.search-row {
  margin: 20px 0px;
}
.search-button {
  flex-direction: column;
}
</style>
