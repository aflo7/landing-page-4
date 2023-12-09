<script setup></script>

<template>
  <main>
    <div class="top-nav">
      <div class="top-nav-inner">
        <div class="flex-with-gap-20" style="align-items: center;">
          <div style="font-weight: bold; text-transform: uppercase;">United States</div>
          <div>Select your location</div>
        </div>
        <div class="flex-with-gap-20" style="align-items: center;">
          <input
            type="text"
            placeholder="Search parts, catalogs, specs and more"
            style="width: 400px; padding: 5px; border-radius: 5px; border: none;"
          />
          <div>Sign in</div>
        </div>
      </div>
    </div>
    <div style="display: flex; justify-content: center; padding: 10px">
      <div
        style="
          width: 1000px;
          display: flex;
          justify-content: space-between;
          align-items: center;
        "
      >
        <img src="./assets/eaton.png" alt="eton-logo" height="60px" />
        <div class="flex-with-gap-20">
          <div style="cursor: pointer;">Products</div>
          <div style="cursor: pointer;">Digital</div>
          <div style="cursor: pointer;">Services</div>
          <div style="cursor: pointer;">Markets</div>
          <div style="cursor: pointer;">Support</div>
          <div style="cursor: pointer;">Company</div>
        </div>
      </div>
    </div>
    <div
      class="main-img"
      style="color: white; display: flex; flex-direction: column; gap: 30px"
    >
      <div style="font-size: 3rem; font-weight: bold">
        Recreated by Andres.*
      </div>
      <div>
        *Developing more efficient, sustainable power management solutions that
        meet the ever-changing needs of our world.
      </div>
      <button class="see-how-btn">See how</button>
    </div>
    <div style="display: flex; justify-content: center; padding: 10px">
      <div
        style="
          display: flex;
          width: 1000px;
          gap: 20px;
          margin-top: -100px;
        "
      >
        <div style="border: 1px solid white">
          <div class="sustainability-img"></div>

          <div class="sustainability-text">
            <div
              style="
                text-transform: uppercase;
                font-weight: bold;
                padding: 20px 20px 0px 20px;
              "
            >
              Made by Andres
            </div>
            <div
              style="color: rgb(39, 92, 178); font-weight: bold; padding: 20px"
            >
              Eaton operations to be carbon neutral by 2030
            </div>
          </div>
        </div>

        <div style="border: 1px solid white">
          <div class="sustainability-img"></div>
          <div class="sustainability-text">
            <div
              style="
                text-transform: uppercase;
                font-weight: bold;
                padding: 20px 20px 0px 20px;
              "
            >
              Made by Andres
            </div>
            <div
              style="color: rgb(39, 92, 178); font-weight: bold; padding: 20px"
            >
              Eaton operations to be carbon neutral by 2030
            </div>
          </div>
        </div>
        <div style="border: 1px solid white">
          <div class="sustainability-img"></div>
          <div class="sustainability-text">
            <div
              style="
                text-transform: uppercase;
                font-weight: bold;
                padding: 20px 20px 0px 20px;
              "
            >
              Made by Andres
            </div>
            <div
              style="
                color: rgb(39, 92, 178);
                font-weight: bold;
                padding: 20px 20px 20px 20px;
              "
            >
              Eaton operations to be carbon neutral by 2030
            </div>
          </div>
        </div>
      </div>
    </div>

    <div style="display: flex; justify-content: center">
      <div style="display: flex; gap: 30px; width: 1000px; padding: 100px 0px">
        <div style="width: 50%; font-size: 2rem">
          We're dedicated to improving people's lives and the environment with
          power management technologies that are more reliable, efficient, safe
          and sustainable.
        </div>
        <div style="width: 50%">
          Every day, all around the world, people depend on technology,
          transportation, energy and infrastructure to live and work. With rapid
          growth in electrification, an energy transition driven by climate
          change and explosive growth in connectivity, we're well positioned to
          solve the world's toughest electrical and mechanical power management
          challenges. Because that's what really matters. And we're here to make
          sure it works.
        </div>
      </div>
    </div>
    <div style="display: flex; justify-content: center">
      <div
        style="
          /* padding: 50px 0px; */
          display: flex;
          width: 800px;
          justify-content: space-between;
          padding-bottom: 100px;
        "
      >
        <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
          <img
            src="https://www.eaton.com/content/dam/eaton/resources/icons/proofpoints/analytics_teal_icon.png"
          />
          <div style="color: rgb(72, 159, 152); font-size: 3rem; font-weight: bold;">ETN</div>
          <div>NYSE ticker</div>
        </div>
        <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
          <img
            src="https://www.eaton.com/content/dam/eaton/resources/icons/proofpoints/us-currency-symbol.png"
          />
          <div style="color: rgb(72, 159, 152); font-size: 3rem; font-weight: bold;">20.8B</div>
          <div>2022 sales (USD)</div>
        </div>
        <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
          <img
            src="https://www.eaton.com/content/dam/eaton/resources/icons/proofpoints/globe_teal_icon.png"
          />
          <div style="color: rgb(72, 159, 152); font-size: 3rem; font-weight: bold;">>92K</div>
          <div>Employees around the world</div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.top-nav {
  display: flex;
  justify-content: center;
  background-color: rgb(39, 92, 178);
  color: white;
  padding: 10px;
}

.top-nav-inner {
  display: flex;
  width: 1000px;
  justify-content: space-between;
}

.flex-with-gap-10 {
  display: flex;
  gap: 10px;
}

.flex-with-gap-20 {
  display: flex;
  gap: 20px;
}

.main-img {
  height: 500px;
  background-image: url(https://dynamicmedia.eaton.com/is/image/eaton/what-matters-city-banner:landing-hero-desktop);
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 10px;
  background-color: rgba(0, 0, 0, 0.5);
  background-blend-mode: multiply;
}

.see-how-btn {
  border: 2px solid white;
  padding: 20px 40px;
  background-color: transparent;
  color: white;
  font-weight: bold;
  text-transform: uppercase;
}

.see-how-btn:hover {
  background-color: white;
  color: rgb(39, 92, 178);


}

.sustainability-img {
  background-image: url(https://www.eaton.com/content/dam/phoenixtec/home-page/landing-hero/how-we-make-what-matters-work-also-matters.jpg.transform/default-desktop/image.jpg);
  background-size: cover;
  height: 240px;
  border-top: 1px solid white;
  border-right: 1px solid white;
  border-left: 1px solid white;
}

.sustainability-text {
  border-bottom: 1px solid lightgray;
  border-right: 1px solid lightgray;
  border-left: 1px solid lightgray;
}
</style>
