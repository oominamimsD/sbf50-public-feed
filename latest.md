# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T09:30:36Z**
- feed_generated_utc: 2026-11-08T09:30:37+00:00
- source_sha256: `294e3d2595a98cf0df7de55a57d28c9a5b1d9a397885dde9db122ccd8b5bf17d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T09:30+00:00, close=75868.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T09:00+00:00, close=75900.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005340|-10.74|-52.05|-10.92|36128489|3.75|
|TIA_USDT|0.426300|-3.46|-13.01|-3.64|7529415|2.35|
|ENA_USDT|0.153620|-2.88|-20.81|-3.06|29507285|0.65|
|WLD_USDT|0.326800|-2.62|-19.18|-2.80|24244153|3.06|
|QNT_USDT|194.330000|-2.27|-3.34|-2.45|43104068|0.52|
|AAVE_USDT|129.800000|-1.83|-4.21|-2.01|10559484|0.77|
|ADA_USDT|0.179400|-1.21|-7.33|-1.39|10129409|5.58|
|DOGE_USDT|0.070780|-1.11|-6.42|-1.29|41781924|1.41|
|ONDO_USDT|0.359200|-1.07|-12.90|-1.25|8469843|2.78|
|SUI_USDT|0.848500|-1.00|-5.93|-1.18|23013752|1.18|
|LINK_USDT|10.737000|-0.98|-7.20|-1.16|65497736|1.86|
|AVAX_USDT|8.135000|-0.92|-4.68|-1.10|8134204|1.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.800000|130.010000|129.820000|3.22|Y|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179400|0.179600|0.179400|14.93|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.005340|0.005136|0.005371|4.14|N|N/N|N/N|Y|N|
|AVAX_USDT|8.135000|8.147000|8.135000|15.06|Y|Y/Y|Y/Y|Y|Y|
|DOGE_USDT|0.070780|0.070930|0.070780|8.17|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.153620|0.153590|0.153620|2.75|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.737000|10.708000|10.738000|1.61|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359200|0.358500|0.359200|3.42|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.330000|194.670000|194.330000|2.06|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.848500|0.848800|0.848700|1.86|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.426300|0.425800|0.426300|1.09|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.326800|0.326300|0.326800|2.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=130.820000, depth_time=2026-11-08T09:30:18+00:00, book20_bid_proxy_usdt=488632, book20_ask_proxy_usdt=408271, funding_indicative=0.000013, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=10559484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.180600, depth_time=2026-11-08T09:30:21+00:00, book20_bid_proxy_usdt=11108077, book20_ask_proxy_usdt=9331369, funding_indicative=-0.000031, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=10129409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.006025, depth_time=2026-11-08T09:30:07+00:00, book20_bid_proxy_usdt=33882, book20_ask_proxy_usdt=37634, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.74%, turnover=36128489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=8.196000, depth_time=2026-11-08T09:30:30+00:00, book20_bid_proxy_usdt=1681608, book20_ask_proxy_usdt=2029936, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=8134204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.071310, depth_time=2026-11-08T09:30:24+00:00, book20_bid_proxy_usdt=3692617, book20_ask_proxy_usdt=6572769, funding_indicative=0.000030, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=41781924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.154850, depth_time=2026-11-08T09:30:11+00:00, book20_bid_proxy_usdt=295868, book20_ask_proxy_usdt=270022, funding_indicative=0.000028, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=29507285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=10.753000, depth_time=2026-11-08T09:30:31+00:00, book20_bid_proxy_usdt=386524, book20_ask_proxy_usdt=756583, funding_indicative=0.000061, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=65497736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.360600, depth_time=2026-11-08T09:30:27+00:00, book20_bid_proxy_usdt=1285678, book20_ask_proxy_usdt=1626302, funding_indicative=0.000047, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.07%, turnover=8469843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=196.140000, depth_time=2026-11-08T09:30:15+00:00, book20_bid_proxy_usdt=84392, book20_ask_proxy_usdt=101922, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=43104068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.855500, depth_time=2026-11-08T09:30:28+00:00, book20_bid_proxy_usdt=1603767, book20_ask_proxy_usdt=1814815, funding_indicative=-0.000023, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=23013752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.431700, depth_time=2026-11-08T09:30:08+00:00, book20_bid_proxy_usdt=335322, book20_ask_proxy_usdt=332412, funding_indicative=0.000047, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=7529415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T09:30:02+00:00, last15m_closed_end=2026-11-08T09:30+00:00, prior8high=0.331200, depth_time=2026-11-08T09:30:12+00:00, book20_bid_proxy_usdt=4026576, book20_ask_proxy_usdt=3542557, funding_indicative=-0.000134, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=24244153. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
