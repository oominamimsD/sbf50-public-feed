# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T23:00:30Z**
- feed_generated_utc: 2026-10-31T23:00:32+00:00
- source_sha256: `5b5ea323eac174439ca9a60e79539e43dd3ef5ad29d7e31b857b697dca25d21a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T23:00+00:00, close=77498.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T23:00+00:00, close=77498.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244320|-18.37|45.49|-18.30|28281826|2.04|
|IDOL_USDT|0.016861|-15.45|113.43|-15.38|6132060|2.96|
|BLESS_USDT|0.009375|-12.07|15.55|-12.00|7738798|3.20|
|TRX_USDT|0.301590|-4.34|-8.31|-4.27|10229971|0.33|
|INJ_USDT|7.212000|-3.66|-4.01|-3.59|20364125|2.77|
|BTW_USDT|1.106100|-3.09|-36.47|-3.02|5419603|0.90|
|ENA_USDT|0.188390|-2.89|0.85|-2.82|45659905|0.53|
|ZEC_USDT|1250.290000|-2.66|9.17|-2.59|1035949148|0.08|
|Q_USDT|0.031590|-1.52|-59.97|-1.45|10522685|3.17|
|FET_USDT|0.159800|-1.41|-7.25|-1.34|5636301|6.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009375|0.009313|0.009379|2.22|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.106100|1.086300|1.106000|0.94|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188390|0.187500|0.188420|1.62|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159800|0.159500|0.159800|0.71|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.016861|0.016323|0.016861|0.41|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.212000|7.198000|7.213000|0.76|N|Y/N|Y/Y|Y|N|
|LSK_USDT|0.244320|0.237060|0.244320|0.40|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031590|0.031320|0.031690|1.20|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.301590|0.300840|0.301590|0.28|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1250.290000|1265.800000|1250.660000|3.26|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-31T23:00:02+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.010161, depth_time=2026-10-31T23:00:12+00:00, book20_bid_proxy_usdt=11447, book20_ask_proxy_usdt=11967, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.07%, turnover=7738798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T23:00:02+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=1.131000, depth_time=2026-10-31T23:00:17+00:00, book20_bid_proxy_usdt=30285, book20_ask_proxy_usdt=16287, funding_indicative=-0.000136, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=5419603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T23:00:01+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.191470, depth_time=2026-10-31T23:00:21+00:00, book20_bid_proxy_usdt=186831, book20_ask_proxy_usdt=221683, funding_indicative=-0.000037, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=45659905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T23:00:02+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.161300, depth_time=2026-10-31T23:00:29+00:00, book20_bid_proxy_usdt=1095665, book20_ask_proxy_usdt=921295, funding_indicative=-0.000242, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=5636301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T23:00:01+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.017468, depth_time=2026-10-31T23:00:10+00:00, book20_bid_proxy_usdt=4135, book20_ask_proxy_usdt=10146, funding_indicative=0.000089, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.45%, turnover=6132060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T23:00:02+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=7.312000, depth_time=2026-10-31T23:00:17+00:00, book20_bid_proxy_usdt=503443, book20_ask_proxy_usdt=311643, funding_indicative=0.000123, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=20364125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T23:00:01+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.249390, depth_time=2026-10-31T23:00:08+00:00, book20_bid_proxy_usdt=3780, book20_ask_proxy_usdt=11739, funding_indicative=-0.000997, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.37%, turnover=28281826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T23:00:02+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.032570, depth_time=2026-10-31T23:00:27+00:00, book20_bid_proxy_usdt=41546, book20_ask_proxy_usdt=77014, funding_indicative=-0.001313, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=1, 24h_change=-1.52%, turnover=10522685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T23:00:02+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=0.305780, depth_time=2026-10-31T23:00:15+00:00, book20_bid_proxy_usdt=85127, book20_ask_proxy_usdt=143679, funding_indicative=-0.001062, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=10229971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-31T23:00:01+00:00, last15m_closed_end=2026-10-31T23:00+00:00, prior8high=1284.960000, depth_time=2026-10-31T23:00:25+00:00, book20_bid_proxy_usdt=529262, book20_ask_proxy_usdt=155482, funding_indicative=-0.000025, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=1035949148. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
