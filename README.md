# Yesterday Stories Developer Challenge

The goal of this task is to develop a small React Native application. The task should take around 3 to 5 Hours - there
is no hard limit on this time although please try to stick to this time frame.

## Requirements

The basic requirements of this task is to display a list of "Stories" on one screen which are clickable through into a
second details screen which will show the user further information about the Stories "Categories".

1. The first screen should have a List View to show all the Stories with the following data:
    1. Story Name
    1. Story Description
1. The second screen will be the click through screen to a detailed view which should have the following displayed:
    1. Story Name
    1. Story Category Names with Icons displayed in any layout that seems fit

The user should be able to easily go between the detail view and the list view through a back button. Be sure to use the
given API's below. Also make sure you commit your work as you go on a feature branch as per the Submission instructions.

## API

Below are the endpoints available for the data you'll need to display on the App. The example structure of the responses
of these endpoints are below. Note - the API Endpoint to be used will be sent to you personally.

1. Story Endpoint

```
GET /stories

[
   {
     "id": 1,
     "name": "Lighthouse Story",
     "description": "Wollongong Harbour's Breakwater lighthouse has been inactive since 1974.",
     "categories": [1,2,3]
   },
   ...
]
```

1. Categories Endpoint

```
GET /categories

{
  "base_endpoint": "https://example.com/categories/",
  "categories": [
    {
      "id": 1,
      "name": "Arts and Monuments",
      "icon": "arts_and_monuments.png"
    },
    ...
  ]
}
```

## Assumptions

- You should pretend that you are submitting code that's going to production
- Make sure the code is adaptable to changing requirements
- Write the code in JavaScript under the React Native Framework (it's fine to use latest versions)
- It's ok to keep the UI as minimal and basic as possible
- It's fine to cater for just the latest iOS and Android versions
- Make sure the UI is flexible and works on multiple devices
- Tests are not necessary but testable code is a must
- Don't need to worry about pagination in the API or UI
- Your code must build and have instructions on how to build and run

## Submission

1. Create a new private GitHub repo and commit your work as you go to a feature branch
1. Add the `yesterdaystoriesjobs` user to your repository when you are finished
1. Open a Pull Request with your work with `yesterdaystoriesjobs` as the reviewer and email back letting us know you
   have finished the task and want to submit
1. A Yesterday Stories developer will review your code and get back to you shortly after submitting
