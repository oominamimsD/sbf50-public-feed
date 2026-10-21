# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T13:45:35Z**
- feed_generated_utc: 2026-10-21T13:45:38+00:00
- source_sha256: `41421edd6f9ce52d25bc4c6fc9e307fd5c6b1bc6d5c3019a0bcc8c1a7033959f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T13:45+00:00, close=83611.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T13:00+00:00, close=83471.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045234|-30.00|179.61|-31.28|6588716|3.54|
|BAT_USDT|0.178110|-17.45|0.41|-18.73|10788591|1.69|
|BTW_USDT|1.624900|-12.14|-16.77|-13.42|25375117|1.23|
|AKE_USDT|0.027932|-10.16|11.42|-11.44|9595553|2.50|
|BR_USDT|0.597300|-8.20|37.94|-9.48|20344897|8.87|
|OP_USDT|0.129260|-1.54|-9.06|-2.82|7496070|1.55|
|TIA_USDT|0.615500|-1.15|6.61|-2.43|45362004|1.62|
|FILECOIN_USDT|1.030000|-0.96|-9.09|-2.24|10884209|0.97|
|QNT_USDT|194.200000|-0.49|-5.02|-1.77|75220022|0.52|
|SILVER_USDT|57.680000|-0.46|-2.87|-1.74|233301580|1.73|
|SEI_USDT|0.061410|-0.35|-1.53|-1.63|9990077|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045234|0.044473|0.045234|0.33|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027932|0.026106|0.027922|1.40|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.178110|0.177790|0.178040|1.05|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.597300|0.587090|0.597490|2.93|N|N/Y|N/N|N|N|
|BTW_USDT|1.624900|1.523600|1.624900|1.13|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.030000|1.033200|1.030000|4.66|Y|N/N|Y/N|N|N|
|OP_USDT|0.129260|0.129460|0.129260|3.14|Y|Y/N|N/N|N|N|
|QNT_USDT|194.200000|195.640000|194.090000|3.63|Y|N/N|N/N|N|N|
|SEI_USDT|0.061410|0.061680|0.061410|3.56|Y|N/N|N/N|N|N|
|SILVER_USDT|57.680000|57.450000|57.700000|2.06|N|N/N|N/N|N|N|
|TIA_USDT|0.615500|0.615000|0.615200|4.15|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.047381, depth_time=2026-10-21T13:45:08+00:00, book20_bid_proxy_usdt=6902, book20_ask_proxy_usdt=15669, funding_indicative=0.000071, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-30.00%, turnover=6588716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.034161, depth_time=2026-10-21T13:45:16+00:00, book20_bid_proxy_usdt=11157, book20_ask_proxy_usdt=13127, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.16%, turnover=9595553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.182410, depth_time=2026-10-21T13:45:11+00:00, book20_bid_proxy_usdt=21550, book20_ask_proxy_usdt=29115, funding_indicative=-0.000208, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-17.45%, turnover=10788591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.633520, depth_time=2026-10-21T13:45:19+00:00, book20_bid_proxy_usdt=4525, book20_ask_proxy_usdt=3005, funding_indicative=0.000037, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.20%, turnover=20344897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=1.710000, depth_time=2026-10-21T13:45:13+00:00, book20_bid_proxy_usdt=8728, book20_ask_proxy_usdt=8094, funding_indicative=-0.005571, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.14%, turnover=25375117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=1.047000, depth_time=2026-10-21T13:45:27+00:00, book20_bid_proxy_usdt=574373, book20_ask_proxy_usdt=672245, funding_indicative=-0.000009, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=10884209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.131020, depth_time=2026-10-21T13:45:21+00:00, book20_bid_proxy_usdt=66003, book20_ask_proxy_usdt=83304, funding_indicative=0.000028, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=7496070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=200.010000, depth_time=2026-10-21T13:45:29+00:00, book20_bid_proxy_usdt=87674, book20_ask_proxy_usdt=78585, funding_indicative=0.000026, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.49%, turnover=75220022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.062450, depth_time=2026-10-21T13:45:34+00:00, book20_bid_proxy_usdt=232229, book20_ask_proxy_usdt=230048, funding_indicative=-0.000043, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.35%, turnover=9990077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=57.950000, depth_time=2026-10-21T13:45:31+00:00, book20_bid_proxy_usdt=33568686, book20_ask_proxy_usdt=32024556, funding_indicative=0.000025, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.46%, turnover=233301580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T13:45:01+00:00, last15m_closed_end=2026-10-21T13:45+00:00, prior8high=0.626700, depth_time=2026-10-21T13:45:23+00:00, book20_bid_proxy_usdt=116300, book20_ask_proxy_usdt=248029, funding_indicative=-0.000079, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=45362004. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
