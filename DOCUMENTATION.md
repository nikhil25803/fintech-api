| Endpoint                    | Description                                  | Parameters                                                |
|-----------------------------|----------------------------------------------|-----------------------------------------------------------|
| GET /simple_interest_rate   | Calculate simple interest rates              | - `amount_paid` (float): The amount paid.                 |
|                             |                                              | - `principle_amount` (float): The principle amount.       |
|                             |                                              | - `months` (int): The number of months.                   |
| GET /future_sip             | Calculate Future Value of SIP                | - `interval_investment` (float): The interval investment  |
|                             |                                              | - `rate_of_return` (float): The rate of return.           |
|                             |                                              | - `number_of_payments` (int): The number of payments.     |
| --------------------------- | ----------------------------------------     | --------------------------------------------------------- |
| POST /capm                  | Calculate Capital Asset Pricing Model (CAPM) | - `risk_free_return` (float): Risk-free rate of return.            |
|                             |                                              | - `sensitivity` (float): Asset's sensitivity.            |
|                             |                                              | - `expected_market_return` (float): Expected return of the market. |
| --------------------------- | ----------------------------------------     | --------------------------------------------------------- |
| POST /debt_service_coverage_ratio | Calculate Debt Service Coverage Ratio  | - `revenue` (float): Amount of Company Revenue.           |
|                                   |                                        | - `operating_expenses` (float): Cost of operating expenses.|
|                                   |                                        | - `interest` (float): Amount of interest to be paid       |
|                                   |                                        | - `tax_rate` (float): The tax rate applied.               |
|                                   |                                        | - `principal` (float): Amount of principal borrowed.      |
| -------------------------------   | ------------------------------------   | --------------------------------------------------------- |