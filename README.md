# Bootstrap-Portfolio

<div class="container ">
    <div class="row">
        <div class="col">
          <div class="box"></div>
        </div>
          <div class="col">
        <div class="box"></div>
        </div>
        <div class="col">
          <div class="box"></div>
        </div>
        <div class="col">
          <div class="box"></div>
        </div>
        <div class="col">
          <div class="box"></div>
        </div>
    </div>
</div>

/////////////////

body {
    margin-top: 40px; /* This margin just makes the text easier to read. You can remove it if you want since it can mess with your other styles. */
  }
  
  body::before {
    content: "XS";
    color: red;
    font-size: 2rem;
    font-weight: bold;
    position: fixed;
    top: 0;
    right: 0;
  }
  
  /* This box class is purely used for explaining how the bootstrap grid system works. */
  .box {
    background-color: lightblue;
    border: 1px solid blue;
    min-height: 50px;
    font-size: 2rem;
  }
  
  @media (min-width: 576px) {
    body::before {
      content: "SM";
    }
  }
  
  @media (min-width: 768px) {
    body::before {
      content: "MD";
    }
  }
  
  @media (min-width: 992px) {
    body::before {
      content: "LG";
    }
  }
  
  @media (min-width: 1200px) {
    body::before {
      content: "XL";
    }
  }
  
  @media (min-width: 1400px) {
    body::before {
      content: "XXL";
    }
  }