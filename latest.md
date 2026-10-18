# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T18:30:18Z**
- feed_generated_utc: 2026-10-18T18:30:20+00:00
- source_sha256: `2ac5b815c143f88b019ffeb81bcf51da08a6283e555540a0b7fa863ef524fcbe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T18:30+00:00, close=81128.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T18:00+00:00, close=81150, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059360|-3.57|-50.23|-3.56|16011374|3.37|
|BAT_USDT|0.170030|-3.05|2.03|-3.04|8798779|1.76|
|PUMPFUN_USDT|0.004126|-1.64|-28.55|-1.63|29634207|2.42|
|HBAR_USDT|0.084400|-1.60|-10.00|-1.59|42350945|1.19|
|WLD_USDT|0.470800|-1.15|-18.71|-1.14|74316143|2.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.170030|0.170170|0.170030|1.82|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.084400|0.084250|0.084400|0.77|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004126|0.004107|0.004126|0.11|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059360|0.058980|0.059370|1.67|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.470800|0.471100|0.470800|1.54|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T18:30:01+00:00, last15m_closed_end=2026-10-18T18:30+00:00, prior8high=0.175860, depth_time=2026-10-18T18:30:10+00:00, book20_bid_proxy_usdt=23443, book20_ask_proxy_usdt=26404, funding_indicative=0.000008, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=8798779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-18T18:30:01+00:00, last15m_closed_end=2026-10-18T18:30+00:00, prior8high=0.086580, depth_time=2026-10-18T18:30:15+00:00, book20_bid_proxy_usdt=816143, book20_ask_proxy_usdt=778137, funding_indicative=0.000022, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=42350945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T18:30:01+00:00, last15m_closed_end=2026-10-18T18:30+00:00, prior8high=0.004143, depth_time=2026-10-18T18:30:13+00:00, book20_bid_proxy_usdt=2295258, book20_ask_proxy_usdt=2145865, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=29634207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T18:30:01+00:00, last15m_closed_end=2026-10-18T18:30+00:00, prior8high=0.061940, depth_time=2026-10-18T18:30:08+00:00, book20_bid_proxy_usdt=288762, book20_ask_proxy_usdt=343620, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=16011374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T18:30:01+00:00, last15m_closed_end=2026-10-18T18:30+00:00, prior8high=0.480000, depth_time=2026-10-18T18:30:16+00:00, book20_bid_proxy_usdt=2189114, book20_ask_proxy_usdt=2141350, funding_indicative=-0.000197, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=74316143. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
