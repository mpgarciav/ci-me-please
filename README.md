# ci-me-please
Sample Gradle app for learning CI

# Instructions
## Testing the app
Use the Gradle wrapper to test your app: 
`./gradlew test`
## Building the app
Use the Gradle wrapper to build your app: 
`./gradlew build`
## Running the app
Use the Gradle wrapper to run your app:
`./gradlew run`

# Your task
- Create a simple CI pipeline for this application on [Travis CI](https://docs.travis-ci.com/) with (at least) the following steps:
    - Checkout
    - Test
    - Build
    - Slack notification on success or failure
    - Do a little CD: Deploy this app to Heroku on success
- Bonus points:
    - Add Pull Requests flows to your CI
    - Build a container for your app in your CI flow
    - Deploy the container to Heroku

# Suggestions
- Read (at least) the [Travis CI Core concepts for Beginners](https://docs.travis-ci.com/user/for-beginners/) and the [Travis CI tutorial](https://docs.travis-ci.com/user/tutorial/). 
    - Ask yourself, if we didn't provide these links, would you have looked for them?
    - How should you approach a completely new tool?
    - Look for the Slack and Heroku integrations in the Travis docs, they are very simple to navigate and easy to follow
- Google *everything* you don't know (Gradle, Travis, and Heroku are probably new tools for you, do you understand their purpose?)
- Remember, you cannot automate something you haven't done it manually first (I mean, you could, but you would struggle more than is necessary)
- Send too many Slack notifications and people will start ignoring them (nobody wants to see your 20-something attempts at setting up Slack notifications, use a test channel or your private conversation)
