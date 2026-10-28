# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T10:30:26Z**
- feed_generated_utc: 2026-10-28T10:30:32+00:00
- source_sha256: `e2beedf22444cf6dfbc6c3beac671b044850292c1e40a4a793f85cb6c9909a21`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T10:30+00:00, close=81496.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T10:00+00:00, close=81515.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.056970|-10.40|-53.59|-11.59|23088067|1.75|
|AKE_USDT|0.019734|-6.58|-36.52|-7.77|6246419|3.55|
|BEAT_USDT|0.086280|-5.28|15.48|-6.47|15341777|4.63|
|SILVER_USDT|53.780000|-1.57|-7.19|-2.76|240272179|1.86|
|DASH_USDT|54.010000|-0.29|8.14|-1.48|15368801|1.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019734|0.020071|0.019883|4.13|Y|Y/Y|Y/Y|N|Y|
|BEAT_USDT|0.086280|0.084100|0.086190|1.17|N|Y/N|N/N|N|N|
|DASH_USDT|54.010000|53.790000|54.010000|0.47|N|Y/Y|N/N|N|N|
|Q_USDT|0.056970|0.056230|0.057110|0.54|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|53.780000|53.770000|53.780000|1.11|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T10:30:07+00:00, last15m_closed_end=2026-10-28T10:30+00:00, prior8high=0.021104, depth_time=2026-10-28T10:30:16+00:00, book20_bid_proxy_usdt=5751, book20_ask_proxy_usdt=3245, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.58%, turnover=6246419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T10:30:06+00:00, last15m_closed_end=2026-10-28T10:30+00:00, prior8high=0.106720, depth_time=2026-10-28T10:30:19+00:00, book20_bid_proxy_usdt=4935, book20_ask_proxy_usdt=9499, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.28%, turnover=15341777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T10:30:07+00:00, last15m_closed_end=2026-10-28T10:30+00:00, prior8high=54.470000, depth_time=2026-10-28T10:30:25+00:00, book20_bid_proxy_usdt=961178, book20_ask_proxy_usdt=578708, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.29%, turnover=15368801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T10:30:06+00:00, last15m_closed_end=2026-10-28T10:30+00:00, prior8high=0.061020, depth_time=2026-10-28T10:30:13+00:00, book20_bid_proxy_usdt=14624, book20_ask_proxy_usdt=29647, funding_indicative=-0.000319, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.40%, turnover=23088067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T10:30:06+00:00, last15m_closed_end=2026-10-28T10:30+00:00, prior8high=54.230000, depth_time=2026-10-28T10:30:21+00:00, book20_bid_proxy_usdt=44209956, book20_ask_proxy_usdt=56096296, funding_indicative=0.000012, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=240272179. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
