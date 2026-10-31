# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T22:00:22Z**
- feed_generated_utc: 2026-10-31T22:00:24+00:00
- source_sha256: `d3a820cc908089726c1c800161994b6b2140c7f1c8c0867f293e1697a95f4563`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T22:00+00:00, close=77631.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T22:00+00:00, close=77631.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.242490|-18.12|44.40|-18.21|27771487|1.24|
|BLESS_USDT|0.009496|-10.10|17.04|-10.19|7868381|3.16|
|IDOL_USDT|0.016994|-3.00|115.11|-3.09|6675378|3.53|
|TRX_USDT|0.303680|-2.76|-7.67|-2.85|9921010|0.33|
|BTW_USDT|1.110700|-2.68|-36.21|-2.77|5558679|3.60|
|FET_USDT|0.160700|-1.59|-6.73|-1.68|5645374|6.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009496|0.009313|0.009505|0.96|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.110700|1.106900|1.110700|0.84|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160700|0.159500|0.160800|1.63|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.016994|0.016323|0.016973|0.76|N|Y/Y|N/N|Y|N|
|LSK_USDT|0.242490|0.237140|0.242730|1.33|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.303680|0.301700|0.303760|0.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-31T22:00:04+00:00, last15m_closed_end=2026-10-31T22:00+00:00, prior8high=0.010182, depth_time=2026-10-31T22:00:11+00:00, book20_bid_proxy_usdt=9314, book20_ask_proxy_usdt=10083, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.10%, turnover=7868381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T22:00:04+00:00, last15m_closed_end=2026-10-31T22:00+00:00, prior8high=1.131000, depth_time=2026-10-31T22:00:16+00:00, book20_bid_proxy_usdt=12546, book20_ask_proxy_usdt=19916, funding_indicative=-0.000091, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=5558679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T22:00:04+00:00, last15m_closed_end=2026-10-31T22:00+00:00, prior8high=0.161300, depth_time=2026-10-31T22:00:20+00:00, book20_bid_proxy_usdt=1301251, book20_ask_proxy_usdt=923454, funding_indicative=-0.000186, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=5645374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T22:00:04+00:00, last15m_closed_end=2026-10-31T22:00+00:00, prior8high=0.017700, depth_time=2026-10-31T22:00:12+00:00, book20_bid_proxy_usdt=9681, book20_ask_proxy_usdt=10870, funding_indicative=0.000109, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=6675378. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T22:00:04+00:00, last15m_closed_end=2026-10-31T22:00+00:00, prior8high=0.260000, depth_time=2026-10-31T22:00:09+00:00, book20_bid_proxy_usdt=4842, book20_ask_proxy_usdt=7316, funding_indicative=-0.000881, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.12%, turnover=27771487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T22:00:04+00:00, last15m_closed_end=2026-10-31T22:00+00:00, prior8high=0.308070, depth_time=2026-10-31T22:00:16+00:00, book20_bid_proxy_usdt=101784, book20_ask_proxy_usdt=108712, funding_indicative=-0.000714, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=9921010. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
