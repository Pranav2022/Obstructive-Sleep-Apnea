<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Testimonial Slider</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      color: #000;
      font-family: 'Nunito', sans-serif;
    }

    .testimonial {
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding-bottom: 5rem;
    }

    h1 {
      margin: 20px 0;
    }

    .line {
      height: 2px;
      width: 6rem;
      background-color: #e26c4f;
      margin-bottom: calc(3rem + 2vmin);
    }

    .arrow-wrapper {
      position: relative;
      width: 70%;
      border-radius: 2rem;
      box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
      overflow: hidden;
      place-items: center;
    }

    .review-wrap {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding-top: calc(2rem + 1vmin);
      width: 100%;
    }

    #imgBox {
      border-radius: 50%;
      width: calc(6rem + 4vmin);
      height: calc(6rem + 4vmin);
      position: relative;
      box-shadow: 5px -3px #e26c4f;
      background-size: cover;
      margin-bottom: calc(0.7rem + 0.5vmin);
    }

    #name {
      margin-bottom: calc(0.7rem + 0.5vmin);
      font-size: calc(1rem + 0.5vmin);
      letter-spacing: calc(0.1rem + 0.1vmin);
      font-weight: bold;
    }

    #profession {
      font-size: calc(0.8rem + 0.3vmin);
      margin-bottom: calc(0.7rem + 0.5vmin);
      color: #e26c4f;
    }

    #description {
      font-size: calc(0.8rem + 0.3vmin);
      width: 70%;
      max-width: 40rem;
      text-align: center;
      margin-bottom: calc(1.4rem + 1vmin);
      color: rgb(92, 92, 92);
      line-height: 2rem;
    }

    .arrow {
      width: calc(1.4rem + 0.6vmin);
      height: calc(1.4rem + 0.6vmin);
      border: solid #e26c4f;
      border-width: 0 calc(0.5rem + 0.2vmin) calc(0.5rem + 0.2vmin) 0;
      cursor: pointer;
      transition: transform 0.3s;
    }

    .arrow:hover {
      transition: 0.3s;
      transform: scale(1.15);
    }

    .left-arrow-wrap {
      position: absolute;
      top: 50%;
      left: 5%;
      transform: rotate(135deg);
    }

    .right-arrow-wrap {
      position: absolute;
      top: 50%;
      right: 5%;
      transform: rotate(-45deg);
    }

    @media screen and (max-width: 900px) {
      .testimonial {
        width: 100%;
      }
    }
  </style>
</head>

<body>
  <div class="testimonial">
    <h1>Our Reviews</h1>
    <div class="line"></div>
    <!-- arrow wrapper contains the review and the arrows -->
    <div class="arrow-wrapper">
      <!-- review section -->
      <div id="reviewWrap" class="review-wrap">
        <div id="imgBox"></div>
        <div id="name"></div>
        <div id="profession"></div>
        <div id="description"></div>
      </div>
      <!-- left arrow -->
      <div class="left-arrow-wrap">
        <div class="arrow"></div>
      </div>
      <!-- right arrow -->
      <div class="right-arrow-wrap">
        <div class="arrow"></div>
      </div>
    </div>
  </div>

  <script>
    const reviewWrap = document.getElementById("reviewWrap");
    const leftArrow = document.querySelector(".left-arrow-wrap .arrow");
    const rightArrow = document.querySelector(".right-arrow-wrap .arrow");
    const imgBox = document.getElementById("imgBox");
    const name = document.getElementById("name");
    const profession = document.getElementById("profession");
    const description = document.getElementById("description");

    let people = [{
        photo: 'url("https://cdn.pixabay.com/photo/2015/03/03/18/58/woman-657753_960_720.jpg")',
        name: "Natalie Grey",
        profession: "Software Engineer",
        description: "While the lovely valley teems with vapour around me, and the meridian sun strikes the upper surface of the impenetrable foliage of my trees, and but a few stray gleams steal into the inner sanctuary, I throw myself down among the tall grass by the trickling stream; and, as I lie close to the earth, a thousand unknown plants are noticed by me:"
      },
      {
        photo: "url('https://cdn.pixabay.com/photo/2018/06/27/07/45/college-student-3500990_960_720.jpg')",
        name: "Dylan Smith",
        profession: "Student",
        description: "I'm baby woke mlkshk wolf bitters live-edge blue bottle, hammock freegan copper mug whatever cold-pressed. Bitters hashtag tumeric sriracha hot chicken gentrify portland. Dreamcatcher neutra irony."
      },
      {
        photo: "url('https://cdn.pixabay.com/photo/2015/01/08/18/30/man-593372__340.jpg')",
        name: "Branson Cook",
        profession: "Web Developer",
        description: "Hello, I'm a web developer. I have been working as a web developer for 5 years. I have worked in many companies and I have worked as a freelancer. I have worked in a team and I have worked alone. I have worked in a big company and I have worked in a small one."
      },
      {
        photo: "url('https://cdn.pixabay.com/photo/2012/10/26/02/12/actor-63082_960_720.jpg')",
        name: "Julius Grohn",
        profession: "Designer",
        description: "Working as a designer is a very interesting job. You can work in a team or alone, you can work in a company or as a freelancer. You can work in an office or at home. You can work in a big company or in a small one. You can work in a big city or in a small town."
      }
    ];

    // set the first person
    imgBox.style.backgroundImage = people[0].photo;
    name.innerText = people[0].name;
    profession.innerText = people[0].profession;
    description.innerText = people[0].description;
    let currentPerson = 0;

    //Select the side where you want to slide
    function slide(side, personNumber) {
      let reviewWrapWidth = reviewWrap.offsetWidth + "px";
      let descriptionHeight = description.offsetHeight + "px";
      //(+ or -)
      let side1symbol = side === "left" ? "" : "-";
      let side2symbol = side === "left" ? "-" : "";

      setTimeout(() => {
        imgBox.style.backgroundImage = people[personNumber].photo;
      }, 0);
      setTimeout(() => {
        description.style.height = descriptionHeight;
      }, 100);
      setTimeout(() => {
        name.innerText = people[personNumber].name;
      }, 200);
      setTimeout(() => {
        profession.innerText = people[personNumber].profession;
      }, 300);
      setTimeout(() => {
        description.innerText = people[personNumber].description;
      }, 400);
    }

    function setNextCardLeft() {
      if (currentPerson === 3) {
        currentPerson = 0;
        slide("left", currentPerson);
      } else {
        currentPerson++;
      }

      slide("left", currentPerson);
    }

    function setNextCardRight() {
      if (currentPerson === 0) {
        currentPerson = 3;
        slide("right", currentPerson);
      } else {
        currentPerson--;
      }

      slide("right", currentPerson);
    }

    leftArrow.addEventListener("click", setNextCardLeft);
    rightArrow.addEventListener("click", setNextCardRight);
  </script>
</body>

</html>