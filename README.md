# module2_solution
assignment for css3 course

<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>MENU</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 15px;
}

p {
  border: 1px solid black;
  background-color: #A52A2A;
  width: 90%;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  font-family: Helvetica;
  color: white;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/********** Large devices only **********/
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
    border: 1px solid green;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/********** Medium devices only **********/
@media (min-width: 950px) and (max-width: 1199px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    border: 1px solid green;
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}

</style>
</head>
<body>
<h1>RESTAURANT MENU</h1>

<div class="row">
  <div class="col-lg-3 col-md-6"><p><b><i>sushi</i></b> is traditional japanese dish made out of raw fish,steamed rice and tangy soy sauce.traditionally served with guava chutney.</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>hotdog</b></i> is a american style street food.consists of a a bun filled with mustard sauce and a cooked roasted sausage.yumm!!!</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>panipuri</i></b> is a indian style street food.also known as golgappa is a wafer kind of stuff usually rounded like small bun and is served by filling different kinds of flavored water like mint,garlic,tamarind etc.</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>Biryani</i></b> is a popular and flavorful rice dish that originated in the Indian subcontinent. It is made by cooking basmati rice with a variety of spices, meat (such as chicken, mutton, or fish), and sometimes vegetables. Biryani is known for its aromatic flavors and is often garnished with fried onions, mint leaves, and boiled eggs. It is a complete meal on its own and is enjoyed by people of all ages. Biryani has different regional variations and is a favorite dish in many countries, including India, Pakistan, Bangladesh, and the Middle East.</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>Pav Bhaji</i></b> is a popular street food dish from India. It consists of a spicy and flavorful vegetable curry called "bhaji" that is served with soft buttered buns called "pav". The bhaji is made by cooking a mix of mashed vegetables like potatoes, peas, and cauliflower with a blend of spices and herbs. It is typically garnished with chopped onions, coriander leaves, and a squeeze of lemon juice. The pav is toasted with butter and served alongside the bhaji. Pav Bhaji is a delicious and satisfying dish that is enjoyed by people of all ages.</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>bhelpuri</i></b> is a indian snack prepared from puffed rice masalas and chutney.</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>gulabjamun</i></b> is traditional indian sweet.</p></div>
  <div class="col-lg-3 col-md-6"><p><b><i>shamshi</i></b> is traditional japanese dish.</p></div>
</div>

</body>
</html>
