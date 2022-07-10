<template>
  <section>
    <img alt="Logo RV & Co" src="@/assets/logo.png" />
    <h1>Studio Rv & Co</h1>
    <p>
      {{ $t("text.1") }}<br />
      {{ $t("text.2") }}
    </p>
    <p>{{ $t("available-soon") }}</p>
    <a href="https://www.youtube.com/channel/UCbTaxj24z8viOFR6NXMKurQ">
      <svg height="30" viewBox="0 0 160 110">
        <path
          d="M154.3 17.5a19.6 19.6 0 0 0-13.8-13.8C128.4.4 79.7.4 79.7.4S31 .5 18.9 3.8A19.6 19.6 0 0 0 5.1 17.6C1.44 39.1.02 71.86 5.2 92.5A19.6 19.6 0 0 0 19 106.3c12.1 3.3 60.8 3.3 60.8 3.3s48.7 0 60.8-3.3a19.6 19.6 0 0 0 13.8-13.8c3.86-21.53 5.05-54.27-.1-75z"
          fill="red"
        />
        <path fill="#fff" d="M64.2 78.4L104.6 55 64.2 31.6z" />
      </svg>
    </a>
    <a href="https://twitter.com/Rv_and_Co">
      <svg height="30" viewBox="0 0 300.00006 244.18703">
        <g transform="translate(-539.17946,-568.85777)" id="layer1">
          <path
            id="path3611"
            style="
              fill: #1da1f2;
              fill-opacity: 1;
              fill-rule: nonzero;
              stroke: none;
            "
            d="m 633.89823,812.04479 c 112.46038,0 173.95627,-93.16765 173.95627,-173.95625 0,-2.64628 -0.0539,-5.28062 -0.1726,-7.90305 11.93799,-8.63016 22.31446,-19.39999 30.49762,-31.65984 -10.95459,4.86937 -22.74358,8.14741 -35.11071,9.62551 12.62341,-7.56929 22.31446,-19.54304 26.88583,-33.81739 -11.81284,7.00307 -24.89517,12.09297 -38.82383,14.84055 -11.15723,-11.88436 -27.04079,-19.31655 -44.62892,-19.31655 -33.76374,0 -61.14426,27.38052 -61.14426,61.13233 0,4.79784 0.5364,9.46458 1.58538,13.94057 -50.81546,-2.55686 -95.87353,-26.88582 -126.02546,-63.87991 -5.25082,9.03545 -8.27852,19.53111 -8.27852,30.73006 0,21.21186 10.79366,39.93837 27.20766,50.89296 -10.03077,-0.30992 -19.45363,-3.06348 -27.69044,-7.64676 -0.009,0.25652 -0.009,0.50661 -0.009,0.78077 0,29.60957 21.07478,54.3319 49.0513,59.93435 -5.13757,1.40062 -10.54335,2.15158 -16.12196,2.15158 -3.93364,0 -7.76596,-0.38716 -11.49099,-1.1026 7.78383,24.2932 30.35457,41.97073 57.11525,42.46543 -20.92578,16.40207 -47.28712,26.17062 -75.93712,26.17062 -4.92898,0 -9.79834,-0.28036 -14.58427,-0.84634 27.05868,17.34379 59.18936,27.46396 93.72193,27.46396"
          />
        </g>
      </svg>
    </a>
    <p>
      <a href="mailto:studio@rvandco.fr">studio@rvandco.fr</a>
    </p>
  </section>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  user-select: unset;
}

body {
  background: rgb(69, 60, 54);
  background: -moz-radial-gradient(
    circle,
    rgba(69, 60, 54, 1) 0%,
    rgba(31, 38, 45, 1) 100%
  );
  background: -webkit-radial-gradient(
    circle,
    rgba(69, 60, 54, 1) 0%,
    rgba(31, 38, 45, 1) 100%
  );
  background: radial-gradient(
    circle,
    rgba(69, 60, 54, 1) 0%,
    rgba(31, 38, 45, 1) 100%
  );
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#453c36",endColorstr="#1f262d",GradientType=1);
  height: 100vh;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  font-family: "Raleway", Helvetica, Arial, sans-serif;
  text-align: center;
  color: white;
  user-select: none;
  overflow: hidden;
  text-shadow: rgba(0, 0, 0, 0.5) 0 0 12px;
  padding: 0 16px;

  img {
    -webkit-user-drag: none;
    -khtml-user-drag: none;
    -moz-user-drag: none;
    -o-user-drag: none;
    user-drag: none;
    pointer-events: none;
  }

  h1 {
    padding-top: 60px;
    font-size: 3em;
  }

  p {
    font-size: 1.3em;
    line-height: 1.55;
    padding-top: 18px;

    &:first-of-type {
      padding-top: 22px;
    }

    &:last-of-type {
      padding: 10px 0 20px;
      font-size: 1em;
    }
  }

  a {
    text-decoration: none;
    color: white;
  }

  svg {
    margin: 40px 14px 0;
    transition: transform 0.2s;

    &:hover {
      transform: scale(1.3);
    }
  }
}
</style>
