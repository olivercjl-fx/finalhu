# finalhuRequirement already satisfied: openpyxl in /usr/local/lib/python3.11/dist-packages (3.1.5)
Requirement already satisfied: et-xmlfile in /usr/local/lib/python3.11/dist-packages (from openpyxl) (2.0.0)
Data shape: (16570, 97)
<class 'pandas.core.frame.DataFrame'>
DatetimeIndex: 16570 entries, 1980-01-01 to 2025-05-13
Data columns (total 97 columns):
 #   Column                     Non-Null Count  Dtype  
---  ------                     --------------  -----  
 0   unemployment_rate          16570 non-null  float64
 1   cpi_all_items              16570 non-null  float64
 2   core_pce                   16570 non-null  float64
 3   real_gdp                   16570 non-null  float64
 4   nominal_gdp                16570 non-null  float64
 5   federal_funds_rate         16570 non-null  float64
 6   10y_treasury_yield         16570 non-null  float64
 7   3m_treasury_yield          15961 non-null  float64
 8   m2_money_stock             16570 non-null  float64
 9   initial_jobless_claims     16510 non-null  float64
 10  continuing_claims          16510 non-null  float64
 11  average_hourly_earnings    7014 non-null   float64
 12  employment_total_nonfarm   16570 non-null  float64
 13  case_shiller_us            14013 non-null  float64
 14  house_price_index          16570 non-null  float64
 15  housing_starts             16570 non-null  float64
 16  total_vehicle_sales        16570 non-null  float64
 17  wti_crude_oil              14288 non-null  float64
 18  brent_crude_oil            13862 non-null  float64
 19  us_dollar_index            7042 non-null   float64
 20  usd_jpy                    16539 non-null  float64
 21  usd_eur                    9599 non-null   float64
 22  usd_cny                    16114 non-null  float64
 23  vix_index                  12886 non-null  float64
 24  pce_inflation              16570 non-null  float64
 25  personal_income            16570 non-null  float64
 26  retail_sales               12187 non-null  float64
 27  industrial_production      16570 non-null  float64
 28  manufacturing_ip           16570 non-null  float64
 29  capacity_utilization       16570 non-null  float64
 30  business_loans             16570 non-null  float64
 31  credit_card_loans          8960 non-null   float64
 32  consumer_sentiment         16570 non-null  float64
 33  truck_employment           12917 non-null  float64
 34  truck_tonnage_index        9265 non-null   float64
 35  heavy_truck_sales          16570 non-null  float64
 36  truck_production_ppi       7835 non-null   float64
 37  used_cars_cpi              16570 non-null  float64
 38  corporate_bond_yield_baa   14288 non-null  float64
 39  real_disposable_income     16570 non-null  float64
 40  real_personal_consumption  6708 non-null   float64
 41  personal_savings_rate      16570 non-null  float64
 42  st_louis_fin_stress        11366 non-null  float64
 43  core_inflation_services    16570 non-null  float64
 44  prime_rate                 16570 non-null  float64
 45  10y_minus_2y               16539 non-null  float64
 46  10y_minus_3m               15808 non-null  float64
 47  federal_funds_effective    9052 non-null   float64
 48  overnight_rp               6069 non-null   float64
 49  10y_nominal                16570 non-null  float64
 50  10y_real                   8079 non-null   float64
 51  10y_breakeven              8079 non-null   float64
 52  5y5y_forward_infl          8079 non-null   float64
 53  aaa_corp_yield             15443 non-null  float64
 54  baa_corp_yield             14288 non-null  float64
 55  vix                        12886 non-null  float64
 56  usd_index_nominal          11060 non-null  float64
 57  sofr_30d_avg               2539 non-null   float64
 58  usd_jpy_spot               16539 non-null  float64
 59  usd_eur_spot               9599 non-null   float64
 60  usd_cny_spot               16114 non-null  float64
 61  nasdaq                     16539 non-null  float64
 62  dow_jones                  3635 non-null   float64
 63  sp500                      3635 non-null   float64
 64  recession_flag             16570 non-null  int64  
 65  AAPL                       16223 non-null  float64
 66  MSFT                       14306 non-null  float64
 67  GOOGL                      7572 non-null   float64
 68  META                       4743 non-null   float64
 69  AMZN                       10225 non-null  float64
 70  NVDA                       9608 non-null   float64
 71  TSLA                       5432 non-null   float64
 72  GC=F                       9022 non-null   float64
 73  CL=F                       9029 non-null   float64
 74  NG=F                       9022 non-null   float64
 75  ZW=F                       9066 non-null   float64
 76  ZC=F                       9066 non-null   float64
 77  ZS=F                       9006 non-null   float64
 78  ^IXIC                      16436 non-null  float64
 79  ^GSPC                      16436 non-null  float64
 80  ^DJI                       12185 non-null  float64
 81  XOM                        16436 non-null  float64
 82  GE                         16436 non-null  float64
 83  IBM                        16436 non-null  float64
 84  JNJ                        16436 non-null  float64
 85  PG                         16436 non-null  float64
 86  WMT                        16436 non-null  float64
 87  KO                         16436 non-null  float64
 88  INTC                       16436 non-null  float64
 89  ORCL                       14307 non-null  float64
 90  CVX                        16436 non-null  float64
 91  BTC-USD                    3892 non-null   float64
 92  ETH-USD                    2743 non-null   float64
 93  SOL-USD                    1860 non-null   float64
 94  BNB-USD                    2743 non-null   float64
 95  DOGE-USD                   2743 non-null   float64
 96  avg_tariff_rate            16570 non-null  float64
dtypes: float64(96), int64(1)
memory usage: 12.4 MB
None
            unemployment_rate  cpi_all_items   core_pce     real_gdp  \
1980-01-01                6.3      78.000000  36.315000  7341.557000   
1980-01-02                6.3      78.032258  36.326677  7339.894714   
1980-01-03                6.3      78.064516  36.338355  7338.232429   
1980-01-04                6.3      78.096774  36.350032  7336.570143   
1980-01-05                6.3      78.129032  36.361710  7334.907857   

            nominal_gdp  federal_funds_rate  10y_treasury_yield  \
1980-01-01  2789.842000               13.82           10.800000   
1980-01-02  2789.924527               13.83           10.851935   
1980-01-03  2790.007055               13.84           10.903871   
1980-01-04  2790.089582               13.85           10.955806   
1980-01-05  2790.172110               13.86           11.007742   

            3m_treasury_yield  m2_money_stock  initial_jobless_claims  ...  \
1980-01-01                NaN     1482.700000                     NaN  ...   
1980-01-02                NaN     1483.083871                     NaN  ...   
1980-01-03                NaN     1483.467742                     NaN  ...   
1980-01-04                NaN     1483.851613                     NaN  ...   
1980-01-05                NaN     1484.235484                     NaN  ...   

            KO  INTC  ORCL  CVX  BTC-USD  ETH-USD  SOL-USD  BNB-USD  DOGE-USD  \
1980-01-01 NaN   NaN   NaN  NaN      NaN      NaN      NaN      NaN       NaN   
1980-01-02 NaN   NaN   NaN  NaN      NaN      NaN      NaN      NaN       NaN   
1980-01-03 NaN   NaN   NaN  NaN      NaN      NaN      NaN      NaN       NaN   
1980-01-04 NaN   NaN   NaN  NaN      NaN      NaN      NaN      NaN       NaN   
1980-01-05 NaN   NaN   NaN  NaN      NaN      NaN      NaN      NaN       NaN   

            avg_tariff_rate  
1980-01-01         3.100000  
1980-01-02         3.100820  
1980-01-03         3.101639  
1980-01-04         3.102459  
1980-01-05         3.103279  

[5 rows x 97 columns]
unemployment_rate        0
cpi_all_items            0
core_pce                 0
real_gdp                 0
nominal_gdp              0
                     ...  
ETH-USD              13827
SOL-USD              14710
BNB-USD              13827
DOGE-USD             13827
avg_tariff_rate          0
Length: 97, dtype: int64
unemployment_rate     4820
cpi_all_items        15901
core_pce             16495
real_gdp             16438
nominal_gdp          16438
                     ...  
ETH-USD               2742
SOL-USD               1860
BNB-USD               2743
DOGE-USD              2518
avg_tariff_rate       9691
Length: 97, dtype: int64
                     count          mean          std          min  \
unemployment_rate  16570.0      6.043570     1.799867     3.400000   
cpi_all_items      16570.0    185.614442    61.805163    78.000000   
core_pce           16570.0     78.604832    21.843611    36.315000   
real_gdp           16570.0  14543.978523  4723.218748  7181.743000   
nominal_gdp        16570.0  12479.226057  7226.311925  2789.842000   
...                    ...           ...          ...          ...   
ETH-USD             2743.0   1535.229889  1220.102260    84.308296   
SOL-USD             1860.0     75.558232    70.984423     0.515273   
BNB-USD             2743.0    239.067908   224.866619     1.510360   
DOGE-USD            2743.0      0.084693     0.102122     0.001038   
avg_tariff_rate    16570.0      2.521497     1.423824     1.200000   

                            25%           50%           75%           max  
unemployment_rate      4.635484      5.661290      7.225188     14.800000  
cpi_all_items        135.654839    180.873333    235.037444    319.775000  
core_pce              62.325508     77.984100     95.075250    125.052000  
real_gdp           10085.644170  14532.800636  18009.386190  23542.349000  
nominal_gdp         6156.623745  11040.822908  17225.359861  29977.632000  
...                         ...           ...           ...           ...  
ETH-USD              288.021759   1556.872681   2458.725220   4812.087402  
SOL-USD               19.255631     38.905603    139.479778    261.869751  
BNB-USD               17.244488    240.498795    399.337280    750.272644  
DOGE-USD               0.002921      0.063234      0.128673      0.684777  
avg_tariff_rate        1.472074      2.320548      3.337808     11.500000  

[97 rows x 8 columns]
Introduction
Understanding and forecasting key economic indicators is central to both macroeconomic policymaking and financial decision-making. This project focuses on building predictive models for two crucial targets in the U.S. economy: Core Personal Consumption Expenditures (Core PCE) inflation and the S&P 500 index. The Core PCE serves as the Federal Reserve's preferred inflation gauge, directly influencing monetary policy decisions such as interest rate adjustments. Meanwhile, the S&P 500 index reflects market sentiment and expectations regarding the broader economy, and is a key benchmark for equity market performance.
Leveraging a comprehensive dataset combining macroeconomic indicators, labor market data, interest rates, commodity prices, and policy variables (such as average tariff rates), we develop machine learning models to understand and predict these targets. In the first part of the project, we model Core PCE inflation using a wide array of real and nominal variables to examine the structural drivers of inflationary pressure. In the second part, we shift focus to the S&P 500, constructing a linear regression model that isolates the effect of macroeconomic fundamentals—excluding market-specific variables—to evaluate how economic conditions relate to equity market movements.
Our models employ scikit-learn pipelines with preprocessing steps such as standardization and one-hot encoding, allowing for efficient feature engineering and robust performance evaluation. The results highlight the most influential variables for each predictive task and provide interpretability through coefficient analysis in the linear model.
This dual-focus approach provides not only forecasting utility but also economic insight, bridging macro-level fundamentals with real-time policy and market signals.
The dataset includes a comprehensive array of macroeconomic, financial, and policy-related variables that are critical to understanding both inflation dynamics and equity market movements. The (unemployment_rate) reflects the proportion of the labor force that is unemployed and actively seeking work, serving as a key indicator of labor market conditions. The (cpi_all_items) captures overall inflation including food and energy, while the (core_pce) excludes these volatile components and serves as the Federal Reserve’s primary inflation gauge. Measures of output and income include (real_gdp) and (nominal_gdp), which track inflation-adjusted and current-dollar economic production respectively. The (federal_funds_rate) denotes the interest rate at which depository institutions lend to each other overnight and is a primary tool of U.S. monetary policy. Long- and short-term interest rates are represented by the (10y_treasury_yield) and (3m_treasury_yield), capturing yield curve dynamics. The (m2_money_stock) represents the broad money supply, while labor market activity is further detailed by (initial_jobless_claims) and (continuing_claims), which track unemployment insurance filings.
Wage pressures and labor income trends are captured through (average_hourly_earnings) and (employment_total_nonfarm), indicating employment levels across sectors. Housing market conditions are reflected in (case_shiller_us) and (house_price_index), as well as (housing_starts), which measure new residential construction. Consumption and investment in durable goods are proxied by (total_vehicle_sales). Commodity price movements are represented by (wti_crude_oil) and (brent_crude_oil), both of which impact inflation expectations and producer costs. The (us_dollar_index) measures the value of the U.S. dollar against major foreign currencies, while exchange rate variables such as (usd_jpy), (usd_eur), and (usd_cny) provide insight into international purchasing power and trade dynamics.
Market risk sentiment is proxied by the (vix_index), a volatility index, while (pce_inflation) represents overall personal consumption expenditure price trends. Measures of consumer and business activity include (personal_income), (retail_sales), (industrial_production), and (manufacturing_ip). Capacity constraints are captured through (capacity_utilization), and credit market behavior is reflected in (business_loans) and (credit_card_loans). Consumer expectations are addressed via (consumer_sentiment). The transportation sector is detailed through (truck_employment), (truck_tonnage_index), (heavy_truck_sales), and (truck_production_ppi), which indicate logistics intensity and industrial demand. Additional inflation-related indicators include (used_cars_cpi) and (corporate_bond_yield_baa), the latter reflecting credit risk premiums. Measures of real income and consumption such as (real_disposable_income) and (real_personal_consumption) further contextualize household behavior. The (personal_savings_rate) indicates consumer caution or confidence, while (st_louis_fin_stress) tracks financial system stress. Finally, (core_inflation_services) highlights service-sector price movements, and monetary conditions are additionally captured by variables such as (prime_rate), (10y_minus_2y), (10y_minus_3m), (federal_funds_effective), (overnight_rp), and (10y_nominal), all of which reflect the prevailing interest rate environment and expectations about future economic conditions.
In addition to macroeconomic and monetary indicators, the dataset includes variables capturing equity markets, commodity markets, digital assets, and policy instruments. The (sp500) represents the S&P 500 index, a benchmark for the performance of large-cap U.S. equities, while (nasdaq) and (dow_jones) offer complementary views of technology-heavy and industrial stock performance, respectively. The (recession_flag) is a binary indicator that marks periods of official U.S. economic recessions, serving as a regime variable in temporal modeling. A set of individual stock prices—such as (AAPL), (MSFT), (GOOGL), (META), (AMZN), (NVDA), (TSLA), and others—represents firm-level equity trends and is primarily used in exploratory analysis or excluded from fundamental-only models.
In the realm of commodities, the dataset includes (GC=F) for gold prices, (CL=F) for crude oil, (NG=F) for natural gas, and several agricultural futures: (ZW=F) for wheat, (ZC=F) for corn, and (ZS=F) for soybeans. These prices are relevant for analyzing supply-side inflation shocks and cost-push pressures. Digital asset indicators such as (BTC-USD) for Bitcoin, (ETH-USD) for Ethereum, and (SOL-USD), (BNB-USD), (DOGE-USD) represent alternative investment activity and investor sentiment, although their volatility may limit predictive value in macro models. Stock prices of major corporations including (XOM), (GE), (IBM), (JNJ), (PG), (WMT), (KO), (INTC), (ORCL), and (CVX) provide additional microeconomic indicators that may reflect sector-specific shocks or broader market trends.
Lastly, the (avg_tariff_rate) captures the average effective tariff level imposed by the U.S., serving as a proxy for trade policy stance. Rising tariffs may indicate protectionist shifts that affect both consumer prices and global supply chains, and thus this variable is especially important in modeling cost-driven inflation under scenarios involving trade shocks.
