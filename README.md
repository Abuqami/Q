# Lahjah [](language,png)
# Team Members
| Name | Role |
|---|---|
| Abdulrahman Albaqami | Idea & Dataset, ML, DL Deployment |
| Raghad Ali | Idea & Dataset ,ML, DL, Data Cleanse |
| Abdullah Alturki | ML, Data Cleanse, Dashboard |
| Saeed Alqahtani | EDA, Presentation, ML |

# Introduction
Natural language processing is one of the most difficult fields, as it deals directly with text, and it is difficult for a computer to classify text with multiple classifications.
This field is considered to be much more difficult in Arabic than in other languages, due to the great difference in Arabic dialects, even from city to city, or from country to country.
Therefore, we decided to create a predictive model that identifies the input dialect by entering the text.

## Dataset Overview 📍
This dataset contains text and dialect labels for 10,000 Arabic sentences. The sentences are from different Arabic dialects, including Egyptian, Levantine, Maghrebi, and Gulf. The labels are the 18 Arabic dialects.

The dataset was created by AIM Technologies, a company that develops Arabic natural language processing technologies. The data was collected from a variety of sources, including social media, news articles, and literature.


## Proposed Algorithms  📋
1. LinearSVC
2. LogisticRegression
3. RNN- GRU


## Final results 📋
The following table summarize the final results for each model
| ML Model                 | R-squared| 
|-----------------------|----------|
| LinearSVC  | 0.76   |
| LogisticRegression| 0.73    | 
| RNN- GRU | 0.71   | 

##  Conclusion 📋
In conclusion, we developed a dialect detection model for the Arabic language. The model was trained on a dataset of 150000 Arabic sentences and achieved an accuracy of 76% on the test set. The model was able to overcome the challenges of high variability of Arabic dialects and lack of large datasets by using data augmentation and transfer learning techniques.
 
