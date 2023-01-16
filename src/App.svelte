<script>
</script>

<main>
  <div>
    <h1 class="heading">Image to pallate</h1>
    <span class="box" />
    <p class="para">
      Lorem ipsum dolor sit amet consectetur. Lorem ipsum dolor sit amet
      consectetur.
    </p>
  </div>
  <div class="container">
    <span class="image-box">
      <span class="image-box1">
        <div class="col">
          <button>Upload Image</button>
          
          <p>or drop a file,</p>
          <p>paste image or <span class="underline">URL</span></p>
        </div>
      </span>
    </span>
    <span class="pallate">
      <span class="empty-box" />
    </span>
    <div class="hex">
      <span class="hexcolor1">#469597</span>
      <span class="hexcolor2">#5BA199</span>
      <span class="hexcolor3">#BBC6C8</span>
      <span class="hexcolor4">#E5E3E4</span>
      <span class="hexcolor5">#FFC4A6</span>
    </div>
    <div class="color-pallates">
      <span class="color1" />
      <span class="color2" />
      <span class="color3" />
      <span class="color4" />
      <span class="color5" />
    </div>
  </div>
</main>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');
  /*Image to palatte*/
  .heading {
    position: absolute;
    width: 252px;
    height: 39px;
    left: 112px;
    top: 56px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 39px;
  }
  .box {
    position: absolute;
    width: 10px;
    height: 30px;
    left: 370px;
    top: 80px;

    background: #ff0066;
  }
  .para {
    position: absolute;
    width: 588px;
    height: 19px;
    left: 112px;
    top: 110px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    letter-spacing: -0.32px;

    color: #000000;
  }
  .container {
    background-image: url("./assets/image.png");
    position: absolute;
    width: 1440px;
    height: 742px;
    left: 50px;
    top: 182px;
  }
  .image-box {
    position: absolute;
    width: 448px;
    height: 500px;
    left: 120px;
    top: 105px;

    background: #eee9e9;
    border-radius: 20px;
  }
  .image-box1 {
    position: absolute;
    width: 397px;
    height: 403px;
    left: 29px;
    top: 51px;

    background: #fff;
    border-radius: 20px;
  }
  .col {
    position: absolute;
    font-weight: bold;
    color: #6e7375;
    text-align: center;
    left: 120px;
    top: 156px;
  }
  .underline {
    text-decoration: underline;
  }
  button {
    /* _Button base */

    box-sizing: border-box;

    /* Auto layout */
    color: #fff;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 10px 18px;
    gap: 8px;

    width: 170px;
    height: 44px;

    background: #0066ff;
    border: 1px solid #0066ff;
    /* Shadow/xs */

    box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);
    border-radius: 8px;

    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 1;
  }
  .pallate {
    position: absolute;
    width: 448px;
    height: 500px;
    left: 808px;
    top: 110px;
    background: #ffffff;
    border-radius: 20px;
  }
  .empty-box {
    position: absolute;
    width: 384px;
    height: 350px;
    left: 35px;
    top: 20px;
    opacity: 10%;

    background: #fd0000;
    border-radius: 20px;
  }
  .color-pallates {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 10px;

    position: relative;
    width: 584px;
    height: 124px;
  }

  /* color-pallate */
  .color1 {
    position: absolute;
    width: 89.6px;
    height: 89.6px;
    left: 808px;
    top: 520px;

    background: #469597;
    border-radius: 0px 0px 0px 20px;
  }
  .color2 {
    position: absolute;
    width: 89.6px;
    height: 89.6px;
    left: 897.6px;
    top: 520px;

    background: #5ba199;
  }
  .color3 {
    position: absolute;
    width: 89.6px;
    height: 89.6px;
    left: 987.2px;
    top: 520px;

    background: #bbc6c8;
  }
  .color4 {
    position: absolute;
    width: 89.6px;
    height: 89.6px;
    left: 1076.8px;
    top: 520px;

    background: #e5e3e4;
  }
  .color5 {
    position: absolute;
    width: 89.6px;
    height: 89.6px;
    left: 1166.4px;
    top: 520px;

    background: #ffc4a6;
    border-radius: 0px 0px 20px 0px;
  }
  /* hex-color */
  .hexcolor1 {
    position: absolute;
    width: 70px;
    height: 19px;
    left: 1166px;
    top: 500px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    letter-spacing: -0.32px;

    color: #000000;
  }
  .hexcolor2 {
    position: absolute;
    width: 68px;
    height: 19px;
    left: 1077px;
    top: 500px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    letter-spacing: -0.32px;

    color: #000000;
  }
  .hexcolor3 {
    position: absolute;
    width: 73px;
    height: 19px;
    left: 987px;
    top: 500px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    letter-spacing: -0.32px;

    color: #000000;
  }
  .hexcolor4 {
    position: absolute;
    width: 66px;
    height: 19px;
    left: 898px;
    top: 500px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    letter-spacing: -0.32px;

    color: #000000;
  }
  .hexcolor5 {
    position: absolute;
    width: 67px;
    height: 19px;
    left: 808px;
    top: 500px;

    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    letter-spacing: -0.32px;

    color: #000000;
  }
</style>
