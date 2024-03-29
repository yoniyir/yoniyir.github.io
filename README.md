# AICF Updater

Are you looking for a tool to help you track and manage your future crypto investment portfolio? Look no further than AICF Updater!

This web app allows you to easily update a symbol's predicted price based on the AICF prediction and download relevant data files from the server. With this information at your fingertips, you'll be able to stay on top of your investments and make informed decisions about your portfolio.

### Example for the CSV file:
The following columns exist:
- `symbol`: the symbol being predicted
- `timestamp`: a timestamp for the prediction
- `time`: the time when the prediction was made
- `current_value`: the current value of the symbol
- `expected_time`: the time when the predicted value is expected to occur
- `time_end`: the end time for the prediction
- `expected_value`: the expected value of the symbol at the expected time
- `actual_value`: the actual value of the symbol at the expected time
- `when_match`: indicates whether the actual value matches the expected value
- `when_match_time`: the time when the actual value matches the expected value (if applicable)


| symbol | timestamp | time         | current_value | expected_time          | time_end         | expected_value | actual_value | when_match | when_match_time |
|--------|-----------|--------------|---------------|------------------------|------------------|----------------|---------------|------------|-----------------|
| BTC    | 161547200 | 2021-01-01   | 10000         | 2021-01-01 12:00:00   | 2021-01-01 12:00 | 10500         | 10500        | True       | 2021-01-01 12:00 |
| ETH    | 161547200 | 2021-01-01   | 200           | 2021-01-01 12:00:00   | 2021-01-01 12:00 | 250           | 240          | False      |                  |
| DOGE   | 161547200 | 2021-01-01   | 0.01          | 2021-01-01 12:00:00   | 2021-01-01 12:00 | 0.012         | 0.011        | False      |                  |
