# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T03:45:24Z**
- feed_generated_utc: 2026-10-18T03:45:26+00:00
- source_sha256: `79a3dfab25921b8730c952fca68adf4f7d1e523849b4129266404fe65be08f5d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T03:45+00:00, close=81941, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T03:00+00:00, close=81790, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.168700|-8.90|70.23|-9.66|14509704|5.94|
|TIA_USDT|0.633600|-3.70|23.50|-4.46|72670804|1.58|
|STRK_USDT|0.063770|-3.59|-31.74|-4.35|14677904|1.57|
|QNT_USDT|195.890000|-2.25|-20.08|-3.01|70473254|0.51|
|FILECOIN_USDT|1.067300|-1.84|-5.36|-2.60|21123804|0.94|
|EIGEN_USDT|0.252200|-1.59|7.04|-2.35|10547749|3.96|
|PUMPFUN_USDT|0.004373|-0.88|-23.61|-1.64|23288542|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|EIGEN_USDT|0.252200|0.247900|0.252300|1.24|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.067300|1.054300|1.067300|0.41|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.168700|0.152200|0.168700|1.31|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004373|0.004299|0.004373|0.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.890000|194.620000|195.890000|0.22|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063770|0.063420|0.063780|0.26|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.633600|0.628300|0.633600|0.50|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- EIGEN_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=0.253200, depth_time=2026-10-18T03:45:21+00:00, book20_bid_proxy_usdt=420193, book20_ask_proxy_usdt=305394, funding_indicative=0.000015, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=10547749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=1.072600, depth_time=2026-10-18T03:45:18+00:00, book20_bid_proxy_usdt=529977, book20_ask_proxy_usdt=573322, funding_indicative=-0.000081, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=21123804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=0.169600, depth_time=2026-10-18T03:45:08+00:00, book20_bid_proxy_usdt=495976, book20_ask_proxy_usdt=135932, funding_indicative=-0.000011, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.90%, turnover=14509704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=0.004390, depth_time=2026-10-18T03:45:23+00:00, book20_bid_proxy_usdt=1691896, book20_ask_proxy_usdt=1878110, funding_indicative=0.000034, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=23288542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=198.820000, depth_time=2026-10-18T03:45:15+00:00, book20_bid_proxy_usdt=83722, book20_ask_proxy_usdt=62974, funding_indicative=-0.000106, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=70473254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=0.064470, depth_time=2026-10-18T03:45:13+00:00, book20_bid_proxy_usdt=278926, book20_ask_proxy_usdt=354654, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.59%, turnover=14677904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T03:45:01+00:00, last15m_closed_end=2026-10-18T03:45+00:00, prior8high=0.640200, depth_time=2026-10-18T03:45:11+00:00, book20_bid_proxy_usdt=176683, book20_ask_proxy_usdt=306777, funding_indicative=-0.000021, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=72670804. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
