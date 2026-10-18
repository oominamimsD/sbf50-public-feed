# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T12:15:31Z**
- feed_generated_utc: 2026-10-18T12:15:33+00:00
- source_sha256: `253d379c3bb7fd766ffe826f6402d0cc578f866aa397b8bd02b2a9b6e8f175d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T12:15+00:00, close=82024.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062080|-6.15|-33.55|-7.02|15427599|1.61|
|EIGEN_USDT|0.241300|-5.85|2.41|-6.72|6028005|4.14|
|SAND_USDT|0.060960|-3.29|-9.40|-4.16|44743623|3.28|
|ZRO_USDT|1.834900|-2.67|-9.19|-3.54|6328986|0.55|
|PUMPFUN_USDT|0.004302|-2.49|-24.85|-3.36|22134721|2.33|
|FILECOIN_USDT|1.063500|-2.19|-5.70|-3.06|17870282|0.94|
|OP_USDT|0.127570|-1.10|-7.92|-1.97|8670278|0.78|
|INJ_USDT|8.404000|-0.68|15.21|-1.55|39015031|1.19|
|DOT_USDT|1.110300|-0.63|-11.66|-1.50|16596046|0.90|
|ICP_USDT|2.914000|-0.47|-7.46|-1.34|6057156|3.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.110300|1.102600|1.110300|2.05|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.241300|0.240100|0.241300|3.17|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.063500|1.053700|1.063500|2.29|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.914000|2.889000|2.914000|0.89|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.404000|8.387000|8.405000|0.39|N|Y/Y|Y/N|N|N|
|OP_USDT|0.127570|0.125830|0.127570|2.53|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004302|0.004269|0.004301|0.95|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.060960|0.060210|0.061030|1.21|N|Y/Y|N/N|N|N|
|STRK_USDT|0.062080|0.061150|0.062080|2.59|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.834900|1.829900|1.834900|0.44|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=1.119200, depth_time=2026-10-18T12:15:28+00:00, book20_bid_proxy_usdt=333130, book20_ask_proxy_usdt=330387, funding_indicative=-0.000052, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.63%, turnover=16596046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=0.249000, depth_time=2026-10-18T12:15:08+00:00, book20_bid_proxy_usdt=579593, book20_ask_proxy_usdt=420665, funding_indicative=-0.000006, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=6028005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=1.069800, depth_time=2026-10-18T12:15:20+00:00, book20_bid_proxy_usdt=611772, book20_ask_proxy_usdt=457666, funding_indicative=0.000038, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=17870282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=2.927000, depth_time=2026-10-18T12:15:29+00:00, book20_bid_proxy_usdt=831997, book20_ask_proxy_usdt=1009257, funding_indicative=0.000047, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.47%, turnover=6057156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=8.527000, depth_time=2026-10-18T12:15:26+00:00, book20_bid_proxy_usdt=295416, book20_ask_proxy_usdt=355835, funding_indicative=0.000200, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=39015031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=0.127480, depth_time=2026-10-18T12:15:23+00:00, book20_bid_proxy_usdt=69876, book20_ask_proxy_usdt=37226, funding_indicative=-0.000197, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=8670278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=0.004339, depth_time=2026-10-18T12:15:17+00:00, book20_bid_proxy_usdt=2072086, book20_ask_proxy_usdt=1345414, funding_indicative=0.000032, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=22134721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=0.061920, depth_time=2026-10-18T12:15:13+00:00, book20_bid_proxy_usdt=945132, book20_ask_proxy_usdt=498450, funding_indicative=-0.004856, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=44743623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=0.063410, depth_time=2026-10-18T12:15:08+00:00, book20_bid_proxy_usdt=284859, book20_ask_proxy_usdt=589977, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.15%, turnover=15427599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T12:15:00+00:00, last15m_closed_end=2026-10-18T12:15+00:00, prior8high=1.862600, depth_time=2026-10-18T12:15:14+00:00, book20_bid_proxy_usdt=85941, book20_ask_proxy_usdt=59566, funding_indicative=-0.000025, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=6328986. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
