# Today's Moon 🌙 ![S3 Deploy status](https://github.com/aharmon413/moon-project/actions/workflows/main.yaml/badge.svg)
**A React app for viewing current and future moon phase information**

_View live at [moons.amberharmon.com](https://moons.amberharmon.com/)_

![moons.amberharmon.com](https://user-images.githubusercontent.com/83358042/160876707-c3062aa4-cc60-417d-85b1-a27aa2c973c9.png)

## About

This project is a combination of my love of programming and all things witchy and magical.

For any given moment, the app displays:
- The current moon phase, along with the date and time
- A brief description of the themes of the current phase
- A few suggestions for activities that go along with the themes of the current phase
- Both the previous and next major moon phases, along with the zodiac sign the moon was in and will be in (a new moon or full moon is considered a 'major moon phase' here)

The current moon phase is calculated using a simple formula by [Ben Daglish](http://www.ben-daglish.net/moon.shtml). It takes the difference between the current date and a known new moon date (January 7, 1970) for a value between 1 and 30. Each moon phase is associated with a numerical range.

The major moon phases, specifically the associated zodiac signs, were a little more complicated. As it turns out, astrology calculations are very complex! I couldn't find an API that fit my needs and stayed within the scope of my ability and this project, so I ended up compiling a few years' worth of moon phase data into a JSON file.

I also used this project as an opportunity to learn about code testing, utilizing the React Testing Library and Jest to write a few simple tests.

## Resources
- [create-react-app](https://github.com/facebook/create-react-app) - initializing the project
- [Ben Daglish](http://www.ben-daglish.net/moon.shtml) - the formula used to calculate the current moon phase
- [AstroSeek](https://mooncalendar.astro-seek.com/full-moons-new-moons) - data about new and full moons
- [FontAwesome](https://fontawesome.com/) - social media icons
- [React Testing Library Tutorial](https://www.youtube.com/watch?v=7dTTFW7yACQ&list=PL4cUxeGkcC9gm4_-5UsNmLqMosM-dzuvQ) - The Net Ninja and Laith Harb's video series on React Testing Library
- Special thank you to [Kevin](https://github.com/mage7223) for setting up a domain and deployment workflow for the project
