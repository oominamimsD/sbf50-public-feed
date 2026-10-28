# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T17:45:31Z**
- feed_generated_utc: 2026-10-28T17:45:35+00:00
- source_sha256: `2647c3d740f07bbe341f45021210e4844e636a468b045efefb2bd4f240e6dbbf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T17:45+00:00, close=80704.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T17:00+00:00, close=80591.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.526800|-2.46|-16.71|-2.67|14745828|1.90|
|STRK_USDT|0.045960|-1.79|-25.83|-2.00|5256083|2.17|
|WLD_USDT|0.426200|-1.52|-25.69|-1.73|64406121|2.35|
|HBAR_USDT|0.074890|-1.34|-12.85|-1.55|11547528|1.33|
|APT_USDT|0.680600|-1.17|-18.54|-1.38|6266460|1.47|
|ONDO_USDT|0.414700|-1.07|-11.12|-1.28|17121098|2.41|
|ARB_USDT|0.166060|-0.98|-15.53|-1.19|18585847|0.60|
|OP_USDT|0.110040|-0.93|-16.57|-1.14|6385797|1.82|
|FET_USDT|0.180000|-0.93|-10.26|-1.14|6212598|5.56|
|DOT_USDT|0.995600|-0.79|-15.61|-1.00|12381469|2.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.680600|0.675400|0.680500|0.87|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166060|0.164410|0.166060|0.87|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.995600|0.987000|0.996000|1.50|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.180000|0.178400|0.180000|1.31|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074890|0.074660|0.074890|2.84|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.414700|0.412000|0.414700|0.39|N|Y/Y|N/N|Y|N|
|OP_USDT|0.110040|0.109270|0.110040|0.50|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045960|0.045520|0.045960|0.59|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.526800|0.523300|0.526800|0.42|N|Y/N|N/Y|Y|N|
|WLD_USDT|0.426200|0.416900|0.426200|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.690200, depth_time=2026-10-28T17:45:17+00:00, book20_bid_proxy_usdt=173772, book20_ask_proxy_usdt=198868, funding_indicative=-0.000137, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=6266460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.167890, depth_time=2026-10-28T17:45:23+00:00, book20_bid_proxy_usdt=64699, book20_ask_proxy_usdt=91606, funding_indicative=-0.000035, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=18585847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=1.006600, depth_time=2026-10-28T17:45:30+00:00, book20_bid_proxy_usdt=310449, book20_ask_proxy_usdt=335472, funding_indicative=0.000020, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=12381469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.182200, depth_time=2026-10-28T17:45:27+00:00, book20_bid_proxy_usdt=1716697, book20_ask_proxy_usdt=1156914, funding_indicative=0.000049, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=6212598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.075940, depth_time=2026-10-28T17:45:15+00:00, book20_bid_proxy_usdt=1258482, book20_ask_proxy_usdt=1261239, funding_indicative=0.000010, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=11547528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.419600, depth_time=2026-10-28T17:45:19+00:00, book20_bid_proxy_usdt=1573831, book20_ask_proxy_usdt=1879226, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.07%, turnover=17121098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.111150, depth_time=2026-10-28T17:45:25+00:00, book20_bid_proxy_usdt=81667, book20_ask_proxy_usdt=147192, funding_indicative=-0.000071, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=6385797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.047080, depth_time=2026-10-28T17:45:10+00:00, book20_bid_proxy_usdt=492744, book20_ask_proxy_usdt=792494, funding_indicative=-0.000006, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=5256083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.543600, depth_time=2026-10-28T17:45:08+00:00, book20_bid_proxy_usdt=266653, book20_ask_proxy_usdt=300863, funding_indicative=0.000025, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=14745828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T17:45:01+00:00, last15m_closed_end=2026-10-28T17:45+00:00, prior8high=0.434900, depth_time=2026-10-28T17:45:13+00:00, book20_bid_proxy_usdt=3530202, book20_ask_proxy_usdt=3563203, funding_indicative=0.000009, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=64406121. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
