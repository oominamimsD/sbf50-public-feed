# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T01:30:27Z**
- feed_generated_utc: 2026-10-31T01:30:29+00:00
- source_sha256: `5cd396f6e9fce69332490f82d3a31a25ebe725b9e10a217d46b34c801e98bc98`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T01:30+00:00, close=77380.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T01:00+00:00, close=77521.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012838|-32.14|-63.31|-31.87|6113778|6.23|
|EVAA_USDT|1.122300|-12.46|113.81|-12.19|6590379|1.78|
|BEAT_USDT|0.098820|-6.01|36.13|-5.74|8405371|2.02|
|BTW_USDT|1.130000|-5.79|-33.62|-5.52|9598817|1.77|
|BLESS_USDT|0.009337|-5.21|14.40|-4.94|12426197|5.35|
|TRX_USDT|0.323100|-3.69|-1.89|-3.42|8700270|1.24|
|HYPE_USDT|89.165000|-3.44|13.72|-3.17|129395163|0.11|
|LIT_USDT|2.762500|-2.18|-16.89|-1.91|6793099|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012838|0.012618|0.012839|0.69|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098820|0.098180|0.098780|2.01|N|N/N|N/N|Y|N|
|BLESS_USDT|0.009337|0.009326|0.009337|0.59|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.130000|1.107500|1.130000|0.63|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.122300|1.123900|1.122300|0.50|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.165000|89.059000|89.165000|0.78|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.762500|2.737200|2.762500|0.34|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.323100|0.321930|0.323100|1.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=0.014277, depth_time=2026-10-31T01:30:08+00:00, book20_bid_proxy_usdt=3279, book20_ask_proxy_usdt=9106, funding_indicative=-0.000006, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-32.14%, turnover=6113778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=0.106950, depth_time=2026-10-31T01:30:12+00:00, book20_bid_proxy_usdt=7201, book20_ask_proxy_usdt=12216, funding_indicative=0.000226, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=8405371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=0.009963, depth_time=2026-10-31T01:30:19+00:00, book20_bid_proxy_usdt=17514, book20_ask_proxy_usdt=15256, funding_indicative=0.000116, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=12426197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=1.161000, depth_time=2026-10-31T01:30:16+00:00, book20_bid_proxy_usdt=24023, book20_ask_proxy_usdt=15253, funding_indicative=-0.000336, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.79%, turnover=9598817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=1.176200, depth_time=2026-10-31T01:30:09+00:00, book20_bid_proxy_usdt=4770, book20_ask_proxy_usdt=9570, funding_indicative=0.000073, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.46%, turnover=6590379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=90.278000, depth_time=2026-10-31T01:30:24+00:00, book20_bid_proxy_usdt=54234, book20_ask_proxy_usdt=175262, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=129395163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T01:30:01+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=2.789800, depth_time=2026-10-31T01:30:26+00:00, book20_bid_proxy_usdt=23138, book20_ask_proxy_usdt=26919, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=6793099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T01:30:00+00:00, last15m_closed_end=2026-10-31T01:30+00:00, prior8high=0.331360, depth_time=2026-10-31T01:30:16+00:00, book20_bid_proxy_usdt=85972, book20_ask_proxy_usdt=83280, funding_indicative=-0.001124, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=8700270. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
