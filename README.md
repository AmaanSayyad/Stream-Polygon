# Stream

## - Decentralized Youtube + Twitch using Polygon
<p align="left">
  <img src="https://img.shields.io/badge/OpenZeppelin-4E5EE4?logo=OpenZeppelin&logoColor=fff&style=for-the-badge" width="155" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" width="110" />
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" width="78" />
  <img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white" width=88" />
  <img src="https://img.shields.io/badge/Solidity-e6e6e6?style=for-the-badge&logo=solidity&logoColor=black" width="120" />
  <img src="https://img.shields.io/badge/YouTube_Gaming-FF0000?style=for-the-badge&logo=youtube-gaming&logoColor=white" width="182" />

</p>

<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" width="110" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" width="105" />
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" width="155" />
  <img src="https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E" width="132" />
  <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" width="120" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" width="150" />


</p>

---

## Inspiration
Streamers pay ~40% to Youtube for superchats and rely on centralized transcoding and distribution by these platforms. However, Streamers have no control over the transcoding quality or transcoding bitrate, and so the quality of their streams is out of their hands. Also, they are subject to strict rules and regulations about what content they can stream. For example, Youtube's new rule requires 'education, scientific research, news reporting, criticism, or commentary as the 'primary purpose of streaming. Streamers could get banned for their content, and will not get paid for their content.

## What it does
Stream makes it easier for Streamers to take ownership of their streams and use Polygon as the decentralized tipping layer to receive 100% of the money tipped by their audiences.  Streamers also have full control over the transcoding bitrate and quality.

## Challenges we ran into
We wanted to embed superchats on top of live streams but most gamers use OBS to stream. So we had to find a way to inject superchats on top of their videos without ever having control of the video.

## Accomplishments that we're proud of
We accomplished this by creating an OBS browser URL that the users can inject into their streams. The browser plugin will listen to events on the blockchain and react inject the right set of popups on the streamer's video.

## What we learned
We learned how to interact with the Polygon network and create a plugin for open-source software. Also, we learnt a lot about OBS, ffmpeg and other tools to bring the streamer's vision to life.

## How we built it
The web app is built with HTML, CSS, JavaScript, React.js, Node.js and the web3.js library. The web app interacts with a solidity smart contract deployed to mumbai.polygonscan.com testnet.

## What's next for Stream
We want to continue to integrate and make it easier for streamers to stream and receive tips in the form of Polygon tokens. Also, we want to add more features to make it easy for streamers to get started and introduce new ways to monetize their streams. The goal is to create a simple and easy-to-use interface to set up tipping, but also allow users to customize it to their own liking.

---

Github: https://github.com/AmaanSayyad/Stream-Polygon

Contract Address: https://mumbai.polygonscan.com/address/0xB2AF8227A5b2257848A57122D62646F6471837b1#code

---

<img src="https://media.giphy.com/media/42D5ycv3au9s8MQtrU/giphy.gif" width="500" />
