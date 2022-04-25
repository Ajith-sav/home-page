<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="
    width=device-width, initinal-scale=1">
    <title>NAR Browser</title>
    <link rel="stylesheet" type="text/css" href="style/style.css">
    <link rel="icon" href="image/NAR-NBG.png" type="image/x-icon">
</head>

<body>
    <section class="logo-and-brand">
        <img
        class="NAR-logo"
        src="image/NAR-NBG.png"
        alt="NARlogo">
    </section> 
   
    <section class="b_name">
       <center><h1 class="brand">NAR Browser</h1></center> 
    </section>
    
    <div class="searchbar" id="searchbar">
        <form action="https://google.com/search" method="get" name="q">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjzC2JyZDZ_RaWf0qp11K0lcvB6b6kYNMoqtZAQ9hiPZ4cTIOB"
            alt=""
            srcset=""
            style="height: 30px;
            text-align: center;
            margin-top: 11px;
            margin-right: 6px;"
          />
          <input
            name="q"
            autocomplete="off"
            placeholder="Search here with duckDuckGo..."
            type="text"
          />
          <button>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="17"
              height="17"
              fill="currentColor"
              class="bi bi-search"
              viewBox="0 0 16 16"
            >
              <path
                d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"
              ></path>
            </svg>
          </button>
        </form>
      </div>

    <div class="toggle-switch"><p>Dark</p><span><label class="switch"><input id="theme-switch" type="checkbox"><span class="slider round"></span></label></span><p>Light</p></div>
    
      <div class="news">
        <div class="accordion" id="newsAccordion"></div>
           </div>
           <h1 class="newsh">Recommended by News API</h2>
           <div class="about" id="about">
           <p>Mr.A Corporation - </p>
         </div>
        <script src="javascript/news.js"></script>
        <script src="javascript./index.js"></script>
      </body>
    </html>
