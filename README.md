# twitch-plays-gather

A Gather NPC you can control via chat.

Also a great example of a mod built with the [Gather API](https://gathertown.notion.site/Gather-Websocket-API-bf2d5d4526db412590c3579c36141063)

(A/V isn't supported yet, sorry!)

## setup

prereq: have NodeJS and npm installed

run `npm install`

put your API key in a file named `api-key.ts` like so:

```js
export const API_KEY = "your-api-key-here";
```

replace the `SPACE_ID` in index.ts with your own spaceId

## running

`npm run start`

## NOTE(!)

Putting in your API key will make the bot join as you!
You probably want to be able to join as yourself and have the bot going at the same time.
Just login with a different email and get an API key for that account, so you can use yours normally.
