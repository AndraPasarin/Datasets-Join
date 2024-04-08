# Datasets-Join

We are given three CSV files that contain information about the same companies, but the data comes from different sources:

- **Google dataset** with the following columns: address, category, city, country code, country name, name, phone, phone country code, raw address, raw phone, region code, region name, text, zip code, domain.
- **Facebook dataset** with the following columns: domain, address, categories, city, country code, country name, description, email, link, name, page type, phone, phone country code, region code, region name, zip code.
- **Website dataset** with the following columns: root domain, domain suffix, language, legal name, main city, main country, main region, phone, site name, TLD, category.

The objective is to create a fourth dataset that includes all the information from the three datasets mentioned above, with greater accuracy in each column.

I will approach this problem by following some steps:

- read the datasets
- preprocess datasets to convert all values to a basic format
- explore the data and understand what columns are important for the merge
- join the datasets
- evaluate the method used
