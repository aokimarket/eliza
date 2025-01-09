# AokiMarket Powered by ElizaOS 🤖

<div align="center">
  <img src="https://pictr.com/images/2025/01/09/x1byDc.jpg" alt="AokiMarket Eliza Banner" width="100%" />
</div>


<div align="center">

🎯 [Website](https://aokimarket.xyz/) | 📖 [Documentation](https://elizaos.github.io/eliza/)

</div>

## 🌍 README Translations

[中文说明](./README_CN.md) | [日本語の説明](./README_JA.md) | [한국어 설명](./README_KOR.md) | [Français](./README_FR.md) | [Português](./README_PTBR.md) | [Türkçe](./README_TR.md) | [Русский](./README_RU.md) | [Español](./README_ES.md) | [Italiano](./README_IT.md) | [ไทย](./README_TH.md) | [Deutsch](./README_DE.md) | [Tiếng Việt](./README_VI.md) | [עִברִית](https://github.com/elizaos/Elisa/blob/main/README_HE.md) | [Tagalog](./README_TG.md) | [Polski](./README_PL.md) | [Arabic](./README_AR.md) | [Hungarian](./README_HU.md) | [Srpski](./README_RS.md)

## 🚩 Overview

<div align="center">
  <img src="https://pictr.com/images/2025/01/09/x1b3Jf.png" alt="Eliza Diagram" width="100%" />
</div>

## ✨ Aoki Market: The Future of Prediction of the Best AI Agents

- Prediction is no longer a gamble; it's the engine of progress. In a world of rapid change, accurate foresight is crucial for businesses, governments, and individuals alike. Built on ElizaOS, Aoki Market reimagines prediction, transforming it from a simple guess to a powerful tool for driving innovation, informed decision-making, and societal evolution.

## ✨ Aoki Market empowers everyone to harness the predictive power of AI.

- User-Friendly and Accessible: Our intuitive platform allows anyone, regardless of technical background, to effortlessly create prediction events and identify the most promising AI agents.
- AI-Driven Accuracy: Aoki Market leverages cutting-edge AI algorithms to analyze vast datasets, identify emerging trends, and provide personalized insights tailored to individual needs.
- Unparalleled Reliability: Powered by the robust Pyth Oracle, Aoki Market ensures real-time, authoritative data accuracy, delivering unparalleled precision and reliability in all predictions.

## ✨ Aoki Market fosters a vibrant and engaged community.

- Real-Time Social Interaction: Engage in dynamic discussions with other users through text, voice, and video. Share insights, learn from experienced traders, and collaborate to refine predictions.
- Personalized AI Agents: Aoki Market develops personalized AI agents that learn from your unique trading habits and preferences, providing customized support and enhancing your predictive accuracy.


## ✨ Aoki Market: A Global Consensus Experiment

- By combining the collective wisdom of a global community with the power of advanced AI, Aoki Market transforms prediction into a powerful tool for societal advancement. This decentralized framework fosters continuous innovation, allowing information to evolve and adapt in real-time.




## Video Tutorials

[AI Agent Dev School](https://www.youtube.com/watch?v=ArptLpQiKfI&list=PLx5pnFXdPTRzWla0RaOxALTSTnVq53fKL)

## 🎯 Use Cases

- 🤖 Chatbots
- 🕵️ Autonomous Agents
- 📈 Business Process Handling
- 🎮 Video Game NPCs
- 🧠 Trading

## 💰 If you plan to launch a token

This framework is the number one open source project on github, we are enabling the next generation of human-machine interface but we still need your help to ensure the code is of the utmost quality with response rapid to critical issues that will affect our builder community at large.

To ensure sustainable development and continued innovation, we ask contributions of 5-10% of initial token distributions from successful launches.

All contributions are publicly tracked on-chain and used exclusively for ecosystem development.

### ⚠️ Don't forget to tip the big guy 10%: ⚠️
[AM84n1iLdxgVTAyENBcLdjXoyvjentTbu5Q6EpKV1PeG](https://solscan.io/account/AM84n1iLdxgVTAyENBcLdjXoyvjentTbu5Q6EpKV1PeG)

## 🚀 Quick Start

### Prerequisites

- [Python 2.7+](https://www.python.org/downloads/)
- [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.

### Use the Starter (Recommended)

```bash
git clone https://github.com/elizaos/eliza-starter.git
cd eliza-starter
cp .env.example .env
pnpm i && pnpm build && pnpm start
```

Once the agent is running, you should see the message to run "pnpm start:client" at the end.
Open another terminal and move to same directory and then run below command and follow the URL to chat to your agent.

```bash
pnpm start:client
```

Then read the [Documentation](https://elizaos.github.io/eliza/) to learn how to customize your Eliza.

### Manually Start Eliza (Only recommended if you know what you are doing)

```bash
# Clone the repository
git clone https://github.com/elizaos/eliza.git

# Checkout the latest release
# This project iterates fast, so we recommend checking out the latest release
git checkout $(git describe --tags --abbrev=0)
```

### Start Eliza with Gitpod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/elizaos/eliza/tree/main)

### Edit the .env file

Copy .env.example to .env and fill in the appropriate values.

```
cp .env.example .env
```

Note: .env is optional. If you're planning to run multiple distinct agents, you can pass secrets through the character JSON
Note: .env is optional. If you're planning to run multiple distinct agents, you can pass secrets through the character JSON

### Automatically Start Eliza

This will run everything to set up the project and start the bot with the default character.

```bash
sh scripts/start.sh
```

### Edit the character file

1. Open `packages/core/src/defaultCharacter.ts` to modify the default character. Uncomment and edit.

2. To load custom characters:
    - Use `pnpm start --characters="path/to/your/character.json"`
    - Multiple character files can be loaded simultaneously
3. Connect with X (Twitter)
    - change `"clients": []` to `"clients": ["twitter"]` in the character file to connect with X

### Manually Start Eliza

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```

### Community & contact

- [GitHub Issues](https://github.com/elizaos/eliza/issues). Best for: bugs you encounter using Eliza, and feature proposals.
- [Discord](https://discord.gg/ai16z). Best for: sharing your applications and hanging out with the community.
- [Developer Discord](https://discord.gg/3f67SH4rXT). Best for: getting help and plugin development.

## Contributors

<a href="https://github.com/elizaos/eliza/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=elizaos/eliza" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=elizaos/eliza&type=Date)](https://star-history.com/#elizaos/eliza&Date)
