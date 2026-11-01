# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T05:00:24Z**
- feed_generated_utc: 2026-11-01T05:00:26+00:00
- source_sha256: `833611f67f809933b3c24a4b8b30f767303ca5ef86404b779b7d6c91f39afc0d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T05:00+00:00, close=77770.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T05:00+00:00, close=77770.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.240000|-18.96|42.92|-19.23|30378129|2.08|
|BLESS_USDT|0.009518|-10.72|17.31|-10.99|6438279|4.20|
|ENA_USDT|0.187410|-3.40|0.33|-3.67|42142282|0.53|
|ZEC_USDT|1248.550000|-2.80|9.02|-3.07|943859557|0.08|
|TRX_USDT|0.308910|-2.02|-6.08|-2.29|10789005|1.94|
|BEAT_USDT|0.097340|-1.21|45.26|-1.48|5978573|1.03|
|NEAR_USDT|4.386000|-0.88|-0.36|-1.15|51623903|2.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BEAT_USDT|0.097340|0.097020|0.097330|0.29|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009518|0.009236|0.009518|1.48|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187410|0.185670|0.187370|3.82|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.240000|0.226590|0.240370|0.74|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.386000|4.380000|4.386000|2.12|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.308910|0.307330|0.308910|0.29|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1248.550000|1238.800000|1248.550000|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BEAT_USDT: quote_utc=2026-11-01T05:00:02+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=0.099240, depth_time=2026-11-01T05:00:21+00:00, book20_bid_proxy_usdt=15353, book20_ask_proxy_usdt=15061, funding_indicative=0.000239, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=5978573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T05:00:02+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=0.009822, depth_time=2026-11-01T05:00:10+00:00, book20_bid_proxy_usdt=11309, book20_ask_proxy_usdt=14188, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.72%, turnover=6438279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T05:00:02+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=0.189100, depth_time=2026-11-01T05:00:13+00:00, book20_bid_proxy_usdt=111728, book20_ask_proxy_usdt=113502, funding_indicative=-0.000007, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.40%, turnover=42142282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T05:00:01+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=0.243180, depth_time=2026-11-01T05:00:08+00:00, book20_bid_proxy_usdt=16018, book20_ask_proxy_usdt=8986, funding_indicative=-0.001491, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.96%, turnover=30378129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T05:00:01+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=4.452000, depth_time=2026-11-01T05:00:22+00:00, book20_bid_proxy_usdt=5081029, book20_ask_proxy_usdt=3893109, funding_indicative=0.000098, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=51623903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T05:00:02+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=0.309910, depth_time=2026-11-01T05:00:18+00:00, book20_bid_proxy_usdt=114994, book20_ask_proxy_usdt=117417, funding_indicative=-0.000951, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=10789005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T05:00:02+00:00, last15m_closed_end=2026-11-01T05:00+00:00, prior8high=1249.000000, depth_time=2026-11-01T05:00:15+00:00, book20_bid_proxy_usdt=1748378, book20_ask_proxy_usdt=205874, funding_indicative=-0.000130, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=943859557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
