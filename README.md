# bitcoinRNN.template
This template shows basic usage of Metis Machine curated data, 3rd party data, and PyTorch framework to implement a recurrent deep learning model to predict the "closing price" of bitcoin.

Discliamer: Obviously, this model is intended to get you started working with neural networks on the Skafos platform. DO NOT use this example model to "predict" the price of Bitcoin, or any other cryptocurrency asset. Using only past observations and Google trend data leaves lots of room for improvement! See full legal disclaimer [here](https://docs.metismachine.io/docs/predict-the-price-of-cryptocurrency-in-10-minutes).

## Dependencies
User must aqcuire an API key from [quandl](https://www.quandl.com/) if they wish to use. Otherwise, user can provide their own coin data.

Set the API key using the skafos CLI:
`skafos env QUANDL_KEY --set <API KEY>`

## Model Tuning
The project represents the bare bones of what it takes to build a sophisticated deep learning model. More hyperparameter tuning, feature engineering, and optimizer testing will improve the model's performance.




### Legal Disclaimer 

NOTHING IN THIS SITE CONSTITUTES OR SHOULD BE CONSTRUED AS PROVIDING FINANCIAL, INVESTMENT, BROKERAGE, TAX, ACCOUNTING, OR LEGAL ADVICE. 


**General.** You understand and acknowledge that there is a very high degree of risk involved in trading securities and, in particular, crypto assets. 


THE MODEL IS PROVIDED “AS IS.” WE AND OUR AFFILIATES AND LICENSORS MAKE NO REPRESENTATIONS OR WARRANTIES OF ANY KIND, WHETHER EXPRESS, IMPLIED, STATUTORY OR OTHERWISE REGARDING THE MODEL, THE SERVICE OR THE THIRD PARTY CONTENT, INCLUDING ANY WARRANTY THAT THE MODEL, THE SERVICE OR THIRD PARTY CONTENT WILL PRODUCE RESULTS OR PROFITS OR WILL ACHIEVE ANY PARTICULAR PURPOSE, WILL BE UNINTERRUPTED, ERROR FREE OR FREE OF HARMFUL COMPONENTS, OR THAT ANY CONTENT, INCLUDING YOUR CONTENT OR THE THIRD PARTY CONTENT, WILL BE SECURE OR NOT OTHERWISE LOST OR DAMAGED. EXCEPT TO THE EXTENT PROHIBITED BY LAW, WE AND OUR AFFILIATES AND LICENSORS DISCLAIM ALL WARRANTIES, INCLUDING ANY IMPLIED WARRANTIES OF MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE, NON- INFRINGEMENT, OR QUIET ENJOYMENT, AND ANY WARRANTIES ARISING OUT OF ANY COURSE OF DEALING OR USAGE OF TRADE.


**Financial and Other.**
NEITHER METIS MACHINE LLC., INDIVIDUALLY, NOR ITS PLATFORM INCLUDING, BUT NOT LIMTED TO SKAFOS, WEBSITE, NOR ANY OF ITS OFFICERS, EMPLOYEES, REPRESENTATIVES, AGENTS, INDEPENDENT CONTRACTORS, OR SUBCONTRACTORS ARE, IN SUCH CAPACITIES, LICENSED FINANCIAL ADVISORS, REGISTERED INVESTMENT ADVISORS, OR REGISTERED BROKER-DEALERS . METISMACHINE.com, SKAFOS AND THIS MODEL ARE NOT INTENDED AS SECURITIES OR CRYPTO ASSET BROKERAGE, INVESTMENT, TAX, ACCOUNTING OR LEGAL ADVICE.


METIS MACHINE, LLC., INCLUDING ITS OFFICERS, DIRECTORS, OWNERS, EMPLOYEES, AGENTS, OR AFFILIATES MAKES NO REPRESENTATIONS OR WARRANTIES ABOUT THE ACCURACY OR COMPLETENESS OF THE INFORMATION PROVIDED IN CONNECTION WITH THE SERVICE. BY YOUR CONTINUED USE OF THE MODEL, YOU AGREE THAT NO INFORMATION PROVIDED BY METIS MACHINE, LLC, OR ANY OFFICER, DIRECTOR, OWNER, EMPLOYEE, AGENT, OR AFFILIATE THEREOF, IS OR WILL BE RELIED UPON AS SECURITIES BROKERAGE, INVESTMENT, TAX, ACCOUNTING OR LEGAL ADVICE, IS AN OFFER OR SOLICITATION OF AN OFFER TO SELL OR BUY, OR IS AN ENDORSEMENT, RECOMMENDATION OR SPONSORSHIP OF ANY COMPANY, SECURITY OR FUND OR AS ADVICE TAILORED TO YOUR OR ANY MEMBER’S PARTICULAR SITUATION. ANY URL LINKS OR COMPANY NAMES OR TICKER SYMBOLS ARE OFFERED AS A MATTER OF CONVENIENCE AND NOTHING CONTAINED IN THIS AGREEMENT OR IN THE SERVICE CONSTITUTES A SOLICITATION, RECOMMENDATION, PROMOTION, ENDORSEMENT, OR OFFER BY METIS MACHINE, LLC OR ANY OFFICER, DIRECTOR, OWNER, EMPLOYEE, AGENT, OR AFFILIATE, OF ANY PARTICULAR SECURITY, TRANSACTION, OR INVESTMENT.


METIS MACHINE,LLC, OR ANY OFFICER, DIRECTOR, OWNER, EMPLOYEE, AGENT, OR AFFILIATE, MAY HAVE POSITIONS IN THE SECURITIES AND ASSETS MENTIONED AND MAY ENTER AND EXIT SUCH POSITIONS AT ANY TIME AND FOR ANY REASON. THE RISK OF LOSS IN TRADING SECURITIES, OPTIONS, FUTURES, FOREX, AND COMMODITIES CAN BE SUBSTANTIAL AND ARE NOT SUITABLE FOR ALL INVESTORS. YOU MUST CONSIDER ALL RELEVANT RISK FACTORS, INCLUDING YOUR OWN PERSONAL FINANCIAL SITUATION, BEFORE TRADING. YOU ASSUME THE RISK OF ANY AND ALL FINANCIAL INVESTMENTS YOU MAKE. METIS MACHINE, LLC., AND ITS OFFICERS, DIRECTORS, OWNERS, EMPLOYEES, AGENTS, OR AFFILIATES ARE NOT RESPONSIBLE FOR ANY FINANCIAL INVESTMENTS YOU MAKE.


RESULTS VARY AND PAST PERFORMANCE IS NOT INDICATIVE OF FUTURE RETURNS.
