# Change Log

## 0.1.20

* Add BitMex live feed
* Add CryptoProvider (exchange rates)
* Add RobustCalculator (exchange rates)
* `Trader` should handle Market orders better

## v0.1.19

* Bugfixes

## v0.1.18

* Add `origin` tag to messages
* Many bugfixes to GDAX feed

## v0.1.17

* New Features
    * Gemini Market feed! Thanks @github-ajt
* Bug Fixes
    * Handle new API feed messages for GDAX
    * GDAX Feed messages handle error messages more elegantly. Thanks @kostola
* Other
    * Use CircleCI for integration testing on Github

## v0.1.16

Bug fixes and basic CCXT integration. There are quite a few bugfixes as well as public REST support for some 70 exchanges :)

## v0.1.13

* New Exchange support: Bittrex
* New Core filters:
    * Product splitter (split a feed stream by product, with proper backpressure handling)

## v0.1.12

* Add ProductSplitter
