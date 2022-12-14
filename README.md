# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://i.imgur.com/LlmmyqM.gif" width=250><br>

### Notes
After creating the collectionview page with the images of movie posters in a grid, at first the icons of the posters were very small due to the default setting in Xcode, but this was fixed after setting the estimated size attribute to none. I was unfamiliar with using auto layout in Xcode so it was a challenge to format the spacing of images and how they are cropped.

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF


<img src="https://i.imgur.com/ODSG0vL.gif" width=250><br>


## Running on real device


<img src="https://i.imgur.com/PbgBFkX.gif" width=250><br>


### Notes
I was unfamiliar with the project structure of Xcode, from how elements in the main swift files connected to the storyboard where the design is made, to setting up an Apple developer profile to run apps on real devices. I had an error installing cocoapods as well but I had to install cocoapods through homebrew and then reinstall the alamofireimage package after I installed cocoapods.

