<template>
  <div class="myskills">
    <div class="container">
      \
      <div class="dispaly-flex">
        <div class="skills padding-r-25">
          <h2>My skills</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum,
            quisquam! Maxime alias doloribus commodi et dolorum voluptatibus
            ullam. Necessitatibus nihil culpa maxime qui consequatur laboriosam
            .
          </p>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem odit
            hic ut atque incidunt ullam .
          </p>
          <button class="skills-btn" type="button>">CONTACT ME</button>
        </div>
        <div class="skills-progress padding-l-25">
          <h2>photoshop</h2>
          <div class="bar"><div class="photoshop-progress">90%</div></div>
          <h2>illustrator</h2>
          <div class="bar"><div class="illustrator-progress">80%</div></div>
          <h2>html/css</h2>
          <div class="bar"><div class="html-css-progress">90%</div></div>
          <h2>php/mysql</h2>
          <div class="bar"><div class="php-mysql-progress">70%</div></div>
        </div>
      </div>
    </div>
  </div>
  <!--Start resume -->
  <div class="resume">
    <div class="container">
      <h2 class="text-center">resume</h2>
      <p class="text-center">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
        aspernatur impedit deserunt doloremque non esse nisi ad. Ipsam quam
        veniam nulla eligendi eveniet, dolor ipsum fuga praesentium incidunt
        nobis voluptate.
      </p>
      <button class="dow-resume " type="button">DOWNLOAD RESUME</button>
    </div>
  </div>
  <!--End resume -->
  <!--dak lmotalat li nazl-->
  <div class="dispaly-flex">
    <div style="flex: 0 0 48%;"></div>
    <span class="motalat"></span>
    <div style="flex: 0 0 48%;"></div>
  </div>
  <!-- End dak lmotalat li nazl-->

  <div class="education">
    <div class="container">
      <div class="myeducation padding-r-25">
        <h2>my education</h2>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum autem
          repellendus architecto sint hic non cumque facere tempora nostrum
          culpa aperiam amet eligendi ratione.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Est amet
          praesentium eaque dignissimos.
        </p>
      </div>
      <div class="diplom padding-l-25">
        <h3>Graphic design diploma</h3>
        <p>Reeves College / June 2008 - May 2010</p>
        <p><span class="dipl-btn">4.0 GPA</span></p>
        <hr />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint fugiat
          facilis magnam nobis, consequuntur voluptas cumque fugiat facilis
          magnam nobis, consequuntur voluptas.
        </p>
        <br />
        <h3>cit doploma</h3>
        <p>Lethbridge College / June 2006 - May 2008</p>
        <p><span class="dipl-btn">4.0 GPA</span></p>
        <hr />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint fugiat
          facilis magnam nobis, consequuntur voluptas cumque fugiat facilis
          magnam nobis, consequuntur voluptas.
        </p>
      </div>
    </div>
    <div class="clearfix"></div>
  </div>

  <div class="education">
    <div class="container">
      <hr />
      <div class="myeducation padding-r-25">
        <h2>Work Ecperience</h2>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum autem
          repellendus architecto sint hic non cumque facere tempora nostrum
          culpa aperiam amet eligendi ratione.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Est amet
          praesentium eaque dignissimos.
        </p>
      </div>
      <div class="diplom padding-l-25">
        <h3>LEad web designer</h3>
        <p>ABC Company Saskatoon / June 2011 - Present</p>
        <p><span class="dipl-btn">3 years</span></p>
        <hr />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint fugiat
          facilis magnam nobis, consequuntur voluptas cumque fugiat facilis
          magnam nobis, consequuntur voluptas.
        </p>
        <br />
        <h3>LEad web designer</h3>
        <p>ABC Company Saskatoon / June 2011 - Present</p>
        <p><span class="dipl-btn">3 years</span></p>
        <hr />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint fugiat
          facilis magnam nobis, consequuntur voluptas cumque fugiat facilis
          magnam nobis, consequuntur voluptas.
        </p>
        <br />
        <h3>LEad web designer</h3>
        <p>ABC Company Saskatoon / June 2011 - Present</p>
        <p><span class="dipl-btn">3 years</span></p>
        <hr />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint fugiat
          facilis magnam nobis, consequuntur voluptas cumque fugiat facilis
          magnam nobis, consequuntur voluptas.
        </p>
        <br />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MySKills",
};
</script>
<style scoped>
.myskills {
  padding-top: 30px;
  padding-bottom: 50px;
}
.myskills .skills,
.myskills .skills-progress {
  flex: 0 0 50%;
}

.skills-btn,
.dow-resume {
  margin: 30px 0;
  color: #2ecc71;
  border: 2px solid #2ecc71;
  padding: 8px 15px;
  text-align: center;
  font-family: "Arial Narrow Bold", sans-serif;
  font-weight: 600;
}
.skills-btn {
  background-color: #fff;
}
.dow-resume {
  margin-left: 40%;
}

.bar {
  height: 25px;
  background-color: #f2f2f2;
}
.photoshop-progress,
.illustrator-progress,
.html-css-progress,
.php-mysql-progress {
  background-color: #2ecc71;
  text-align: right;
  color: white;
  height: 100%;
  padding-right: 8px;
  padding-top: 3px;
}
.photoshop-progress {
  width: 90%;
}
.illustrator-progress {
  width: 80%;
}
.html-css-progres {
  width: 90%;
}
.php-mysql-progress {
  width: 70%;
}

/* End My Skills */
/* Start Resume*/
.resume {
  padding: 40px 0;
  background-color: #f2f2f2;
}

.motalat {
  flex: 0 0 4%;
}
.motalat::before {
  border: 18px solid #f2f2f2;
  box-sizing: border-box;
  content: "";
  display: inline-block;
  position: relative;
  top: -25px;
  transition: all 0.3s ease;
  transform: rotate(45deg);
  overflow: hidden;
  width: 25px;
}

/* End Resume*/
/* Start Education And Diploma */
.education {
  padding: 30px 0;
}
.myeducation,
.diplom {
  float: left;
  width: 50%;
}
.myeducation {
}
.diplom {
  margin: 30px 0;
}
.dipl-btn {
  background-color: #2ecc71;
  color: #fff;
  padding: 5px 10px;
  margin-bottom: 10px;
}
.education hr {
  color: #82828247;
  margin: 30px 0;
}
</style>
