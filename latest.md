# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T06:45:18Z**
- feed_generated_utc: 2026-10-19T06:45:20+00:00
- source_sha256: `57e3fc85f7d4d64cf140ec2fe47086794148ae7d4a3237b56d58afc2bcdc46ef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T06:45+00:00, close=82780.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T06:00+00:00, close=82726.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.173000|-3.56|63.20|-5.58|7220013|5.78|
|STRK_USDT|0.059640|-3.11|-49.99|-5.13|17650172|1.68|
|TIA_USDT|0.607400|-1.69|3.17|-3.71|57987716|1.65|
|HBAR_USDT|0.084360|-1.65|-10.04|-3.67|50928744|1.19|
|BTW_USDT|2.274500|-1.34|35.20|-3.36|21925468|3.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.274500|2.166400|2.274500|1.67|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084360|0.083810|0.084360|1.01|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.173000|0.168800|0.173000|0.42|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059640|0.059530|0.059640|1.47|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.607400|0.604400|0.607500|0.24|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T06:44:58+00:00, last15m_closed_end=2026-10-19T06:45+00:00, prior8high=2.309200, depth_time=2026-10-19T06:45:17+00:00, book20_bid_proxy_usdt=9127, book20_ask_proxy_usdt=14392, funding_indicative=-0.000164, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=21925468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T06:44:58+00:00, last15m_closed_end=2026-10-19T06:45+00:00, prior8high=0.084640, depth_time=2026-10-19T06:45:14+00:00, book20_bid_proxy_usdt=843719, book20_ask_proxy_usdt=958536, funding_indicative=-0.000038, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=50928744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T06:44:58+00:00, last15m_closed_end=2026-10-19T06:45+00:00, prior8high=0.194500, depth_time=2026-10-19T06:45:07+00:00, book20_bid_proxy_usdt=112353, book20_ask_proxy_usdt=109768, funding_indicative=-0.000148, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=7220013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T06:44:59+00:00, last15m_closed_end=2026-10-19T06:45+00:00, prior8high=0.060780, depth_time=2026-10-19T06:45:10+00:00, book20_bid_proxy_usdt=738052, book20_ask_proxy_usdt=657969, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=17650172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T06:44:58+00:00, last15m_closed_end=2026-10-19T06:45+00:00, prior8high=0.616500, depth_time=2026-10-19T06:45:12+00:00, book20_bid_proxy_usdt=210070, book20_ask_proxy_usdt=210673, funding_indicative=-0.000027, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=57987716. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
