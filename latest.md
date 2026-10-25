# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T06:00:27Z**
- feed_generated_utc: 2026-10-25T06:00:30+00:00
- source_sha256: `311fd8f92117ffc9673f4284ff7070bf0fc96e5332cb63fcd0db7321fbc924f6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T06:00+00:00, close=80572.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T06:00+00:00, close=80572.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.056850|-15.65|83.68|-16.66|13748544|5.28|
|STRK_USDT|0.046090|-1.36|-30.32|-2.37|8625697|2.17|
|DOT_USDT|1.035200|-1.32|-7.35|-2.33|11526204|1.93|
|SUI_USDT|0.920100|-0.81|-6.28|-1.82|63856669|1.09|
|TIA_USDT|0.531100|-0.54|-19.28|-1.55|21152008|3.77|
|ARB_USDT|0.166700|-0.28|-9.36|-1.29|14756469|0.60|
|LINK_USDT|11.444000|-0.13|-3.88|-1.14|47679419|1.75|
|SEI_USDT|0.053230|-0.13|-14.15|-1.14|9238771|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166700|0.166600|0.166700|1.02|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.035200|1.036400|1.035200|3.08|Y|Y/Y|Y/Y|Y|Y|
|LINK_USDT|11.444000|11.442000|11.444000|2.98|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.056850|0.054550|0.057030|0.80|N|Y/N|N/N|Y|N|
|SEI_USDT|0.053230|0.053220|0.053230|9.42|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046090|0.046150|0.046080|2.94|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.920100|0.919300|0.920100|3.52|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.531100|0.530200|0.531100|4.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-25T06:00:01+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=0.168320, depth_time=2026-10-25T06:00:21+00:00, book20_bid_proxy_usdt=77499, book20_ask_proxy_usdt=93531, funding_indicative=-0.000011, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.28%, turnover=14756469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T06:00:01+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=1.043200, depth_time=2026-10-25T06:00:13+00:00, book20_bid_proxy_usdt=257348, book20_ask_proxy_usdt=282538, funding_indicative=-0.000108, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=11526204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T06:00:01+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=11.595000, depth_time=2026-10-25T06:00:23+00:00, book20_bid_proxy_usdt=389810, book20_ask_proxy_usdt=544995, funding_indicative=0.000069, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.13%, turnover=47679419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T06:00:01+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=0.063890, depth_time=2026-10-25T06:00:08+00:00, book20_bid_proxy_usdt=28503, book20_ask_proxy_usdt=30316, funding_indicative=-0.001585, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-15.65%, turnover=13748544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T06:00:02+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=0.053880, depth_time=2026-10-25T06:00:26+00:00, book20_bid_proxy_usdt=160241, book20_ask_proxy_usdt=427275, funding_indicative=-0.000064, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.13%, turnover=9238771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T06:00:02+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=0.047320, depth_time=2026-10-25T06:00:11+00:00, book20_bid_proxy_usdt=685269, book20_ask_proxy_usdt=660972, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=8625697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T06:00:01+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=0.938400, depth_time=2026-10-25T06:00:16+00:00, book20_bid_proxy_usdt=929642, book20_ask_proxy_usdt=1422141, funding_indicative=-0.000013, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=63856669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T06:00:01+00:00, last15m_closed_end=2026-10-25T06:00+00:00, prior8high=0.535300, depth_time=2026-10-25T06:00:17+00:00, book20_bid_proxy_usdt=249409, book20_ask_proxy_usdt=277469, funding_indicative=-0.000012, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.54%, turnover=21152008. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
