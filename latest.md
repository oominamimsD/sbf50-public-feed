# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T22:45:21Z**
- feed_generated_utc: 2026-10-30T22:45:23+00:00
- source_sha256: `7a1ca50b9a1d8d76882321f1fc7628aae35dcb27c968ee571971840d76a8aa49`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T22:45+00:00, close=76954.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T22:00+00:00, close=76670.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013164|-30.42|-62.38|-29.62|5256608|7.60|
|EVAA_USDT|1.120900|-12.57|113.54|-11.77|6715900|1.78|
|BTW_USDT|1.146000|-4.46|-32.68|-3.66|10487180|4.36|
|HYPE_USDT|89.400000|-3.18|14.02|-2.38|155126560|0.11|
|LIT_USDT|2.740000|-2.98|-17.56|-2.18|9513392|0.36|
|TRX_USDT|0.329330|-1.83|0.00|-1.03|13700835|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013164|0.013039|0.013164|0.69|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.146000|1.144800|1.146000|0.69|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.120900|1.082800|1.120900|0.53|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.400000|89.002000|89.400000|0.78|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.740000|2.686200|2.740000|0.33|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.329330|0.329510|0.329330|0.70|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T22:45:01+00:00, last15m_closed_end=2026-10-30T22:45+00:00, prior8high=0.014049, depth_time=2026-10-30T22:45:08+00:00, book20_bid_proxy_usdt=6590, book20_ask_proxy_usdt=6444, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-30.42%, turnover=5256608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T22:45:01+00:00, last15m_closed_end=2026-10-30T22:45+00:00, prior8high=1.262200, depth_time=2026-10-30T22:45:13+00:00, book20_bid_proxy_usdt=16203, book20_ask_proxy_usdt=18877, funding_indicative=-0.000277, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=10487180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T22:45:01+00:00, last15m_closed_end=2026-10-30T22:45+00:00, prior8high=1.132500, depth_time=2026-10-30T22:45:09+00:00, book20_bid_proxy_usdt=4869, book20_ask_proxy_usdt=9999, funding_indicative=0.000131, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.57%, turnover=6715900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T22:45:01+00:00, last15m_closed_end=2026-10-30T22:45+00:00, prior8high=90.590000, depth_time=2026-10-30T22:45:16+00:00, book20_bid_proxy_usdt=70951, book20_ask_proxy_usdt=174328, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=155126560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T22:45:01+00:00, last15m_closed_end=2026-10-30T22:45+00:00, prior8high=2.738800, depth_time=2026-10-30T22:45:17+00:00, book20_bid_proxy_usdt=34387, book20_ask_proxy_usdt=24388, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=9513392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-30T22:45:01+00:00, last15m_closed_end=2026-10-30T22:45+00:00, prior8high=0.332130, depth_time=2026-10-30T22:45:20+00:00, book20_bid_proxy_usdt=108159, book20_ask_proxy_usdt=104709, funding_indicative=-0.000217, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=13700835. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
