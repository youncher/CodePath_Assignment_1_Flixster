# Flixster (CodePath Assignment 1)
Flixster is an app that allows users to browse movies from the [The Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction).

---

## Flixster Part 1

### User Stories
Required:
- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

Optional:
- [x] Views should be responsive for both landscape/portrait mode.
   - [x] In portrait mode, the poster image, title, and movie overview is shown.
   - [x] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [ ] Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ ] Improved the user interface by experimenting with styling and coloring.
- [ ] For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF
Portrait Mode

<img src='Portrait_Demo.gif' title='Video Walkthrough' width='250' alt='Video Walkthrough' />

Landscape Mode

<img src='Landscape_Demo.gif' title='Video Walkthrough' width='500' alt='Video Walkthrough' />

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
