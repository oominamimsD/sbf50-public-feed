# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T08:45:34Z**
- feed_generated_utc: 2026-10-13T08:45:37+00:00
- source_sha256: `430030ccd4e445cb4883dc7b55620239b644b6d9f226a34b0b305b82b10de7a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T08:45+00:00, close=83772.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.226300|-21.83|6.24|-23.15|9402065|4.42|
|W_USDT|0.019328|-19.66|36.66|-20.98|30519237|8.80|
|NEAR_USDT|5.221000|-5.91|3.96|-7.23|272557629|1.92|
|LIT_USDT|3.411900|-5.88|-10.26|-7.20|10316411|0.29|
|ZRO_USDT|2.137200|-5.47|4.47|-6.79|25586583|2.81|
|STRK_USDT|0.086580|-4.51|66.14|-5.83|62132718|1.16|
|PUMPFUN_USDT|0.005101|-3.91|-19.47|-5.23|32083191|1.96|
|RLC_USDT|0.950500|-3.85|73.44|-5.17|6818473|1.05|
|SEI_USDT|0.064280|-3.14|-10.61|-4.46|9160706|1.56|
|PONS_USDT|0.287000|-2.61|-25.16|-3.93|6246124|3.48|
|JUP_USDT|0.334300|-2.50|-1.06|-3.82|8657523|2.99|
|QNT_USDT|226.060000|-1.01|-11.96|-2.33|77148949|1.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.226300|0.223500|0.226300|0.50|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.334300|0.333800|0.334300|0.76|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.411900|3.407500|3.411900|2.62|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.221000|5.151000|5.221000|0.83|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.287000|0.285600|0.287000|1.29|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005101|0.005044|0.005100|0.75|N|Y/Y|Y/Y|N|N|
|QNT_USDT|226.060000|224.910000|226.010000|1.33|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.950500|0.917000|0.950500|1.48|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.064280|0.064210|0.064280|0.75|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.086580|0.083010|0.086580|0.29|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019328|0.019206|0.019328|1.06|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.137200|2.075100|2.137200|0.92|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T08:45:00+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.234500, depth_time=2026-10-13T08:45:08+00:00, book20_bid_proxy_usdt=64035, book20_ask_proxy_usdt=68831, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.83%, turnover=9402065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.339000, depth_time=2026-10-13T08:45:29+00:00, book20_bid_proxy_usdt=672805, book20_ask_proxy_usdt=547636, funding_indicative=-0.000021, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=8657523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=3.461200, depth_time=2026-10-13T08:45:13+00:00, book20_bid_proxy_usdt=23430, book20_ask_proxy_usdt=36848, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.88%, turnover=10316411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T08:45:00+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=5.339000, depth_time=2026-10-13T08:45:11+00:00, book20_bid_proxy_usdt=2647268, book20_ask_proxy_usdt=3317335, funding_indicative=0.000012, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.91%, turnover=272557629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.295200, depth_time=2026-10-13T08:45:28+00:00, book20_bid_proxy_usdt=224618, book20_ask_proxy_usdt=221322, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=6246124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.005142, depth_time=2026-10-13T08:45:20+00:00, book20_bid_proxy_usdt=1753821, book20_ask_proxy_usdt=1825183, funding_indicative=-0.000008, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.91%, turnover=32083191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=230.870000, depth_time=2026-10-13T08:45:33+00:00, book20_bid_proxy_usdt=48082, book20_ask_proxy_usdt=57674, funding_indicative=0.000065, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=77148949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.959800, depth_time=2026-10-13T08:45:23+00:00, book20_bid_proxy_usdt=54749, book20_ask_proxy_usdt=49184, funding_indicative=-0.000914, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=6818473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.064840, depth_time=2026-10-13T08:45:26+00:00, book20_bid_proxy_usdt=170513, book20_ask_proxy_usdt=192960, funding_indicative=0.000035, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=9160706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T08:45:00+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.088100, depth_time=2026-10-13T08:45:19+00:00, book20_bid_proxy_usdt=166466, book20_ask_proxy_usdt=94443, funding_indicative=0.000015, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.51%, turnover=62132718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T08:45:00+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=0.019668, depth_time=2026-10-13T08:45:10+00:00, book20_bid_proxy_usdt=18895, book20_ask_proxy_usdt=22521, funding_indicative=-0.000499, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.66%, turnover=30519237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T08:45:01+00:00, last15m_closed_end=2026-10-13T08:45+00:00, prior8high=2.157300, depth_time=2026-10-13T08:45:17+00:00, book20_bid_proxy_usdt=33384, book20_ask_proxy_usdt=53214, funding_indicative=-0.000031, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.47%, turnover=25586583. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
