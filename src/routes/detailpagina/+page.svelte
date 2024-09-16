<body>

    <a href="/">back</a>

    <div class="achtergrondblokje"></div>
    <div><h1>Akiko Schermer</h1></div>


		<img src="/Akiko.JPG" class="student" alt="Akiko" />


        <article>
            <h2> About me</h2>
            <p class="text"> 
                Hi, Ik ben Akiko Schermer,
                Ik woon in Amstelveen. Momenteel volg ik de studie Frontend-end Development & Design
            </p>
        </article>
 
       <p class="socials"> Socials</p>

</body>

<style>

    a {
        color:#66e5bf;
        text-decoration: none;
        margin-top: 10px;
    }

    h1 {
     text-align: center;
     width: 275px;
    height: 50px;
 
    }

    div {
    background-color: #66e5bf;
    color: darkblue;
    width: 275px;
    height: 50px;
    position: relative;
    z-index: 2;
   }

   div.achtergrondblokje{
    background-color:#AFFFF0;
    color: darkblue;
    width: 278px;
    height: 50px;
    position: absolute;
    transform: rotate(-10deg);
    z-index: 1;
    top: 45px;
   }

   h2 {
    padding-left: 5px;
    border-radius: 5px;
    background-color: aquamarine;
    color: darkblue
   }

    article {
        background: white;
        border-radius: 5px;
        height: 160px;
    }

    p.text {
        color: darkblue;
        margin-left: 10px;
        margin-right: 10px;
    }

    p.socials {
        background-color: aquamarine;
        color: darkblue;
        width: 70px;
        height: 25px;
        border-radius: 5px;
        text-align: center;
    }

    img {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }


    .student {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 50%;
        margin-top: 1em;
        margin-bottom: 1em;
    }


	</style>