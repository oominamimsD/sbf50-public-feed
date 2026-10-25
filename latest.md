# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T06:30:23Z**
- feed_generated_utc: 2026-10-25T06:30:26+00:00
- source_sha256: `4920e599493f607cc98db84408037cb64c4f7d04afbb9f5c90602bc05d167dad`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T06:30+00:00, close=80597.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T06:00+00:00, close=80572.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.056060|-16.82|81.13|-17.86|13789341|1.78|
|BIRB_USDT|0.082820|-15.19|70.69|-16.23|7035888|3.63|
|IRYS_USDT|0.040620|-11.79|218.33|-12.83|34093934|7.39|
|STRK_USDT|0.045920|-1.73|-30.58|-2.77|8800393|2.18|
|DOT_USDT|1.030600|-0.81|-7.76|-1.85|11735301|0.97|
|SUI_USDT|0.920900|-0.44|-6.20|-1.48|65255372|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.082820|0.081770|0.082820|0.75|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.030600|1.027800|1.030600|0.73|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.040620|0.039230|0.040620|0.65|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.056060|0.054500|0.055970|1.00|N|Y/N|N/N|Y|N|
|STRK_USDT|0.045920|0.045690|0.045920|1.51|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.920900|0.914900|0.920900|2.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T06:30:00+00:00, last15m_closed_end=2026-10-25T06:30+00:00, prior8high=0.091370, depth_time=2026-10-25T06:30:11+00:00, book20_bid_proxy_usdt=13994, book20_ask_proxy_usdt=12056, funding_indicative=-0.011844, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.19%, turnover=7035888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T06:30:00+00:00, last15m_closed_end=2026-10-25T06:30+00:00, prior8high=1.042400, depth_time=2026-10-25T06:30:19+00:00, book20_bid_proxy_usdt=297731, book20_ask_proxy_usdt=314610, funding_indicative=-0.000095, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=11735301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T06:30:00+00:00, last15m_closed_end=2026-10-25T06:30+00:00, prior8high=0.049340, depth_time=2026-10-25T06:30:13+00:00, book20_bid_proxy_usdt=52644, book20_ask_proxy_usdt=41761, funding_indicative=-0.002001, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-11.79%, turnover=34093934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T06:30:00+00:00, last15m_closed_end=2026-10-25T06:30+00:00, prior8high=0.063890, depth_time=2026-10-25T06:30:09+00:00, book20_bid_proxy_usdt=66785, book20_ask_proxy_usdt=32735, funding_indicative=-0.001438, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-16.82%, turnover=13789341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T06:30:00+00:00, last15m_closed_end=2026-10-25T06:30+00:00, prior8high=0.047320, depth_time=2026-10-25T06:30:16+00:00, book20_bid_proxy_usdt=816048, book20_ask_proxy_usdt=1063749, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=8800393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T06:30:00+00:00, last15m_closed_end=2026-10-25T06:30+00:00, prior8high=0.936800, depth_time=2026-10-25T06:30:22+00:00, book20_bid_proxy_usdt=1142666, book20_ask_proxy_usdt=1571356, funding_indicative=0.000031, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.44%, turnover=65255372. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
