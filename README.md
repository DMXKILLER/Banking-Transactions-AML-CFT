#
Datasets of Banking Transactions with basis on Anti-Money Laundering and Terrorism Financing
============================================

This repository presents a description of the datasets available on banking systems that can be used to classify and identify money laundering and terrorism financing within payment networks and banking systems. The datasets provide a conglomerate of transactionary data (in motion) as well as client profiles (static). In addition to this, it references a specific plug in point for the National Payment Systems of a Central Bank within Eastern Africa. If interested in contributing to this repository for terror reports or open investigations within the region region of East and Central Africa, reach me at dnmakiya@fc.ul.pt



[__Client Profile Data__](#tie)
This contains datapoints specific to the Know your Customer (KYC) and Customer Due Diligence (CDD) requirements with respect to the Financial Action Task Force (FATF regulations). Such datapoints include the type of client(individual/natural person), customer segment, Political exposure, economic activity, Age of client etc.  nature of the client.


[__Transactionary__](#tie)
This contains datapoints specific to the occurence of a singular transaction. They are unique at the occurence of each transaction like the amount, currency, income source/purpose of funds, geographical location, intermediary banks etc.


[__National Risk Points__](#tie)
The World Bank/IMF have provided a cross-border methodology for performing Risk assessments across specific nations where there is adoptation of the FATF regulations/guidelines. In East and Central Africa, the Eastern and Southern Africa Anti-Money Laundering Group (ESAAMLG) operates as a key information exchange hub within the region. The National Risk Assessment reports within the member bodies of ESAAMLG provide the ideal datapoints from the qualitative Risk assessment going back a period of 4 years. The Risk Assessments within the member bodies provide risk classifications on a scale of 0-1 on the basis of given industries/sectors, compliance levels existence of controls and etc.

<br><br>

1. Client Profiling

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|
| [Financial Institution in Mexico](jorocha@ucm.es)| 2 | English | 2022 | [Detection of Shell Companies. This dataset is not Publicly available. To access it, a request should be done to the Authors as provided in the link; Jose-de-Jesús Rocha-Salazar](papers/Detection_of_shell_companies_in_financial_institutions_using_dynamic_social_network.pdf)|

1.a) Terror Watchlists 

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|

2. Transactional

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|
| [Financial Institution in Mexico](jorocha@ucm.es)| 2 | English | 2022 | [Money Laundering and Terrorism Financing Detection with Neural Networks. This dataset is not Publicly available. To access it, a request should be done to the Authors as provided in the link; Jose-de-Jesús Rocha-Salazar](papers/Money_laundering_and_terrorism_financing_detection_using_neural_networks_abnormality_indicator.pdf)|
| [Synthetic Financial Data](jorocha@ucm.es)| 2 | English | 2016 | [Structural Similarity. This dataset was generated synthetically to prove the methodology proposed in this specific paper. The dataset is structured with labels AccountID, TransactionID, SenderAccountID, ReceiverAccountID, Amount and a TimeStamp only. To access the simulator one can review the work here](papers/A_new_algorithm_for_money_laundering_detection_based_on_structural_similarity___Clustering.pdf)|




3. National Payment System

A Payments System is an arrangement that enables payments to be effected between a payer and a beneficiary, or facilitates the circulation of money, and includes any instruments and procedures that relate to the system. According to the Bank of International Settlements (BIS), a payment system “consists of a set of instruments, banking procedures and, typically, interbank funds transfer systems that ensure the circulation of money.” They are a major channel by which shocks can be transmitted across domestic and international financial systems and markets. Therefore, National Payments System are the conduits through which buyers and sellers of financial products and services make transactions and are an important component of a country’s financial system. In Kenya participants comprise of the Central Bank of Kenya, the Government, Commercial Banks, Financial Institutions and Payment System Providers. The Kenya Electronic Payment and Settlement System (KEPSS) is classified as a Systemically Important Payment Systems (SIPS) due to the value of transactions it processes and its impact in the economy. The system was implemented on July 29, 2005 and is wholly owned and managed by the Central Bank of Kenya (CBK).

The need to enhance efficiency in payment systems within the East African Community (EAC) and Common Market for East and South Africa (COMESA) regions – and therefore promote regional trade and economic integration – resulted in the development of two regional payment systems. The East African Payment System (EAPS) and the Regional Payment and Settlement System (REPSS) objectives are to facilitate cross border payment and settlement within the EAC and COMESA regions, respectively. Both are integrated in KEPSS. 

The Payment systems within these region generate the datasets provided below. They can be used to build National/Regional Risk profiles by Volumes of transactions, geographical frequency weights as well as distribution clusters for currency weightings.


| Dataset                           | Nr. Classes   | Language | Size | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|------| 
| [National Payment System RTGS](datasets/KEPSSRTGS.xlsx)| 2 | English |33.4kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/kepss-rtgs/)|
| [Domestic Foreign Currency](datasets/DFCC.xlsx)| 8 | English |40.1kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/automated-clearing-house/dfcc/)|
| [Diaspora Remittances](datasets/DiasporaRemittances.xlsx)| 6 | English |58.3kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/diaspora-remittances/)|
| [Card Payments](datasets/CardPayments.zip)| 3 | English |19.1kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/payment-cards)|
| [Mobile Payments](datasets/MobilePayments.xlsx)| 6 | English |37.2kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/mobile-payments/)|
| [Jurisdictions Under Increased Monitoring](https://www.fatf-gafi.org/publications/high-risk-and-other-monitored-jurisdictions/documents/increased-monitoring-march-2022.html#zimbabwe)| 6 | English |--| 2022 | [FATF, 2022](https://www.fatf-gafi.org/publications/high-risk-and-other-monitored-jurisdictions/documents/increased-monitoring-march-2022.html#zimbabwe)|
