# Question
```python
data = {
  "s": {
    "AAPL": 0.25133422827795837,
    "GOOG": 0.3334488626006967,
    "AMZN": 0.3740810988798152,
    "NVDA": 0.5380555051571062,
    "TSLA": 0.5978797177153061,
    "LLY": 0.27668983620418824,
    "JPM": 0.21769958048869922,
    "XOM": 0.2622961333517632,
    "AVGO": 0.32762039500874146,
    "V": 0.18849603446983362,
    "JNJ": 0.16470111192176468,
    "PG": 0.15020283486133143,
    "MA": 0.2085917915162287,
    "HD": 0.23516338551999078,
    "ADBE": 0.3491675706381003,
    "MRK": 0.19328049253425997,
    "COST": 0.20399242233838977,
    "CVX": 0.2442523141032357,
    "ABBV": 0.1983861287795725,
    "WMT": 0.15528602884693177,
    "PEP": 0.1511472835108664,
    "KO": 0.14192521797403318,
    "CSCO": 0.19798244935255943,
    "CRM": 0.34361379918075297,
    "ACN": 0.26322917771381316,
    "NFLX": 0.42258542083434136,
    "MCD": 0.1397354070055457,
    "LIN": 0.20283398441141257,
    "AMD": 0.4939505006751646,
    "BAC": 0.26238259593786306,
    "ORCL": 0.27720520875055465,
    "CMCSA": 0.25278548226092584,
    "PFE": 0.21768908588572533,
    "ABT": 0.21193232700378156,
    "INTC": 0.38880430429409446,
    "DIS": 0.3172399100887614,
    "VZ": 0.24141000756602202,
    "WFC": 0.27876461422646787,
    "INTU": 0.3447721392599972,
    "AMGN": 0.21113599866532942,
    "PM": 0.17651330055509842,
    "QCOM": 0.35978479141741715,
    "COP": 0.3149581026890284,
    "IBM": 0.17697878513657805,
    "SPY": 0.15700684137533322,
    "QQQ": 0.21313815359347674
  },
  "c": {
    "AAPL231229C00185000": {
      "S": 188.01,
      "K": 185
    },
    "GOOG231229C00136000": {
      "S": 136.38,
      "K": 136
    },
    "AMZN231229C00143000": {
      "S": 143.2,
      "K": 143
    },
    "NVDA231229C00485000": {
      "S": 488.88,
      "K": 485
    },
    "TSLA231229C00240000": {
      "S": 242.84,
      "K": 240
    },
    "LLY231229C00585000": {
      "S": 588.54,
      "K": 585
    },
    "JPM231229C00149000": {
      "S": 149.74,
      "K": 149
    },
    "XOM231229P00104000": {
      "S": 103.66,
      "K": 104
    },
    "AVGO231229C00975000": {
      "S": 975.4,
      "K": 975
    },
    "V231229C00245000": {
      "S": 248.11,
      "K": 245
    },
    "JNJ231229C00145000": {
      "S": 148.8,
      "K": 145
    },
    "PG231229P00145000": {
      "S": 151.42,
      "K": 145
    },
    "MA231229P00395000": {
      "S": 396.83,
      "K": 395
    },
    "HD231229C00305000": {
      "S": 308.19,
      "K": 305
    },
    "ADBE231229P00590000": {
      "S": 595.31,
      "K": 590
    },
    "MRK231229P00102000": {
      "S": 101.35,
      "K": 102
    },
    "COST231229C00595000": {
      "S": 596.78,
      "K": 595
    },
    "CVX231229C00145000": {
      "S": 145.56,
      "K": 145
    },
    "ABBV231229P00138000": {
      "S": 137.6,
      "K": 138
    },
    "WMT231229C00165000": {
      "S": 169.78,
      "K": 165
    },
    "PEP231229C00165000": {
      "S": 167.25,
      "K": 165
    },
    "KO231229C00057000": {
      "S": 57.21,
      "K": 57
    },
    "CSCO231229C00053000": {
      "S": 53.28,
      "K": 53
    },
    "CRM231229P00220000": {
      "S": 219.42,
      "K": 220
    },
    "ACN231229C00335000": {
      "S": 325.5,
      "K": 335
    },
    "NFLX231229C00460000": {
      "S": 461.94,
      "K": 460
    },
    "MCD231229P00265000": {
      "S": 270.39,
      "K": 265
    },
    "AMD231229P00119000": {
      "S": 118,
      "K": 119
    },
    "BAC231229C00030000": {
      "S": 29.62,
      "K": 30
    },
    "ORCL231229P00111000": {
      "S": 114.06,
      "K": 111
    },
    "CMCSA231229C00042000": {
      "S": 42.53,
      "K": 42
    },
    "PFE231229C00030000": {
      "S": 30.19,
      "K": 30
    },
    "ABT231229C00098000": {
      "S": 98,
      "K": 98
    },
    "INTC231229C00040000": {
      "S": 40.61,
      "K": 40
    },
    "DIS231229C00093000": {
      "S": 93.93,
      "K": 93
    },
    "VZ231229C00035000": {
      "S": 36,
      "K": 35
    },
    "WFC231229C00042000": {
      "S": 42.84,
      "K": 42
    },
    "AMGN231229C00270000": {
      "S": 273.03,
      "K": 270
    },
    "QCOM231229C00128000": {
      "S": 128.92,
      "K": 128
    },
    "COP231229P00116000": {
      "S": 115.03,
      "K": 116
    },
    "IBM231229C00152500": {
      "S": 152.58,
      "K": 152.5
    },
    "SPY231229C00449000": {
      "S": 449.68,
      "K": 449
    },
    "QQQ231229C00349000": {
      "S": 385.62,
      "K": 349
    }
  }
}

sum([round(premium(line, r=0.05, T=0.13778), 2) for line in data.c])
```

# Solution

This goal of this challenge is to calculate the option premium for each of the options listed.  
My guess for what each of the symbol means is as follows.  
```
"s": annualized volatility of the asset's returns
"c": list of option contracts (name + info)
"S": current asset price
"K": strike price of the option
"r": risk free rate
"T": time until option expiration
```

By inputting these values into the Black–Scholes model, we would be able to calculate the premium for each of the 
options and get the correct answer of 463.29.  

That said, this implementation of the Black-Scholes model does not take into account the dividends paid out by the 
stock. "AAPL" for example pays a dividend. However, in this challenge there is no value provided for the dividend of 
the stock. Therefore, we can use the current implementation of the Black-Scholes model to complete the challenge.

Reference: https://www.codearmo.com/python-tutorial/options-trading-black-scholes-model
