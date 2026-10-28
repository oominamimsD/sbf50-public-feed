# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T08:00:14Z**
- feed_generated_utc: 2026-10-28T08:00:17+00:00
- source_sha256: `871f27876856363217b0daf44fc0a6d3a57e516d9b4dc912d9daedd548bda899`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.020487|-30.70|-34.10|-31.59|5782650|2.44|
|Q_USDT|0.058500|-11.34|-52.34|-12.23|29430472|1.71|
|BULLA_USDT|0.067200|-2.74|-4.55|-3.63|10560955|2.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020487|0.020384|0.020487|0.41|N|Y/Y|Y/Y|N|N|
|BULLA_USDT|0.067200|0.057000|0.067160|0.76|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.058500|0.048529|0.058500|0.55|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T08:00:01+00:00, last15m_closed_end=2026-10-28T08:00+00:00, prior8high=0.021690, depth_time=2026-10-28T08:00:09+00:00, book20_bid_proxy_usdt=5356, book20_ask_proxy_usdt=9903, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-30.70%, turnover=5782650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T08:00:01+00:00, last15m_closed_end=2026-10-28T08:00+00:00, prior8high=0.069560, depth_time=2026-10-28T08:00:14+00:00, book20_bid_proxy_usdt=6920, book20_ask_proxy_usdt=10626, funding_indicative=-0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=10560955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T08:00:01+00:00, last15m_closed_end=2026-10-28T08:00+00:00, prior8high=0.074627, depth_time=2026-10-28T08:00:11+00:00, book20_bid_proxy_usdt=18935, book20_ask_proxy_usdt=21572, funding_indicative=-0.001105, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.34%, turnover=29430472. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
