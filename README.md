# Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information

> Lending Club is a lending platform that lends money to people in need at an interest rate based on their credit history and other factors. In this blog, we will analyze this data and pre-process it based on our need and build a machine learning model that can identify a potential defaulter based on customer history of transactions with Lending Club..

### Project Background

> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Typically, larger loans receive lower grades; the median amount for grade G loans is approximately $10,000 higher than that for grade   A, B, or C loans.
- The total number of credit lines currently in the borrower's credit file shows high correlation with opening credit line of borrower.
- The monthly installment amount also have high correlation with loan amount which is self explanatory.
- Lenders assess risk based on loan amount. Larger loans pose higher potential losses if defaulted. Hence, to compensate for this risk, lenders often charge higher interest rates. Higher loan amounts usually greater than $25000 are given at higher interest rates.
- Clearly we can see that borrowers who have 10 + years of work experience shows highest percentage of loan defaulting both on 36 months and 60 months loan term .
- Chances of defaulting are higher for 60 month loan term irrespective of employment length.
- Clearly we can see that borrowers who have rent accommodation and L1 income level(lowest income level) shows the highest percentage of loan defaulting( 78.79 %) which is self explanatory.
- Borrowers having their own home and highest income level ( L11) have 0 chance of loan defaulting.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Pandas - version 1.5.3
- NumPy - version 1.23.5
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.1
- Jupiter - 1.0.0
- Git - 2.41.0
- Github

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contributors

Arjun Kumar
Aratrika Chaudhury



<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.

<!-- You don't have to include all sections - just the one's relevant to your project -->
