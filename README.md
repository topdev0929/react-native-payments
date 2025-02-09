# react-native-payments

[![Codeship Status for freeman-industries/react-native-payments](https://app.codeship.com/projects/d6d17e65-23f0-4154-b7ce-33ce59471b08/status?branch=master)](https://app.codeship.com/projects/418096)

# 🚨 Important notice 🚨

This project is no longer maintained. The good news is that the landscape of payments on React Native has massively changed in the last few years. There is still room for this repo to evolve which I'll detail below, but first I would like to direct your attention to well-funded and well-maintained alternatives that will give you fewer grey hairs.

## Stripe

- Stripe has released an official React Native SDK supporting Apple Pay that has a huge team of paid engineers behind it.
- It has also been included in the [Expo managed environment](https://docs.expo.dev/versions/latest/sdk/stripe/), which means it works on Expo Go. Huge achievement.
- For a bug free experience and easy integration I strongly recommend you use [@stripe/stripe-react-native](https://github.com/stripe/stripe-react-native) on any new projects.
- More information and discussion in this issue: https://github.com/naoufal/react-native-payments/issues/335

# Introduction

Welcome to the best and most comprehensive library for integrating payments like Apple Pay and Google Pay into your React Native app.

This library is designed to be fully compatible with React Native 0.61 and onwards.

<div>
<img width="200px" src="https://user-images.githubusercontent.com/1627824/27758096-9fc6bf9a-5dc1-11e7-9d8f-b2d409302fc7.gif" />
<img width="200px" src="https://user-images.githubusercontent.com/1627824/30039983-d75d1b3e-91d8-11e7-9ac9-71d2ed12958c.png" />
</div>

# Installation

```
npm install --save react-native-payments
```

You'll need to autolink on each platform:

### Android

```
npx jetify
```

### iOS

```
cd ios
pod install
```

# Guides

## Example projects

- [iOS](https://github.com/freeman-industries/react-native-payments-example-ios)

## API Spec

Down below we have a detailed specification for PaymentRequest and instructions for configuring Apple Pay and Google Pay, which is hopefully enough to get you started.

We also have some legacy example projects in the `examples` directory that will be rewritten soon and linked above.

Bear with us while we organize things a bit.

# Roadmap

## Completed

- Apple Pay Stripe

## Completed, untested

- Apple Pay Braintree
- Google Pay (Stripe, Braintree)
- Web

## In progress

- Stripe: Payment Intents (for SCA)
