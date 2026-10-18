# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T06:30:44Z**
- feed_generated_utc: 2026-10-18T06:30:46+00:00
- source_sha256: `5ab121f8efb118a0a8bb9d6fa2e9f2228edbdfeb6f565876951181fa79397138`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T06:30+00:00, close=81664, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T06:00+00:00, close=81700.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062810|-5.04|-32.77|-5.46|14203974|1.59|
|TIA_USDT|0.627200|-4.68|22.26|-5.10|61991188|1.59|
|EIGEN_USDT|0.246900|-3.66|4.79|-4.08|8410055|4.05|
|FILECOIN_USDT|1.049100|-3.52|-6.97|-3.94|19967354|0.95|
|QNT_USDT|194.460000|-2.96|-20.67|-3.38|69812619|0.51|
|PUMPFUN_USDT|0.004285|-2.87|-25.15|-3.29|23466088|2.33|
|ZRO_USDT|1.837300|-2.54|-9.07|-2.96|7224005|0.54|
|XPL_USDT|0.078300|-2.28|-9.75|-2.70|5242180|1.28|
|OP_USDT|0.126070|-2.27|-9.00|-2.69|9750267|0.79|
|DOT_USDT|1.100600|-1.50|-12.43|-1.92|16795434|0.91|
|APT_USDT|0.787300|-1.27|-4.77|-1.69|10427085|1.27|
|WLD_USDT|0.491000|-0.92|-12.16|-1.34|60009298|2.04|
|ENA_USDT|0.187550|-0.85|-15.53|-1.27|28475776|0.53|
|AVAX_USDT|9.749000|-0.71|-7.37|-1.13|79671353|1.03|
|ICP_USDT|2.910000|-0.61|-7.58|-1.03|6336242|3.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.787300|0.780900|0.787400|2.26|N|Y/Y|Y/Y|N|N|
|AVAX_USDT|9.749000|9.701000|9.749000|1.14|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.100600|1.089000|1.100600|2.42|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.246900|0.244000|0.246900|1.38|N|Y/Y|N/Y|N|N|
|ENA_USDT|0.187550|0.186180|0.187550|1.72|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.049100|1.040400|1.049100|1.13|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.910000|2.885000|2.911000|1.18|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.126070|0.124920|0.126070|2.63|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004285|0.004262|0.004286|0.57|N|Y/Y|Y/Y|N|N|
|QNT_USDT|194.460000|191.970000|194.540000|0.81|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.062810|0.062440|0.062800|3.70|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.627200|0.623000|0.627100|1.33|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.491000|0.483600|0.490900|0.83|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.078300|0.077620|0.078300|6.09|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.837300|1.827700|1.837300|0.46|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.793700, depth_time=2026-10-18T06:30:31+00:00, book20_bid_proxy_usdt=125570, book20_ask_proxy_usdt=151691, funding_indicative=-0.000120, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=10427085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=9.830000, depth_time=2026-10-18T06:30:40+00:00, book20_bid_proxy_usdt=713317, book20_ask_proxy_usdt=589286, funding_indicative=-0.000002, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=79671353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=1.110800, depth_time=2026-10-18T06:30:30+00:00, book20_bid_proxy_usdt=246091, book20_ask_proxy_usdt=342722, funding_indicative=-0.000075, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=16795434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.251300, depth_time=2026-10-18T06:30:10+00:00, book20_bid_proxy_usdt=544342, book20_ask_proxy_usdt=460790, funding_indicative=-0.000044, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=8410055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.190230, depth_time=2026-10-18T06:30:36+00:00, book20_bid_proxy_usdt=161324, book20_ask_proxy_usdt=208606, funding_indicative=0.000005, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=28475776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=1.065800, depth_time=2026-10-18T06:30:12+00:00, book20_bid_proxy_usdt=395508, book20_ask_proxy_usdt=762113, funding_indicative=-0.000101, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=19967354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T06:30:02+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=2.935000, depth_time=2026-10-18T06:30:41+00:00, book20_bid_proxy_usdt=796400, book20_ask_proxy_usdt=1093991, funding_indicative=0.000014, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=6336242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.128390, depth_time=2026-10-18T06:30:27+00:00, book20_bid_proxy_usdt=38984, book20_ask_proxy_usdt=64240, funding_indicative=-0.000173, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=9750267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.004361, depth_time=2026-10-18T06:30:19+00:00, book20_bid_proxy_usdt=1467834, book20_ask_proxy_usdt=1225481, funding_indicative=0.000041, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=23466088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=196.160000, depth_time=2026-10-18T06:30:15+00:00, book20_bid_proxy_usdt=68186, book20_ask_proxy_usdt=80970, funding_indicative=-0.000080, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=69812619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.063490, depth_time=2026-10-18T06:30:07+00:00, book20_bid_proxy_usdt=510486, book20_ask_proxy_usdt=364414, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=14203974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.637700, depth_time=2026-10-18T06:30:09+00:00, book20_bid_proxy_usdt=197404, book20_ask_proxy_usdt=323235, funding_indicative=-0.000009, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=61991188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.494900, depth_time=2026-10-18T06:30:35+00:00, book20_bid_proxy_usdt=1556738, book20_ask_proxy_usdt=1991655, funding_indicative=-0.000122, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=60009298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T06:30:02+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=0.078990, depth_time=2026-10-18T06:30:23+00:00, book20_bid_proxy_usdt=526186, book20_ask_proxy_usdt=367968, funding_indicative=0.000013, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=5242180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T06:30:01+00:00, last15m_closed_end=2026-10-18T06:30+00:00, prior8high=1.894900, depth_time=2026-10-18T06:30:22+00:00, book20_bid_proxy_usdt=33881, book20_ask_proxy_usdt=43481, funding_indicative=0.000032, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=7224005. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
