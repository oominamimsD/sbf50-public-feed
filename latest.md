# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T10:15:25Z**
- feed_generated_utc: 2026-11-08T10:15:26+00:00
- source_sha256: `35733f5041e63fd9b01325fe362ba11847a75270e5c0e4cf11a73787968cbb1f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T10:15+00:00, close=75853.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T10:00+00:00, close=75899.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.425900|-3.55|-13.09|-3.71|7375530|2.35|
|ENA_USDT|0.153400|-3.02|-20.93|-3.18|28139118|0.65|
|WLD_USDT|0.327300|-2.47|-19.06|-2.63|24022216|3.06|
|AAVE_USDT|130.510000|-1.30|-3.68|-1.46|10323997|0.77|
|ADA_USDT|0.179500|-1.15|-7.28|-1.31|9861232|5.57|
|SUI_USDT|0.847900|-1.07|-5.99|-1.23|21638337|1.18|
|DOGE_USDT|0.070820|-1.06|-6.37|-1.22|39882769|1.41|
|ONDO_USDT|0.359500|-0.99|-12.82|-1.15|8033103|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.510000|129.470000|130.510000|0.68|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179500|0.178900|0.179500|2.59|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.070820|0.070450|0.070820|0.46|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153400|0.152950|0.153400|1.73|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359500|0.358000|0.359500|0.85|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.847900|0.846700|0.847900|3.22|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.425900|0.424900|0.425900|0.41|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327300|0.325700|0.327300|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=130.820000, depth_time=2026-11-08T10:15:14+00:00, book20_bid_proxy_usdt=352862, book20_ask_proxy_usdt=730670, funding_indicative=0.000022, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=10323997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.180300, depth_time=2026-11-08T10:15:16+00:00, book20_bid_proxy_usdt=9454489, book20_ask_proxy_usdt=8568490, funding_indicative=-0.000049, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=9861232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.071270, depth_time=2026-11-08T10:15:21+00:00, book20_bid_proxy_usdt=3905284, book20_ask_proxy_usdt=6389847, funding_indicative=0.000061, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=39882769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.154630, depth_time=2026-11-08T10:15:08+00:00, book20_bid_proxy_usdt=238554, book20_ask_proxy_usdt=303762, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=28139118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.360600, depth_time=2026-11-08T10:15:22+00:00, book20_bid_proxy_usdt=1567466, book20_ask_proxy_usdt=1889503, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=8033103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.854000, depth_time=2026-11-08T10:15:18+00:00, book20_bid_proxy_usdt=1690991, book20_ask_proxy_usdt=1871857, funding_indicative=-0.000013, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=21638337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.430800, depth_time=2026-11-08T10:15:05+00:00, book20_bid_proxy_usdt=379023, book20_ask_proxy_usdt=384967, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=7375530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T10:15:01+00:00, last15m_closed_end=2026-11-08T10:15+00:00, prior8high=0.330100, depth_time=2026-11-08T10:15:10+00:00, book20_bid_proxy_usdt=3822283, book20_ask_proxy_usdt=4314095, funding_indicative=-0.000070, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=24022216. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
