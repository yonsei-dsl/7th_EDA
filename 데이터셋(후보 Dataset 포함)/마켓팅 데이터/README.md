# Marketing Campaign
해당 데이터는 kaggle에서 제공하는 marketing sample 데이터입니다.<br>
Marketing campaign을 효율적으로 달성하기 위한 response model을 개발하는 것을 최종 목적으로 하는 데이터지만, 여러분은 해당 데이터로 EDA를 진행해주시면 되겠습니다. 

데이터의 구성은 다음과 같습니다.<br> 크게 소비자의 특징 / 소비자의 패턴 / 1 ~ 6번째(Response, target으로 표시되는 column입니다).) 캠페인의 반응 여부 등으로 구성되어있습니다. <br>추가적인 연구의 여지를 남기기 위해, kaggle에서 제공하는 원문만 하단에 따로 첨부합니다.

기업에 대한 데이터는 별도로 주어져 있지 않습니다. 주어진 column에 기반해서 기업의 종류와 BM, 매출 등을 가정해서 EDA를 진행해도 재밌겠습니다. 실제 기업의 경우를 참고해도 되고요.

- AcceptedCmp1 - 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2 - 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3 - 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4 - 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5 - 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
- Complain - 1 if customer complained in the last 2 years
- DtCustomer - date of customer’s enrolment with the company
- Education - customer’s level of education
- Marital - customer’s marital status
- Kidhome - number of small children in customer’s household
-  Teenhome - number of teenagers in customer’s household
-  Income - customer’s yearly household income
- MntFishProducts - amount spent on fish products in the last 2 years
- MntMeatProducts - amount spent on meat products in the last 2 years
- MntFruits - amount spent on fruits products in the last 2 years
- MntSweetProducts - amount spent on sweet products in the last 2 years
- MntWines - amount spent on wine products in the last 2 years
- MntGoldProds - amount spent on gold products in the last 2 years
- NumDealsPurchases - number of purchases made with discount
- NumCatalogPurchases - number of purchases made using catalogue
- NumStorePurchases - number of purchases made directly in stores
- NumWebPurchases - number of purchases made through company’s web site
- NumWebVisitsMonth - number of visits to company’s web site in the last month
- Recency - number of days since the last purchase
