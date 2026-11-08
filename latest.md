# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T11:00:40Z**
- feed_generated_utc: 2026-11-08T11:00:41+00:00
- source_sha256: `0278c0a2fe71e25ec42bbf7a2a48fe3d6dcf46ea6d49700fd8c9303fbc303519`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T11:00+00:00, close=75861.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T11:00+00:00, close=75861.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001933|-4.21|64.67|-4.38|25382710|0.52|
|TIA_USDT|0.424900|-3.65|-13.30|-3.82|7202041|2.35|
|ENA_USDT|0.152780|-3.41|-21.25|-3.58|27988212|0.66|
|WLD_USDT|0.328000|-2.49|-18.89|-2.66|22587984|3.05|
|SUI_USDT|0.847600|-1.53|-6.03|-1.70|21297452|1.18|
|ADA_USDT|0.179800|-1.53|-7.12|-1.70|9361952|5.56|
|LINK_USDT|10.746000|-1.45|-7.12|-1.62|61178457|2.79|
|DOGE_USDT|0.070880|-1.35|-6.29|-1.52|38722193|1.41|
|XLM_USDT|0.149900|-1.29|-12.71|-1.46|16441405|2.00|
|ONDO_USDT|0.359900|-1.18|-12.73|-1.35|7768259|2.78|
|AVAX_USDT|8.159000|-1.13|-4.40|-1.30|8293418|1.23|
|AAVE_USDT|130.310000|-1.09|-3.83|-1.26|9875986|0.77|
|HYPE_USDT|77.024000|-1.04|-12.01|-1.21|20032252|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.310000|129.470000|130.310000|0.16|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179800|0.178900|0.179800|0.88|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.159000|8.114000|8.159000|0.74|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.070880|0.070450|0.070880|0.41|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.152780|0.152210|0.152790|0.81|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|77.024000|76.688000|77.024000|2.13|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.746000|10.704000|10.746000|0.87|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359900|0.358000|0.359900|2.52|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001933|0.001981|0.001933|2.20|Y|Y/N|N/N|Y|N|
|SUI_USDT|0.847600|0.846400|0.847600|1.42|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.424900|0.422800|0.424900|0.40|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.328000|0.325700|0.328000|1.23|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.149900|0.149550|0.149880|1.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=130.800000, depth_time=2026-11-08T11:00:36+00:00, book20_bid_proxy_usdt=749610, book20_ask_proxy_usdt=622372, funding_indicative=0.000042, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=9875986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.180300, depth_time=2026-11-08T11:00:21+00:00, book20_bid_proxy_usdt=10037378, book20_ask_proxy_usdt=8786479, funding_indicative=-0.000070, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=9361952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=8.175000, depth_time=2026-11-08T11:00:34+00:00, book20_bid_proxy_usdt=1174625, book20_ask_proxy_usdt=2531265, funding_indicative=0.000065, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=8293418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.071180, depth_time=2026-11-08T11:00:25+00:00, book20_bid_proxy_usdt=3602008, book20_ask_proxy_usdt=5187979, funding_indicative=0.000082, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=38722193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.154630, depth_time=2026-11-08T11:00:11+00:00, book20_bid_proxy_usdt=244052, book20_ask_proxy_usdt=235079, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=27988212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=77.515000, depth_time=2026-11-08T11:00:36+00:00, book20_bid_proxy_usdt=95046, book20_ask_proxy_usdt=114744, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=20032252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=10.775000, depth_time=2026-11-08T11:00:23+00:00, book20_bid_proxy_usdt=852252, book20_ask_proxy_usdt=426321, funding_indicative=0.000030, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=61178457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.360700, depth_time=2026-11-08T11:00:30+00:00, book20_bid_proxy_usdt=2036834, book20_ask_proxy_usdt=1424728, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=7768259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.002247, depth_time=2026-11-08T11:00:07+00:00, book20_bid_proxy_usdt=15469, book20_ask_proxy_usdt=12071, funding_indicative=-0.002140, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=25382710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.853300, depth_time=2026-11-08T11:00:18+00:00, book20_bid_proxy_usdt=1689616, book20_ask_proxy_usdt=1914415, funding_indicative=0.000006, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=21297452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.428400, depth_time=2026-11-08T11:00:04+00:00, book20_bid_proxy_usdt=332552, book20_ask_proxy_usdt=358772, funding_indicative=0.000034, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=7202041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.328500, depth_time=2026-11-08T11:00:15+00:00, book20_bid_proxy_usdt=4094202, book20_ask_proxy_usdt=4525093, funding_indicative=-0.000033, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=22587984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-08T11:00:01+00:00, last15m_closed_end=2026-11-08T11:00+00:00, prior8high=0.150510, depth_time=2026-11-08T11:00:22+00:00, book20_bid_proxy_usdt=142362, book20_ask_proxy_usdt=207923, funding_indicative=-0.000072, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=16441405. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
