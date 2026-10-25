# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T05:45:22Z**
- feed_generated_utc: 2026-10-25T05:45:25+00:00
- source_sha256: `4dda4dd7e02f1b6311cc72f954dd6cfa3c394bdaac9e2afcdd1c62e747d6e373`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T05:45+00:00, close=80550.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T05:00+00:00, close=80894.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.056770|-15.77|83.42|-16.76|13734512|1.76|
|BIRB_USDT|0.082470|-15.55|69.97|-16.54|7715808|1.21|
|IRYS_USDT|0.039980|-13.18|213.32|-14.17|34276664|2.50|
|STRK_USDT|0.046240|-1.04|-30.09|-2.03|8680192|2.16|
|SUI_USDT|0.921800|-0.34|-6.11|-1.33|64484384|1.08|
|DOT_USDT|1.038000|-0.10|-7.10|-1.09|11602130|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.082470|0.079540|0.082380|0.71|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.038000|1.036400|1.038000|1.07|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.039980|0.038110|0.039930|0.62|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.056770|0.054550|0.056770|1.23|N|N/Y|N/N|Y|N|
|STRK_USDT|0.046240|0.046520|0.046240|2.69|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.921800|0.927400|0.921800|8.28|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T05:45:02+00:00, last15m_closed_end=2026-10-25T05:45+00:00, prior8high=0.091370, depth_time=2026-10-25T05:45:11+00:00, book20_bid_proxy_usdt=13331, book20_ask_proxy_usdt=17572, funding_indicative=-0.010900, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.55%, turnover=7715808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T05:45:02+00:00, last15m_closed_end=2026-10-25T05:45+00:00, prior8high=1.043200, depth_time=2026-10-25T05:45:21+00:00, book20_bid_proxy_usdt=353242, book20_ask_proxy_usdt=373204, funding_indicative=-0.000100, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.10%, turnover=11602130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T05:45:02+00:00, last15m_closed_end=2026-10-25T05:45+00:00, prior8high=0.049460, depth_time=2026-10-25T05:45:14+00:00, book20_bid_proxy_usdt=30653, book20_ask_proxy_usdt=57659, funding_indicative=-0.001412, next_funding_utc=2026-10-25T06:00:00+00:00, funding_cycle_h=1, 24h_change=-13.18%, turnover=34276664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T05:45:02+00:00, last15m_closed_end=2026-10-25T05:45+00:00, prior8high=0.063890, depth_time=2026-10-25T05:45:09+00:00, book20_bid_proxy_usdt=52101, book20_ask_proxy_usdt=68210, funding_indicative=-0.001476, next_funding_utc=2026-10-25T06:00:00+00:00, funding_cycle_h=1, 24h_change=-15.77%, turnover=13734512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T05:45:02+00:00, last15m_closed_end=2026-10-25T05:45+00:00, prior8high=0.047320, depth_time=2026-10-25T05:45:16+00:00, book20_bid_proxy_usdt=1100679, book20_ask_proxy_usdt=694604, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=8680192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T05:45:02+00:00, last15m_closed_end=2026-10-25T05:45+00:00, prior8high=0.938600, depth_time=2026-10-25T05:45:19+00:00, book20_bid_proxy_usdt=1133804, book20_ask_proxy_usdt=972308, funding_indicative=-0.000033, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.34%, turnover=64484384. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
