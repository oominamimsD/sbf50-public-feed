# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T02:00:13Z**
- feed_generated_utc: 2026-10-16T02:00:15+00:00
- source_sha256: `2011c987b319b744b12e559c8aff0ea123826e6d3a0162585fa45f116f2abd9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T02:00+00:00, close=82052.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T02:00+00:00, close=82052.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.046830|-12.13|40.67|-11.74|6225694|4.27|
|BTW_USDT|1.822500|-5.55|31.27|-5.16|21834231|2.74|
|NIL_USDT|0.085720|-3.77|-1.00|-3.38|10784997|3.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.822500|1.802900|1.822500|1.52|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.085720|0.084360|0.085720|0.52|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.046830|0.046910|0.046860|4.78|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-16T02:00:00+00:00, last15m_closed_end=2026-10-16T02:00+00:00, prior8high=1.878400, depth_time=2026-10-16T02:00:10+00:00, book20_bid_proxy_usdt=11641, book20_ask_proxy_usdt=10209, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.55%, turnover=21834231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T02:00:00+00:00, last15m_closed_end=2026-10-16T02:00+00:00, prior8high=0.087500, depth_time=2026-10-16T02:00:11+00:00, book20_bid_proxy_usdt=22733, book20_ask_proxy_usdt=13578, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=10784997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T02:00:00+00:00, last15m_closed_end=2026-10-16T02:00+00:00, prior8high=0.051850, depth_time=2026-10-16T02:00:08+00:00, book20_bid_proxy_usdt=106633, book20_ask_proxy_usdt=86278, funding_indicative=-0.000529, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.13%, turnover=6225694. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
