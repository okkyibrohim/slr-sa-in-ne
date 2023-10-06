# Sentiment Analysis for the Natural Environment: a Systematic Review

## About this repository
This repository provides the scraper code for scraping paper metadata and its result including the annotated version for each stage as the complement of our sentiment analysis in the natural environment topics survey paper that has been accepted and will be published in ACM Computing Surveys (https://dl.acm.org/journal/csur).

## About the scraper code and its result
To use the code to scrape and filter paper metadata following the Kitchenham framework as we did in our paper, use the `Python notebook (ipynb)` files in the `code_and_paper_metadata` folder. The flow of using those codes is explained in our paper. For the scraping and filtering result, see the `.xlsx` files in that folder. Before running the code, please install the requirement first, simply run `$ pip install -r requirements.txt` in your virtual environment. The code provided in this repository is the code we used when we conducted the systematic review paper, which may not have been efficient in some aspects since at that time our goal was only focused on getting and filtering paper metadata following the Kitchenham framework. For the wrapped version and easier to use, please refer to the KitchenScrap repository (https://github.com/okkyibrohim/kitchenscrap).

## About the annotated paper metadata
To see how we annotate the paper metadata for each selection stage following the Kitchenham guideline, please see the `.xlsx` files in the `annotated_paper_metadata` folder. For the stage explanation including its relevant/decision criteria, please read them in our paper.

## More detail
If you want to know more about the flow of using the code and the complete survey paper result, please read them in our paper here: https://dl.acm.org/doi/abs/10.1145/3604605.

## Citation
The code and the data in this repository can be used for free, but if you want to publish a paper/publication using this code/data, please cite this publication:
**Muhammad Okky Ibrohim, Cristina Bosco, and Valerio Basile. 2023. Sentiment Analysis for the Natural Environment: a Systematic Review. *ACM Computing Surveys*.** (Every paper template may have different citation writing. For LaTex users, please see `citation.bib`.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
