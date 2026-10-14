# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T11:15:25Z**
- feed_generated_utc: 2026-10-14T11:15:26+00:00
- source_sha256: `ee70799a34c9dfd41040cbc7d691a7af68077f6a56121e44b9346dd072f00554`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T11:15+00:00, close=83423.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T11:00+00:00, close=83430.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078290|-9.93|50.00|-9.96|27735771|1.28|
|TIA_USDT|0.543200|-5.90|14.04|-5.93|35383273|1.84|
|W_USDT|0.015955|-5.04|9.94|-5.07|6355826|1.25|
|UNI_USDT|7.334000|-3.14|-15.36|-3.17|18229119|1.36|
|SILVER_USDT|58.630000|-1.27|-4.46|-1.30|262785256|1.71|
|DOT_USDT|1.143100|-1.19|-4.85|-1.22|19125723|3.50|
|XLM_USDT|0.188920|-1.07|-11.58|-1.10|9487602|0.53|
|ICP_USDT|3.081000|-0.99|-9.43|-1.02|9256377|3.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.143100|1.129300|1.143600|1.19|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.081000|3.053000|3.083000|0.23|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.630000|58.570000|58.640000|3.41|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.078290|0.077870|0.078280|0.62|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.543200|0.540100|0.543100|1.37|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.334000|7.328000|7.334000|1.08|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015955|0.015659|0.015955|1.46|N|Y/Y|Y/Y|N|N|
|XLM_USDT|0.188920|0.188210|0.188920|1.05|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T11:15:02+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=1.143800, depth_time=2026-10-14T11:15:19+00:00, book20_bid_proxy_usdt=235391, book20_ask_proxy_usdt=176281, funding_indicative=0.000022, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=19125723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T11:15:02+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=3.100000, depth_time=2026-10-14T11:15:24+00:00, book20_bid_proxy_usdt=688068, book20_ask_proxy_usdt=914055, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=9256377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T11:15:01+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=58.760000, depth_time=2026-10-14T11:15:16+00:00, book20_bid_proxy_usdt=40659355, book20_ask_proxy_usdt=51316958, funding_indicative=0.000100, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=262785256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T11:15:01+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=0.081420, depth_time=2026-10-14T11:15:08+00:00, book20_bid_proxy_usdt=176663, book20_ask_proxy_usdt=316244, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.93%, turnover=27735771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T11:15:02+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=0.553700, depth_time=2026-10-14T11:15:09+00:00, book20_bid_proxy_usdt=150582, book20_ask_proxy_usdt=202820, funding_indicative=-0.000052, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.90%, turnover=35383273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T11:15:02+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=7.381000, depth_time=2026-10-14T11:15:14+00:00, book20_bid_proxy_usdt=1286141, book20_ask_proxy_usdt=1672362, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=18229119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T11:15:02+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=0.016370, depth_time=2026-10-14T11:15:11+00:00, book20_bid_proxy_usdt=50311, book20_ask_proxy_usdt=27031, funding_indicative=-0.000263, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=6355826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T11:15:02+00:00, last15m_closed_end=2026-10-14T11:15+00:00, prior8high=0.189520, depth_time=2026-10-14T11:15:21+00:00, book20_bid_proxy_usdt=104693, book20_ask_proxy_usdt=172375, funding_indicative=-0.000107, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=9487602. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
