# Predict-accident-risk-score-for-unique-postcode-by-swiss-re-MachineHack-
# Overview
Swiss Re is one of the largest reinsurers in the world headquartered in Zurich with offices in over 25 countries. Swiss Re’s core expertise is in underwriting in life, health, as well as the property and casualty insurance space whereas its tech strategy focuses on developing smarter and innovative solutions for clients’ value chains by leveraging data and technology.
# Problem Description
According to IBEF “Domestic automobiles production increased at 2.36% CAGR between FY16-20 with 26.36 million vehicles being manufactured in the country in FY20.Overall, domestic automobiles sales increased at 1.29% CAGR between FY16-FY20 with 21.55 million vehicles being sold in FY20”.The rise in vehicles on the road will also lead to multiple challenges and the road will be more vulnerable to accidents.Increased accident rates also leads to more insurance claims and payouts rise for insurance companies.
In order to pre-emptively plan for the losses, the insurance firms leverage accident data to understand the risk across the geographical units e.g. Postal code/district etc.
In this challenge, we are providing you the dataset to predict the “Accident_Risk_Index” against the postcodes.Accident_Risk_Index (mean casualties at a postcode) = sum(Number_of_casualities)/count(Accident_ID)
# Tasks that participant has to do
The participants are required to predict the 'Accident_risk_index' for the test.csv and against the postcode on the test data.

Then submit your 'my_submission_file.csv' on the submission tab of the hackathon page.

Pro-tip: The participants are required to perform feature engineering to first roll-up the train data at postcode level and create a column as “accident_risk_index” and optimize the model against postcode level.

Few Hypothesis to help you think: "More accidents happen in the later part of the day as those are office hours causing congestion"

"Postal codes with more single carriage roads have more accidents"

Additionally, we are providing you with road network data (contains info on the nearest road to a postcode and it's characteristics) and population data (contains info about population at area level). This info are for augmentation of features, but not mandatory to use.
# For train and test csv download it from
https://machinehack.com/hackathon/predict_accident_risk_score_for_unique_postcode/overview
