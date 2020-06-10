# Github Finder

> Github user information finder tool

> https://patrickpro2-githubfinder.netlify.app

## Functionality

- Search Github user's information through keywords of username
- Show target Github users from a user list
- Show user's general information and public repos' name for each user page

## Technology

- ReactJS
- Netlify

## Deployment

The project has been built on the [Netlify](https://app.netlify.com/), so you can see `build` folder here. If you want to run this repo standalone, just download this repo and execute `npm start`.

**Attention**: Since Github API has rate limitation, I apply an OAuth App to get API. You should also apply an OAuth App and Github will give you `Client ID` and `Client Secret`. In my repo, these two sensitive variables are saved in a local file `.env.local`. You can create this file under root directory and define variables like this (use keywords given by Github to replace xxx below):

```
REACT_APP_GITHUB_CLIENT_ID='xxx'
REACT_APP_GITHUB_CLIETN_SECRET='xxx'
```
