# Macro Econ Agent

![economics](https://img.shields.io/badge/economics-blue?style=flat-square) ![finance](https://img.shields.io/badge/finance-blue?style=flat-square) ![prediction](https://img.shields.io/badge/prediction-blue?style=flat-square)

An agent that monitors central bank releases and predicts market volatility impacts.

## Overview
Macro Econ Agent is an automated intelligence tool designed to bridge the gap between macroeconomic policy and financial market movements. It autonomously tracks updates from major central banks (such as the Fed, ECB, and BoE) to analyze sentiment and policy shifts. By processing high-frequency data releases, the agent provides actionable insights and forecasts regarding potential volatility spikes in global markets.

## Features
*   **Real-time Monitoring:** Automated scraping and API integration for immediate notification of central bank press releases and meeting minutes.
*   **Sentiment Analysis:** Utilizes NLP models tailored for financial terminology to interpret "hawkish" or "dovish" signals.
*   **Volatility Prediction:** Employs statistical models to estimate the impact of specific economic indicators on market variance.
*   **Customizable Alerts:** Configurable thresholds for risk levels, allowing users to receive warnings for high-impact events.

## Installation
Ensure you have Python 3.8+ installed. Clone the repository and install the necessary dependencies using pip:

```bash
git clone https://github.com/username/macro-econ-agent.git
cd macro-econ-agent
pip install -r requirements.txt
```

## Usage
To start the agent and begin monitoring upcoming economic events, run the main execution script:

```bash
python main.py
```

**Example:**
To analyze a specific recent release from the Federal Reserve, you can pass the source flag:
```bash
python main.py --source fed --analyze "latest"
```

## Contributing
Contributions are welcome! If you would like to help improve the prediction models or add support for additional central banks, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](LICENSE).