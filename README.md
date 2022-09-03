# Credit Risk Prediction

### Number of Instances: 31375 
### Number of Attributes: 39

### Attribute information:

| Variable | Description |
|---|--------------------|
| ID | client ID |
| LIMIT | credit Limit of a client in dollars |
| GENDER | 1 = male, 2 = female |
| EDUCATION | (1=graduate school, 2=university, 3=high school, 0 = others, 4=others, 5=special program, 6=unknown) |
| MARRIAGE | marital status (1=married, 2=single, 3=divorced, 0 = others) |
| AGE | age in years |
| AGE_CTG | age category (1= from 20 to 34; 2 = from 35 to 49; 3 = from 50 to 64; 4 = 65 and over)
| PY1, PY2, PY3, PY4, PY5, PY6 | History of past payments. <br /> PY1 = the repayment status in period X; PY2 = the repayment status in period (X-1) <br /> PY3 = the repayment status in period (X-2); PY4 = the repayment status in period (X-3) <br /> PY5 = the repayment status in period (X-4); PY6 = the repayment status in period (X-5) <br /> Categories in these variables are: <br /> -2: No consumption/transaction <br /> -1: Paid in full <br /> 0: small payment <br /> 1 = payment delay for one period <br /> 2 = payment delay for two periods; ... <br /> 8 = payment delay for eight periods <br /> 9 = payment delays for nine periods and above |
| BILL1, BILL2, BILL3, BILL4, BILL5, BILL6 | Amount of bill statement in dollars <br /> BILL1: bill statement in period X; BILL2: bill statement in period (X-1) <br /> BILL3: bill statement in period (X-2); BILL4: bill statement in period (X-3) <br /> BILL5: bill statement in period (X-4); BILL6: bill statement in period (X-5) |
| PYAMT1, PYAMT2, PYAMT3, PYAMT4, PYAMT5, PYAMT6 | Amount of previous payment in dollars <br /> PYAMT1: amount paid in period X; PYAMT2: amount paid in period (X-1) <br /> PYAMT3: amount paid in period (X-2); PYAMT4: amount paid in period (X-3) <br /> PYAMT5: amount paid in period (X-4); PYAMT6: amount paid in period (X-5) |
| SATISFACTION | service satisfaction (0 = not satisfactory; 1= normal; 2 = satisfactory) |
| FREQTRANSACTION | how frequently client visits Universal Plus (0 = rarely, 1 = regularly) |
| PHONE | whether the client has a landline or not (0 = no phone; 1 = yes) |
| DEPENDENT | whether the client has children or not (0 = no child; 1 = yes) |
| CREDITCRD | number of credit cards |
| RSTATUS | current accommodation status (0= shared lease, 1= homeowner,  2= rent) |
| OTH_ACCOUNT | whether the client has several bank accounts (0= no, 1= yes) |
| CAR | whether the client has a car (0 = no, 1 = yes) |
| YEARSINADD | years in the current address (3 = three years or below, 4 = four years, ..., 7 = seven years or above) |
| SECONDHOME | whether the client has another address (0 = no, 1 = yes) |
| EMPLOYMENT | whether the client has a permenant job (0 = no, 1 = yes) |
| NEW_CSTM | whether the client joined Universal Plus in the last two years or s/he is an existing customer (0 = joined in the last two years, 1 = existing customer) |
| CM_HIST | criminal history, e.g. insurance fraud (0 = no, 1 = yes) |
| CLASS | 0 = the client paid the credit back; 1 = the client did not pay the credit and went into default |
