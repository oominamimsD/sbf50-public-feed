# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T06:00:26Z**
- feed_generated_utc: 2026-10-14T06:00:28+00:00
- source_sha256: `fc1ba033c5bf64d1c0389e339a71e6ca4b43fa5ebbf11c0c316c416b3b676157`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T06:00+00:00, close=83434.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T06:00+00:00, close=83434.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056790|-19.56|29.95|-19.60|24369518|3.52|
|STRK_USDT|0.081240|-6.54|55.66|-6.58|29960831|1.23|
|TIA_USDT|0.553600|-5.36|16.22|-5.40|44574302|1.81|
|MAGIC_USDT|0.112870|-4.87|65.69|-4.91|5611147|0.89|
|W_USDT|0.016043|-4.52|10.54|-4.56|7138893|1.87|
|UNI_USDT|7.299000|-3.60|-15.76|-3.64|20144203|1.37|
|SILVER_USDT|58.730000|-1.11|-4.30|-1.15|234135044|1.70|
|LINK_USDT|12.858000|-1.03|-7.73|-1.07|89481128|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LINK_USDT|12.858000|12.888000|12.858000|1.82|Y|Y/N|Y/Y|N|N|
|MAGIC_USDT|0.112870|0.112370|0.112870|2.64|N|Y/Y|Y/N|N|N|
|SILVER_USDT|58.730000|59.150000|58.770000|2.75|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.081240|0.080450|0.081200|2.08|N|Y/Y|Y/Y|N|N|
|S_USDT|0.056790|0.056650|0.056790|1.63|N|Y/N|N/N|N|N|
|TIA_USDT|0.553600|0.566000|0.553600|5.84|Y|Y/Y|N/N|N|N|
|UNI_USDT|7.299000|7.311000|7.299000|1.50|Y|Y/Y|Y/N|N|N|
|W_USDT|0.016043|0.015973|0.016043|1.40|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- LINK_USDT: quote_utc=2026-10-14T06:00:02+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=13.043000, depth_time=2026-10-14T06:00:25+00:00, book20_bid_proxy_usdt=448334, book20_ask_proxy_usdt=530584, funding_indicative=-0.000007, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=89481128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-14T05:59:58+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=0.115850, depth_time=2026-10-14T06:00:15+00:00, book20_bid_proxy_usdt=184415, book20_ask_proxy_usdt=175877, funding_indicative=-0.000096, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=5611147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T06:00:02+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=59.470000, depth_time=2026-10-14T06:00:23+00:00, book20_bid_proxy_usdt=40201298, book20_ask_proxy_usdt=58666292, funding_indicative=0.000078, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=234135044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T06:00:02+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=0.085530, depth_time=2026-10-14T06:00:09+00:00, book20_bid_proxy_usdt=156362, book20_ask_proxy_usdt=207435, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.54%, turnover=29960831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T06:00:02+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=0.060850, depth_time=2026-10-14T06:00:07+00:00, book20_bid_proxy_usdt=82522, book20_ask_proxy_usdt=96657, funding_indicative=-0.000074, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.56%, turnover=24369518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T06:00:02+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=0.581500, depth_time=2026-10-14T06:00:13+00:00, book20_bid_proxy_usdt=124808, book20_ask_proxy_usdt=208893, funding_indicative=-0.000015, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=44574302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T05:59:58+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=7.534000, depth_time=2026-10-14T06:00:20+00:00, book20_bid_proxy_usdt=1465105, book20_ask_proxy_usdt=1576799, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.60%, turnover=20144203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T05:59:58+00:00, last15m_closed_end=2026-10-14T06:00+00:00, prior8high=0.016644, depth_time=2026-10-14T06:00:18+00:00, book20_bid_proxy_usdt=41093, book20_ask_proxy_usdt=23326, funding_indicative=-0.000137, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=7138893. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
