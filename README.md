TechnicalGurujiClone AI

This repository contains an AI model trained on a large dataset of smartphones, replicating the knowledge and conversational style of Technical Guruji. It provides insights into various phone models, their specifications, and market trends, offering detailed phone reviews and suggestions.

Quick Guide
Follow this guide to set up the AI model on your machine.

Installation
Install the Gaia Node by running the command below:

curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Set Up Environment
After installation, run the command printed on the terminal to set up the environment path. This command will start with source to configure your environment.

Initialize Configuration
Update the configuration to use the phone dataset:

gaianet init --config https://raw.githubusercontent.com/your-repo/phone-dataset-config.json

Run the Node
Start the node and interact with the Technical Guruji AI:


gaianet start

Features
Provides phone reviews and recommendations based on the latest models.
Mimics the conversational style of Technical Guruji.
Offers detailed insights into phone specifications and features.
Usage
Once the node is running, interact with the AI by asking questions about smartphones, upcoming models, and phone comparisons.
