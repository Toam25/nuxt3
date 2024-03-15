<template>
    <div>
      <section id="about" >
        <div class="container-about">
            <div class="container-image">

            </div>
            <h1 class="name last-name">Rakotoarimanana</h1>
            <h2 class="name first-name">Rado Nirina</h2>
            <div>
                <p>A passionate  <span class="post">Full-stack PHP Developer</span>  at <a href = "https://www.softibox.com/">softibox</a> since 2023</p>
            </div>
            <hr>
            <div class="social-network">
                <a>linkedIn</a>
                <a>Github</a>
                <a>facebook</a>
            </div>
        </div>
      </section>
      <section>
          <div class="carreer">
              <div class="divider-carreer"><span class="date-carreer">2023 - now</span> <span class="line"></span></div>
              <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro tempora aliquam numquam odio, officia excepturi itaque recusandae rem, nisi dolore, soluta animi optio harum amet labore tempore eius. Aspernatur, accusamus?
              </p>
          </div>
      </section>
    </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style>
  .line {
      display: block;
      width: 100%;
      height: 1px;
      opacity: .3;
      background-color: #07013f;

  }
  .date-carreer{
    white-space: nowrap;
    margin: 0 10px 0 0 ;
  }
  .divider-carreer {
  display: flex;
  justify-content: center;
  align-items: center;
}
  .social-network > a{
  color: white;
  background-color: black;
  padding: 5px 10px;
  border-radius: 11px;
  margin: 0 2px;
  }
  .social-network {
  display: flex;
  justify-content: center;
  align-items: center;
}
.name{
  margin: 2px;
  background: -webkit-linear-gradient(0deg,#FF1A7A, #FFB800);
  padding: 5px 33px;
}
  .post{
    font-size: 50px;
  background: -webkit-linear-gradient(0deg,#FF1A7A, #FFB800);
    background-clip: border-box;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 900;
  }
   body{
    background-color: #fff4f4;
    margin : 0;
    padding : 0;
    font-family: "Inter", "-apple-system", "BlinkMacSystemFont", "Segoe UI", "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
   }
   .container-image{
    height: 100px;
    width: 101px;
    border: 1px solid;
    border-radius: 10px;
    margin-bottom: 10px;
   }
   section{
    height : 100vh;
   }
   .container-about {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin: 50px;
  }
  .container-about > h1,  .container-about > h2 {
      margin : 2px
  }
  #about {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
