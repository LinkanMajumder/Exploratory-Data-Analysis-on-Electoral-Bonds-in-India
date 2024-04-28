# Exploratory Data Analysis of Electoral Bonds in India

This dataset provides details on transactions involving electoral bonds, a mechanism for anonymous political donations in India, handled by the State Bank of India (SBI). Information includes buyer identities, donation types (individual or firm), and encashment details by political parties.

**Data Exploration**

Jupyter Notebook was used to analyze the data, revealing trends in funding patterns, donor profiles, and transparency in Indian political financing.

**Data Columns**

* **Buyer**: Entity purchasing the electoral bonds.
* **Donor Type**: Classification (individual or firm) assigned to the buyer.
* **Encashment Date**: Date the electoral bonds were redeemed by a political party.
* **Political Party**: Recipient of the donation.
* **Bond Amount**: Face value of the electoral bonds.

**Analysis of Bond Buyers**
![output1](https://github.com/LinkanMajumder/Exploratory-Data-Analysis-of-Electoral-Bonds-in-India/assets/66352815/20ae46b5-6f6d-42e9-83b0-b2cf1e39fe67)

* **Unique Buyers**: 1314 individuals and firms participated in bond purchases.
* **Donor Breakdown**: Firms dominated purchases (938), followed by individuals (365).
* **Average Purchase Amounts**: Firms bought the most on average (₹123,321,425).
* **Top Buyers**:
    * Firm - FUTURE GAMING AND HOTEL SERVICES PRIVATE LIMITED (₹13,680,000,000)
    * Individual - LAKSHMI NIWAS MITTAL (₹350,000,000)
    * 'AGARWAL' Entities - Total purchases of ₹179,082,000

**Analysis of Encashment Data**
![output](https://github.com/LinkanMajumder/Exploratory-Data-Analysis-of-Electoral-Bonds-in-India/assets/66352815/29f18787-9f47-4f2f-ac81-d200d895d35a)


* **Unique Political Parties**: The dataset covers transactions involving 27 political parties.
* **Top Recipient**: BHARATIYA JANATA PARTY received the most donations (₹60,605,110,000).
* **Highest Encashment Day**: May 10, 2019 (total ₹4,116,500,000).
* **Party on Peak Encashment Day**: BHARATIYA JANATA PARTY (₹3,961,500,000)

**Conclusion**

These findings highlight the significant financial activity facilitated by electoral bonds, demonstrating the influence of both buyers and political parties in India's electoral funding system.



The dataset has been sourced from 'https://www.kaggle.com/datasets/newtonbaba12345/electoral-bonds-dataset'.
