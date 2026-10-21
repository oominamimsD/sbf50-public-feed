# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T15:45:22Z**
- feed_generated_utc: 2026-10-21T15:45:24+00:00
- source_sha256: `e1b76711b06f02790c85ac4c6143cb0b95dadf06a5e489ca0232d081df6b5f14`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T15:45+00:00, close=84449.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T15:00+00:00, close=84530, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.050378|-22.05|211.41|-24.30|6355591|3.17|
|BTW_USDT|1.497600|-19.03|-23.29|-21.28|26911675|2.00|
|BAT_USDT|0.179780|-16.67|1.35|-18.92|9335613|3.89|
|BR_USDT|0.546460|-16.01|26.20|-18.26|19931517|1.65|
|AKE_USDT|0.027018|-13.10|7.78|-15.35|9824361|0.74|
|JCT_USDT|0.004165|-9.19|111.63|-11.44|19190957|9.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.050378|0.044780|0.050652|2.28|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027018|0.026563|0.027018|0.56|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.179780|0.177360|0.179650|0.53|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.546460|0.532370|0.546490|1.78|N|Y/Y|N/N|N|N|
|BTW_USDT|1.497600|1.471900|1.493400|0.61|N|Y/Y|Y/Y|N|N|
|JCT_USDT|0.004165|0.004088|0.004154|0.81|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T15:45:03+00:00, last15m_closed_end=2026-10-21T15:45+00:00, prior8high=0.049631, depth_time=2026-10-21T15:45:09+00:00, book20_bid_proxy_usdt=4026, book20_ask_proxy_usdt=6189, funding_indicative=0.000198, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.05%, turnover=6355591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T15:45:03+00:00, last15m_closed_end=2026-10-21T15:45+00:00, prior8high=0.028653, depth_time=2026-10-21T15:45:17+00:00, book20_bid_proxy_usdt=13120, book20_ask_proxy_usdt=10681, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.10%, turnover=9824361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T15:45:03+00:00, last15m_closed_end=2026-10-21T15:45+00:00, prior8high=0.181140, depth_time=2026-10-21T15:45:14+00:00, book20_bid_proxy_usdt=20832, book20_ask_proxy_usdt=33850, funding_indicative=-0.000247, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.67%, turnover=9335613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T15:45:03+00:00, last15m_closed_end=2026-10-21T15:45+00:00, prior8high=0.634300, depth_time=2026-10-21T15:45:16+00:00, book20_bid_proxy_usdt=3073, book20_ask_proxy_usdt=6263, funding_indicative=-0.000051, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.01%, turnover=19931517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T15:45:03+00:00, last15m_closed_end=2026-10-21T15:45+00:00, prior8high=1.641600, depth_time=2026-10-21T15:45:11+00:00, book20_bid_proxy_usdt=10899, book20_ask_proxy_usdt=10617, funding_indicative=-0.004343, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.03%, turnover=26911675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T15:45:03+00:00, last15m_closed_end=2026-10-21T15:45+00:00, prior8high=0.004835, depth_time=2026-10-21T15:45:21+00:00, book20_bid_proxy_usdt=57684, book20_ask_proxy_usdt=59732, funding_indicative=0.000129, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=19190957. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
