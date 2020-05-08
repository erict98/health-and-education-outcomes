# Health and Education Outcomes
Simple independent side-project investigating how the determinants of education influence health outcomes (measured in DALY).
I used explored two types of model: one at the state-level (USA) and one at the country-level (global), and found the features that could be easily obtained for both.
I used the USA model as the training model for the country-level dataset. It ended in failure simply because the USA dataset was much cleaner and did not have missing data compared to the country dataset as well as the fact the USA's outcome is very similar, so the model did not account for much variation.

There are many errors in my analysis, but provides a oppurtune learning experience and practice:
1. Write down objectives so that I know what direction I am heading. It was annoying having to re-adjust my work each time I though of something interesting to add it, so pre-planning or making so that I did not waste time exploring my code again to incorporate new topics is something I will definitely do next time.
2. Standardizing my dataset and ensuring the credibility. Pulling data from different sources meant that there is no clear standard or there was different method for measurement.
3. Validating my data. I think this is the hardest part for me. My statistics courses and machine learning courses did not really teach how to deal with messy data since all the examples taught were very clean and did not require complex validation methods.
