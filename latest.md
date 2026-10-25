# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T10:45:41Z**
- feed_generated_utc: 2026-10-25T10:45:44+00:00
- source_sha256: `dd11e75edefe0fc0097fc5c5833e709579029b044d91c8be913ee389d11f91ba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T10:45+00:00, close=80291.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T10:00+00:00, close=80293, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.050260|-25.43|62.39|-26.09|11770121|3.98|
|IRYS_USDT|0.035390|-23.14|177.35|-23.80|31912907|2.83|
|BTW_USDT|1.665400|-4.35|-26.61|-5.01|11457676|1.80|
|WLD_USDT|0.443200|-4.06|-10.57|-4.72|94534328|2.26|
|STRK_USDT|0.045290|-3.08|-31.53|-3.74|9351500|2.21|
|DOT_USDT|1.017300|-2.09|-8.95|-2.75|12224028|0.98|
|SUI_USDT|0.910100|-1.61|-7.30|-2.27|67956924|1.10|
|APT_USDT|0.692200|-1.38|-13.20|-2.04|5880997|1.45|
|PENGU_USDT|0.007358|-1.14|-1.27|-1.80|5789512|1.36|
|SEI_USDT|0.052350|-1.00|-15.57|-1.66|7823984|1.91|
|ARB_USDT|0.164510|-0.74|-10.55|-1.40|15823618|0.61|
|LINK_USDT|11.316000|-0.57|-4.95|-1.23|47664781|0.88|
|ONDO_USDT|0.400000|-0.34|-9.00|-1.00|15072992|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.692200|0.687600|0.692200|0.16|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164510|0.163130|0.164510|0.61|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.665400|1.610600|1.664800|0.84|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.017300|1.011600|1.017300|3.75|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035390|0.034520|0.035380|0.73|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.316000|11.255000|11.315000|0.45|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.400000|0.396800|0.400000|0.47|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.050260|0.048370|0.050260|0.75|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007358|0.007294|0.007358|0.42|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052350|0.051870|0.052350|0.52|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045290|0.045060|0.045290|0.32|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.910100|0.903500|0.910100|0.84|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.443200|0.431900|0.443100|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.696000, depth_time=2026-10-25T10:45:27+00:00, book20_bid_proxy_usdt=180538, book20_ask_proxy_usdt=149311, funding_indicative=-0.000098, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=5880997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.164850, depth_time=2026-10-25T10:45:34+00:00, book20_bid_proxy_usdt=115130, book20_ask_proxy_usdt=81767, funding_indicative=0.000064, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=15823618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=1.684800, depth_time=2026-10-25T10:45:14+00:00, book20_bid_proxy_usdt=9338, book20_ask_proxy_usdt=7847, funding_indicative=-0.018881, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=11457676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=1.026000, depth_time=2026-10-25T10:45:21+00:00, book20_bid_proxy_usdt=280031, book20_ask_proxy_usdt=381389, funding_indicative=-0.000035, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=12224028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.038010, depth_time=2026-10-25T10:45:11+00:00, book20_bid_proxy_usdt=36369, book20_ask_proxy_usdt=53489, funding_indicative=-0.001111, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-23.14%, turnover=31912907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=11.359000, depth_time=2026-10-25T10:45:37+00:00, book20_bid_proxy_usdt=764124, book20_ask_proxy_usdt=451533, funding_indicative=0.000013, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.57%, turnover=47664781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.401600, depth_time=2026-10-25T10:45:39+00:00, book20_bid_proxy_usdt=2795522, book20_ask_proxy_usdt=2878761, funding_indicative=0.000028, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.34%, turnover=15072992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T10:45:00+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.053130, depth_time=2026-10-25T10:45:08+00:00, book20_bid_proxy_usdt=80381, book20_ask_proxy_usdt=126408, funding_indicative=-0.001627, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-25.43%, turnover=11770121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.007408, depth_time=2026-10-25T10:45:29+00:00, book20_bid_proxy_usdt=165074, book20_ask_proxy_usdt=257647, funding_indicative=-0.000074, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=5789512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.052520, depth_time=2026-10-25T10:45:32+00:00, book20_bid_proxy_usdt=315712, book20_ask_proxy_usdt=354138, funding_indicative=-0.000121, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=7823984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.045770, depth_time=2026-10-25T10:45:17+00:00, book20_bid_proxy_usdt=831823, book20_ask_proxy_usdt=980763, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=9351500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.915200, depth_time=2026-10-25T10:45:23+00:00, book20_bid_proxy_usdt=1364701, book20_ask_proxy_usdt=1460148, funding_indicative=0.000015, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=67956924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T10:45:01+00:00, last15m_closed_end=2026-10-25T10:45+00:00, prior8high=0.457500, depth_time=2026-10-25T10:45:15+00:00, book20_bid_proxy_usdt=1967062, book20_ask_proxy_usdt=1698478, funding_indicative=0.000000, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=94534328. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
