<template>
  <div
    style="
      width: 100%;
      min-height: 100vh;
      padding: 25px;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #f5f5f5;
    "
  >

    <div
      style="
        width: 100%;
        max-width: 1400px;
        display: grid;
        grid-template-columns: 1.35fr repeat(4, 1fr);
        grid-template-rows: repeat(3, 230px);
        gap: 6px;
      "
    >

      <q-card class="info-card"
        style="
          grid-row: 1 / 4;
          overflow: hidden;
          position: relative;
          width: 600px;
        "
      >

        <img
          :src="image"
          class="cover-image"
          style="
            width: 90%;
            height: 85%;
            object-fit: cover;
            position: absolute;
            top: 20px;
            left: 5%;
          "
        />

        <div
          style="
            position: absolute;
            left: 45px;
            top: 110px;
            color: white;
            font-size: 25px;
            letter-spacing: 5px;
            transform: rotate(-90deg);
            transform-origin: left bottom;
          "
        >
        </div>

        <div
          style="
            position: absolute;
            left: 25px;
            right: 25px;
            bottom: 12px;
            display: flex;
            justify-content: space-between;
            font-size: 9px;
          "
        >
          <div>
            <small>Design by:</small>
            <div>Creative Studio</div>
          </div>

          <div>2023</div>
        </div>

      </q-card>


      <q-card class="info-card">

        <div>
          <h3>INDEX</h3>
          <q-separator />

          <p>ABOUT THE STUDIO</p>
          <q-separator />
          <p>TEAM</p>
          <q-separator />
          <p>MISSION</p>
          <q-separator />
          <p>COLLECTION</p>
        </div>

        <img :src="image"
        class="cover-image"
        style="
        margin-top: 80px;
        height: 60%;">

      </q-card>


      <q-card class="info-card">

        <div>
          <h3>ABOUT THE STUDIO</h3>
          <p>
            About our studio, creative vision
            and approach to modern fashion.
          </p>

          <p>
            We create unique visual experiences
            through thoughtful design.
          </p>
        </div>

        <div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
          <img :src="image"
          class="cover-image"
          style="
          margin-top: 40px;
          height: 60%;">
        </div>


      </q-card>


      <q-card class="info-card">

        <div>
          <h3>ABOUT THE STUDIO</h3>
          <p>
            About our studio, creative vision
            and approach to modern fashion.
          </p>

          <p>
            We create unique visual experiences
            through thoughtful design.
          </p>

          <p>
            We create unique visual experiences
            through thoughtful design.
          </p>
          <p>
            We create unique visual experiences
            through thoughtful design.
          </p>
        </div>

        <div class="q-pa-md">
        <div class="q-gutter-md column">

        <q-img
          :src="image"
          class="cover-image"
          style="width: 100%; height: 55px;"
          fit="cover"
        />

        <q-img
          :src="image"
          class="cover-image"
          style="width: 100%; height: 55px;"
          fit="cover"
        />

        <q-img
          :src="image"
          class="cover-image"
          style="width: 100%; height: 55px;"
          fit="cover"
        />

         </div>
      </div>

      </q-card>


      <q-card class="info-card">

        <div>
          <h3>MISSION</h3>
          <p>
            About our studio, creative vision
            and approach to modern fashion.
          </p>

          <p>
            We create unique visual experiences
            through thoughtful design.
          </p>
        </div>

        <div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
          <img :src="image"
          class="cover-image"
          style="
          margin-top: 40px;
          height: 60%;">
        </div>


      </q-card>


      <q-card class="info-card"
        style="
          display: flex;
          flex-direction: column;
        "
      >

        <h3
          style="
            margin: 0 0 15px;
            font-size: 14px;
            font-weight: 500;
          "
        >
          MODERN FASHION
        </h3>

        <q-img
          :src="image"
          class="cover-images"
          style="
            width: 70%;
            height: 100px;
          "
          fit="cover"
        />

        <div
          style="
            display: flex;
            justify-content: space-between;
            gap: 30px;
            margin-top: 15px;
          "
        >

          <div style="width: 70%;">
            <p
              style="
                margin: 0;
                font-size: 5px;
                line-height: 1.5;
                color: #555;
              "
            >
              About our studio, creative vision
              and approach to modern fashion.
            </p>
          </div>

          <div style="width: 30%;">
            <p
              style="
                margin: 0;
                font-size: 5px;
                line-height: 1.5;
                color: #555;
              "
            >
              Through thoughtful design.
            </p>
          </div>

        </div>

      </q-card>

      <q-card class="info-card"
        style="
          display: block;
          width: 100%;
          box-sizing: border-box;
        "
      >

        <div>
          <h3>MODERN FASHION SHOW</h3>

          <p style=" width: 70%; font-size: 5px;">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui nam illum saepe ipsum asperiores. Pariatur accusamus eius sunt facere vitae modi minus iure a accusantium! Laborum iusto veniam odio quos?
          </p>
        </div>

        <div style="width: 100%;">

          <q-img
            :src="image"
            style="
              width: 70%;
              height: 70px;
            "
            fit="cover"
          />

          <div
            style="
              display: grid;
              grid-template-columns: repeat(2, 1fr);
              gap: 6px;
              margin-top: 6px;
              width: 100%;
            "
          >

            <q-img
              :src="image"
              style="
                width: 100%;
                height: 80px;
              "
              fit="cover"
            />

            <q-img
              :src="image"
              style="
                width: 100%;
                height: 80px;
              "
              fit="cover"
            />

          </div>

        </div>

      </q-card>

      <q-card class="info-card">

        <div>
          <h3>NEW COLLECTION</h3>
          <p>
            About our studio, creative vision
            and approach to modern fashion.
          </p>

          <p>
            We create unique visual experiences
            through thoughtful design.
          </p>
        </div>

        <div>

          <img :src="image"
          class="cover-image"
          style="
          margin-top: 80px;
          height: 60%;">
        </div>


      </q-card>


      <q-card class="info-card">

        <div>

          <p
          style="padding-top: 30px;">
            New ideas, new styles and
            contemporary fashion.
          </p>

          <img :src="image"
          class="cover-image"
          style="
          margin-top: 70px;
          height: 30%;">
        </div>

        <div>
          <img :src="image"
        class="cover-image"
        style="
        height: 45%;">

        <p
          style="padding-top: 30px;">
            New ideas, new styles and
            contemporary fashion.
        </p>
        </div>

      </q-card>


      <q-card class="info-card">

        <div>

          <h3>INTERIORS</h3>

          <img :src="image"
          class="cover-image"
          style="
          margin-top: 20px;
          height: 60%;">

          <p>
            New ideas, new styles and
            contemporary fashion.
        </p>
        </div>

        <div>
          <img :src="image"
        class="cover-image"
        style="
        height: 45%;">

        <p
          style="padding-top: 30px;">
            New ideas, new styles and
            contemporary fashion.
        </p>
        </div>

      </q-card>


      <q-card class="info-card"
        style="
          display: block;
          width: 100%;
          box-sizing: border-box;
        "
      >

        <div style="width: 100%; margin-top: 20px;" >

          <q-img
            :src="image"
            style="
              width: 48%;
              height: 70px;
            "
            fit="cover"
          />

          <div
            style="
              display: grid;
              grid-template-columns: repeat(2, 1fr);
              gap: 6px;
              margin-top: 6px;
              width: 100%;
            "
          >

            <q-img
              :src="image"
              style="
                width: 100%;
                height: 80px;
              "
              fit="cover"
            />

            <q-img
              :src="image"
              style="
                width: 100%;
                height: 80px;
                margin-top: -50px;
              "
              fit="cover"
            />

          </div>

        </div>

      </q-card>


      <q-card class="info-card">

        <div>

          <h3>BEST COLLECTION</h3>
          <p
          style="padding-top: 5px;">
            New ideas, new styles and
            contemporary fashion.
          </p>

          <img :src="image"
          class="cover-image"
          style="
          margin-top: 10px;
          height: 40%;">
          <p
          style="padding-top: 5px;">
            New ideas, new styles and
            contemporary fashion.
          </p>
        </div>

        <div>

        <p
          style="padding-top: 60px;">
            New ideas, new styles and
            contemporary fashion.
        </p>
          <img :src="image"
        class="cover-image"
        style="
        height: 45%;">
        </div>

      </q-card>


      <q-card class="info-card"
        style="
          display: block;
          width: 100%;
          box-sizing: border-box;
        "
      >

        <div>
          <p style=" width: 70%; font-size: 5px;">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui nam illum saepe ipsum asperiores. Pariatur accusamus eius sunt facere vitae modi minus iure a accusantium! Laborum iusto veniam odio quos?
          </p>
        </div>

        <div style="width: 100%; margin-top: 20px;" >

          <q-img
            :src="image"
            style="
              width: 48%;
              height: 70px;
            "
            fit="cover"
          />

          <div
            style="
              display: grid;
              grid-template-columns: repeat(2, 1fr);
              gap: 6px;
              margin-top: 6px;
              width: 100%;
            "
          >

            <q-img
              :src="image"
              style="
                width: 100%;
                height: 80px;
              "
              fit="cover"
            />

            <q-img
              :src="image"
              style="
                width: 100%;
                height: 80px;
                margin-top: -50px;
              "
              fit="cover"
            />

          </div>

        </div>

      </q-card>

    </div>

  </div>
</template>

<script setup> import image from 'src/assets/image.png' </script>

<style scoped>

.info-card {
  border-radius: 0;
  padding: 10px;
  display: grid;
  grid-template-columns: 1fr 0.8fr;
  gap: 8px;
  overflow: hidden;
  background: white;
  box-shadow: 0 2px 6px #ccc;
}

.info-card h3 {
  margin: 0 0 7px;
  font-size: 11px;
  font-weight: 500;
  line-height: 1.2;
}

.info-card p {
  margin: 5px 0;
  font-size: 7px;
  line-height: 1.5;
  color: #555;
}

.info-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

</style>
