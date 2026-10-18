# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T10:15:26Z**
- feed_generated_utc: 2026-10-18T10:15:27+00:00
- source_sha256: `0ab7e0b0aa14b9cc184f8739433d0bf177ba92ae94c4e0da756994aa117a152a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T10:15+00:00, close=82191.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T10:00+00:00, close=82122.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063300|-4.30|-32.24|-5.36|14372051|1.58|
|EIGEN_USDT|0.248900|-2.88|5.64|-3.94|6631325|4.02|
|SAND_USDT|0.061400|-2.60|-8.75|-3.66|47367847|1.63|
|PUMPFUN_USDT|0.004322|-2.03|-24.50|-3.09|23217820|2.31|
|FILECOIN_USDT|1.067600|-1.82|-5.33|-2.88|18290096|1.87|
|OP_USDT|0.127450|-1.20|-8.01|-2.26|8530969|2.36|
|ZRO_USDT|1.862500|-1.20|-7.82|-2.26|7075803|0.54|
|TIA_USDT|0.653000|-0.75|27.29|-1.81|60208572|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|EIGEN_USDT|0.248900|0.245800|0.248900|1.16|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.067600|1.044000|1.067600|0.56|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.127450|0.125540|0.127450|0.64|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004322|0.004256|0.004322|1.47|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.061400|0.060800|0.061400|0.16|N|N/N|N/N|Y|N|
|STRK_USDT|0.063300|0.062680|0.063300|1.25|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.653000|0.631900|0.653000|1.86|N|N/Y|Y/Y|Y|N|
|ZRO_USDT|1.862500|1.823800|1.862500|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- EIGEN_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=0.249900, depth_time=2026-10-18T10:15:08+00:00, book20_bid_proxy_usdt=451448, book20_ask_proxy_usdt=408176, funding_indicative=0.000008, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=6631325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=1.065600, depth_time=2026-10-18T10:15:18+00:00, book20_bid_proxy_usdt=731726, book20_ask_proxy_usdt=500354, funding_indicative=-0.000054, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=18290096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=0.128100, depth_time=2026-10-18T10:15:19+00:00, book20_bid_proxy_usdt=79962, book20_ask_proxy_usdt=37893, funding_indicative=-0.000200, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=8530969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=0.004347, depth_time=2026-10-18T10:15:14+00:00, book20_bid_proxy_usdt=2059142, book20_ask_proxy_usdt=885060, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=23217820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=0.064900, depth_time=2026-10-18T10:15:13+00:00, book20_bid_proxy_usdt=418638, book20_ask_proxy_usdt=622796, funding_indicative=-0.008684, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=47367847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=0.064850, depth_time=2026-10-18T10:15:08+00:00, book20_bid_proxy_usdt=537998, book20_ask_proxy_usdt=414484, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=14372051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=0.665300, depth_time=2026-10-18T10:15:25+00:00, book20_bid_proxy_usdt=221219, book20_ask_proxy_usdt=132242, funding_indicative=-0.000086, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.75%, turnover=60208572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T10:15:02+00:00, last15m_closed_end=2026-10-18T10:15+00:00, prior8high=1.874500, depth_time=2026-10-18T10:15:22+00:00, book20_bid_proxy_usdt=82466, book20_ask_proxy_usdt=23197, funding_indicative=0.000003, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=7075803. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
