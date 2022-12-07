# Banking-Transactions-AML-CFT
Datasets of Banking Transactions with basis on Anti-Money Laundering an Terrorism Financing
============================================

This repository presents a description of the datasets available on banking systems that can be used to classify and identify money laundering and terrorism financing within transactions. The datasets provide a conglomerate of transactionary data (in motion) as well as client profiles (static). In addition to this, it references a specific plug in point for the National Payment Systems of a Central Bank within Eastern Africa.



[__Client Profile Data__](#tie)
This contains datapoints specific to the Know your Customer (KYC) and Customer Due Diligence (CDD) requirements with respect to the Financial Action Task Force (FATF regulations). Such datapoints are include the type of client(individual/natural person), customer segment, Politically exposure, economic activity, Age of client etc.  nature of the client.


[__Transactionary__](#tie)
This contains datapoints specific to the occurence of a singular transaction. Such datapoints are unique at the occurence of each transaction such as the currency, income source/purpose of funds, geographical location, intermediary banks etc.


[__National Risk Points__](#tie)
The World Bank/IMF have provided a cross-border methodology for performing Risk assessments across specific nations where there is adoptation of the FATF regulations/guidelines. In East and Central Africa, the Eastern and Southern Africa Anti-Money Laundering Group (ESAAMLG). The National Risk Assessment reports within the member bodies of ESAAMLG provide the ideal datapoints from the qualitative Risk assessment going back a period of 4 years. The Risk Assessments within the member bodies provide risk classifications on a scale of 0-1 on the basis of given industries/sectors, compliance levels existence of controls and etc.

<br><br>

1. Client Profiling

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|

1.a) Terror Watchlists 

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|

2. Transactional

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|

3. National Payment System

| Dataset                           | Nr. Classes   | Language | Size | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|
| [National Payment System RTGS](datasets/KEPSSRTGS.xlsx)| 2 | English |33.4kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/kepss-rtgs/)|
| [Domestic Foreign Currency](datasets/DFCC.xlsx)| 8 | English |40.1kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/automated-clearing-house/dfcc/)|
| [Diaspora Remittances](datasets/DiasporaRemittances.xlsx)| 6 | English |58.3kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/diaspora-remittances/)|
| [Card Payments](datasets/CardPayments.zip)| 6 | English |19.1kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/payment-cards)|
| [Mobile Payments](datasets/MobilePayments.xlsx)| 6 | English |37.2kb| 2022 | [Central Bank of Kenya](https://www.centralbank.go.ke/national-payments-system/mobile-payments/)|