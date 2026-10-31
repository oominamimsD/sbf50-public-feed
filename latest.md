# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T08:45:34Z**
- feed_generated_utc: 2026-10-31T08:45:37+00:00
- source_sha256: `c40ec077d8ec91ae1b2cbb68826a0232072f5b549ba91ba9058a2ad8b98c442c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T08:45+00:00, close=77259.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010611|-43.91|-69.68|-43.50|9782122|8.48|
|Q_USDT|0.032820|-30.87|-72.26|-30.46|18114908|9.14|
|BEAT_USDT|0.097820|-6.97|34.75|-6.56|8242583|1.02|
|HYPE_USDT|86.630000|-6.18|10.49|-5.77|105713953|0.12|
|EVAA_USDT|1.219600|-4.87|132.34|-4.46|5628756|4.10|
|TRX_USDT|0.319880|-4.65|-2.87|-4.24|6051791|2.19|
|WLD_USDT|0.396500|-3.73|-25.52|-3.32|48898602|2.52|
|FET_USDT|0.161600|-3.00|-13.72|-2.59|6054845|6.19|
|BTW_USDT|1.164100|-2.95|-31.62|-2.54|9555623|0.86|
|DASH_USDT|47.620000|-2.89|-11.56|-2.48|13562309|2.10|
|LTC_USDT|54.580000|-2.04|-6.62|-1.63|6622750|3.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010611|0.009146|0.010669|1.89|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097820|0.096500|0.097820|0.57|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.164100|1.124600|1.164100|1.00|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.620000|47.680000|47.620000|1.56|Y|Y/Y|Y/Y|Y|Y|
|EVAA_USDT|1.219600|1.168700|1.219300|0.72|N|N/N|N/N|Y|N|
|FET_USDT|0.161600|0.161600|0.161600|0.20|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.630000|87.166000|86.630000|3.23|Y|Y/Y|N/N|Y|N|
|LTC_USDT|54.580000|54.570000|54.580000|5.14|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.032820|0.031210|0.032820|0.33|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.319880|0.321050|0.319850|7.99|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.396500|0.395600|0.396500|1.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=0.013245, depth_time=2026-10-31T08:45:09+00:00, book20_bid_proxy_usdt=9513, book20_ask_proxy_usdt=4890, funding_indicative=-0.001422, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-43.91%, turnover=9782122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=0.098520, depth_time=2026-10-31T08:45:13+00:00, book20_bid_proxy_usdt=15493, book20_ask_proxy_usdt=11513, funding_indicative=0.000184, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=8242583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=1.181700, depth_time=2026-10-31T08:45:29+00:00, book20_bid_proxy_usdt=12913, book20_ask_proxy_usdt=11306, funding_indicative=-0.000297, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=9555623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T08:45:01+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=48.110000, depth_time=2026-10-31T08:45:30+00:00, book20_bid_proxy_usdt=910966, book20_ask_proxy_usdt=548458, funding_indicative=0.000044, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=13562309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=1.226600, depth_time=2026-10-31T08:45:18+00:00, book20_bid_proxy_usdt=10810, book20_ask_proxy_usdt=4822, funding_indicative=0.000215, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=5628756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=0.164200, depth_time=2026-10-31T08:45:26+00:00, book20_bid_proxy_usdt=1405169, book20_ask_proxy_usdt=761386, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=6054845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=88.891000, depth_time=2026-10-31T08:45:16+00:00, book20_bid_proxy_usdt=51146, book20_ask_proxy_usdt=193358, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.18%, turnover=105713953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=55.350000, depth_time=2026-10-31T08:45:32+00:00, book20_bid_proxy_usdt=1398230, book20_ask_proxy_usdt=1450415, funding_indicative=0.000021, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=6622750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=0.033340, depth_time=2026-10-31T08:45:11+00:00, book20_bid_proxy_usdt=76991, book20_ask_proxy_usdt=52643, funding_indicative=-0.000705, next_funding_utc=2026-10-31T09:00:00+00:00, funding_cycle_h=1, 24h_change=-30.87%, turnover=18114908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=0.325500, depth_time=2026-10-31T08:45:21+00:00, book20_bid_proxy_usdt=83941, book20_ask_proxy_usdt=117878, funding_indicative=-0.000377, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.65%, turnover=6051791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T08:45:00+00:00, last15m_closed_end=2026-10-31T08:45+00:00, prior8high=0.401700, depth_time=2026-10-31T08:45:24+00:00, book20_bid_proxy_usdt=2697586, book20_ask_proxy_usdt=2540084, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=48898602. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
