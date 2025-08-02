# DS-Capstone-2025
This repository was created to capture the following required deliverables for the DS Capstone course for 2025 are being submitted as part of this repository.
1. The Project Implementation
2. The Proof of Testing
3. All Stocks - All Output

# Project Implementation
Two files have been uploaded for this portion - capstone_code.ipynb and capstone_code.py. The .py file is meant to be the complete code for the project (i.e. all data extraction and processing, all code for the main reinforment learning algorithm, and all code for the baseline model implementations). It is provided if the file viewer wishes to download it and run. The second file provided contains the exact same code but in the form of a "python notebook" (ipynb file). This contains both the code itself and the output from running each segment of the code. The captured output shows all of the exact numbers and findings documented in the final presentation paper to be submitted to the professor. 

## Specific Instructions for running the project implementation code
As detailed in the final paper, the code is tested on 3 stocks - AAPL, PLUG, and RIOT. The baseline model code sections (i.e. the random guessing code, the buy/hold code, and the random forest code) will product the results for all 3 symbols at once. However, due to some issues I was having with the reinforcement learning segment of the code, I ended up implementing the RL section in such a way that it must be run one symbol at a time. Thus if the user runs the RL code and wishes to run on a different one of the three stocks, the user will need to update the RL function calls to have the different stock as an input (e.g. change "AAPL" to "PLUG" where the function is called). Because the RL code outoput in the .pynb file only contains the the output of the latest stock tested, a separate file titled "All Stocks - All Output" will be provided so the user can easily view all of the numbers described in the final paper.

# Proof of Testing
Similar to the Project Implementation, both the .py file and .ipynb file are provided - the code is identical in both files but the .py file is provided if the user wishes to easily run the code and the .ipynb file is provided if the user wishes to see the exact output from running the code.

# All Stocks - All Output
This is just a supplementary file that only contains the results of all 3 stocks on all trading algorithms used in this project (this includes both the RL runs and the baseline model runs).
