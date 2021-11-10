# Economics Data Access Libraries

Collection of Economics Libraries. The wishlist is to have a unique codification of time series names across all data sets.
For example: BIPNOM.EUR for BIP Nominal in EUR and access it e.g. via BIPNOM.EUR.M.1997-2020.* for all countries.

# What we want to add here

Focus on R and Python. The rest go elsewhere.

Data Set types 1: Macro

Goal is to collect some decent interfaces for the following statistics libraries:
- Central Banks:  BIS, ECB, FED, BOJ, BOE, BoC
- UN Outlets:     UNStats
- NGOs:           OECD.Stat
- Governments:    BEA, Eurostat, etc. 

Data Set types 2: FX 

For some stuff you need intra day data and more than central bank and BIS FX close prices. So some good FX libs would be nice. You also want trading volume and all that.

Data Set types 3: Calendars

Some people believe the market data is enough for shocks. But you cannot predict a shock, you can predict a macro announcement and the possible delta of expectation and reality and the volatility surrounding it. 

Data Set Types 4: Factors

Yeah, you also want some factor stuff like Benchmark Indices and ideally some reasonable constituents. 

