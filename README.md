# Public Speaking Dashboard

<div style="padding-left: 20px;"> 
Public Speaking Dashboard is an open-source public speaking tool. 
</div>
<div style="padding-left: 20px;"> 
Please feel free to copy and use the source code. Also, please feel free to remix and experiment. 
</div>
<div style="padding-left: 20px;"> 
---

[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
---

Find instructions below for cloning your own instance of Public Speaking Dashboard. 

</div>


<details>
<summary><h2 style="display: inline-block;">✨ Getting Started: Create Your Own Instance on Netlify</h2></summary>

<div style="padding-left: 20px;">

This guide will walk you through the steps for setting up your own instance of Public Speaking Dashboard on Netlify.

<h3 style="display: inline-block;">1. **Create a Mistral AI Account**</h3>

<ul style="list-style-type: disc;">
<li><strong>Create an account:</strong> [Mistral AI](https://mistral.ai/)</li>
<li>This will be the AI "back end" of your application.</li>
<li><strong>Generate a Mistral AI API Key:</strong> [Instructions](https://docs.mistral.ai/getting-started/quickstart/#account-setup) </li>
<li>Store this key in a safe place.</li>
<li><strong>Important Note:</strong> Mistral is a "pay as you go" service, meaning that everytime a user runs the app, it will result in a charge to your Mistral account. Share the link only with intended audiences. </li>
</ul>
<h3 style="display: inline-block;">2. **(Optional) Create a DeepGram Account**</h3>

<ul style="list-style-type: disc;">
<li><strong>Create an account:</strong> [DeepGram](https://deepgram.com/)</li>
<li>This is for voice transcription on Android mobile devices (transcription will not work on Android without this service)</li>
<li><strong>Generate a DeepGram API Key:</strong> [Instructions](https://developers.deepgram.com/docs/create-additional-api-keys)</li>
<li>Store this key in a safe place.</li>
<li><strong>Important Note:</strong> The way that Public Speaking Dashboard is configured, this API key is exposed to whoever has access to the the App when it is deployed on Netlify. The DeepGram service is free, but, even so, share the link only with intended audiences. </li>
</ul>

<h3 style="display: inline-block;">3. **GitHub Account**</h3>

<ul style="list-style-type: disc;">
<li><strong>Create an account:</strong> [GitHub](https://github.com/)</li>
<li>This gives you access to the Public Speaking Dashboard source code.</li>
</ul>
</div>
</details>


<details>
<summary><h2 style="display: inline-block;">🚀 Running Locally</h2></summary>

<div style="padding-left: 20px;">

This app is built with Vue.js and requires Node.js 16.

<h3 style="display: inline-block;">1. **Create a `.env` File**</h3>
In the app's root directory, create a `.env` file with:
VUE_APP_ROOT_API2=yourMistralAPIKey
VUE_APP_ROOT_API3=yourDeepGramAPIKey

<h3 style="display: inline-block;">2. **Project Setup**</h3>
`npm install`

<h3 style="display: inline-block;">3. **Development**</h3>
`npm run serve`

<h3 style="display: inline-block;">4. **Production**</h3>
`npm run build`

<h3 style="display: inline-block;">5. **Linting**</h3>
`npm run lint`


For configuration details: Vue CLI Configuration

</div>
</details>

<div style="padding-left: 20px;">

# [Attribution Credits and Dependencies for Public Speaking Dashboard](https://raw.githubusercontent.com/PublicSpeakingDB/PSD/main/package-lock.json)
</div>

