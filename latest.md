# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T11:30:18Z**
- feed_generated_utc: 2026-11-08T11:30:19+00:00
- source_sha256: `31cff4808092d7b21b666f5406188581d0dee56c04e2033a434cbb17df921d96`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T11:30+00:00, close=75943.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T11:00+00:00, close=75861.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.031480|-5.45|79.67|-5.73|16341609|4.45|
|ONE_USDT|0.001932|-5.13|64.55|-5.41|25806447|0.52|
|TIA_USDT|0.427100|-3.28|-12.85|-3.56|7306433|2.34|
|ENA_USDT|0.155040|-1.98|-20.08|-2.26|29456757|0.65|
|WLD_USDT|0.329300|-1.87|-18.57|-2.15|22971424|3.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.155040|0.152210|0.155030|3.33|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.031480|0.030644|0.031480|3.30|N|N/N|N/N|Y|N|
|ONE_USDT|0.001932|0.001872|0.001932|1.16|N|Y/N|N/N|Y|N|
|TIA_USDT|0.427100|0.422800|0.427100|1.61|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329300|0.325700|0.329300|1.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T11:30:01+00:00, last15m_closed_end=2026-11-08T11:30+00:00, prior8high=0.154340, depth_time=2026-11-08T11:30:14+00:00, book20_bid_proxy_usdt=171666, book20_ask_proxy_usdt=120006, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=29456757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T11:30:01+00:00, last15m_closed_end=2026-11-08T11:30+00:00, prior8high=0.033952, depth_time=2026-11-08T11:30:04+00:00, book20_bid_proxy_usdt=8112, book20_ask_proxy_usdt=4575, funding_indicative=0.000539, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=16341609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T11:30:01+00:00, last15m_closed_end=2026-11-08T11:30+00:00, prior8high=0.002228, depth_time=2026-11-08T11:30:09+00:00, book20_bid_proxy_usdt=10144, book20_ask_proxy_usdt=6583, funding_indicative=-0.001659, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=25806447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T11:30:01+00:00, last15m_closed_end=2026-11-08T11:30+00:00, prior8high=0.427500, depth_time=2026-11-08T11:30:11+00:00, book20_bid_proxy_usdt=325792, book20_ask_proxy_usdt=339672, funding_indicative=0.000011, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=7306433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T11:30:01+00:00, last15m_closed_end=2026-11-08T11:30+00:00, prior8high=0.328600, depth_time=2026-11-08T11:30:17+00:00, book20_bid_proxy_usdt=4040354, book20_ask_proxy_usdt=3313226, funding_indicative=-0.000045, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=22971424. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
