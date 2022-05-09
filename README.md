# Team Blind Review dataset

![GitHub repo size](https://img.shields.io/github/repo-size/HarshCasper/Blind-App-Reviews)
![GitHub contributors](https://img.shields.io/github/contributors/HarshCasper/Blind-App-Reviews)
![GitHub stars](https://img.shields.io/github/stars/HarshCasper/Blind-App-Reviews?style=social)
![GitHub forks](https://img.shields.io/github/forks/HarshCasper/Blind-App-Reviews?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/harsh_casper?style=social)

## About the dataset

[Team Blind](https://www.teamblind.com/) is a professional's anonymous social networking platform. Work email-verified professionals can connect with their coworkers and other professionals by holding conversations on various topics, like compensation, work-life balance, pros/cons, and their overall opinion about their workplace. 

According to a [Fortune article](https://fortune.com/2022/04/15/social-network-blind-careers-return-to-office-great-resignation/):

> On the platform, employees talk openly about pay transparency and seek career advice. The forum also has job postings, as part of the  [Talent by Blind](https://www.talentbyblind.com/)  recruiting portion of the app. But they also make more honest and frustrated [statements](https://fortune.com/2022/04/04/apple-return-to-office-employees-threaten-quit-hybrid-work/)  about how they disagree with company culture.

According to the above article, an average Blind user is `ambitious, independent, and direct` and says that the `users are set apart by their questions about how they should advance their careers.` Thus it becomes more plausible to understand the various reviews that employees of particular tech companies have shared about their work over the dataset.

The Blind App Dataset is a dataset of reviews of over 25 companies, distributed across tech & consulting, and what their employees think about their workplace. The dataset covers the reviews of employees ever since Blind App was launched till May 8, 2022, when we generated this dataset. It covers an overall rating, description, pros, cons, author information, and their resignation reason (if they are a former employee).

The various companies covered in this dataset along with their number of reviews are:

|Company      |Review size|
|-------------|-----------|
|Adobe        |954        |
|Airbnb       |515        |
|Amazon       |9903       |
|Apple        |1797       |
|Atlassian    |458        |
|Bloomberg    |1116       |
|Bytedance    |688        |
|Cisco        |1488       |
|Coinbase     |305        |
|Deloitte     |1047       |
|Goldman Sachs|897        |
|Google       |5315       |
|IBM          |1247       |
|Intel        |1227       |
|Intuit       |785        |
|Meta         |1680       |
|Microsoft    |5830       |
|Netflix      |288        |
|Oracle       |1469       |
|SAP Labs     |822        |
|Salesforce   |1732       |
|Stripe       |496        |
|Twitter      |685        |
|Uber         |1679       |
|Walmart      |1377       |

The data is available in a CSV and a JSON file. Each review has a `Rating`, `Description`, `Pros`, `Cons`, `Author Info` & `Resignation Reason`. This dataset can be used to answer questions such as:

- What is each company's rating, and how do reviews differ across various rating levels?
- What are the main topics discussed for each company when it comes to Pros versus Cons?
- What key aspects make a company good or bad across various factors (like work-life balance, management, compensation)?
- What are the main reasons for former employees resigning from a company?
- What are the main factors from which a prospective employee should choose a particular company?

The dataset has been scraped from [Team Blind](https://www.teamblind.com/), and we used individual company reviews to develop the dataset. You can navigate to any specific company directory and check out the reviews on the original company-specific forum. Given that the data is scraped from Blind, all data attribution rests with them and the specific authors (who are anonymous at the moment). 

## Using the dataset

The dataset can be cloned using `git`:

```sh
git clone git@github.com:HarshCasper/Blind-App-Reviews.git
```

After a successful clone, you can use the dataset to load the individual CSV/JSON file of a particular company and start the analysis. Alternatively, you can download the ZIP of the entire repository, albeit without the version control available.

You can also use the dataset over [Kaggle](https://www.kaggle.com/datasets/harshcasper/blind-app-company-reviews). Install the Kaggle library using `pip install kaggle` and create a new API token JSON file and save it over `~/.kaggle/` directory. Download the dataset using `kaggle datasets download -d harshcasper/blind-app-company-reviews`.

## Contributing to the dataset

The scrapper engine used to develop the dataset is currently not open-source. However, it will be open-sourced at a later stage. To contribute to the dataset, you may create an [issue](https://github.com/HarshCasper/Blind-App-Reviews/issues) to request new companies to be added to the dataset or the dataset to be updated for existing companies. At a later stage, you can self-generate new datasets using the scrapper engine and submit patches.

To fix existing dataset issues or clean certain areas, feel free to raise a pull request. Follow the [GitHub guide to submit a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to contribute to the sanctity of the dataset. You may also develop Exploratory Data Analysis, Topic Modelling, and other NLP-related analyses with the dataset to create more data-driven insights.

## License

This project uses the following license: [MIT](LICENSE).
