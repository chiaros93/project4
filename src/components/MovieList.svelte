<script>
    const URL =
        "https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=false&language=en-US&page=2&sort_by=popularity.desc";

    const options = {
        method: "GET",
        headers: {
            accept: "application/json",
            Authorization:
                "Bearer eyJhbGciOiJIUzI1NiJ9.eyJhdWQiOiJhZTI3ZTg1YTY3NzdjMWJiY2QyMTIwM2Y5OGM3NDcyYSIsInN1YiI6IjY1MzBmNjNiZjE3NTljMDExYzE2MDI0YSIsInNjb3BlcyI6WyJhcGlfcmVhZCJdLCJ2ZXJzaW9uIjoxfQ.8DDAsffJjfE2JjHZvVbeQAHUb_jX2UBsUpPapIdSW0s",
        },
    };

    let movies = [];

    fetch(URL, options)
        .then((response) => response.json())
        .then((data) => (movies = data.results))
        .catch((err) => console.error(err));


</script>

<div>
    <p class="Oferta">Los más populares</p>
</div>

<div class="movies">
    {#each movies as movie}
        <div class="movieContainer">
            <img src={`https://image.tmdb.org/t/p/w500${movie.poster_path}`} alt={movie.title} width="250px"/>
            <div class="movieTitleOverlay">
            <p class="movieTitle">{movie.title}</p>
            </div>
        </div>
    {/each}
</div>

…
<element class="movie-title" />

<style>
    .movies {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 30px;
        margin-left: 70px;
        position: relative;
        width: auto;
    }

    .movieContainer {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        color: white;
        text-align: center;
        position: relative;
    }

    .Oferta {
        color: white;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
            Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
            sans-serif;
        font-size: 25px;
        font-weight: bolder;
        text-align: left;
        margin-left: 70px;
    }
    .movieTitle {
        color: white;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
        sans-serif;
        font-size: 20px;
        font-weight: 600;
    }
</style>
