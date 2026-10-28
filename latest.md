# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T01:00:12Z**
- feed_generated_utc: 2026-10-28T01:00:15+00:00
- source_sha256: `694bb8fd624844a47f3f2c8e2f7c178e2b1e34ce4e071077b51b66a24ab8c300`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T01:00+00:00, close=80713.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T01:00+00:00, close=80713.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053482|-15.88|-56.43|-16.11|40131264|3.37|
|NIL_USDT|0.088120|-3.13|-0.83|-3.36|5691880|9.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.088120|0.088520|0.088120|2.56|Y|Y/Y|N/N|N|N|
|Q_USDT|0.053482|0.051075|0.053484|0.60|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-28T01:00:01+00:00, last15m_closed_end=2026-10-28T01:00+00:00, prior8high=0.092250, depth_time=2026-10-28T01:00:11+00:00, book20_bid_proxy_usdt=7354, book20_ask_proxy_usdt=2862, funding_indicative=-0.000401, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=5691880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T01:00:01+00:00, last15m_closed_end=2026-10-28T01:00+00:00, prior8high=0.054785, depth_time=2026-10-28T01:00:08+00:00, book20_bid_proxy_usdt=24022, book20_ask_proxy_usdt=27854, funding_indicative=-0.000204, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.88%, turnover=40131264. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
