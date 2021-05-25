This project is a take-home challenge designed to evaluate frontend developers who are interested in working at Dovetale.

## The challenge

The goal of this challenge is build a React application for viewing and searching GIFs using the Giphy API.

Requirements:
* When a user first loads the app, they should see the first page of trending GIFs from [Giphy's Trending Endpoint](https://developers.giphy.com/docs/api/endpoint#trending)
* A user should be able to search for GIFs that should be pulled from [Giphy's Search Endpoint](https://developers.giphy.com/docs/api/endpoint#search)
* A user should be able to save and unsave GIFs, they should be able to see their saved GIFs which should persist after closing or refreshing the page

Expectations:
* To mimic our codebase, we ask that you use functional components and hooks rather than class components
* To mimic our codebase, we ask that you reach for using Context and the useReducer hook rather than Redux when managing complex state or state for deeply nested components
* Your pages and layouts should consider both desktop and mobile views

**Optional improvements**

We only expect a time commitment of around 4 to 6 hours to complete this challenge. If you are able to complete the base requirements with some time to spare, you might consider adding one or more of these improvements to show off more of your skills:
* Add pagination to the trending and/or search page to allow users to see more GIFs. This could be implemented as an infinite scroll, numbered pages or a "show more" button
* Show placeholders or skeletons for the page while GIFs are being fetched and loaded
* Add an animation to the "save" or "like" button to make it more fun to save a GIF

## Getting started
1. This repo contains a boilerplate starting point using [create-react-app](https://create-react-app.dev/), you can clone this repo to get started or feel free to create your own if you'd like to use a different structure
2. If you use the boilerplate in this repo, install dependencies and start your app by running `npm install` and `npm start`. 
3. Follow [Giphy's Quickstart](https://developers.giphy.com/docs/api#quick-start-guide) to create a Giphy App in their Developer Dashboard which will provide you with an API key to use for making requests 
4. Checkout [Giphy's API Explorer](https://developers.giphy.com/explorer) as a helper for making API requests and viewing responses


## Submission
Please submit your completed project as a single zip file, please do not open a pull request for your submission.

Outline any interesting choices you made, approaches you are proud of and any parts that we might miss. This helps us when reviewing your submission to see the details of everything you worked on.

We also welcome all feedback on what you thought of the project, any roadblocks or hurdles you faced, whether the time expectation is reasonable, etc.
