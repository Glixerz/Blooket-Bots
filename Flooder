//defining vars
let nameOfbot = prompt("Name of bots: ")
let gameId = prompt("Enter Game Pin: ");
let numberOfBots = prompt("How many Bots: ")
let botsToJoin;

//Credit
console.log('%c Created by Sean v  :D', 'background: #222; color: yellow');



// Making a for loop for flood
for(botsToJoin = 0; botsToJoin < numberOfBots; botsToJoin++)

fetch("https://api.blooket.com/api/firebase/join", {
  "headers": {
    "accept": "application/json, text/plain, */*",
    "accept-language": "en-US,en;q=0.9",
    "content-type": "application/json;charset=UTF-8",
    "sec-ch-ua-mobile": "?0",
    "sec-fetch-dest": "empty",
    "sec-fetch-mode": "cors",
    "sec-fetch-site": "same-site"
  },
  "referrer": "https://www.blooket.com/",
  "referrerPolicy": "strict-origin-when-cross-origin",
  //adding vars to body for correct values
  "body": "{\"id\":\"" + gameId+ "\",\"name\":\"" + nameOfbot + botsToJoin+ "\"}",
  "method": "PUT",
  "mode": "cors",
  "credentials": "omit"
});
