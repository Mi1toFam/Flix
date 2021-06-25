# Project 2 - *Flix*

**Flix** is a movies app using the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Time spent: **16** hours spent in total

## User Stories

The following **required** functionality is complete:

- [X] User sees an app icon on the home screen and a styled launch screen.
- [X] User can view a list of movies currently playing in theaters from The Movie Database.
- [X] Poster images are loaded using the UIImageView category in the AFNetworking library.
- [X] User sees a loading state while waiting for the movies API.
- [X] User can pull to refresh the movie list.
- [x] User sees an error message when there's a networking error.
- [x] User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

**NOTE**: Since this was created on MacinCloud and required an internet connection to work on, I was not able to test the functionality of the 
networking error message. Also, I was unable to utilize the Network Link Conditioner on MacinCloud either. 
However, I did implement it into my code, as shown below. 

<img width="443" alt="NetworkError" src="https://user-images.githubusercontent.com/65626248/123491581-013e0180-d5e5-11eb-84e7-dc7e1049befb.PNG">


The following **optional** features are implemented:

- [x] User can tap a poster in the collection view to see a detail screen of that movie
- [x] User can search for a movie.
- [ ] All images fade in as they are loading.
- [ ] User can view the large movie poster by tapping on a cell.
- [ ] For the large poster, load the low resolution image first and then switch to the high resolution image when complete.
- [ ] Customize the selection effect of the cell.
- [ ] Customize the navigation bar.
- [x] Customize the UI.
- [ ] User can view the app on various device sizes and orientations.
- [ ] Run your app on a real device.

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. How to extend the app to different APIs (ex: using an API with better ratings for the app)
2. How to optimize the design of the UI while maintaining simplicity

## Video Walkthrough

Here's a walkthrough of implemented user stories:

Launching the app and seeing the loading state and pull to refresh:

![Loading](https://user-images.githubusercontent.com/65626248/123491240-431a7800-d5e4-11eb-8056-7a782a9857fa.gif)

Scrolling and searching through the movies, along with clicking on them to view the details:

![Posters-min](https://user-images.githubusercontent.com/65626248/123491062-cb4c4d80-d5e3-11eb-9ed6-f08474016060.gif)

Scrolling through the collection, along with clicking on posters to view the details:

![Collection-min](https://user-images.githubusercontent.com/65626248/123491191-267e4000-d5e4-11eb-86dc-3b8cbb7cbd7c.gif)


## Notes

Describe any challenges encountered while building the app.

## Credits

- [MacinCloud](https://www.macincloud.com/) - Mac environment for Windows

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library

## License

    Copyright 2021 Milto Geleta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
