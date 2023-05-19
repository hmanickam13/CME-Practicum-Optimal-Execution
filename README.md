# CME-Practicum-Optimal-Execution

## Description
This paper presents a comprehensive solution for the efficient liquidation of large orders in a fixed time-period while minimizing losses and achieving optimal liquidation prices. The challenge of liquidating orders that are significantly larger than the average trading volume is addressed through the development of a trading strategy based on machine learning techniques. The strategy utilizes a predictive model trained on parameters such as Net-buy, Multilevel Order Flow Imbalance (MLOFI), and Mean Reversion Lag to forecast the next second's price change (∆𝑃). The algorithm leverages these predictions to make informed trading decisions. The participation rate and replenishment rate act as governing constraints during the trading process. Additionally, a test harness is introduced to simulate a reactionless market environment for algorithmic trading and gradual replenishment of orders. The proposed solution is evaluated using a large dataset of high precision order book data for the Treasury bond futures for the 10-year Treasury Note over a two-month period. The primary objective is to design a trading strategy that effectively manages both volume and slippage to optimize overall liquidation prices. The results highlight the systematic approach employed to address the complexities of liquidating large orders in a dynamic market environment.

## Contents
1. Jupyter Notebook:<br>
This file contains all the functions which were creeated and used for this project/paper.

2. Final Presentation:<br>
This is the presentation my team and I presented in the Practicum Competition organized by the Financial Engineering Department at UIUC.

Contact me for further informtion or if you want access to the full 40 page final report