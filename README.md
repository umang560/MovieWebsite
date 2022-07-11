# MovieWebsite
SIGNIN.HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CINEMA</title>
    <link rel="stylesheet" href="signin.css">
</head>

<body>
    <div class="logo">
        <div class="wrapper">
            <div class="logo">
                <div class="containerr">
                    <p>Cine<span>MA</span></p>
                </div>
            </div>
        </div>



        <div class="sign">
            Sign-In
        </div>

        <form action="">
            <div class="full">
                <div class="email">Email</div>
                <div class="inputemail"> <input type="mail" id="mail"></div>
                <div class="pass">Password</div>
                <div class="passinput"><input type="password" name="" id="passs"></div>
                <div class="signinbutton"><a href="home.html">Sign-In</a></div>
                <div class="new">New to CineMA?</div>
                <div class="create"> <a href="signup.html">Create Your CINEMA Account</a></div>
            </div>
        </form>
    </div>
</body>

</html>





signin.css


@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,600;0,700;1,300;1,700&family=Roboto+Mono:wght@100&family=Roboto:wght@100&display=swap');

body{
    font-family: 'Open Sans', sans-serif;
}

:root{
    --md-dark-color: #1d1d1d;
    --dark-color: #171717;
    --light-dark-color: #292929;
    --yellow-color: #11d452;
}
*{
    padding: 0;
    margin: 0;
    -webkit-box-sizing: border-box;
            box-sizing: border-box;
}

a{
    text-decoration: none;
}
img{
    width: 100%;
    display: block;
}
.wrapper{
    min-height: 100vh;
    background-color: var(--dark-color);
}
.wrapper .containerr{
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}
.logo{
    padding: 0rem 0;
    border-bottom: 1px solid var(--light-dark-color);
}
.logo p{
    display: flex;
    position: absolute;
    top: 18px;
    left: 278px;
    font-size: 2rem;
    color: #fff;
    font-weight: bold;
}
.logo p span{
    color: var(--yellow-color);
}

.email{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 220px;

}
.inputemail{
    display: flex;
    /* align-items: center;
    justify-content: center; */
    position: absolute;
    color: #fff;
    left: 40%;
    top: 248px;
    font-size: 23px;
}
.inputemail input{
    height: 36px;
    width: 350px;
    border-radius: 6px;
}

.pass{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 320px;
}

.passinput{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    left: 40%;
    top: 348px;
    font-size: 23px;
}
.passinput input{
    height: 36px;
    width: 350px;
    border-radius: 6px;
}
.sign{
    display:flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 28px;
    line-height: 1.2;
    left: 40%;
    top: 150px;

}

.signinbutton{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 410px;
    /* border: 1px solid black; */
    height: 36px;
    width: 350px;
    border-radius: 6px;
    background-color:#11d452;
    /* color: white; */
}
.signinbutton a{
    color: white;
}
.new{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 46%;
    top: 480px;
}

.create{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 550px;
    height: 36px;
    width: 350px;
    border-radius: 6px;
    background-color:#3acd6b;
}
.create a{
    color: white;
    font-size: 23px;
}
.full email{
    border: 1px solid white;
}





signup.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CINEMA</title>
    <link rel="stylesheet" href="signup.css">
</head>
<body>
    <div class="logo">
        <div class="wrapper">
            <div class="logo">
                <div class="containerr">
                    <p>Cine<span>MA</span></p>
                </div>
            </div>
        </div>



        <div class="createe">
            Create Account
        </div>

        <form action="">
            <div class="full">
                <div class="name">Your Name</div>
                <div class="inputname"> <input type="text" id="name"></div>

                <div class="email">Email</div>
                <div class="inputemail"> <input type="mail" id="mail"></div>

                <div class="pass">Password</div>
                <div class="passinput"><input type="password" name="" id="passs"></div>

                <div class="repass">Re-enter Password</div>
                <div class="repassinput"><input type="password" name="" id="passs"></div>

                <div class="signupbutton"><a href="home.html">Create Your Account</a></div>
                <div class="already">Already Have an account?</div>
                <div class="create"> <a href="signin.html">Sign-In</a></div>
            </div>
        </form>
    </div>
</body>
</html>




signup.css


@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,600;0,700;1,300;1,700&family=Roboto+Mono:wght@100&family=Roboto:wght@100&display=swap');

body{
    font-family: 'Open Sans', sans-serif;
}

:root{
    --md-dark-color: #1d1d1d;
    --dark-color: #171717;
    --light-dark-color: #292929;
    --yellow-color: #11d452;
}
*{
    padding: 0;
    margin: 0;
    -webkit-box-sizing: border-box;
            box-sizing: border-box;
}

a{
    text-decoration: none;
}
img{
    width: 100%;
    display: block;
}
.wrapper{
    min-height: 100vh;
    background-color: var(--dark-color);
}
.wrapper .containerr{
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}
.logo{
    padding: 0rem 0;
    border-bottom: 1px solid var(--light-dark-color);
}
.logo p{
    display: flex;
    position: absolute;
    top: 18px;
    left: 278px;
    font-size: 2rem;
    color: #fff;
    font-weight: bold;
}
.logo p span{
    color: var(--yellow-color);
}

.createe{
    display:flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 28px;
    line-height: 1.2;
    left: 40%;
    top: 150px;

}

.name{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 223px;

}
.inputname{
    display: flex;
    /* align-items: center;
    justify-content: center; */
    position: absolute;
    color: #fff;
    left: 40%;
    top: 248px;
    font-size: 23px;
}
.inputname input{
    height: 36px;
    width: 350px;
    border-radius: 6px;
}

.email{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 326px;

}
.inputemail{
    display: flex;
    /* align-items: center;
    justify-content: center; */
    position: absolute;
    color: #fff;
    left: 40%;
    top: 350px;
    font-size: 23px;
}
.inputemail input{
    height: 36px;
    width: 350px;
    border-radius: 6px;
}

.pass{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 436px;
}

.passinput{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    left: 40%;
    top: 462px;
    font-size: 23px;
}
.passinput input{
    height: 36px;
    width: 350px;
    border-radius: 6px;
}

.repass{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 543px;
}

.repassinput{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    left: 40%;
    top: 570px;
    font-size: 23px;
}
.repassinput input{
    height: 36px;
    width: 350px;
    border-radius: 6px;
}

.signupbutton{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 650px;
    /* border: 1px solid black; */
    height: 36px;
    width: 360px;
    border-radius: 6px;
    background-color: #11d452;
}

.already{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 40%;
    top: 718px;
}
.create{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    color: #fff;
    font-size: 22px;
    line-height: 1.2;
    left: 56%;
    top: 718px;
}



home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CINEMA</title>
    <link rel="stylesheet" href="main.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class = "wrapper">
        <!-- logo -->
        <div class = "logo">
            <div class = "container">
                <p>Cine<span>MA</span></p>
            </div>
        </div>
        <!-- end of logo -->
        <!-- search container -->
        <div class = "search-container">
            <div class = "search-element">
                <h3>Search Movie:</h3>
                <input type = "text" class = "form-control" placeholder="Search Movie Title ..." id = "movie-search-box" onkeyup="findMovies()" onclick = "findMovies()">

                <div class = "search-list" id = "search-list">
                    <!-- list here -->
                    <!-- <div class = "search-list-item">
                        <div class = "search-item-thumbnail">
                            <img src = "medium-cover.jpg">
                        </div>
                        <div class = "search-item-info">
                            <h3>Guardians of the Galaxy Vol. 2</h3>
                            <p>2017</p>
                        </div>
                    </div> -->
                </div>
            </div>
        </div>
        <!-- end of search container -->

        <!-- result container -->
        <div class = "container">
            <div class = "result-container">
                <div class = "result-grid" id = "result-grid">
                    <!-- movie information here -->
                    <!-- <div class = "movie-poster">
                        <img src = "medium-cover.jpg" alt = "movie poster">
                    </div>
                    <div class = "movie-info">
                        <h3 class = "movie-title">Guardians of the Galaxy Vol. 2</h3>
                        <ul class = "movie-misc-info">
                            <li class = "year">Year: 2017</li>
                            <li class = "rated">Ratings: PG-13</li>
                            <li class = "released">Released: 05 May 2017</li>
                        </ul>
                        <p class = "genre"><b>Genre:</b> Action, Adventure, Comedy</p>
                        <p class = "writer"><b>Writer:</b> James Gunn, Don Abnett, Andy Lanning</p>
                        <p class = "actors"><b>Actors: </b>Chris Pratt, Zoe Saldana, Dave Bautista</p>
                        <p class = "plot"><b>Plot:</b> The Guardians struggle to keep together as a team while dealing with their personal family issues, notably Star-Lord's ecounter with his father the ambitious celestial being Ego.</p>
                        <p class = "language"><b>Language:</b> English</p>
                        <p class = "awards"><b><i class = "fas fa-award"></i></b> Nominated for 1 Oscar</p>
                    </div> -->
                </div>
            </div>
        </div>
        <!-- end of result container -->
    </div>


    <script src="script.js" ></script>
</body>
</html>


main.css


@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,600;0,700;1,300;1,700&family=Roboto+Mono:wght@100&family=Roboto:wght@100&display=swap');

body{
    font-family: 'Open Sans', sans-serif;
}


:root{
    --md-dark-color: #1d1d1d;
    --dark-color: #171717;
    --light-dark-color: #292929;
    --yellow-color: #11d452;
}
*{
    padding: 0;
    margin: 0;
    -webkit-box-sizing: border-box;
            box-sizing: border-box;
}

a{
    text-decoration: none;
}
img{
    width: 100%;
    display: block;
}
.wrapper{
    min-height: 100vh;
    background-color: var(--dark-color);
}
.wrapper .container{
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}
.search-container{
    background-color: var(--md-dark-color);
    height: 180px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
}
.logo{
    padding: 1rem 0;
    border-bottom: 1px solid var(--light-dark-color);
}
.logo p{
    font-size: 2rem;
    color: #fff;
    font-weight: bold;
}
.logo p span{
    color: var(--yellow-color);
}
.search-element{
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: stretch;
        -ms-flex-align: stretch;
            align-items: stretch;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-direction: column;
            flex-direction: column;
    position: relative;
}
.search-element h3{
    -ms-flex-item-align: center;
        align-self: center;
    margin-right: 1rem;
    font-size: 2rem;
    color: #fff;
    font-weight: 500;
    margin-bottom: 1.5rem;
}
.search-element .form-control{
    padding: 1rem 2rem;
    font-size: 1.4rem;
    border: none;
    border-top-left-radius: 3px;
    border-bottom-left-radius: 3px;
    outline: none;
    color: var(--light-dark-color);
    width: 350px;
}
.search-list{
    position: absolute;
    right: 0;
    top: 100%;
    max-height: 500px;
    overflow-y: scroll;
    z-index: 10;
}
.search-list .search-list-item{
    background-color: var(--light-dark-color);
    padding: 0.5rem;
    border-bottom: 1px solid var(--dark-color);
    width: calc(350px - 8px);
    color: #fff;
    cursor: pointer;
    -webkit-transition: background-color 200ms ease;
    -o-transition: background-color 200ms ease;
    transition: background-color 200ms ease;
}
.search-list .search-list-item:Hover{
    background-color: #1f1f1f;
}
.search-list-item{
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
}
.search-item-thumbnail img{
    width: 40px;
    margin-right: 1rem;
}
.search-item-info h3{
    font-weight: 600;
    font-size: 1rem;
}
.search-item-info p{
    font-size: 0.8rem;
    margin-top: 0.5rem;
    font-weight: 600;
    opacity: 0.6;
}

/* thumbnail */
.search-list::-webkit-scrollbar{
    width: 8px;
}
.search-list::-webkit-scrollbar-track{
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
            box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
}
.search-list::-webkit-scrollbar-thumb{
    background-color: var(--yellow-color);
    outline: none;
    border-radius: 10px;
}

/* js related class */
.hide-search-list{
    display: none;
}

/* movie result */
.result-container{
    padding: 3rem 0;
}
.movie-poster img{
    max-width: 300px;
    margin: 0 auto;
    border: 4px solid #fff;
}
.movie-info{
    text-align: center;
    color: rgb(255, 255, 255);
    padding-top: 3rem;
}

/* movie info stylings */
.movie-title{
    font-size: 2rem;
    color: var(--yellow-color);
}
.movie-misc-info{
    list-style-type: none;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    padding: 1rem;
}
.movie-info .year{
    font-weight: 500;
}
.movie-info .rated{
    background-color: var(--yellow-color);
    padding: 0.4rem;
    margin: 0 0.4rem;
    border-radius: 3px;
    font-weight: 600;
}
.movie-info .released{
    font-size: 0.9rem;
    opacity: 0.9;
}
.movie-info .writer{
    padding: 0.5rem;
    margin: 1rem 0;
}
.movie-info .genre{
    background-color: var(--light-dark-color);
    display: inline-block;
    padding: 0.5rem;
    border-radius: 3px;
}
.movie-info .plot{
    max-width: 400px;
    margin: 1rem auto;
}
.movie-info .language{
    color: var(--yellow-color);
    font-style: italic;
}
.movie-info .awards{
    font-weight: 300;
    font-size: 0.9rem;
}
.movie-info .awards i{
    color: var(--yellow-color);
    margin: 1rem 0.7rem 0 0;
}

@media(max-width: 450px){
    .logo p{
        font-size: 1.4rem;
    }
    .search-element .form-control{
        width: 90%;
        margin: 0 auto;
        padding: 0.5rem 1rem;
    }
    .search-element h3{
        font-size: 1.4rem;
    }
    .search-list{
        width: 90%;
        right: 50%;
        -webkit-transform: translateX(50%);
            -ms-transform: translateX(50%);
                transform: translateX(50%);
    }
    .search-list .search-list-item{
        width: 100%;
    }
    .movie-misc-info{
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
    }
    .movie-misc-info li:nth-child(2){
        margin: 0.8rem 0;
    }
}

@media(min-width: 800px){
    .search-element{
        -webkit-box-orient: horizontal;
        -webkit-box-direction: normal;
            -ms-flex-direction: row;
                flex-direction: row;
    }
    .search-element h3{
        margin-bottom: 0;
    }
    .result-grid{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }
    .movie-info{
        text-align: left;
        padding-top: 0;
    }
    .movie-info .movie-misc-info{
        -webkit-box-pack: start;
            -ms-flex-pack: start;
                justify-content: flex-start;
        padding-left: 0;
    }
    .movie-info .plot{
        margin-left: 0;
    }
    .movie-info .writer{
        padding-left: 0;
        margin-left: 0;
    }
}



script.js


const movieSearchBox = document.getElementById('movie-search-box');
const searchList = document.getElementById('search-list');
const resultGrid = document.getElementById('result-grid');

// load movies from API
async function loadMovies(searchTerm){
    const URL = `https://omdbapi.com/?s=${searchTerm}&page=1&apikey=7ffdc127`;
    const res = await fetch(`${URL}`);
    const data = await res.json();
    // console.log(data.Search);
    if(data.Response == "True") displayMovieList(data.Search);
}

function findMovies(){
    let searchTerm = (movieSearchBox.value).trim();
    if(searchTerm.length > 0){
        searchList.classList.remove('hide-search-list');
        loadMovies(searchTerm);
    } else {
        searchList.classList.add('hide-search-list');
    }
}

function displayMovieList(movies){
    searchList.innerHTML = "";
    for(let idx = 0; idx < movies.length; idx++){
        let movieListItem = document.createElement('div');
        movieListItem.dataset.id = movies[idx].imdbID; // setting movie id in  data-id
        movieListItem.classList.add('search-list-item');
        if(movies[idx].Poster != "N/A")
            moviePoster = movies[idx].Poster;
        else 
            moviePoster = "image_not_found.png";

        movieListItem.innerHTML = `
        <div class = "search-item-thumbnail">
            <img src = "${moviePoster}">
        </div>
        <div class = "search-item-info">
            <h3>${movies[idx].Title}</h3>
            <p>${movies[idx].Year}</p>
        </div>
        `;
        searchList.appendChild(movieListItem);
    }
    loadMovieDetails();
}

function loadMovieDetails(){
    const searchListMovies = searchList.querySelectorAll('.search-list-item');
    searchListMovies.forEach(movie => {
        movie.addEventListener('click', async () => {
            // console.log(movie.dataset.id);
            searchList.classList.add('hide-search-list');
            movieSearchBox.value = "";
            const result = await fetch(`http://www.omdbapi.com/?i=${movie.dataset.id}&apikey=7ffdc127`);
            const movieDetails = await result.json();
            // console.log(movieDetails);
            displayMovieDetails(movieDetails);
        });
    });
}

function displayMovieDetails(details){
    resultGrid.innerHTML = `
    <div class = "movie-poster">
        <img src = "${(details.Poster != "N/A") ? details.Poster : "image_not_found.png"}" alt = "movie poster">
    </div>
    <div class = "movie-info">
        <h3 class = "movie-title">${details.Title}</h3>
        <ul class = "movie-misc-info">
            <li class = "year">Year: ${details.Year}</li>
            <li class = "rated">Ratings: ${details.Rated}</li>
            <li class = "released">Released: ${details.Released}</li>
        </ul>
        <p class = "genre"><b>Genre:</b> ${details.Genre}</p>
        <p class = "writer"><b>Writer:</b> ${details.Writer}</p>
        <p class = "actors"><b>Actors: </b>${details.Actors}</p>
        <p class = "plot"><b>Plot:</b> ${details.Plot}</p>
        <p class = "language"><b>Language:</b> ${details.Language}</p>
        <p class = "awards"><b><i class = "fas fa-award"></i></b> ${details.Awards}</p>
    </div>
    `;
}


window.addEventListener('click', (event) => {
    if(event.target.className != "form-control"){
        searchList.classList.add('hide-search-list');
    }
});
