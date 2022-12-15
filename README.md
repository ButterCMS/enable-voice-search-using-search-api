# ButterCMS Voice Search Application

This React.js application was designed to be a clone of the FAQ section of the ButterCMS Knowledge Base. It provides a voice search feature by integrating the Microsoft Azure Cognitive Service through the `microsoft-cognitiveservices-speech-sdk` SDK. 

[Read the article](https://buttercms.com/blog/enable-voice-search-using-buttercms-search-api) that explains the steps to build this application.

## Important Notice
This project was created as an example use case of ButterCMS in conjunction with a blog article, [How to Enable Voice Search Using the ButterCMS Search API](https://buttercms.com/blog/enable-voice-search-using-buttercms-search-api/), and will not be actively maintained. 

If you’re interested in exploring the best, most up-to-date way to integrate Butter into javascript frameworks like React, you can check out the following resources:

### Starter Projects

The following turn-key starters are fully integrated with dynamic sample content from your ButterCMS account, including main menu, pages, blog posts, categories, and tags, all with a beautiful, custom theme with already-implemented search functionality. All of the included sample content is automatically created in your account dashboard when you sign up for a free trial of ButterCMS.
- [React Starter](https://buttercms.com/starters/react-starter-project/)
- [Angular Starter](https://buttercms.com/starters/angular-starter-project/)
- [Vue.js Starter](https://buttercms.com/starters/vuejs-starter-project/)
- Or see a list of all our [currently-maintained starters](https://buttercms.com/starters/). (Over a dozen and counting!)

### Other Resources
- Check out the [official ButterCMS Docs](https://buttercms.com/docs/)
- Check out the [official ButterCMS API docs](https://buttercms.com/docs/api/)

## Prequisites
- Nodejs installed on your computer
- An Azure account with a Speech Service created

## Local Installation
- Clone the repository to your local machine. 
- Install project dependencies using the `yarn install` or `npm installl` command. 

## Credentials 
To access the Cognitive Service API, the `microsoft-cognitiveservices-speech-sdk` uses a Secret Token from the Cognitive service. It also accesses a ButterCMS API through the ButterCMS token.

Create a .env file, and store the credentials in the following format:

```bash
REACT_APP_SPEECH_SERVICE_KEY=<COGNITIVE_SERVICE_KEY>
REACT_APP_SPEECH_SERVICE_REGION=<COGNITIVE_SERVICE_REGION>
REACT_APP_BUTTERCMS_TOKEN=<BUTTERCMS_TOKEN>
```

## One last thing 🤫

Please star ( ⭐️ ) this repository if you find this application useful. The stars ( 🌟 ) provide encouragement.

Happy Hacking ✌️ 
