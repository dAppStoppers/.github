# DappStop

<p align="center">
<a href="https://weathered-limit-7676.on.fleek.co/">
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-Banner.png"/>
<a>
<i>A Censorship Resistant & Creator First Dappstore</i>

🌐 Website: <https://dappstop.xyz/>

🖌️ UI/UX Design: <https://www.figma.com/file/fpqeSa01XbUwN4g4EDzN3Z/DappStop---ETH-Bogota-draft>

🖥️ Frontend: <https://github.com/dAppStoppers/dAppStop-interface>

💡 Backend: <https://github.com/dAppStoppers/dAppStop-core>

## Motivations

Most web3 mobile games are banned on the Google Playstore and App Store because these games are against the Terms of Service of the mentioned appstore. In addition, these appstores impose hefty taxes on in-game purchases which we feel is unfair to the game developers.

In the spirit of censorship resistance and giving power back to creators, dAppStore aims to provide a fair platform for both web3 mobile game developers and players.

The current appstores are also lacking a social aspect, if implemented, could boost the audience of the Dapps distributed on the platform.

## Solution

A censorship-resistant Dapp distribution platform.

## 📑 Deck

<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_1.png"/>
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_2.png"/>
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_3.png"/>
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_4.png"/>
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_5.png"/>
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_6.png"/>
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-deck_Page_7.png"/>


We've built a decentralized app store for mobile dapps. The minimal delightful point is that the creators/publishers can deliver their dapps without any permission. It was definitely new and delightful value for them.
https://twitter.com/0xmoriki/status/1579042246090838017
https://twitter.com/yukiw_eth/status/1579047768881971200
## Data Structures

- Dapp Metadata

```txt
{
  name: string
  description: string
  image: string
  ceramic_uri: string
}
```

- Dapp Datastructure

```txt
{
  title: string
  description: string
  version: string
  app_icon_url: string
  preview_images: string[4]
  chain: enum(Polygon, Optimism, Klaytn)
  category: enum(Game, dApp)
  apk_url: string
  token_gated: bool
  price: number
}

```

## TODOs

- [x] Create Schema for Documentation
- [x] Create Dummy Data

- [x] Upload to IPFS images

- [x] Publisher page (upload)

  - [x] Login
  - [x] upload game files to IPFS
  - [x] upload new version game files to IPFS
    - [x] PUSH notifications using EPNS/PUSH
  - [x] setup Game Profile
    - [x] App Logo
    - [x] Preview Image
    - [x] Chain
    - [x] APK File
    - [x] Token Gated?
    - [x] Price
    - [x] Name
    - [x] Description

- [x] Consumer pages (downloads)

  - [x] Login
  - [x] Explore (hardcoded)
  - [x] View app
    - [x] App Logo
    - [x] Proof of Purchase Detection
  - [x] Download

- [x] Proof of Purchase NFT Image

  - [x] DappStop Logo + Applogo

- [x] Demo
  - [x] Demo Video
  - [x] Submission on ETH Global Website
  - [x] Pitch Deck
  - [x] Sample APK to upload to IPFS

## Demo
