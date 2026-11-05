# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T01:15:38Z**
- feed_generated_utc: 2026-11-05T01:15:39+00:00
- source_sha256: `839bc4dd77f3554e303f97fc9402056e224b064560a94d9ae324d167b8ea4448`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T01:15+00:00, close=80489.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T01:00+00:00, close=80509.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002387|-15.05|-88.12|-15.32|16290491|8.38|
|TRUMPOFFICIAL_USDT|1.241000|-12.85|-27.38|-13.12|27231457|8.07|
|IDOL_USDT|0.021413|-8.75|147.34|-9.02|6146868|6.54|
|VVV_USDT|21.266000|-8.15|-10.71|-8.42|5115763|1.41|
|BTW_USDT|1.011600|-7.95|-41.79|-8.22|6064221|1.98|
|CLANKER_USDT|17.200000|-7.57|28.74|-7.84|20096814|5.83|
|WLD_USDT|0.374600|-4.46|-13.44|-4.73|74600265|2.67|
|PUMPFUN_USDT|0.004270|-4.04|1.49|-4.31|16586994|2.34|
|OP_USDT|0.109580|-4.04|-1.35|-4.31|11038316|0.91|
|ZRO_USDT|1.820000|-2.39|6.30|-2.66|10507501|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002387|0.002379|0.002389|2.90|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.011600|1.012200|1.011600|1.95|Y|Y/Y|Y/N|N|N|
|CLANKER_USDT|17.200000|16.300000|17.200000|0.30|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021413|0.021076|0.021422|0.72|N|Y/Y|N/N|N|N|
|OP_USDT|0.109580|0.109240|0.109580|2.10|N|Y/Y|Y/N|N|N|
|PUMPFUN_USDT|0.004270|0.004236|0.004270|4.55|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.241000|1.238000|1.241000|0.47|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.266000|20.977000|21.266000|0.50|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374600|0.373600|0.374600|3.07|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.820000|1.808300|1.820000|1.55|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T01:15:03+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=0.002588, depth_time=2026-11-05T01:15:07+00:00, book20_bid_proxy_usdt=73218, book20_ask_proxy_usdt=83592, funding_indicative=-0.000981, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.05%, turnover=16290491. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T01:15:03+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=1.041100, depth_time=2026-11-05T01:15:16+00:00, book20_bid_proxy_usdt=35140, book20_ask_proxy_usdt=21252, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.95%, turnover=6064221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T01:15:02+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=18.850000, depth_time=2026-11-05T01:15:20+00:00, book20_bid_proxy_usdt=156805, book20_ask_proxy_usdt=186326, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.57%, turnover=20096814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T01:15:02+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=0.022404, depth_time=2026-11-05T01:15:11+00:00, book20_bid_proxy_usdt=11157, book20_ask_proxy_usdt=4411, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.75%, turnover=6146868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T01:14:59+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=0.112050, depth_time=2026-11-05T01:15:34+00:00, book20_bid_proxy_usdt=106652, book20_ask_proxy_usdt=73123, funding_indicative=0.000009, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=11038316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T01:15:03+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=0.004317, depth_time=2026-11-05T01:15:31+00:00, book20_bid_proxy_usdt=2631276, book20_ask_proxy_usdt=1401789, funding_indicative=0.000002, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=16586994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T01:15:03+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=1.286000, depth_time=2026-11-05T01:15:09+00:00, book20_bid_proxy_usdt=1020967, book20_ask_proxy_usdt=1182435, funding_indicative=-0.000425, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.85%, turnover=27231457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T01:14:59+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=22.241000, depth_time=2026-11-05T01:15:15+00:00, book20_bid_proxy_usdt=26416, book20_ask_proxy_usdt=17509, funding_indicative=-0.000423, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.15%, turnover=5115763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T01:15:03+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=0.381000, depth_time=2026-11-05T01:15:23+00:00, book20_bid_proxy_usdt=1808650, book20_ask_proxy_usdt=2432652, funding_indicative=-0.000383, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=74600265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T01:15:03+00:00, last15m_closed_end=2026-11-05T01:15+00:00, prior8high=1.842800, depth_time=2026-11-05T01:15:37+00:00, book20_bid_proxy_usdt=63882, book20_ask_proxy_usdt=25426, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=10507501. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
