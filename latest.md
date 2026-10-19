# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T10:15:20Z**
- feed_generated_utc: 2026-10-19T10:15:22+00:00
- source_sha256: `ebf0adb882a54a6db71b3d12e188a47069d816f74dfd0d3cd822215067612fef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T10:15+00:00, close=82651, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T10:00+00:00, close=82729.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.170100|-5.86|29.00|-7.71|21263038|1.84|
|STRK_USDT|0.059300|-3.67|-50.28|-5.52|17571156|1.69|
|HBAR_USDT|0.083930|-2.15|-10.50|-4.00|43955080|1.19|
|TIA_USDT|0.612200|-0.92|3.99|-2.77|52688997|1.63|
|SAND_USDT|0.058450|-0.52|-12.02|-2.37|15502853|3.42|
|SEI_USDT|0.060250|0.01|-15.00|-1.84|8684343|1.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.170100|2.155000|2.170100|1.41|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.083930|0.084050|0.083970|1.31|Y|Y/Y|Y/Y|N|Y|
|SAND_USDT|0.058450|0.058100|0.058470|0.36|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060250|0.060240|0.060240|1.89|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.059300|0.059130|0.059300|0.92|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.612200|0.605200|0.612200|0.90|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T10:15:02+00:00, last15m_closed_end=2026-10-19T10:15+00:00, prior8high=2.310800, depth_time=2026-10-19T10:15:06+00:00, book20_bid_proxy_usdt=12794, book20_ask_proxy_usdt=25837, funding_indicative=-0.000582, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.86%, turnover=21263038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T10:15:02+00:00, last15m_closed_end=2026-10-19T10:15+00:00, prior8high=0.084960, depth_time=2026-10-19T10:15:12+00:00, book20_bid_proxy_usdt=1124636, book20_ask_proxy_usdt=523933, funding_indicative=-0.000052, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=43955080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T10:15:02+00:00, last15m_closed_end=2026-10-19T10:15+00:00, prior8high=0.060320, depth_time=2026-10-19T10:15:15+00:00, book20_bid_proxy_usdt=649621, book20_ask_proxy_usdt=750169, funding_indicative=-0.003915, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.52%, turnover=15502853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T10:15:02+00:00, last15m_closed_end=2026-10-19T10:15+00:00, prior8high=0.061600, depth_time=2026-10-19T10:15:20+00:00, book20_bid_proxy_usdt=211066, book20_ask_proxy_usdt=333949, funding_indicative=0.000035, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.01%, turnover=8684343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T10:15:02+00:00, last15m_closed_end=2026-10-19T10:15+00:00, prior8high=0.059970, depth_time=2026-10-19T10:15:10+00:00, book20_bid_proxy_usdt=807589, book20_ask_proxy_usdt=754130, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.67%, turnover=17571156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T10:15:02+00:00, last15m_closed_end=2026-10-19T10:15+00:00, prior8high=0.614400, depth_time=2026-10-19T10:15:15+00:00, book20_bid_proxy_usdt=192030, book20_ask_proxy_usdt=314393, funding_indicative=0.000001, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=52688997. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
