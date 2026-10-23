# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T08:00:24Z**
- feed_generated_utc: 2026-10-23T08:00:26+00:00
- source_sha256: `51726f761b7c065b926a1c02ba39646eadfc34de46f427a8c21da867fdb25450`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.409300|-6.34|10.28|-5.98|9493253|0.29|
|STRK_USDT|0.052870|-3.76|-45.13|-3.40|10447009|1.89|
|TIA_USDT|0.554800|-3.63|-7.91|-3.27|24462871|1.80|
|QNT_USDT|187.790000|-2.65|-9.67|-2.29|47620583|0.53|
|SILVER_USDT|53.920000|-2.42|-5.63|-2.06|336107564|1.85|
|PUMPFUN_USDT|0.004593|-2.29|1.48|-1.93|37272357|2.18|
|XMR_USDT|610.000000|-1.70|12.14|-1.34|19928497|0.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.409300|3.409600|3.409300|1.99|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004593|0.004606|0.004593|1.07|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.790000|187.970000|187.790000|1.56|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|53.920000|53.920000|53.930000|0.77|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052870|0.052400|0.052870|4.12|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.554800|0.557000|0.554800|2.16|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|610.000000|604.400000|610.000000|0.29|N|Y/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=3.450000, depth_time=2026-10-23T08:00:08+00:00, book20_bid_proxy_usdt=25778, book20_ask_proxy_usdt=29077, funding_indicative=-0.000009, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=9493253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=0.004684, depth_time=2026-10-23T08:00:21+00:00, book20_bid_proxy_usdt=2331763, book20_ask_proxy_usdt=1290999, funding_indicative=0.000008, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=37272357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=190.340000, depth_time=2026-10-23T08:00:16+00:00, book20_bid_proxy_usdt=86685, book20_ask_proxy_usdt=52789, funding_indicative=-0.000138, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=47620583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=54.630000, depth_time=2026-10-23T08:00:19+00:00, book20_bid_proxy_usdt=28841914, book20_ask_proxy_usdt=34950075, funding_indicative=0.000163, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=336107564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=0.053510, depth_time=2026-10-23T08:00:10+00:00, book20_bid_proxy_usdt=811435, book20_ask_proxy_usdt=554389, funding_indicative=-0.000035, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.76%, turnover=10447009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=0.562000, depth_time=2026-10-23T08:00:14+00:00, book20_bid_proxy_usdt=218343, book20_ask_proxy_usdt=356731, funding_indicative=-0.000014, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=24462871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T08:00:01+00:00, last15m_closed_end=2026-10-23T08:00+00:00, prior8high=613.420000, depth_time=2026-10-23T08:00:21+00:00, book20_bid_proxy_usdt=16799, book20_ask_proxy_usdt=13154, funding_indicative=0.000100, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=19928497. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
