# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T09:30:17Z**
- feed_generated_utc: 2026-10-28T09:30:20+00:00
- source_sha256: `0706d491bc9a740a467b64f8eb96b56f000e830a6565dc3de7d095ad288870cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T09:30+00:00, close=81436.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T09:00+00:00, close=81450, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.059040|-7.14|-51.90|-8.26|26139650|1.70|
|INJ_USDT|7.933000|-3.16|-7.75|-4.28|24998863|1.26|
|AKE_USDT|0.020590|-2.53|-33.77|-3.65|5981881|2.92|
|DASH_USDT|54.080000|-0.16|8.28|-1.28|16197656|1.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020590|0.020071|0.020590|1.24|N|Y/Y|Y/Y|N|N|
|DASH_USDT|54.080000|53.960000|54.080000|0.23|N|Y/Y|N/N|N|N|
|INJ_USDT|7.933000|7.895000|7.933000|0.88|N|Y/Y|N/N|N|N|
|Q_USDT|0.059040|0.055690|0.059040|0.37|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T09:30:02+00:00, last15m_closed_end=2026-10-28T09:30+00:00, prior8high=0.021005, depth_time=2026-10-28T09:30:13+00:00, book20_bid_proxy_usdt=3784, book20_ask_proxy_usdt=5569, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=5981881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T09:30:02+00:00, last15m_closed_end=2026-10-28T09:30+00:00, prior8high=54.730000, depth_time=2026-10-28T09:30:10+00:00, book20_bid_proxy_usdt=1101538, book20_ask_proxy_usdt=685260, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.16%, turnover=16197656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T09:30:02+00:00, last15m_closed_end=2026-10-28T09:30+00:00, prior8high=8.006000, depth_time=2026-10-28T09:30:10+00:00, book20_bid_proxy_usdt=314137, book20_ask_proxy_usdt=202498, funding_indicative=0.000247, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=24998863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T09:30:02+00:00, last15m_closed_end=2026-10-28T09:30+00:00, prior8high=0.061020, depth_time=2026-10-28T09:30:08+00:00, book20_bid_proxy_usdt=20209, book20_ask_proxy_usdt=10358, funding_indicative=-0.000576, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.14%, turnover=26139650. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
