# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T22:15:35Z**
- feed_generated_utc: 2026-11-02T22:15:38+00:00
- source_sha256: `df58deb7def5143c45127bebe92946d8c5f99331bceaf10037d05607ad437724`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T22:15+00:00, close=76870.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T22:00+00:00, close=76830.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.116900|-11.90|-53.01|-11.12|6449393|8.56|
|ZEC_USDT|1154.640000|-7.93|-7.46|-7.15|1864728921|0.09|
|XPL_USDT|0.066860|-3.90|-10.00|-3.12|10294930|1.50|
|PUMPFUN_USDT|0.003967|-3.33|-8.34|-2.55|9416233|2.52|
|QNT_USDT|195.780000|-3.29|-6.89|-2.51|49285927|0.51|
|NEAR_USDT|3.892000|-2.94|-14.89|-2.16|82348152|2.57|
|ZRO_USDT|1.718400|-2.81|0.66|-2.03|5947756|1.16|
|AAVE_USDT|127.280000|-2.51|-6.91|-1.73|23336248|0.79|
|XLM_USDT|0.163810|-2.26|-3.40|-1.48|33250701|0.61|
|ENA_USDT|0.171420|-2.06|-18.51|-1.28|74214877|0.58|
|ARB_USDT|0.156410|-1.83|-7.98|-1.05|13373137|0.64|
|TRUMPOFFICIAL_USDT|1.606000|-1.83|-4.91|-1.05|12478239|6.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.280000|126.730000|127.280000|0.62|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.156410|0.155130|0.156410|0.59|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171420|0.169020|0.171430|0.24|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.892000|3.856000|3.893000|0.54|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003967|0.003913|0.003967|0.30|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.780000|192.940000|195.780000|1.29|N|Y/Y|Y/N|Y|N|
|TRUMPOFFICIAL_USDT|1.606000|1.576000|1.606000|0.83|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.116900|0.112100|0.116900|0.74|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163810|0.163550|0.163850|0.46|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066860|0.066130|0.066860|1.06|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1154.640000|1135.710000|1153.660000|0.69|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.718400|1.692200|1.718400|0.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T22:15:03+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=128.160000, depth_time=2026-11-02T22:15:24+00:00, book20_bid_proxy_usdt=386144, book20_ask_proxy_usdt=581516, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=23336248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T22:15:04+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=0.157420, depth_time=2026-11-02T22:15:31+00:00, book20_bid_proxy_usdt=75515, book20_ask_proxy_usdt=80217, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=13373137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T22:15:03+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=0.172390, depth_time=2026-11-02T22:15:28+00:00, book20_bid_proxy_usdt=178675, book20_ask_proxy_usdt=254972, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=74214877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T22:15:03+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=3.936000, depth_time=2026-11-02T22:15:19+00:00, book20_bid_proxy_usdt=4613176, book20_ask_proxy_usdt=4869827, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=82348152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T22:15:04+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=0.003996, depth_time=2026-11-02T22:15:15+00:00, book20_bid_proxy_usdt=3274106, book20_ask_proxy_usdt=2623256, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=9416233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T22:15:03+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=197.490000, depth_time=2026-11-02T22:15:17+00:00, book20_bid_proxy_usdt=84886, book20_ask_proxy_usdt=38369, funding_indicative=0.000093, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=49285927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T22:15:04+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=1.609000, depth_time=2026-11-02T22:15:33+00:00, book20_bid_proxy_usdt=2232546, book20_ask_proxy_usdt=1669737, funding_indicative=-0.000017, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=12478239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T22:15:03+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=0.121600, depth_time=2026-11-02T22:15:06+00:00, book20_bid_proxy_usdt=152930, book20_ask_proxy_usdt=101883, funding_indicative=-0.000090, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.90%, turnover=6449393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T22:15:04+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=0.165410, depth_time=2026-11-02T22:15:24+00:00, book20_bid_proxy_usdt=127721, book20_ask_proxy_usdt=176666, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=33250701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T22:15:04+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=0.067700, depth_time=2026-11-02T22:15:09+00:00, book20_bid_proxy_usdt=329618, book20_ask_proxy_usdt=637289, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=10294930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T22:15:03+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=1164.850000, depth_time=2026-11-02T22:15:10+00:00, book20_bid_proxy_usdt=251850, book20_ask_proxy_usdt=392177, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.93%, turnover=1864728921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T22:15:04+00:00, last15m_closed_end=2026-11-02T22:15+00:00, prior8high=1.727400, depth_time=2026-11-02T22:15:22+00:00, book20_bid_proxy_usdt=30409, book20_ask_proxy_usdt=80185, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=5947756. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
