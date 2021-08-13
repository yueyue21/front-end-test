<!-- Please remove this file from your project -->
<template>
  <div class="card">
    <div class="content" style="margin-left: 41px; margin-top: 21px">
      <!-- first step -->
      <div class="step d-flex justify-content-start">
        <div style="flex-basis: 29px">
          <div>
            <svg
              aria-hidden="true"
              focusable="false"
              data-prefix="fas"
              data-icon="check-circle"
              class="check-mark"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                fill="currentColor"
                d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"
              ></path>
            </svg>
          </div>
          <div class="first-bottom-line"></div>
        </div>
        <div class="position-relative">
          <div class="text-nowrap step-counter">01</div>
          <div class="main-content">
            <div class="step-title">Step One</div>
            <div class="step-body text-truncate">Your basket</div>
          </div>
        </div>
      </div>
      <div class="gap">
        <div class="gap-content"></div>
      </div>
      <!-- second step -->
      <div class="step d-flex justify-content-start">
        <div style="flex-basis: 29px" class="position-relative">
          <div class="top-line"></div>
          <div>
            <svg
              class="check-mark"
              aria-hidden="true"
              focusable="false"
              data-prefix="fas"
              data-icon="check-circle"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                fill="currentColor"
                d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"
              ></path>
            </svg>
          </div>
          <div class="bottom-line"></div>
        </div>
        <div class="position-relative">
          <div class="text-nowrap step-counter">02</div>
          <div class="main-content">
            <div class="step-title">Step Two</div>
            <div class="step-body text-truncate mt-1">Your deals</div>
          </div>
        </div>
      </div>
      <div class="gap">
        <div class="gap-content"></div>
      </div>
      <!-- third step -->
      <div class="step d-flex justify-content-start">
        <div style="flex-basis: 29px" class="position-relative">
          <div class="top-line"></div>
          <div>
            <svg
              aria-hidden="true"
              focusable="false"
              data-prefix="far"
              data-icon="circle"
              class="check-mark"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                fill="currentColor"
                d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 448c-110.5 0-200-89.5-200-200S145.5 56 256 56s200 89.5 200 200-89.5 200-200 200z"
              ></path>
            </svg>
          </div>
          <!-- disable when it is end of active step -->
          <!-- <div class="bottom-line"></div> -->
        </div>
        <div class="position-relative">
          <div class="text-nowrap step-counter">03</div>
          <div class="main-content">
            <div class="step-title">Step Three</div>
            <div class="step-body text-truncate mt-1">Payment</div>
          </div>
        </div>
      </div>
      <div class="gap">
        <!-- disable when it is end of active step -->
        <!-- <div class="gap-content"></div> -->
      </div>
      <!-- forth step -->
      <div class="step d-flex justify-content-start">
        <div style="flex-basis: 29px" class="position-relative">
          <!-- disable when it is not ready -->
          <!-- <div class="top-line"></div> -->
          <div>
            <svg
              aria-hidden="true"
              focusable="false"
              data-prefix="far"
              data-icon="circle"
              class="check-mark"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                fill="#678C94"
                d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 448c-110.5 0-200-89.5-200-200S145.5 56 256 56s200 89.5 200 200-89.5 200-200 200z"
              ></path>
            </svg>
          </div>
          <!-- disable when it is end of active step -->
          <!-- <div class="bottom-line"></div> -->
        </div>
        <div class="position-relative">
          <div class="text-nowrap step-counter">04</div>
          <div class="main-content">
            <div class="step-title">Step Four</div>
            <div class="step-body text-truncate mt-1">Order Complete</div>
          </div>
        </div>
      </div>
      <div class="gap">
        <!-- disable when it is end of active step -->
        <!-- <div class="gap-content"></div> -->
      </div>
    </div>
  </div>
</template>
<script>
export default {}
</script>

<style scoped>
.check-mark {
  width: 16px;
  height: 16px;
  margin-top: 10px;
  margin-left: 4px;
  color: red;
}
.gap-content {
  margin-left: 11px;
  border: 1px solid red;
  width: 1px;
  height: 100%;
}
.gap {
  height: 20px;
}
.top-line {
  width: 1px;
  height: 13px;
  border: 1px solid red;
  margin-left: 37%;
  position: absolute;
}
.first-bottom-line {
  width: 1px;
  height: 18px;
  border: 1px solid #ff0000;
  margin-left: 37%;
}
.bottom-line {
  width: 1px;
  height: 25px;
  border: 1px solid #ff0000;
  margin-left: 37%;
}
.main-content {
  position: absolute;
  z-index: 1;
  left: 16px;
  top: 4px;
}

@font-face {
  font-family: Asap;
  src: url('./Asap-VariableFont_wght.ttf');
}
.step-body {
  font-family: Asap;
  font-style: normal;
  font-weight: bold;
  font-size: 23px;
  line-height: 23px;
  width: 220px;
  /* identical to box height, or 100% */

  color: #27474e;
  margin-top: 4px;
}
@font-face {
  font-family: SairaCondensed;
  src: url('./SairaCondensed.ttf');
}
.step-title {
  margin-top: 4px;

  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 14px;
  /* identical to box height, or 87% */
  text-transform: uppercase;
  font-family: 'SairaCondensed';
  color: #496970;
}
.step-counter {
  position: absolute;
  left: 0%;
  /* right: 69.81%; */
  top: 0%;
  /* bottom: 45.45%; */

  font-family: Saira Condensed;
  font-style: normal;
  font-weight: 900;
  font-size: 23px;
  line-height: 23px;
  /* identical to box height, or 100% */

  color: #eff1f1;
}
.step {
  min-width: 159px;
  /* width: 159px; */
  height: 44px;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
.content {
  /* display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px; */

  /* width: 159px;
  height: 236px;
  left: 510px;
  top: 238px; */
}
.card {
  position: absolute;
  width: 329px;
  height: 282px;
  left: 476px;
  top: 219px;
  background: #fdfdfd;
  border: 1px solid #ebf0f1;
  box-sizing: border-box;
  box-shadow: 0px 0px 40px rgba(39, 71, 78, 0.1);
  border-radius: 20px;
}
</style>
