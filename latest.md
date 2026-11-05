# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T18:15:32Z**
- feed_generated_utc: 2026-11-05T18:15:34+00:00
- source_sha256: `0155d20164453376517752c023baad12df3e67e34143ab5e365875ece636be67`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T18:15+00:00, close=76109.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T18:00+00:00, close=75920.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002107|-18.33|-89.99|-18.42|16131686|4.75|
|FLUID_USDT|2.440000|-3.63|18.21|-3.72|8863056|4.10|
|TRUMPOFFICIAL_USDT|1.134000|-2.82|-34.37|-2.91|29470761|8.82|
|BCH_USDT|273.610000|-1.97|-5.08|-2.06|10110254|3.66|
|ONDO_USDT|0.367300|-1.39|-14.54|-1.48|29234157|2.73|
|NEAR_USDT|3.658000|-1.26|-21.31|-1.35|69177984|5.47|
|PENGU_USDT|0.006440|-1.04|-20.79|-1.13|6147106|1.55|
|XLM_USDT|0.152660|-1.00|-11.62|-1.09|46050757|0.66|
|XPL_USDT|0.058000|-0.99|-26.51|-1.08|11701202|1.73|
|HYPE_USDT|77.943000|-0.96|-17.02|-1.05|89718062|0.13|
|XRP_USDT|1.233200|-0.91|-5.82|-1.00|423837992|0.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002107|0.002062|0.002105|3.07|N|Y/N|Y/Y|Y|N|
|BCH_USDT|273.610000|273.260000|273.610000|0.86|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.440000|2.364000|2.440000|0.25|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.943000|77.688000|77.988000|0.47|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.658000|3.683000|3.659000|1.81|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.367300|0.369700|0.367300|3.87|Y|Y/Y|Y/Y|Y|Y|
|PENGU_USDT|0.006440|0.006338|0.006440|0.36|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.134000|1.112000|1.134000|2.23|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.152660|0.151960|0.152670|1.26|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.058000|0.057810|0.058000|0.93|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.233200|1.232300|1.233200|0.95|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=0.003465, depth_time=2026-11-05T18:15:07+00:00, book20_bid_proxy_usdt=39700, book20_ask_proxy_usdt=31716, funding_indicative=-0.015922, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-18.33%, turnover=16131686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T18:15:01+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=284.120000, depth_time=2026-11-05T18:15:14+00:00, book20_bid_proxy_usdt=58312, book20_ask_proxy_usdt=76989, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=10110254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=2.611000, depth_time=2026-11-05T18:15:09+00:00, book20_bid_proxy_usdt=197570, book20_ask_proxy_usdt=165000, funding_indicative=0.000209, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=8863056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=80.266000, depth_time=2026-11-05T18:15:29+00:00, book20_bid_proxy_usdt=284974, book20_ask_proxy_usdt=11469, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=89718062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=3.810000, depth_time=2026-11-05T18:15:19+00:00, book20_bid_proxy_usdt=500059, book20_ask_proxy_usdt=1775989, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=69177984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=0.379600, depth_time=2026-11-05T18:15:17+00:00, book20_bid_proxy_usdt=1155614, book20_ask_proxy_usdt=1872404, funding_indicative=0.000036, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=29234157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T18:15:01+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=0.006695, depth_time=2026-11-05T18:15:22+00:00, book20_bid_proxy_usdt=192256, book20_ask_proxy_usdt=130838, funding_indicative=-0.000021, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=6147106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=1.204000, depth_time=2026-11-05T18:15:12+00:00, book20_bid_proxy_usdt=1263769, book20_ask_proxy_usdt=1706462, funding_indicative=-0.000041, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=29470761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-05T18:15:01+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=0.156980, depth_time=2026-11-05T18:15:24+00:00, book20_bid_proxy_usdt=131647, book20_ask_proxy_usdt=118429, funding_indicative=-0.000058, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=46050757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-05T18:15:01+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=0.059950, depth_time=2026-11-05T18:15:27+00:00, book20_bid_proxy_usdt=340069, book20_ask_proxy_usdt=456296, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=11701202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T18:15:00+00:00, last15m_closed_end=2026-11-05T18:15+00:00, prior8high=1.259400, depth_time=2026-11-05T18:15:31+00:00, book20_bid_proxy_usdt=2787871, book20_ask_proxy_usdt=3111131, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=423837992. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
