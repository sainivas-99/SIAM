# SIAG/FME Code Quest 2023 DeFi & RoboAdvising Challenge

## Introduction
Welcome to my submission for the SIAG/FME Code Quest 2023 DeFi & RoboAdvising Challenge! This coding challenge, sponsored by World Business Chicago and organized by the SIAM Activity Group on Mathematical Finance and Engineering (SIAG/FME), focuses on solving mathematical and financial modeling problems using computational tools. The challenge is dedicated to exploring and implementing solutions related to Decentralized Finance (DeFi) and Automated Asset Management (RoboAdvising).

## Challenge Objectives
The primary objectives of the challenge are:
1. Grasp and code the essential operations of constant product market makers in Python to accurately reproduce the processes of liquidity taking and provision.
2. Implement a liquidity provision strategy across multiple pools that minimizes predefined risk measures and attains a certain investment goal.

## Implementation Details
### Code Structure
My implementation is organized into several Python classes within the `amm` module. These classes model the behavior of liquidity pools, market makers, and the overall simulation environment.

### Implemented Features
I have successfully implemented the following features:
- **Swapping:** The `swap` method accurately simulates the swapping of coin-X for coin-Y and vice versa in the liquidity pools.
- **Minting and Burning:** The `mint` and `burn` methods facilitate the minting and burning of liquidity provider (LP) coins, respecting the LP trading conditions.
- **Swap then Mint and Burn then Swap:** The methods `swap_and_mint` and `burn_and_swap` combine swapping with subsequent minting or burning operations.

### Simulation
The `simulate` method simulates the trading environment based on specified parameters, allowing for the study of LP performance across multiple paths.

## How to Run
To test and run the provided code, follow these steps:

1. Ensure you have Python installed on your machine.
2. Clone this repository: `git clone [repository_url]`.
3. Navigate to the project directory: `cd siag_fme_code_quest_2023`.
4. Run the test notebook: `jupyter notebook test_notebook.ipynb`.

## Results
Check the results and performance metrics in the test notebook. The average performance and standard deviation are computed, providing insights into the effectiveness of the implemented strategy.

## Additional Notes
Include any additional notes or considerations that you think are important for the reviewers to know.

## Contact
If you have any questions or feedback regarding my submission, please feel free to contact me at sainivasnani99@gmail.com

Thank you for considering my submission! Kindly upvote my submission and provide stars to support my work!!
