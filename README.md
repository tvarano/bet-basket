# bet-basket

## Submodule information
This repo is split into several submodules, segmenting functionality. 
- [basket](https://github.com/tvarano/basket/) is the location of the Solidity smart contract powering this application. All Dapp-focused code is there.
- [basket-frontend](https://github.com/tvarano/basket-frontend) is the location of all frontend code.
- [basket-scraper](https://github.com/tvarano/basket-scraper) holds the Python code for scraping odds of matches from sites and hosting them in an API.

## Information for devs: 
To clone this repo, run `git clone --recursive https://github.com/tvarano/bet-basket.git`. All the submodules will be cloned from their proper locations. 
When working on a submodule, you can edit, branch, and commit as normal. Make sure not to push to this repo directly (if you run `git remote -v` and it shows this repo, 
go into the child directory). This repo is just a collection of submodules, and code should not be directly committed here. When updating this repo (pointing submodules to 
correct locations) make sure the refs are on their respective correct branches (likely master). You can branch this entire repo if needed, but it isn't necessary so long as 
commits are in the right place.

Keep track of progress by sticking to our [Project](https://github.com/tvarano/bet-basket/projects) and [Milestone](https://github.com/tvarano/bet-basket/milestones) timelines.
Submit any issues or todos [here](https://github.com/tvarano/bet-basket/issues) and assign to proper milestones, labels, and projects.
