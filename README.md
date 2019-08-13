# fama-french-visualization
### Background Info: 
Eugene Fama, Kenneth French, and Mark Carhart came up with a model that
explain a firm’s/portfolio’s return based on 4 factors:
1. Value (how cheap it is)   
	measured by High Minus Low (HML)
	- Price to Book ratio (market cap / net book value)
	 where net BV = Total Assets - Total Liabilities
	- supposedly, firms with high P/B (value stocks) tend to outperform 
	those with lower P/B
2. Size
	measured by Small Minus Big (SMB)
	- market capitalization
	- small cap stocks tend to outperform large stocks
3. Momentum
	- measured by Up Minus Down (UMD), stock price
	- winners will tend to win, and losers will tend to lose
4. Sensitivity of market’s return to firm/portfolio return

### Project Overview:
This project attempts to visualize the 4-factor model. 

### Functionality
	- users can type in the name of a publicly listed company into a search bar
	- a graph will appear showing the breakdown of how each factor affects the
	portfolio/firm
	- there are options/buttons to toggle between different graphs/visualizations

### Wireframe
![wireframe1](https://i.imgur.com/xnKEJJQ.png "wireframe 1")
![wireframe2](https://i.imgur.com/viE1lBW.png "wireframe 2")


### Technologies Employed
- Vanila JavaScript
- D3 for data mapping
- Webpack
- HTML/CSS


### MVPS
- 1 Search Bar. user can type in the name of a company
- 2 Main Graph- displays breakdown of each factor
- 3 other graphs- users can toggle between different graph types


### Development Timeline

Day 1:
- review D3 Tutorial
- complete skeleton setup and basic page
- complete wireframes for different graphs
- find correct data/API
- start search bar

Day 2:
- search bar

Day 3:
- create Main graph

Day 4:
- create graph 2

Day 5:
- create graph 3

BONUS
- find new way to visualize data
