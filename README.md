# Developer Test
First of all congratulations on making it to the next stage of the interview process. We have designed this test to assess your technical skills and problem solving abilities. We are looking for a well structured, clean and efficient solution.

## Objective
- Build a github trending list application.
- The list can be sorted by stars and name.
- Shows Internet not connected screen if the data from cache is not available and internet not
connected.
- Implement accordion for each item in the list.

## Bonus Points
- Implement local caching in case of no internet connection.
- Implement pull to refresh.
- Optimise the performance of the application.
- FPS benchmarking.

## Requirements
- You must use Flutter v3+ to build the application.
- You must use the provided API to fetch the data.
- You must use freezed for data classes.
- You must use flutter_bloc for state management.
- You must use a navigation library.

## Submission
- You must send us a link to a public git repository with your solution.
- You must include a README.md file with instructions on how to run your application.
- Demonstrate your understanding of the problem and solution with clear and concise comments.
- Show us demo of your application running on an emulator or physical device.

## Our Assessment Criteria
- UI similarity to our mockup
- App functionalities
- Code cleanliness and simplicity
- Component modularization
- Perfomance approaches
- Git commit message

## References
The complete API docs are available [here](https://docs.github.com/en/rest/repos?apiVersion=2022-11-28). You need to fetch the data from `/repositories` endpoint.

You will use this API to get a list of the repositories in the [Flutter](https://github.com/flutter) organization as a response from this
API.

## Mockup
![Alt text](https://raw.githubusercontent.com/farellsujanto/code-test/main/mockup.png)
