The Lottery Lot
What Makes a Lottery Winner

PROJECT OVERVIEW
Problem Area
The lottery is innately unpredictable and uncertain but the variables at play during the purchase of the lottery ticket could affect the possibility of being a winner. The goal is to identify if there are variables that can skew the lottery in one’s favor or if it is purely random. 
Some challenges are that lotteries are regional, so demographic may skew towards that region (in this case Texas), lack of results if the lottery really is just chance, outliers skewing the data.

Users
- Lottery players
- Lottery retailers
- Lottery companies
- State governments

Proposed Solution
By compiling and finding trends in data of Texas Lottery winners, we aim to pinpoint certain aspects such as:
- Demographic of buyer
- Date and time of purchase
- Location of retailer
- Sales of tickets
By comparing and contrasting these variables we can find most likely traits that make up a lottery winner, providing clues to if distribution of lottery tickets, types of people who buy them make a difference in who wins the lottery.

Impact
The impact that this project has includes:
Having more people win the lottery, more evenly distributing wealth between lottery players
Making the lottery more “equal” by identifying skewing variables
Identify demographics prone to gambling

Data
The analysis employs the dataset of winners of the Texas Lottery from July, 1999 to April, 2025. We will compare the prize won to various variables that could be affected from the type of buyer and the distribution of tickets.

Data Dictionary
| Variable         | Description                                                              | Type        |
| :--------------  | :---------:                                                              | :----       |
| Amount Won       | Amount won from the lottery (any prize, doesn’t have to be jackpot)      | Float       |
| Price of Ticket  | Price of the purchased ticket                                            | Float       |
| US Citizen Flag  | Marks if winner is a US citizen                                          | Categorical |
| City             | City where claimer resides                                               | Categorical |
| State            | State where claimer resides                                              | Categorical |
| County           | County where claimer resides                                             | Categorical |
| Retail Name      | Name of retailer that sold ticket                                        | Categorical |
| Scratch or Draw  | Identifies lottery as a draw game (including name) or a scratch-off      | Categorical |
| Date Ticket Sold | The date the ticket was sold                                             | Date        |