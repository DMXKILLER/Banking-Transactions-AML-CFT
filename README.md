#
Datasets of Banking Transactions with basis on Anti-Money Laundering and Terrorism Financing
============================================

This repository presents a description of the datasets available on banking systems that can be used to classify and identify money laundering and terrorism financing within payment networks and banking systems. The datasets provide a conglomerate of transactional data (in motion) as well as client profiles (static). In addition to this, it references a specific plug in point for the National Payment Systems of a Central Bank within Eastern Africa. If interested in contributing to this repository for terror reports or open investigations within the region of East and Central Africa, reach me at dnmakiya@fc.ul.pt



[__Client Profile Data__](#tie)
This contains datapoints specific to the Know your Customer (KYC) and Customer Due Diligence (CDD) requirements with respect to the Financial Action Task Force (FATF regulations). Such datapoints include the type of client(individual/natural person), customer segment, Political exposure, economic activity, nature of the client Age of client etc.


[__Transactionary__](#tie)
This contains datapoints specific to the occurence of a singular transaction. They are unique at the occurence of each transaction like the amount, currency, income source/purpose of funds, geographical location, intermediary banks etc.


[__National Risk Points__](#tie)
The World Bank/IMF have provided a cross-border methodology for performing Risk assessments across specific nations where there is adoptation of the [__FATF regulations/guidelines__](papers/Risk_Assessment_IMF.pdf). In East and Central Africa, The Eastern and Southern Africa Anti-Money Laundering Group [__ (ESAAMLG) __] (https://www.esaamlg.org/index.php/about) operates as a key information exchange hub within the region. The National Risk Assessment reports within the member bodies of ESAAMLG provide the ideal datapoints from the qualitative Risk assessment going back a period of 4 years. The [__Risk Assessments__](papers/Kenya_NRA_Report_Public_Version_Final_For_Publication_January_2022.pdf)  within the member bodies provide risk classifications on a scale of 0-1 on the basis of given industries/sectors, compliance levels existence of controls and etc.

<br><br>

1. 
a) Client Profiling

| Dataset                           | Description   | Language | Size | Year | Citation - Use Cases | Availability | 
| --------------------------------- |:-------------:| :-------:|------|------|------|------| 
| [Bank_Datamart](datasets/Bank_Datamart-master.zip)| The dataset conists of 7 asc with the account, client, card, dispositions, location, loans and orders. It additionally has a the produced csv file with the general motion entries combining all key elements of the client profiles into one flow, including the transactional balanaces | English |3MB| 2018 | [Datamart for a Bank based Bank based on different datasets containing information about customers. The datamart is customer-centric and it was created using joining functions. It can be used to build a clusters for unusual/suspicious client bases](https://github.com/alejazllano/Bank_Datamart)| Public Access |
| [Customer Churn Based Data](datasets/Churn_Modelling.csv)| Dataset of a bank with 10,000 customers measuring key attributes of the customer spanning with over 14 columns. The dataset takes the sampleset with specific attributes of (name, credit score, grography, age, tenure, balance, numOfProducts, credit card, active member, estimated salary, exited, etc.). | English | 668kB | 2019 | [The original idea behind the dataset was to reate a geographic segmentation model to tell which of the customers are at highest risk of leaving the bank. However, the dataset can purposively be used to build customer clusters on the bases of risk in relation to Terror Financing and Money Laundering.](https://github.com/amit21AIT/Artifitial-Neural-Network-Churn-Modeling)| Public Access |
| [Financial Institution in Mexico] | Restricted | English | -- | 2022 | [Detection of Shell Companies. This dataset is not Publicly available. To access it, a request should be done to the Authors as provided in the link; Jose-de-Jesús Rocha-Salazar (jorocha@ucm.es)](papers/Detection_of_shell_companies_in_financial_institutions_using_dynamic_social_network.pdf)| Restricted |

b) Terror Watchlists 

| Dataset                           | Description   | Language | Size | Year | Citation - Use Cases | Availability | 
| --------------------------------- |:-------------:| :-------:|------|------|------|------| 
| [Global Terrorism Data](datasets/Global_Terrorism-START_data.zip)| The Global Terrorism Database™ (GTD) is includes information on terrorist events around the world from 1970 through 2020. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 200,000 cases. The dataset has over 135 independent variables reflective of | English |28.6MB| 2020 | [The systematic data on domestic and international terrorist incidents can be used to map the influx/flow of funds across given regions with the confirmation of occurrence of terror incidents. A correlation through Exploratory Data Analysis can be performed based on transactional data with Client Profiles. The dataset provides a confirmation of over 200,000 cases across the globe ](https://www.start.umd.edu/gtd/)| Public Access |
| [High-risk and other monitored jurisdictions ](https://www.fatf-gafi.org/publications/high-risk-and-other-monitored-jurisdictions/?hf=10&b=0&s=desc(fatf_releasedate))| WebPage | English | -- |--| 2022 | [FATF, 2022](https://www.fatf-gafi.org/publications/high-risk-and-other-monitored-jurisdictions/documents/increased-monitoring-march-2022.html#zimbabwe)| Public Access |
| [Jurisdictions Under Increased Monitoring - "Grey list"](https://www.fatf-gafi.org/publications/high-risk-and-other-monitored-jurisdictions/documents/increased-monitoring-march-2022.html#zimbabwe)| WebPage | English |--| 2022 | [FATF, 2022](https://www.fatf-gafi.org/publications/high-risk-and-other-monitored-jurisdictions/documents/increased-monitoring-march-2022.html#zimbabwe)| Public Access |


2. Transactional

| Dataset                           | Description   | Language | Size | Year | Citation - Use Cases | Availability | 
| --------------------------------- |:-------------:| :-------:|------|------|------|------| 
| [Bank Transactions](datasets/bank_transactions.xlsx)| This is a 8 column .xlsx providing transactional data of a random clients over the period of June 2017 to March 2019.| English |6.45MB| 2020 | [The original purpose behind this dataset was to detect fraud transactions and money laundering. ](https://www.kaggle.com/datasets/apoorvwatsky/bank-transaction-data)| Public Access |
| [PKDD'99 Discovery Challenge - Dataset](datasets/Czech_FI_financial_db_Teradata.zip)| The dataset conists of 8 tsv files by listing containing the accounts, clients, disposition, loans, credit card info., permanent order and demographics. The transactions are based on a real life Finanical Institution in The Czech Republic from 1993 to 1998 however, they were lagged by 20 years to mirror the period of 2003 to 2018. | English |55MB| 2019 | [The original purpose behind this dataset was a discovery challenge posed by a bank to improve the delivery of services to its client. This data was prepared by Petr Berka and Marta Sochorova and modified by dnoeth.](https://sorry.vse.cz/~berka/challenge/pkdd1999/berka.htm)| Public Access |
| [FinCrime](datasets/FinCrimes-master.zip)| It encapsulates a dataset with transactions and accounts profiles that have been set within given risk levels. The categorization of risk range from low-medium-high. The dataset includes an observed table measure for sudden account changes alerts, high risk transactions and suspicious monitoring variables on Risk.  | English | 4.1MB | 2019 | [Focusing on ML & FT, the dataset can directly be used to group transactions and clients into the respective Risk occurence areas, based on Geographical locations, Age of account ownership, frequency of transaction and even more clusters through Exploratory Data Analysis.](https://github.com/Gehlotr/FinCrimes)| Public Access |
| [Azerbaijani Laundromat - The Raw Data](https://www.occrp.org/en/azerbaijanilaundromat/raw-data/)| The database below contains nearly 17,000 payments made to and from the four core UK-registered companies that made up the Azerbaijani Laundromat. It provides where the money came from, where it went, who was involved and how it was spent. They cover the period form June 2012 until the end of 2014 in a table with 7 unique columns.  | English | -- | 2022 | This dataset is publicly available. Their bank accounts were held at the Estonian branch of Danske Bank and were obtained by Berlinske, an OCCRP partner. The dataset can be used to generate key clusters particularly for confirmed cases of customers within the network for Money Laundering. The dataset provides a conglomerate of both legitimate and illegitimate transactions.| Public Access |
| [Financial Institution in Mexico](jorocha@ucm.es)| 2 | English | -- | 2022 | [Money Laundering and Terrorism Financing Detection with Neural Networks. This dataset is not Publicly available. To access it, a request should be done to the Authors as provided in the link; Jose-de-Jesús Rocha-Salazar](papers/Money_laundering_and_terrorism_financing_detection_using_neural_networks_abnormality_indicator.pdf)| Restricted Access |
| Synthetic Financial Data - Structural Similarity| This dataset was generated synthetically to prove the methodology proposed in this specific paper. The dataset is structured with labels AccountID, TransactionID, SenderAccountID, ReceiverAccountID, Amount and a TimeStamp only | English | dynamic | 2016 | [The simulator can be used to generate a myriad of transactional and client based dataset for generic tests to be conducted. To access the simulator one can review the work here](papers/A_new_algorithm_for_money_laundering_detection_based_on_structural_similarity___Clustering.pdf)| Restricted |

3. National Payments System

A Payments System is an arrangement that enables payments to be effected between a payer and a beneficiary, or facilitates the circulation of money, and includes any instruments and procedures that relate to the system. According to the Bank of International Settlements (BIS), a payment system “consists of a set of instruments, banking procedures and, typically, interbank funds transfer systems that ensure the circulation of money.” They are a major channel by which shocks can be transmitted across domestic and international financial systems and markets. Therefore, National Payments System are the conduits through which buyers and sellers of financial products and services make transactions and are an important component of a country’s financial system. In Kenya participants comprise of the Central Bank of Kenya, the Government, Commercial Banks, Financial Institutions and Payment System Providers. The Kenya Electronic Payment and Settlement System (KEPSS) is classified as a Systemically Important Payment Systems (SIPS) due to the value of transactions it processes and its impact in the economy. The system was implemented on July 29, 2005 and is wholly owned and managed by the Central Bank of Kenya (CBK).

The need to enhance efficiency in payment systems within the East African Community (EAC) and Common Market for East and South Africa (COMESA) regions – and therefore promote regional trade and economic integration – resulted in the development of two regional payment systems. The East African Payment System (EAPS) and the Regional Payment and Settlement System (REPSS) objectives are to facilitate cross border payment and settlement within the EAC and COMESA regions, respectively. Both are integrated in KEPSS. 

The Payment systems within these region generate the datasets provided below. They can be used to build National/Regional Risk profiles by Volumes of transactions, geographical frequency weights as well as distribution clusters for currency weightings.


| Dataset                           | Description   | Language | Size | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|------| 
| [National Payment System RTGS](datasets/KEPSSRTGS.xlsx)| 2 | English |33.4kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/kepss-rtgs/)|
| [Domestic Foreign Currency](datasets/DFCC.xlsx)| 8 | English |40.1kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/automated-clearing-house/dfcc/)|
| [Diaspora Remittances](datasets/DiasporaRemittances.xlsx)| 6 | English |58.3kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/diaspora-remittances/)|
| [Card Payments](datasets/CardPayments.zip)| 3 | English |19.1kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/payment-cards)|
| [Mobile Payments](datasets/MobilePayments.xlsx)| 6 | English |37.2kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/mobile-payments/)|

