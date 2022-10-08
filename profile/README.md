# Unblogged

<p align="center">
<a href="https://weathered-limit-7676.on.fleek.co/">
<img src="https://raw.githubusercontent.com/dAppStoppers/.github/main/profile/assets/DappStop-Banner.png"/>
</a>
_A Decentralized DappStore_

🌐 Website: <https://dappstop.xyz/>

🖌️ UI/UX Design: <https://www.figma.com/file/fpqeSa01XbUwN4g4EDzN3Z/DappStop---ETH-Bogota-draft>

🖥️ Frontend: <https://github.com/dAppStoppers/dAppStop-interface>

💡 Backend: <https://github.com/dAppStoppers/dAppStop-core>

## Motivations

Most web3 mobile games are banned on the Google Playstore and App Store because these games are against the Terms of Service of the mentioned appstore. In addition, these appstores impose hefty taxes on in-game purchases which we feel is unfair to the game developers.

In the spirit of censorship resistance and giving power back to creators, dAppStore aims to provide a fair platform for both web3 mobile game developers and players.

The current appstores are also lacking a social aspect, if implemented, could boost the audience of the Dapps distributed on the platform.

## Solution

A censorship-resistant Dapp distribution platform

## TODOs

- Dapp Datastructure

```tx
{
  title: string
  app_icon_url: string
  preview_images: string[4]
  chain: enum(Polygon, Optimism, Klaytn)
  category: enum(Game, dApp)
  description: string
  apk_url: string
  token_gated: bool
  price: number
}

```

- [ ] Upload to IPFS images

- [ ] Publisher page (upload)

  - [ ] Login
  - [ ] upload game files to IPFS
  - [ ] upload new version game files to IPFS
    - [ ] PUSH notifications using EPNS/PUSH
  - [ ] setup Game Profile
    - [ ] App Logo
    - [ ] Preview Image
    - [ ] Chain
    - [ ] APK File
    - [ ] Token Gated?
    - [ ] Price
    - [ ] Name
    - [ ] Description

- [ ] Consumer pages (downloads)

  - [ ] Login
  - [ ] Explore (hardcoded)
  - [ ] View app
    - [ ] App Logo
    - [ ] Proof of Purchase Detection
  - [ ] Download

- [ ] Proof of Purchase NFT Image

  - [ ] DappStop Logo + Applogo

- [ ] Demo
  - [ ] Demo Video
  - [ ] Submission on ETH Global Website
  - [ ] Pitch Deck
  - [ ] Sample APK to upload to IPFS

## 📑 Deck

## Demo
