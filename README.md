# New Year Countdown

Landing page that counts down from the current date to the next new year

## Description

This is a countdown timer that counts down to the next new year's day.

It starts by selecting the necessary HTML elements using their IDs, including the elements that will display the countdown timer and the loading spinner.

The code then gets the current year using the Date object, and calculates the time until the next new year's day using a new Date object that sets the date to January 1 of the next year at midnight.

The year displayed in the background is updated to the current year plus one.

The `updateCountdown` function is defined to calculate the difference between the current time and the new year's time and convert it into days, hours, minutes, and seconds. These values are then added to the DOM using the selected HTML elements.

A `setTimeout` function is used to remove the loading spinner after 1 second and display the countdown timer.

Finally, a `setInterval` function is used to call the updateCountdown function every second to update the countdown timer.

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
