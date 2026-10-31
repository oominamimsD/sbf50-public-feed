# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T13:00:32Z**
- feed_generated_utc: 2026-10-31T13:00:35+00:00
- source_sha256: `1564e2e34bfdff3b85bef4769de120364b7f1e2ebf6526e27b432b72cc96ca8e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T13:00+00:00, close=77509.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T13:00+00:00, close=77509.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011733|-37.98|-66.47|-37.90|11343539|3.41|
|Q_USDT|0.031980|-32.64|-72.97|-32.56|12121128|3.12|
|BTW_USDT|1.115000|-8.40|-34.50|-8.32|8372658|1.79|
|BEAT_USDT|0.099300|-6.08|36.79|-6.00|7241654|3.02|
|TRX_USDT|0.318580|-5.30|-3.26|-5.22|6642608|0.31|
|HYPE_USDT|88.107000|-5.00|12.37|-4.92|90955744|0.11|
|WLD_USDT|0.397100|-3.59|-25.41|-3.51|42639416|2.52|
|FET_USDT|0.161100|-3.30|-13.98|-3.22|6037766|6.21|
|DASH_USDT|48.000000|-2.37|-10.86|-2.29|9405717|2.08|
|LTC_USDT|54.960000|-1.18|-5.97|-1.10|5757890|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011733|0.010668|0.011747|0.37|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099300|0.099730|0.099300|0.56|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.115000|1.081300|1.115000|3.54|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.000000|47.700000|48.000000|3.06|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161100|0.160400|0.161200|7.21|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.107000|87.134000|88.107000|1.75|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.960000|54.780000|54.960000|0.33|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031980|0.031390|0.031960|0.34|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318580|0.316430|0.318580|0.99|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397100|0.394200|0.397000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=0.012080, depth_time=2026-10-31T13:00:08+00:00, book20_bid_proxy_usdt=5719, book20_ask_proxy_usdt=9193, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.98%, turnover=11343539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=0.103100, depth_time=2026-10-31T13:00:16+00:00, book20_bid_proxy_usdt=10890, book20_ask_proxy_usdt=9150, funding_indicative=0.000205, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.08%, turnover=7241654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=1.204600, depth_time=2026-10-31T13:00:13+00:00, book20_bid_proxy_usdt=12824, book20_ask_proxy_usdt=10610, funding_indicative=-0.000361, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.40%, turnover=8372658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=48.200000, depth_time=2026-10-31T13:00:29+00:00, book20_bid_proxy_usdt=818248, book20_ask_proxy_usdt=605170, funding_indicative=-0.000104, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=9405717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=0.161900, depth_time=2026-10-31T13:00:25+00:00, book20_bid_proxy_usdt=1383290, book20_ask_proxy_usdt=746445, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=6037766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=88.782000, depth_time=2026-10-31T13:00:21+00:00, book20_bid_proxy_usdt=91838, book20_ask_proxy_usdt=133487, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.00%, turnover=90955744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=55.120000, depth_time=2026-10-31T13:00:32+00:00, book20_bid_proxy_usdt=1233076, book20_ask_proxy_usdt=1338236, funding_indicative=-0.000062, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=5757890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=0.033250, depth_time=2026-10-31T13:00:11+00:00, book20_bid_proxy_usdt=61641, book20_ask_proxy_usdt=46253, funding_indicative=-0.000451, next_funding_utc=2026-10-31T14:00:00+00:00, funding_cycle_h=1, 24h_change=-32.64%, turnover=12121128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=0.320970, depth_time=2026-10-31T13:00:18+00:00, book20_bid_proxy_usdt=52245, book20_ask_proxy_usdt=62210, funding_indicative=-0.000966, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.30%, turnover=6642608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T13:00:02+00:00, last15m_closed_end=2026-10-31T13:00+00:00, prior8high=0.398800, depth_time=2026-10-31T13:00:23+00:00, book20_bid_proxy_usdt=3355574, book20_ask_proxy_usdt=4015454, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.59%, turnover=42639416. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
