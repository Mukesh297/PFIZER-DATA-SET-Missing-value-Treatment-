# PFIZER-DATA-SET-Missing-value-Treatment-
# **ABOUT PFIZER:**
Pfizer is one of the world’s leading pharmaceutical companies, founded more than 170 years ago. We specialise with expert therapy in 6 product-portfolios of- Vaccines, Oncology, Internal Medicine, Rare Diseases, Inflammation and Immunology, and Hospitals.

Pfizer-India was established in 1950, and has a rich heritage of 70 years, successfully launching and supporting clinical developments across the country.

# Aim of Case Study:
The ongoing campaigning of API drug development of Pfizer.

To monitor the Drug stability of three Drugs **Diltiazem hydrochloride**, **docetaxel injection**, **ketamine hydrochloride** in a drug development Test.

The stability data comprises of Temperature, pressure and are recorded after an interval of 1 hour everyday and import from Industrial Internet of Things (IIoT) sensors.


==> These data points are thus used to identify the optimal set of values of parameters for the stability of the drugs.

There will be some missing values in every record and thus this missing values is need to manage using various methods.

## **Coulmn Profilling**

As we saw earlier, the dataset has **18 rows** and **15 columns**.

If you notice further, you'll see:
- The columns are `1:30:00`, `2:30:00`, `3:30:00`, ... so on.
- `Temperature` and `Pressure` of each date is in a separate row.

Need to restructure data into A format like `Date | time | Drug_Name | Pressure | Temperature`.