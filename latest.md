# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T16:00:28Z**
- feed_generated_utc: 2026-10-12T16:00:31+00:00
- source_sha256: `ea97035e8efbb8aa4c73fd947cefec7afd89a89ba05c4e64d3fa33cddb533fd5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.988600|-3.70|80.40|-3.86|10891786|2.02|
|FILECOIN_USDT|1.162300|-3.63|6.88|-3.79|43851223|0.86|
|GRASS_USDT|0.747000|-3.01|5.92|-3.17|11359503|1.34|
|STRK_USDT|0.090670|-2.79|73.99|-2.95|72169744|1.10|
|PUMPFUN_USDT|0.005309|-2.15|-16.19|-2.31|23666446|1.88|
|PONS_USDT|0.294700|-1.50|-23.15|-1.66|6248886|3.40|
|S_USDT|0.057390|-1.13|33.62|-1.29|31142282|1.74|
|BAT_USDT|0.150320|-0.90|43.81|-1.06|6370923|1.33|
|ATOM_USDT|1.828000|-0.86|2.58|-1.02|14623819|5.47|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.828000|1.820000|1.828000|0.66|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.150320|0.148480|0.150320|0.41|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.162300|1.174700|1.162300|4.22|Y|Y/Y|N/N|Y|N|
|GRASS_USDT|0.747000|0.769200|0.747000|2.94|Y|Y/Y|N/N|Y|N|
|PONS_USDT|0.294700|0.285300|0.294700|0.13|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.005309|0.005284|0.005309|1.87|N|Y/Y|Y/Y|Y|N|
|RLC_USDT|0.988600|0.999300|0.988600|1.65|Y|Y/Y|N/N|Y|N|
|STRK_USDT|0.090670|0.090800|0.090670|0.75|N|Y/Y|Y/N|Y|N|
|S_USDT|0.057390|0.056520|0.057390|1.14|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=1.864000, depth_time=2026-10-12T16:00:27+00:00, book20_bid_proxy_usdt=621500, book20_ask_proxy_usdt=737202, funding_indicative=0.000066, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=14623819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=0.153140, depth_time=2026-10-12T16:00:25+00:00, book20_bid_proxy_usdt=22425, book20_ask_proxy_usdt=19742, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=6370923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=1.221500, depth_time=2026-10-12T16:00:08+00:00, book20_bid_proxy_usdt=452811, book20_ask_proxy_usdt=583044, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=43851223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=0.809000, depth_time=2026-10-12T16:00:13+00:00, book20_bid_proxy_usdt=43418, book20_ask_proxy_usdt=99450, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=11359503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=0.310300, depth_time=2026-10-12T16:00:20+00:00, book20_bid_proxy_usdt=207805, book20_ask_proxy_usdt=240731, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=6248886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=0.005630, depth_time=2026-10-12T16:00:18+00:00, book20_bid_proxy_usdt=1283005, book20_ask_proxy_usdt=1187700, funding_indicative=-0.000021, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=23666446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=1.051400, depth_time=2026-10-12T16:00:07+00:00, book20_bid_proxy_usdt=55319, book20_ask_proxy_usdt=49822, funding_indicative=-0.001095, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=10891786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=0.096980, depth_time=2026-10-12T16:00:16+00:00, book20_bid_proxy_usdt=264975, book20_ask_proxy_usdt=235614, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=72169744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-12T16:00:00+00:00, last15m_closed_end=2026-10-12T16:00+00:00, prior8high=0.061100, depth_time=2026-10-12T16:00:23+00:00, book20_bid_proxy_usdt=98580, book20_ask_proxy_usdt=133640, funding_indicative=0.000010, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=31142282. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
