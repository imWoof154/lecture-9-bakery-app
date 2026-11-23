# Lecture 9 Bakery Tracker

Batch & Bloom is a standalone order tracker for the MGOC50 bakery exercise.

## Run the app

Download `index.html` and open it in Chrome or another modern browser. The file contains the app and the sample orders and messages. It runs without a server or package installation. Progress is saved in the current browser, and the **Download HTML** button provides a fresh copy to share.

## Work through the exercise

1. Check the pickup calendar and oven schedule. Book a helper at least two days ahead if you need more oven time.
2. Fetch the day's sample Instagram messages. Review the requested pickups and any changes or cancellations the app applied.
3. Reject individual requests if needed, then choose **Accept all and go to next day**. The app checks oven capacity again after every acceptance. Advancing closes that day's 5 PM pickups.

## Implementation

`index.html` contains the HTML, CSS, JavaScript, and embedded sample data. Fixed rules apply the two-day notice requirement, the eight-hour daily oven limit, and the four-hour extension from a $100 helper. The app keeps request decisions and confirmed orders in browser local storage.