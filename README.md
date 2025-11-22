# AdMobPlugin-Documentation

AdMob Plugin for Unreal Engine

A polished and reliable AdMob integration plugin for Unreal Engine (Android only).
Includes Banner, Interstitial, Rewarded, and Rewarded Interstitial ads with full Blueprint support and clean callbacks.

Installation
Place the plugin inside your project:
```
YourProject/
└── Plugins/
    └── AdMobPlugin/
```
Then:
1.Restart Unreal Engine
2.Go to Edit → Plugins
3.Enable AdMob Plugin
4.Add AdMob App ID in Project Settings/Engine/AdMob Settings/AppID


---

## 🎮 Blueprint Usage

Below are all the supported ad formats with preview images and node details.

---

## 🟦 **Banner Ad**

![Banner Ad Example](Assets/BannerAd.png)

Show Banner Ad

Inputs: AdUnitID, UseAdaptiveBanner (true/false)

Callbacks:

OnSuccess

OnFailed


---

## 🟥 **Interstitial Ad**

![Interstitial Ad Example](Assets/InterstitialAd.png)

Show Interstitial Ad

Callbacks:

OnSuccess

OnFailed


---

## 🟩 **Rewarded Ad**

![Rewarded Ad Example](Assets/RewardedAd.png)

Show Rewarded Ad
Input:

AdUnitID

Callbacks:

OnCompleted → Reward Player

OnFailed → Load/Show Error



---

## 🟨 **Rewarded Interstitial Ad**

![Rewarded Interstitial Example](Assets/RewardedInterstitial.png)

Show Rewarded Interstitial Ad
Callbacks:

OnCompleted

OnFailed



