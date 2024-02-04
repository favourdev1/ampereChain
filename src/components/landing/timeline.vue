<template>
  <div
    class="container relative overflow-hidden"
         
  >
    <div class="journey-timeline-section">
      <div class="w-layout-grid block md:flex journey-grid">
        <div
          id="w-node-_59590ed9-1c3e-cf25-f3e0-c9b56d1d308d-fb9174d9"
          class="journey-content-lef basis-2/4"
        >
          <div
            id="w-node-_59590ed9-1c3e-cf25-f3e0-c9b56d1d308e-fb9174d9"
            class="about-sticky-content"
          >
            <div
              style="
                opacity: 1;
                transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1)
                  rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
                transform-style: preserve-3d;
              "
              class="fade-in-move-on-scroll block"
            >
              <div class="feature-title-holder">
                <h2 class="no-margin-padding">
                  From imagining to building the <span>dream.</span
                  ><span class="text-gradient"></span>
                </h2>
              </div>
            </div>
            <div
              style="
                opacity: 1;
                transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1)
                  rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
                transform-style: preserve-3d;
              "
              class="fade-in-move-on-scroll"
            >
              <div class="feature-paragraph-holder">
                <p>
                  Timeline for launching project, ecosystem, marketing and
                  exchange listing.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div
          style="
            opacity: 1;
            transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg)
              rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
            transform-style: preserve-3d;
          "
          class="timeline-holder grow "
          ref="containerMain"
        >
          <div class="about-timeline-step">
            <div class="timeline-icon-holder">
              <img
                src="https://assets-global.website-files.com/6596e1df914ba595fb917495/6596e1df914ba595fb91755e_About%20Story%20Icon%204.svg"
                loading="lazy"
                alt="Idea icon"
                class="timeline-icon"
              />
            </div>
            <div class="timeline-content-holder">
              <div class="timeline-time">Dec 2023-Mar 2024</div>
              <div class="timeline-title">Phase - 1</div>
              <p>
                - Website Launch<br />- Testnet Launch<br />- Pre &amp; Post
                Marketing<br />- Community Building<br />- Pinksale
                Fairlaunch<br />- CMC &amp; CG Listing<br />- PanCakeSwap
                Listing<br />- Mainnet Launch<br />- Bridge<br />- Validator
                Portal
              </p>
            </div>
          </div>
          <div class="about-timeline-step">
            <div class="timeline-icon-holder">
              <img
                src="https://assets-global.website-files.com/6596e1df914ba595fb917495/6596e1df914ba595fb917560_About%20Story%20Icon%203.svg"
                loading="lazy"
                alt="Research icon"
                class="timeline-icon"
              />
            </div>
            <div class="timeline-content-holder">
              <div class="timeline-time">Apr 2024-Jul 2024</div>
              <div class="timeline-title">Phase - 2</div>
              <p>
                - CEX Listing<br />- Airdrop<br />- Further Marketing<br />-
                AmpereSwap Hybrid Dex<br />- Staking<br />- Partnership<br />-
                Web Wallet
              </p>
            </div>
          </div>
          <div class="about-timeline-step">
            <div class="timeline-icon-holder">
              <img
                src="https://assets-global.website-files.com/6596e1df914ba595fb917495/6596e1df914ba595fb91755f_About%20Story%20Icon%202.svg"
                loading="lazy"
                alt="Layers icon"
                class="timeline-icon"
              />
            </div>
            <div class="timeline-content-holder">
              <div class="timeline-time">Aug 2024-Dec 2024</div>
              <div class="timeline-title">Phase - 3</div>
              <p>
                - AmpereChain DApp Library<br />- Partnership with Existing
                DApps<br />- Partnership with Web3 Communities<br />- Creating
                liquidity on SushiSwap, UniSwap &amp; 1inches<br />- Further CEX
                Listing
              </p>
            </div>
          </div>
          <div
            class="timeline-progress-line"
            ref="scrollingLine"
            style="will-change: width, height; height: 21.5828%"
          ></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TimeLine",
};
</script>

<style scoped>
.container {
  z-index: 1;
  max-width: 1350px;
  flex-direction: column;
  justify-content: flex-end;
  align-items: center;
  margin-left: auto;
  margin-right: auto;
  padding: 2em;
  display: flex;
  position: relative;
}
.journey-timeline-section {
  padding-top: 140px;
  padding-bottom: 140px;
}
.journey-grid {
  grid-column-gap: 30px;
  grid-row-gap: 30px;
  grid-template-rows: auto;
  grid-template-columns: 0.75fr 0.75fr;
}
.w-layout-grid {
  /* grid-row-gap: 16px;
  grid-column-gap: 16px;
  grid-template-rows: auto auto;
  grid-template-columns: 1fr 1fr;
  grid-auto-columns: 1fr;
  display: grid; */
}

#w-node-e47c069d-51d7-284d-78ea-1a9fefaeb67b-fb9174d9,
#w-node-a3b02ea5-fe06-092d-0f2b-56a827894d53-fb9174d9,
#w-node-c36d6e98-b327-13e2-ecdc-bf65e9f876f7-fb9174d9,
#w-node-fa2d9d29-9e4b-494d-e1f7-8981ad8ed31a-fb9174d9,
#w-node-_59590ed9-1c3e-cf25-f3e0-c9b56d1d308d-fb9174d9,
#w-node-_59590ed9-1c3e-cf25-f3e0-c9b56d1d308e-fb9174d9,
#w-node-_56fd49a8-4265-ce65-7c80-0258e12f2f6c-e12f2f69,
#w-node-_56fd49a8-4265-ce65-7c80-0258e12f2f79-e12f2f69,
#w-node-_56fd49a8-4265-ce65-7c80-0258e12f2f89-e12f2f69,
#w-node-_01072e2e-39fe-66d5-3029-92556f24cf47-fb9174e0,
#w-node-_92276520-dc21-615d-5a0f-c2e666ed2da7-fb9174e0,
#w-node-_1cafd2c7-25d7-e4ce-e188-1eae55ce471a-fb9174e0,
#w-node-d645ba90-749e-1ffd-f7e0-5c365502922b-fb9174e0,
#w-node-_64c98c85-efd4-6534-988f-09c5c07895fc-fb9174e0,
#w-node-_1576a68e-76dc-52c2-c869-8ff5e12b15fa-fb9174e0 {
  grid-area: span 1 / span 1 / span 1 / span 1;
}

.about-sticky-content {
  position: -webkit-sticky;
  position: sticky;
  top: 20%;
}

.feature-title-holder {
  max-width: 950px;
  padding-top: 20px;
  padding-bottom: 20px;
}

.no-margin-padding {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
}
h2 {
  color: white;
  margin-top: 20px;
  margin-bottom: 10px;
  font-size: 48px;
  font-weight: 500;
  line-height: 1.3;
}

.text-gradient {
  -webkit-text-fill-color: transparent;
  background-image: linear-gradient(
    276deg,
    rgba(255, 255, 255, 0.44),
    #fff 57%,
    rgba(255, 255, 255, 0.22)
  );
  -webkit-background-clip: text;
  background-clip: text;
  font-weight: 600;
}

.fade-in-move-on-scroll {
  justify-content: center;
  align-items: center;
}

.feature-paragraph-holder {
  max-width: 550px;
  margin-bottom: 20px;
}

p {
  color: #ffffff9e;
  margin-top: 20px;
  margin-bottom: 10px;
  font-size: 16px;
  font-weight: 400;
}

.timeline-holder {
  flex-direction: column;
  margin-top: 20px;
  display: flex;
  position: relative;
  overflow: hidden;
}

.about-timeline-step {
  z-index: 1;
  grid-column-gap: 25px;
  grid-row-gap: 25px;
  grid-template-rows: auto auto;
  grid-template-columns: 0.25fr 1fr;
  grid-auto-columns: 1fr;
  justify-content: flex-start;
  align-items: flex-start;
  padding-bottom: 60px;
  display: flex;
  position: relative;
}

.timeline-icon-holder {
  width: 72px;
  height: 72px;
  min-height: 72px;
  min-width: 72px;
  border: 1px solid #222;
  background-color: #17181b;
  border-radius: 100px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.timeline-icon {
  width: 30px;
  max-width: 30px;
}

.timeline-content-holder {
  grid-column-gap: 15px;
  grid-row-gap: 15px;
  flex-direction: column;
  display: flex;
}

.timeline-time {
  color: white;
  font-size: 16px;
}

.timeline-title {
  color: white;
  font-size: 24px;
  font-weight: 500;
  line-height: 1.3;
}

.timeline-progress-line {
  width: 1px;
  height: 75%;
  border-left: 1px solid #222;
  position: absolute;
  top: 0%;
  bottom: 0%;
  left: 2.5em;
  right: auto;
}
</style>
