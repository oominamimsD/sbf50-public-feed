# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T03:30:20Z**
- feed_generated_utc: 2026-10-23T03:30:22+00:00
- source_sha256: `dbdb522d6922064a4dff483ad07d6497b74ba0b3eae6822ed8c5bff3705be9d7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T03:30+00:00, close=81755.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T03:00+00:00, close=81942.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.487100|-3.51|12.80|-3.63|11077956|0.29|
|PHA_USDT|0.060280|-2.85|19.31|-2.97|8165464|4.98|
|SILVER_USDT|54.120000|-2.06|-5.28|-2.18|372017621|1.85|
|STRK_USDT|0.053240|-2.06|-44.74|-2.18|12040582|1.88|
|ZEC_USDT|1220.750000|-1.09|3.47|-1.21|1914751894|0.08|
|TIA_USDT|0.563200|-0.91|-6.52|-1.03|23524148|1.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.487100|3.385300|3.487100|0.48|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.060280|0.059190|0.060280|1.79|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.120000|53.570000|54.120000|0.82|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053240|0.052520|0.053240|1.72|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.563200|0.554300|0.563200|0.85|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1220.750000|1210.650000|1220.750000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T03:30:01+00:00, last15m_closed_end=2026-10-23T03:30+00:00, prior8high=3.544400, depth_time=2026-10-23T03:30:07+00:00, book20_bid_proxy_usdt=18671, book20_ask_proxy_usdt=25498, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.51%, turnover=11077956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T03:30:00+00:00, last15m_closed_end=2026-10-23T03:30+00:00, prior8high=0.060450, depth_time=2026-10-23T03:30:09+00:00, book20_bid_proxy_usdt=59050, book20_ask_proxy_usdt=82748, funding_indicative=-0.000451, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=8165464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T03:30:00+00:00, last15m_closed_end=2026-10-23T03:30+00:00, prior8high=54.590000, depth_time=2026-10-23T03:30:12+00:00, book20_bid_proxy_usdt=27088006, book20_ask_proxy_usdt=30877214, funding_indicative=0.000085, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=372017621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T03:30:01+00:00, last15m_closed_end=2026-10-23T03:30+00:00, prior8high=0.053500, depth_time=2026-10-23T03:30:14+00:00, book20_bid_proxy_usdt=497069, book20_ask_proxy_usdt=579756, funding_indicative=0.000029, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=12040582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T03:30:00+00:00, last15m_closed_end=2026-10-23T03:30+00:00, prior8high=0.567500, depth_time=2026-10-23T03:30:19+00:00, book20_bid_proxy_usdt=342850, book20_ask_proxy_usdt=289625, funding_indicative=-0.000002, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=23524148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T03:30:00+00:00, last15m_closed_end=2026-10-23T03:30+00:00, prior8high=1244.740000, depth_time=2026-10-23T03:30:17+00:00, book20_bid_proxy_usdt=344247, book20_ask_proxy_usdt=192028, funding_indicative=0.000008, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=1914751894. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
