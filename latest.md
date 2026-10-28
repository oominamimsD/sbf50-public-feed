# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T09:00:19Z**
- feed_generated_utc: 2026-10-28T09:00:22+00:00
- source_sha256: `095e106a0fba08aad04b23d3bfa34a08c24eba5bcd8c6da1e3e766588eb38b0c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T09:00+00:00, close=81450, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T09:00+00:00, close=81450, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.058900|-7.36|-52.01|-8.53|25956067|3.39|
|AKE_USDT|0.020196|-4.39|-35.04|-5.56|5876669|0.49|
|BULLA_USDT|0.066340|-3.99|-5.78|-5.16|10495868|3.02|
|INJ_USDT|7.916000|-3.36|-7.95|-4.53|24732287|1.26|
|QNT_USDT|198.000000|0.05|1.45|-1.12|70814476|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020196|0.020149|0.020197|0.63|N|Y/Y|Y/Y|N|N|
|BULLA_USDT|0.066340|0.061910|0.066310|0.57|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.916000|7.913000|7.913000|1.41|N|Y/Y|N/N|N|N|
|QNT_USDT|198.000000|197.650000|197.810000|0.69|N|Y/Y|N/N|N|N|
|Q_USDT|0.058900|0.053780|0.058970|0.84|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T09:00:02+00:00, last15m_closed_end=2026-10-28T09:00+00:00, prior8high=0.021100, depth_time=2026-10-28T09:00:11+00:00, book20_bid_proxy_usdt=5735, book20_ask_proxy_usdt=6206, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.39%, turnover=5876669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T09:00:02+00:00, last15m_closed_end=2026-10-28T09:00+00:00, prior8high=0.070500, depth_time=2026-10-28T09:00:13+00:00, book20_bid_proxy_usdt=7468, book20_ask_proxy_usdt=7271, funding_indicative=-0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=10495868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T09:00:02+00:00, last15m_closed_end=2026-10-28T09:00+00:00, prior8high=8.006000, depth_time=2026-10-28T09:00:16+00:00, book20_bid_proxy_usdt=296444, book20_ask_proxy_usdt=151233, funding_indicative=0.000243, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=24732287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T09:00:02+00:00, last15m_closed_end=2026-10-28T09:00+00:00, prior8high=201.750000, depth_time=2026-10-28T09:00:18+00:00, book20_bid_proxy_usdt=72763, book20_ask_proxy_usdt=85068, funding_indicative=-0.000369, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.05%, turnover=70814476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T09:00:02+00:00, last15m_closed_end=2026-10-28T09:00+00:00, prior8high=0.061120, depth_time=2026-10-28T09:00:09+00:00, book20_bid_proxy_usdt=19653, book20_ask_proxy_usdt=22294, funding_indicative=-0.000765, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.36%, turnover=25956067. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
