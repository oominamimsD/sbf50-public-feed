# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T19:15:18Z**
- feed_generated_utc: 2026-10-30T19:15:19+00:00
- source_sha256: `a7929ffa4a37556e7d4fa721f72e41a561fe5e1433ea0749068c8de3894dcee1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T19:15+00:00, close=76500.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T19:00+00:00, close=76616.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.140500|-11.04|117.27|-9.65|6704852|7.01|
|BLESS_USDT|0.008823|-10.43|8.11|-9.04|14957940|2.27|
|Q_USDT|0.045020|-5.18|-61.95|-3.79|24318393|4.45|
|PUMPFUN_USDT|0.003962|-3.53|-13.17|-2.14|25345884|2.53|
|LIT_USDT|2.742600|-2.88|-17.49|-1.49|12392729|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.008823|0.008535|0.008854|0.47|N|Y/Y|Y/N|Y|N|
|EVAA_USDT|1.140500|1.072200|1.142500|1.65|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.742600|2.683300|2.742600|0.62|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003962|0.003918|0.003962|0.65|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045020|0.044090|0.045020|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T19:15:02+00:00, last15m_closed_end=2026-10-30T19:15+00:00, prior8high=0.009789, depth_time=2026-10-30T19:15:10+00:00, book20_bid_proxy_usdt=10731, book20_ask_proxy_usdt=12985, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.43%, turnover=14957940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T19:15:02+00:00, last15m_closed_end=2026-10-30T19:15+00:00, prior8high=1.298300, depth_time=2026-10-30T19:15:07+00:00, book20_bid_proxy_usdt=5201, book20_ask_proxy_usdt=4239, funding_indicative=0.000138, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.04%, turnover=6704852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T19:15:02+00:00, last15m_closed_end=2026-10-30T19:15+00:00, prior8high=2.800000, depth_time=2026-10-30T19:15:17+00:00, book20_bid_proxy_usdt=22766, book20_ask_proxy_usdt=27130, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=12392729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T19:15:02+00:00, last15m_closed_end=2026-10-30T19:15+00:00, prior8high=0.004070, depth_time=2026-10-30T19:15:14+00:00, book20_bid_proxy_usdt=299855, book20_ask_proxy_usdt=524410, funding_indicative=-0.000017, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.53%, turnover=25345884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T19:15:01+00:00, last15m_closed_end=2026-10-30T19:15+00:00, prior8high=0.048350, depth_time=2026-10-30T19:15:12+00:00, book20_bid_proxy_usdt=23598, book20_ask_proxy_usdt=39500, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.18%, turnover=24318393. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
