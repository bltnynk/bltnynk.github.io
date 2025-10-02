+++
widget = "blank"
headless = true
active = true
weight = 10

title = ""
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

+++

<style>

/* 🔹 Global fix: reduce spacing between all sections */

::-moz-selection {
   background: #FDEEC9;
   /* color: #fff; */
}
::selection {
   background: #FDEEC9;
   /* color: #fff; */
}

body{
  font-size: 14pt;
  margin-left: 12%;
  margin-right: 12%;
}

img {
    float: left;
    width: 288px;
    margin-right: 40px;
    margin-top: 35px;
    margin-bottom: 10px;
}

.br {
  line-height: 70%;
}

#intro {
  font-size: 14pt;
  margin-left: 270px;
  margin-right: 5%;
}

.ref {
  color: #546447; /*  #AB6F55*/
}

.section {
  font-size: 25pt;
  font-weight: 500;
  margin-bottom: 7px;
}

.divider {
   border: 0;
   border-top: 1.5px solid #DAD8C9;
   background: none;
   margin-top: 0;
}

a {
      -webkit-transition: color 0s; /* For Safari 3.0 to 6.0 */
      transition: color 0s; /* For modern browsers */
  }
a:hover {
  text-decoration: none;
  color: #4f8b04; /* #EC7D3C #856256 */
}


/*1410 - 1100*/
@media only screen and (max-width: 1410px) {
  img {
    margin-bottom: 150px;
  }
}

@media only screen and (max-width: 1100px) {
  img {
    margin-bottom: 10px;
  }
}

@media only screen and (max-width: 1044px) {
  #intro {
    margin-left: 0px;
  }
}

@media only screen and (max-width: 768px) {
 img {
   float: middle;
   width: 100%;
   /* padding-right: 10%; */
   /* padding-left: 10%;  */
   padding-bottom: 10px;
 } 
 body {
  font-size: 11pt;
  /* text-align:center; */
  margin-left: 0%;
  margin-right: 0%;
 }
 #intro {
  font-size: 11pt;
  margin-left: 0px;
  margin-right: 0px;
 }
 .section {
  font-size: 18pt;
 }
}

.profile-photo {
  float: left;
  width: 288px;
  margin-right: 40px;
  margin-bottom: 10px;
  text-align: center; /* centers icons under the image */
}

.profile-photo img {
  width: 100%;
  display: block;
}

.profile-icons {
  margin-top: 10px;
}

.profile-icons a {
  font-size: 22px;
  margin: 0 10px;
  color: inherit;
  text-decoration: none;
}

.profile-icons a:hover {
  color: #4f8b04;
}


</style>

<div class="profile-photo">
  <img src="uploads/long-narrow.png" alt="Thanh-Long V. Le">

  <div class="profile-icons">
    <a href="mailto:thanhlongtdk2000@gmail.com" title="Email">
      {{< icon name="envelope" pack="fas" >}}
    </a>
    <a href="https://www.linkedin.com/in/bltnynk/" title="LinkedIn">
      {{< icon name="linkedin-in" pack="fab" >}}
    </a>
    <a href="https://scholar.google.com/citations?user=XjoR4p4AAAAJ&hl=en" title="Google Scholar">
      {{< icon name="graduation-cap" pack="fas" >}}
    </a>
    <a href="uploads/ThanhLong_251001.pdf" title="CV" target="_blank">
      {{< icon name="file" pack="fas" >}}
    </a>
  </div>
</div>

## **Thanh-Long V. Le**

<div id='intro'>
Hey there! Glad to have you here. Call me Long for short 😆.
<div class='br'><br></div>

I am a first-year M.S. student at <a class='ref' href="https://gsai.kaist.ac.kr/">KAIST AI</a>, advised by <a class='ref' href="https://mli.kaist.ac.kr/people/">Prof. Eunho Yang</a> and working closely with <a class='ref' href="https://laiviet.github.io/">Dr. Viet Lai</a> (Adobe Research). Previously, I received my B.S. degree in Computer Science at <a class='ref' href="https://www.kaist.ac.kr/en/">KAIST</a>, advised by <a class='ref' href="https://sites.google.com/site/wewantsj/">Prof. Sung-Ju Lee</a>.

My research centers on <b>large language models (LLMs)</b>, with a focus on enhancing their reasoning capabilities through <b>reinforcement learning</b> and other <b>post-training</b> techniques. Recently, I have also begun exploring generative modeling, particularly <b>diffusion models for video generation</b> and <b>diffusion-based LLMs</b>.

Outside of research, I’m deeply passionate about cinema and photography. If you ever find yourself in Seoul, feel free to shoot me an email—we could grab a coffee and yap about research and movies, or head out for some spontaneous photo-taking!

<div class="contact-clear"></div>
</div>
<!-- [{{< icon name="file" pack="fas" >}} CV](uploads/CV_YewonKim.pdf) -->
