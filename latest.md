# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T11:00:41Z**
- feed_generated_utc: 2026-10-18T11:00:43+00:00
- source_sha256: `77ba9679cda7f6247569cb9b0ea6fdb28fb2b1b25335d148100904b39334bf5e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T11:00+00:00, close=82060.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T11:00+00:00, close=82060.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.091132|-11.27|191.21|-12.18|12411170|8.01|
|STRK_USDT|0.062280|-5.85|-33.34|-6.76|15344352|3.21|
|EIGEN_USDT|0.244000|-4.79|3.56|-5.70|6900821|4.10|
|SAND_USDT|0.061110|-3.06|-9.18|-3.97|47906737|1.64|
|PUMPFUN_USDT|0.004305|-2.42|-24.80|-3.33|23498246|2.32|
|TIA_USDT|0.642200|-2.40|25.18|-3.31|62497164|6.23|
|FILECOIN_USDT|1.063100|-2.23|-5.73|-3.14|18521199|0.94|
|ZRO_USDT|1.843300|-2.22|-8.77|-3.13|7155040|0.54|
|XPL_USDT|0.078730|-1.74|-9.25|-2.65|5859119|1.27|
|OP_USDT|0.126760|-1.73|-8.50|-2.64|8775981|1.58|
|ZEC_USDT|1129.880000|-1.00|-8.27|-1.91|1226599830|0.09|
|ICP_USDT|2.900000|-0.95|-7.90|-1.86|6046613|3.45|
|DOT_USDT|1.109100|-0.74|-11.75|-1.65|16954502|0.90|
|INJ_USDT|8.421000|-0.48|15.45|-1.39|40265391|2.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.109100|1.098300|1.109100|1.65|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.244000|0.245800|0.244000|4.28|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.063100|1.044000|1.063100|0.17|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.900000|2.904000|2.900000|0.95|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.421000|8.426000|8.422000|2.05|Y|Y/Y|N/N|Y|N|
|OP_USDT|0.126760|0.125540|0.126760|1.54|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004305|0.004256|0.004305|0.87|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.091132|0.088905|0.091132|3.10|N|Y/N|N/N|Y|N|
|SAND_USDT|0.061110|0.060830|0.061110|0.35|N|Y/N|N/N|Y|N|
|STRK_USDT|0.062280|0.061570|0.062290|1.03|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.642200|0.640300|0.642100|1.15|N|Y/N|Y/Y|Y|N|
|XPL_USDT|0.078730|0.077860|0.078730|0.21|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1129.880000|1120.180000|1129.880000|0.94|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.843300|1.823800|1.843300|1.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=1.120400, depth_time=2026-10-18T11:00:38+00:00, book20_bid_proxy_usdt=298549, book20_ask_proxy_usdt=292346, funding_indicative=-0.000073, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=16954502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.249900, depth_time=2026-10-18T11:00:12+00:00, book20_bid_proxy_usdt=589119, book20_ask_proxy_usdt=435331, funding_indicative=-0.000013, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.79%, turnover=6900821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=1.069800, depth_time=2026-10-18T11:00:23+00:00, book20_bid_proxy_usdt=697253, book20_ask_proxy_usdt=557404, funding_indicative=-0.000021, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=18521199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=2.941000, depth_time=2026-10-18T11:00:35+00:00, book20_bid_proxy_usdt=1164218, book20_ask_proxy_usdt=1025013, funding_indicative=0.000007, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=6046613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=8.544000, depth_time=2026-10-18T11:00:40+00:00, book20_bid_proxy_usdt=327210, book20_ask_proxy_usdt=250589, funding_indicative=0.000235, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=40265391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.128100, depth_time=2026-10-18T11:00:30+00:00, book20_bid_proxy_usdt=60648, book20_ask_proxy_usdt=64094, funding_indicative=-0.000219, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=8775981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.004347, depth_time=2026-10-18T11:00:18+00:00, book20_bid_proxy_usdt=2073859, book20_ask_proxy_usdt=1020686, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=23498246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.136988, depth_time=2026-10-18T11:00:08+00:00, book20_bid_proxy_usdt=12079, book20_ask_proxy_usdt=12746, funding_indicative=0.000035, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.27%, turnover=12411170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.063750, depth_time=2026-10-18T11:00:16+00:00, book20_bid_proxy_usdt=525853, book20_ask_proxy_usdt=694705, funding_indicative=-0.007001, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=47906737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.064850, depth_time=2026-10-18T11:00:09+00:00, book20_bid_proxy_usdt=492932, book20_ask_proxy_usdt=445348, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=15344352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.665300, depth_time=2026-10-18T11:00:20+00:00, book20_bid_proxy_usdt=268014, book20_ask_proxy_usdt=303600, funding_indicative=-0.000057, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=62497164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=0.079080, depth_time=2026-10-18T11:00:28+00:00, book20_bid_proxy_usdt=478179, book20_ask_proxy_usdt=329792, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=5859119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=1143.000000, depth_time=2026-10-18T11:00:33+00:00, book20_bid_proxy_usdt=153618, book20_ask_proxy_usdt=454067, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=1226599830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T10:59:59+00:00, last15m_closed_end=2026-10-18T11:00+00:00, prior8high=1.874500, depth_time=2026-10-18T11:00:22+00:00, book20_bid_proxy_usdt=29946, book20_ask_proxy_usdt=39857, funding_indicative=-0.000017, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=7155040. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
