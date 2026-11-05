# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T21:00:15Z**
- feed_generated_utc: 2026-11-05T21:00:16+00:00
- source_sha256: `51230e1a545d7885e646a73172f05faae79834429190d6d9588f3767535c6007`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T21:00+00:00, close=76205.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T21:00+00:00, close=76205.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002117|-17.94|-89.94|-18.17|19665645|4.72|
|BCH_USDT|275.420000|-1.32|-4.46|-1.55|10233011|3.63|
|QNT_USDT|189.520000|-1.19|-4.63|-1.42|44092569|0.53|
|XRP_USDT|1.232200|-0.99|-5.90|-1.22|432126668|0.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002117|0.002009|0.002117|0.30|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|275.420000|273.980000|275.420000|0.24|N|Y/Y|Y/N|Y|N|
|QNT_USDT|189.520000|187.630000|189.520000|0.57|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.232200|1.228700|1.232200|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T20:59:58+00:00, last15m_closed_end=2026-11-05T21:00+00:00, prior8high=0.002495, depth_time=2026-11-05T21:00:07+00:00, book20_bid_proxy_usdt=53776, book20_ask_proxy_usdt=31256, funding_indicative=-0.004318, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.94%, turnover=19665645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T20:59:58+00:00, last15m_closed_end=2026-11-05T21:00+00:00, prior8high=278.650000, depth_time=2026-11-05T21:00:10+00:00, book20_bid_proxy_usdt=42432, book20_ask_proxy_usdt=54997, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=10233011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T20:59:58+00:00, last15m_closed_end=2026-11-05T21:00+00:00, prior8high=193.570000, depth_time=2026-11-05T21:00:12+00:00, book20_bid_proxy_usdt=42752, book20_ask_proxy_usdt=44965, funding_indicative=0.000011, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=44092569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T20:59:58+00:00, last15m_closed_end=2026-11-05T21:00+00:00, prior8high=1.245300, depth_time=2026-11-05T21:00:14+00:00, book20_bid_proxy_usdt=2332123, book20_ask_proxy_usdt=2678867, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=432126668. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
