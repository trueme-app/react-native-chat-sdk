<div style="width:100%">
<div style="width:100%">
	<div style="width:50%; display:inline-block">
		<p align="center">
		<img style="text-align:center" width="180" height="180" alt="" src="https://raw.githubusercontent.com/cometchat-pro/ios-swift-chat-app/master/Screenshots/CometChat%20Logo.png">	
		</p>	
	</div>	
</div>
</br>
</br>
</div>

CometChat Pro enables you to add voice, video & text chat for your website & app.

<a href="https://www.npmjs.com">[![Platform](https://img.shields.io/badge/Platform-Javascript-blue.svg)](#)</a>
<a href="https://www.npmjs.com">[![Platform](https://img.shields.io/badge/Platform-NPM-orange.svg)](#)</a>

# Quick Start

This guide demonstrates how to add chat to a Javascript application using CometChat. Before you begin, we strongly recommend you read the <a href="https://prodocs.cometchat.com/docs/concepts" target="_blank">Key Concepts</a> guide.

## Get your Application Keys

<a href="https://app.cometchat.io" target="_blank">Signup for CometChat</a> and then:

1. Create a new app: Enter a name & hit the **+** button
2. Head over to the **API Keys** section and click on the **Create API Key** button
3. Enter a name and select the scope as **Auth Only**
4. Now note the **API Key** and **App ID**

## Add the CometChat Dependency

### NPM
First, install via npm

```
npm install @cometchat-pro/react-native-chat react-native-cometchat-calling-component@1.2.6 react-native-google-signin@2.0.0 react-native-background-timer@2.1.1 react-native-callstats@3.61.0 react-native-immersive@2.0.0 react-native-keep-awake@4.0.0 react-native-linear-gradient@2.5.6 react-native-sound@0.11.0 react-native-sound@0.11.0 react-native-svg@9.7.1 react-native-svg-transformer@0.13.0 react-native-swipeout@2.3.6 react-native-watch-connectivity@0.2.0 react-native-webrtc@1.75.2 react-native-webview@7.4.1 @react-native-community/netinfo@4.1.5 react-native-calendar-events@github:jitsi/react-native-calendar-events#902e6e92d6bae450a6052f76ba4d02f977ffd8f2 --save
```

or Yarn

```
yarn add @cometchat-pro/react-native-chat react-native-cometchat-calling-component@1.2.6 react-native-google-signin@2.0.0 react-native-background-timer@2.1.1 react-native-callstats@3.61.0 react-native-immersive@2.0.0 react-native-keep-awake@4.0.0 react-native-linear-gradient@2.5.6 react-native-sound@0.11.0 react-native-sound@0.11.0 react-native-svg@9.7.1 react-native-svg-transformer@0.13.0 react-native-swipeout@2.3.6 react-native-watch-connectivity@0.2.0 react-native-webrtc@1.75.2 react-native-webview@7.4.1 @react-native-community/netinfo@4.1.5 react-native-calendar-events@github:jitsi/react-native-calendar-events#902e6e92d6bae450a6052f76ba4d02f977ffd8f2
```

Then, import the `CometChat` object wherever you want to use CometChat

```
import { CometChat } from "@cometchat-pro/react-native-chat" 
```


To learn more, please refer to our Documentation: <a href="https://prodocs.cometchat.com/v2.0/docs/react-native-quick-start">Documentation</a>