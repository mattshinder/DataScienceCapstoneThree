# Stock Market Sector Analysis
## Model Metrics
### Auto ARIMA
start_p = 1
start_q = 1
test = 'adf'
max_p = 5
max_q = 5
m = 7
d = None
seasonal = False
D = 0
trace = True
error_action = 'ignore'
supress_warning = True
stepwise = False

### Libaries
Data Collection: yfinance (!pip install yfinance)
Modeling: pmdarima (!pip install pmdarima)
ARIMA: statsmodels.tsa.arima.model
Auto ARIMA: pmdarima.arima
