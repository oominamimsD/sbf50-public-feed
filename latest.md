# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T12:00:31Z**
- feed_generated_utc: 2026-10-25T12:00:35+00:00
- source_sha256: `78688fb29edbd2a6aaf5560a86a96b0ec9919c4051c4bbef80a61abff120be1f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047210|-29.95|52.53|-30.92|8096193|2.12|
|IRYS_USDT|0.033960|-26.25|166.14|-27.22|26894219|2.94|
|BTW_USDT|1.662900|-4.50|-26.72|-5.47|12038618|3.00|
|STRK_USDT|0.045770|-3.25|-30.80|-4.22|10027382|2.19|
|DOT_USDT|1.024900|-2.30|-8.27|-3.27|12315269|1.95|
|PENGU_USDT|0.007409|-1.86|-0.59|-2.83|5844594|1.35|
|APT_USDT|0.698100|-1.20|-12.46|-2.17|6072185|1.43|
|SUI_USDT|0.919100|-0.92|-6.38|-1.89|68215448|1.09|
|SEI_USDT|0.052830|-0.88|-14.80|-1.85|7532622|1.89|
|ARB_USDT|0.166210|-0.58|-9.62|-1.55|16101685|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.698100|0.689400|0.698100|2.03|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166210|0.163860|0.166210|2.11|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.662900|1.610600|1.692400|5.71|N|N/Y|Y/Y|Y|N|
|DOT_USDT|1.024900|1.013200|1.024900|3.02|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033960|0.033850|0.033960|0.99|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047210|0.046680|0.047200|0.62|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007409|0.007333|0.007409|0.81|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052830|0.052220|0.052830|3.60|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045770|0.044870|0.045770|7.15|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.919100|0.907500|0.919100|1.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.695500, depth_time=2026-10-25T12:00:23+00:00, book20_bid_proxy_usdt=155325, book20_ask_proxy_usdt=180422, funding_indicative=-0.000117, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=6072185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.165000, depth_time=2026-10-25T12:00:31+00:00, book20_bid_proxy_usdt=113740, book20_ask_proxy_usdt=72636, funding_indicative=0.000069, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.58%, turnover=16101685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=1.695000, depth_time=2026-10-25T12:00:14+00:00, book20_bid_proxy_usdt=13473, book20_ask_proxy_usdt=17149, funding_indicative=-0.015252, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=12038618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=1.026000, depth_time=2026-10-25T12:00:19+00:00, book20_bid_proxy_usdt=363643, book20_ask_proxy_usdt=353542, funding_indicative=-0.000040, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=12315269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.036110, depth_time=2026-10-25T12:00:11+00:00, book20_bid_proxy_usdt=62150, book20_ask_proxy_usdt=37806, funding_indicative=-0.000250, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-26.25%, turnover=26894219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.053130, depth_time=2026-10-25T12:00:09+00:00, book20_bid_proxy_usdt=88506, book20_ask_proxy_usdt=55648, funding_indicative=-0.001514, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-29.95%, turnover=8096193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T12:00:03+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.007401, depth_time=2026-10-25T12:00:19+00:00, book20_bid_proxy_usdt=239942, book20_ask_proxy_usdt=231571, funding_indicative=-0.000067, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=5844594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.052560, depth_time=2026-10-25T12:00:28+00:00, book20_bid_proxy_usdt=248486, book20_ask_proxy_usdt=360312, funding_indicative=-0.000091, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=7532622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.045550, depth_time=2026-10-25T12:00:16+00:00, book20_bid_proxy_usdt=880307, book20_ask_proxy_usdt=857764, funding_indicative=0.000028, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=10027382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T12:00:02+00:00, last15m_closed_end=2026-10-25T12:00+00:00, prior8high=0.915300, depth_time=2026-10-25T12:00:26+00:00, book20_bid_proxy_usdt=1637140, book20_ask_proxy_usdt=1598511, funding_indicative=-0.000013, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=68215448. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
