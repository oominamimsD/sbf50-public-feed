# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T21:45:25Z**
- feed_generated_utc: 2026-10-31T21:45:27+00:00
- source_sha256: `1b7408b071f18e66be76db45d23f5de8667c59f2e80d5a5348492b3addb1c5c5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T21:45+00:00, close=77496.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T21:00+00:00, close=77523.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.242750|-18.03|44.56|-17.95|27513557|0.82|
|BLESS_USDT|0.009541|-9.68|17.60|-9.60|8130659|3.14|
|INJ_USDT|7.213000|-3.64|-4.00|-3.56|22152629|1.39|
|TRX_USDT|0.303130|-2.94|-7.84|-2.86|9870893|0.33|
|IDOL_USDT|0.017021|-2.85|115.45|-2.77|7091683|1.76|
|FET_USDT|0.160400|-1.77|-6.90|-1.69|5873892|6.23|
|WLD_USDT|0.397500|-1.70|-13.96|-1.62|34473042|2.52|
|APT_USDT|0.633600|-1.12|-9.73|-1.04|5039619|1.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.633600|0.629300|0.633600|9.97|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009541|0.009313|0.009541|1.42|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160400|0.159500|0.160400|2.27|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.017021|0.016323|0.017021|0.39|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.213000|7.202000|7.213000|0.34|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.242750|0.237140|0.242750|0.52|N|Y/N|N/N|Y|N|
|TRX_USDT|0.303130|0.302520|0.303130|1.78|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397500|0.394900|0.397500|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.635400, depth_time=2026-10-31T21:45:24+00:00, book20_bid_proxy_usdt=114445, book20_ask_proxy_usdt=150201, funding_indicative=0.000072, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=5039619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.010306, depth_time=2026-10-31T21:45:10+00:00, book20_bid_proxy_usdt=7790, book20_ask_proxy_usdt=11857, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.68%, turnover=8130659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.161400, depth_time=2026-10-31T21:45:20+00:00, book20_bid_proxy_usdt=1183279, book20_ask_proxy_usdt=867218, funding_indicative=-0.000181, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=5873892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.018086, depth_time=2026-10-31T21:45:16+00:00, book20_bid_proxy_usdt=7794, book20_ask_proxy_usdt=9193, funding_indicative=0.000101, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=7091683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=7.304000, depth_time=2026-10-31T21:45:13+00:00, book20_bid_proxy_usdt=348344, book20_ask_proxy_usdt=236043, funding_indicative=0.000176, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=22152629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.281310, depth_time=2026-10-31T21:45:07+00:00, book20_bid_proxy_usdt=4294, book20_ask_proxy_usdt=5861, funding_indicative=-0.000887, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.03%, turnover=27513557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.308070, depth_time=2026-10-31T21:45:15+00:00, book20_bid_proxy_usdt=61598, book20_ask_proxy_usdt=72372, funding_indicative=-0.000620, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=9870893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T21:44:59+00:00, last15m_closed_end=2026-10-31T21:45+00:00, prior8high=0.397900, depth_time=2026-10-31T21:45:22+00:00, book20_bid_proxy_usdt=2089478, book20_ask_proxy_usdt=2485408, funding_indicative=0.000100, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=34473042. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
