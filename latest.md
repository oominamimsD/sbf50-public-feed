# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T03:30:20Z**
- feed_generated_utc: 2026-10-19T03:30:22+00:00
- source_sha256: `bcd78995a7e8332dc6b78b75e03a839949cb3126480686d621300e474188295d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T03:30+00:00, close=82534.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T03:00+00:00, close=82682.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.171200|-4.57|61.50|-6.29|7697716|5.84|
|BTW_USDT|2.244600|-2.63|33.43|-4.35|21755969|2.23|
|STRK_USDT|0.060020|-2.50|-49.67|-4.22|17311124|1.67|
|BAT_USDT|0.171860|-2.00|3.13|-3.72|6275265|0.58|
|HBAR_USDT|0.084200|-1.84|-10.21|-3.56|51402231|1.19|
|TIA_USDT|0.615600|-0.37|4.56|-2.09|56057835|8.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.171860|0.170000|0.171860|0.26|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.244600|2.237300|2.244600|0.88|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084200|0.083740|0.084200|0.11|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.171200|0.163100|0.171100|1.26|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060020|0.060450|0.060020|1.03|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.615600|0.616500|0.615200|1.24|N|Y/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-19T03:30:00+00:00, last15m_closed_end=2026-10-19T03:30+00:00, prior8high=0.176060, depth_time=2026-10-19T03:30:15+00:00, book20_bid_proxy_usdt=21124, book20_ask_proxy_usdt=22001, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=6275265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T03:29:59+00:00, last15m_closed_end=2026-10-19T03:30+00:00, prior8high=2.347600, depth_time=2026-10-19T03:30:10+00:00, book20_bid_proxy_usdt=7422, book20_ask_proxy_usdt=10130, funding_indicative=-0.000290, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=21755969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T03:29:59+00:00, last15m_closed_end=2026-10-19T03:30+00:00, prior8high=0.084670, depth_time=2026-10-19T03:30:17+00:00, book20_bid_proxy_usdt=558579, book20_ask_proxy_usdt=880228, funding_indicative=-0.000027, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=51402231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T03:29:59+00:00, last15m_closed_end=2026-10-19T03:30+00:00, prior8high=0.183100, depth_time=2026-10-19T03:30:07+00:00, book20_bid_proxy_usdt=159736, book20_ask_proxy_usdt=93723, funding_indicative=-0.000097, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.57%, turnover=7697716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T03:30:00+00:00, last15m_closed_end=2026-10-19T03:30+00:00, prior8high=0.061960, depth_time=2026-10-19T03:30:12+00:00, book20_bid_proxy_usdt=362617, book20_ask_proxy_usdt=322506, funding_indicative=-0.000002, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=17311124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T03:29:59+00:00, last15m_closed_end=2026-10-19T03:30+00:00, prior8high=0.631600, depth_time=2026-10-19T03:30:20+00:00, book20_bid_proxy_usdt=236270, book20_ask_proxy_usdt=312716, funding_indicative=-0.000018, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.37%, turnover=56057835. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
