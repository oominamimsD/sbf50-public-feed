# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T04:00:21Z**
- feed_generated_utc: 2026-10-19T04:00:23+00:00
- source_sha256: `9fc62cbf5c8a8a8fd9d8998cbcb6895e5a4fe251f4c98dfeb52abd0bd5c24e19`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.177000|-3.80|66.98|-5.47|7503267|5.64|
|HBAR_USDT|0.084080|-3.68|-10.34|-5.35|50795794|1.19|
|BAT_USDT|0.172120|-3.41|3.28|-5.08|6063430|0.58|
|BTW_USDT|2.268500|-3.39|34.85|-5.06|21425044|1.76|
|AGT_USDT|0.067553|-2.39|281.97|-4.06|7165537|0.44|
|STRK_USDT|0.060020|-1.31|-49.67|-2.98|17025596|1.67|
|TIA_USDT|0.614400|0.42|4.36|-1.25|55589533|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067553|0.062132|0.067553|1.31|N|Y/Y|N/N|N|N|
|BAT_USDT|0.172120|0.170000|0.172120|0.66|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.268500|2.217800|2.267900|0.81|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084080|0.083740|0.084080|0.17|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.177000|0.163100|0.177000|1.68|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060020|0.060000|0.060020|0.20|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.614400|0.614200|0.614400|0.58|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=0.075740, depth_time=2026-10-19T04:00:16+00:00, book20_bid_proxy_usdt=3121, book20_ask_proxy_usdt=4857, funding_indicative=0.000240, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=7165537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=0.176060, depth_time=2026-10-19T04:00:11+00:00, book20_bid_proxy_usdt=29230, book20_ask_proxy_usdt=21839, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=6063430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=2.347600, depth_time=2026-10-19T04:00:14+00:00, book20_bid_proxy_usdt=11043, book20_ask_proxy_usdt=8122, funding_indicative=-0.000205, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=21425044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=0.084590, depth_time=2026-10-19T04:00:08+00:00, book20_bid_proxy_usdt=1103394, book20_ask_proxy_usdt=1102894, funding_indicative=-0.000029, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=50795794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=0.180900, depth_time=2026-10-19T04:00:06+00:00, book20_bid_proxy_usdt=106785, book20_ask_proxy_usdt=116092, funding_indicative=-0.000090, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=7503267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=0.061960, depth_time=2026-10-19T04:00:18+00:00, book20_bid_proxy_usdt=704840, book20_ask_proxy_usdt=736334, funding_indicative=0.000008, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=17025596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T04:00:01+00:00, last15m_closed_end=2026-10-19T04:00+00:00, prior8high=0.631600, depth_time=2026-10-19T04:00:21+00:00, book20_bid_proxy_usdt=293626, book20_ask_proxy_usdt=301460, funding_indicative=0.000004, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.42%, turnover=55589533. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
