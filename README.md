# WEB102 Prework - GameQuest Hub

Submitted by: Gildardo Orea Amador

GameQuest Hub is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 6 hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] List anything else that you can get done to improve the app functionality!
* [x] Added a navigation bar at the top of the page to get to any of the three sections quickly

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ScreenToGif
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

- A major challenge was learning how to dynamically create and append elements to the DOM. At first, I tried to pass entire HTML strings into createElement, which did not work. I had to switch to using ".innerHTML" inside newly created elements, or chaining createElement with appendChild.
- The reduce method was a little bit tricky. I initially confused the accumulator’s starting value, which sometimes led to unexpected results. Once I read more documentation and understood how the accumulator works, I was able to calculate totals like the number of contributions and total pledge amounts more easily.
- Finally, understanding how to use the ternary operator inside template literals for pluralization (“1 game remains” vs. “2 games remain”) took some time, but it helped me to understand clearly how they can be used for displaying and rendering text.

## License

    Copyright [2025] [Gildardo Orea Amador]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
