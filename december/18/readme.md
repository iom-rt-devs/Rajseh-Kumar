
<body>
    <div class="card-wrap ">
        <div class="card-header one">
           <i class="fa-solid fa-code "></i>
        </div>
        <div class="card-content">
            <h2 class="card-title">Title</h2>
            <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            <button class="card-btn btn-one">CODE</button>

        </div>
    </div>


    <div class="card-wrap">
        <div class="card-header two">
            <i class="fa-brands fa-css3-alt"></i>
        </div>
        <div class="card-content">
          <h1 class="card-title">Title</h1>
          <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
          <button class="card-btn btn-two">code</button>
       </div>
      </div>


      <div class="card-wrap">
        <div class="card-header three">
            <i class="fa-brands fa-html5"></i>
        </div>
        <div class="card-content">
          <h1 class="card-title">Title</h1>
          <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
          <button class="card-btn btn-three">code</button>
       </div>
      </div>

      <div class="card-wrap">
        <div class="card-header four">
            <i class="fa-brands fa-js"></i>
        </div>
        <div class="card-content">
          <h1 class="card-title">Title</h1>
          <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
          <button class="card-btn btn-four">code</button>
       </div>
      </div>


   

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>
***************************************************************************************************************************************
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
 body{
    height: 100vh;
    display: flex;
   flex-wrap: wrap;
   justify-content: center;
   align-items: center;
   
   
  }
 .card-wrap{
    width: 250px;
    margin: 20px;
    background-color: #ffff;
    border-radius: 25px;
    border: 5px solid #ffff;
    box-shadow: 0px 0px 20px 2px rgb(0, 0, 0,0.19);
    transition: all .2s ease-in-out;
 }  


.card-header{
          width: 100%;
          height: 12.5rem;
          display: grid;
          place-items: center;
          /* background-color: red; */ 
          /* border-bottom-right-radius: 100%;
           */
           border-bottom-right-radius: 110px;
           border-top-right-radius: 20px;
           border-top-left-radius: 30px;
           border-bottom-left-radius: 4px;
          

}
.card-header i{
    font-size: 60px;
    color: #ffffff;
}
.card-title{
    margin-top: 10px;
    margin-bottom: 20px;
    text-transform: uppercase;
    text-align: center;

}
.card-text{
    font-size: 20px;
    font-family: serif;
}
.card-btn{
    /* background:linear-gradient(to right, #fff700 , rgb(255, 0, 0)); */
    margin-left: 55px;
    border-radius: 55px;
    padding: 3px 30px;
    text-transform: uppercase;
    padding-bottom: 5px;
    border: none;
    color: #ffffff;
    font-weight: 200px;
}
.card-text{
  text-align: center;
  font-size: 20px;
  padding-top: 15px;
  padding-bottom: 20px;
  
}
.one{
  background:linear-gradient(to bottom left,  rgb(255, 0, 0),#fff700 );
}

.two{
  background: linear-gradient(to top right, #E100ff, #7F00FF);
}
/* .two{
  background: linear-gradient(to bottom left, #7f00ff,#E100ff);
} */
.three{
  background: linear-gradient(to top right,#7e59b6, #2d67a2);
}
.four{
  background: linear-gradient(to top right,#a8c0ff, #11998e);
}

.card-wrap:hover{
    transform: scale(1.1);
}
.btn-one{
  background:linear-gradient(to bottom left,  rgb(255, 0, 0),#fff700 );
}
.btn-two{
  background: linear-gradient(to top right, #E100ff, #7F00FF);

}
.btn-three{
  background: linear-gradient(to top right,#7e59b6, #2d67a2);
}
.btn-four{
  background: linear-gradient(to top right,#a8c0ff, #11998e);
}
