# Assignment 1 - ReactJS app.

Name: Adam Kenny (20102588)

## Overview.

A react app using the movies database to show different movies, be they upcoming, popular or playing in the cinema

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ Added a Upcoming movies Page
+ Added a Now Playing movies Page
+ Added a Popular movies Page
+ The watchlist page can be added to and have movies removed from it

## Setup requirements.

Unavailable

## API endpoints.

[ List the __additional__ TMDB endpoints used, giving the description and pathname for each one.] 

e.g.
+ Discover list of movies - discover/movie
+ Movie details - movie/:id
+ Movie genres = /genre/movie/list
+ Upcoming movies = /pages/upcomingMoviesPage
+ Watchlist = /pages/WatchListPage
+ Now playing movies = /pages/nowPlayingMoviesPage
+ Popular movies = /pages/popularMoviesPage

## Routing.

[ List the __new routes__ supported by your app and state the associated page.]

<Routes>
            <Route path="/movies/favorites" element={<FavoriteMoviesPage />} />
            <Route path="/reviews/:id" element={ <MovieReviewPage /> } />
            <Route path="/movies/:id" element={<MoviePage />} />
            <Route path="/" element={<HomePage />} />
            <Route path="*" element={ <Navigate to="/" /> } />
            <Route path="/reviews/form" element={ <AddMovieReviewPage /> } />
            <Route path="/movies/upcoming" element={<UpcomingMoviesPage/>} />
            <Route path="/movies/mustWatch" element={<WatchListPage/>} />
            <Route path="/movies/now_playing" element={<NowPlayingMoviesPage/>} />
            <Route path="/movies/popular" element={<PopularMoviesPage/>} />
          </Routes>

## Independent learning (If relevant).

This Module has made me actually understand how to do web app dev unlike the previous
 
