# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T06:45:23Z**
- feed_generated_utc: 2026-10-25T06:45:26+00:00
- source_sha256: `e13db87b5b7854ee4810338ea550c11b74b10adb8a0d639ea9a2f79d90cac667`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T06:45+00:00, close=80483.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T06:00+00:00, close=80572.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.055730|-17.31|80.06|-18.21|13803297|5.38|
|BIRB_USDT|0.083290|-14.71|71.66|-15.61|7048410|1.20|
|IRYS_USDT|0.040340|-12.39|216.14|-13.29|34250705|2.48|
|STRK_USDT|0.045920|-1.73|-30.58|-2.63|8828897|2.18|
|DOT_USDT|1.027300|-1.13|-8.06|-2.03|11817334|0.97|
|SUI_USDT|0.917100|-0.85|-6.58|-1.75|65633032|1.09|
|APT_USDT|0.700300|-0.22|-12.18|-1.12|5919651|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.700300|0.701300|0.700100|3.76|Y|Y/Y|Y/Y|Y|Y|
|BIRB_USDT|0.083290|0.081770|0.083320|0.68|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.027300|1.027800|1.027300|1.80|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.040340|0.039230|0.040340|0.46|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.055730|0.054500|0.055580|0.60|N|Y/N|N/N|Y|N|
|STRK_USDT|0.045920|0.045690|0.045900|0.55|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.917100|0.914900|0.917200|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T06:45:04+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=0.714100, depth_time=2026-10-25T06:45:23+00:00, book20_bid_proxy_usdt=102300, book20_ask_proxy_usdt=156845, funding_indicative=-0.000036, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.22%, turnover=5919651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T06:45:03+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=0.090440, depth_time=2026-10-25T06:45:10+00:00, book20_bid_proxy_usdt=27431, book20_ask_proxy_usdt=17800, funding_indicative=-0.012021, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.71%, turnover=7048410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T06:45:03+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=1.042400, depth_time=2026-10-25T06:45:18+00:00, book20_bid_proxy_usdt=346274, book20_ask_proxy_usdt=373813, funding_indicative=-0.000111, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=11817334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T06:45:03+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=0.048220, depth_time=2026-10-25T06:45:13+00:00, book20_bid_proxy_usdt=37437, book20_ask_proxy_usdt=41965, funding_indicative=-0.002126, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-12.39%, turnover=34250705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T06:45:03+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=0.063890, depth_time=2026-10-25T06:45:08+00:00, book20_bid_proxy_usdt=58641, book20_ask_proxy_usdt=76117, funding_indicative=-0.001476, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-17.31%, turnover=13803297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T06:45:04+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=0.047320, depth_time=2026-10-25T06:45:15+00:00, book20_bid_proxy_usdt=888185, book20_ask_proxy_usdt=740597, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=8828897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T06:45:03+00:00, last15m_closed_end=2026-10-25T06:45+00:00, prior8high=0.935600, depth_time=2026-10-25T06:45:20+00:00, book20_bid_proxy_usdt=1264629, book20_ask_proxy_usdt=484809, funding_indicative=0.000032, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=65633032. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
