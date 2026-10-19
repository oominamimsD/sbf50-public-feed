# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T08:00:18Z**
- feed_generated_utc: 2026-10-19T08:00:20+00:00
- source_sha256: `600694728edae51ee16e9eafe69543b5387a7d913b5c887bf8603a1a21cf12ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.170500|-7.33|60.84|-9.24|6801064|5.87|
|BTW_USDT|2.243500|-4.46|33.36|-6.37|21397395|2.23|
|HBAR_USDT|0.084430|-3.28|-9.97|-5.19|47778436|1.18|
|STRK_USDT|0.059660|-1.90|-49.97|-3.81|17674572|1.68|
|TIA_USDT|0.614400|0.42|4.36|-1.49|56557793|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.243500|2.166400|2.243400|0.67|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084430|0.084010|0.084430|0.64|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.170500|0.167000|0.170500|0.40|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.059660|0.059350|0.059660|0.77|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.614400|0.606800|0.614400|2.94|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T08:00:02+00:00, last15m_closed_end=2026-10-19T08:00+00:00, prior8high=2.321000, depth_time=2026-10-19T08:00:10+00:00, book20_bid_proxy_usdt=9599, book20_ask_proxy_usdt=12736, funding_indicative=-0.000297, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=21397395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T08:00:02+00:00, last15m_closed_end=2026-10-19T08:00+00:00, prior8high=0.085160, depth_time=2026-10-19T08:00:12+00:00, book20_bid_proxy_usdt=1037332, book20_ask_proxy_usdt=956798, funding_indicative=-0.000056, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=47778436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T08:00:02+00:00, last15m_closed_end=2026-10-19T08:00+00:00, prior8high=0.178300, depth_time=2026-10-19T08:00:07+00:00, book20_bid_proxy_usdt=127340, book20_ask_proxy_usdt=109704, funding_indicative=-0.000073, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.33%, turnover=6801064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T08:00:02+00:00, last15m_closed_end=2026-10-19T08:00+00:00, prior8high=0.060350, depth_time=2026-10-19T08:00:14+00:00, book20_bid_proxy_usdt=918295, book20_ask_proxy_usdt=657126, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=17674572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T08:00:02+00:00, last15m_closed_end=2026-10-19T08:00+00:00, prior8high=0.620500, depth_time=2026-10-19T08:00:17+00:00, book20_bid_proxy_usdt=396458, book20_ask_proxy_usdt=325309, funding_indicative=-0.000051, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=0.42%, turnover=56557793. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
