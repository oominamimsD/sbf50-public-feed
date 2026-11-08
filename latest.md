# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T03:15:17Z**
- feed_generated_utc: 2026-11-08T03:15:18+00:00
- source_sha256: `3c5c069b4420266bf2064e87124865cf4ce228d090d1c7395b04a0d414779868`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T03:15+00:00, close=75870.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T03:00+00:00, close=75758, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001940|-4.74|65.23|-4.93|26430964|1.55|
|QNT_USDT|194.330000|-2.27|-3.34|-2.46|43419699|0.52|
|ENA_USDT|0.155210|-1.87|-19.99|-2.06|28032467|1.93|
|WLD_USDT|0.332100|-1.04|-17.87|-1.23|24877552|3.01|
|TIA_USDT|0.437200|-0.99|-10.79|-1.18|7180087|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.155210|0.153550|0.155210|1.36|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001940|0.001906|0.001940|1.04|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.330000|193.120000|194.330000|0.74|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.437200|0.434500|0.437200|0.72|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.332100|0.329000|0.332100|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T03:14:59+00:00, last15m_closed_end=2026-11-08T03:15+00:00, prior8high=0.157680, depth_time=2026-11-08T03:15:10+00:00, book20_bid_proxy_usdt=147272, book20_ask_proxy_usdt=189078, funding_indicative=-0.000046, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=28032467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T03:14:59+00:00, last15m_closed_end=2026-11-08T03:15+00:00, prior8high=0.002086, depth_time=2026-11-08T03:15:06+00:00, book20_bid_proxy_usdt=12329, book20_ask_proxy_usdt=11082, funding_indicative=-0.000064, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.74%, turnover=26430964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T03:14:59+00:00, last15m_closed_end=2026-11-08T03:15+00:00, prior8high=195.920000, depth_time=2026-11-08T03:15:09+00:00, book20_bid_proxy_usdt=62421, book20_ask_proxy_usdt=49675, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=43419699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T03:14:59+00:00, last15m_closed_end=2026-11-08T03:15+00:00, prior8high=0.438500, depth_time=2026-11-08T03:15:15+00:00, book20_bid_proxy_usdt=307230, book20_ask_proxy_usdt=314446, funding_indicative=0.000043, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=7180087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T03:14:59+00:00, last15m_closed_end=2026-11-08T03:15+00:00, prior8high=0.332400, depth_time=2026-11-08T03:15:14+00:00, book20_bid_proxy_usdt=3168636, book20_ask_proxy_usdt=3076920, funding_indicative=-0.000078, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=24877552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
