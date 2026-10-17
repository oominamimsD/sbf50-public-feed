# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T08:30:42Z**
- feed_generated_utc: 2026-10-17T08:30:44+00:00
- source_sha256: `728a2b2803cd05d1b3564193cf422b6891290ec4b9901b8f1b121461970f847e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T08:30+00:00, close=81692.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.960800|-6.68|-3.73|-7.13|12413357|0.51|
|OP_USDT|0.135260|-3.38|9.77|-3.83|14990095|0.74|
|ARB_USDT|0.188450|-3.32|4.23|-3.77|27392968|0.53|
|APT_USDT|0.828700|-3.20|3.52|-3.65|12012650|1.21|
|RIVER_USDT|1.092000|-3.01|-7.61|-3.46|5050875|9.17|
|FET_USDT|0.194000|-2.80|-10.59|-3.25|12174814|5.16|
|INJ_USDT|8.741000|-2.63|26.15|-3.08|93400603|1.14|
|STRK_USDT|0.072020|-2.60|-4.36|-3.05|20217863|1.39|
|TAO_USDT|275.100000|-1.96|0.15|-2.41|64270614|1.09|
|ZEC_USDT|1167.970000|-1.68|-4.13|-2.13|1328899644|0.17|
|FILECOIN_USDT|1.150900|-1.36|7.56|-1.81|24591167|0.87|
|ICP_USDT|2.999000|-1.28|-0.66|-1.73|8463737|3.33|
|ENA_USDT|0.197430|-1.25|-8.41|-1.70|38219652|0.51|
|SUI_USDT|1.008000|-1.22|-4.68|-1.67|91875468|0.99|
|FARTCOIN_USDT|0.152840|-1.21|-6.44|-1.66|7193007|1.96|
|DOT_USDT|1.157300|-1.15|-2.58|-1.60|19517066|0.86|
|SEI_USDT|0.063590|-1.10|-2.88|-1.55|19187490|1.57|
|ONDO_USDT|0.453300|-0.83|-5.58|-1.28|28323976|2.21|
|LTC_USDT|59.450000|-0.68|-6.52|-1.13|8443245|1.68|
|XLM_USDT|0.179540|-0.62|-6.82|-1.07|14747829|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.828700|0.823300|0.828700|3.08|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.188450|0.188080|0.188450|1.06|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.197430|0.197300|0.197430|1.98|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.152840|0.151850|0.152890|0.60|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194000|0.193900|0.194000|0.78|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.150900|1.152300|1.150900|2.65|Y|N/N|N/N|Y|N|
|ICP_USDT|2.999000|2.988000|2.999000|1.48|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.741000|8.753000|8.740000|1.17|N|N/N|N/N|Y|N|
|OP_USDT|0.135260|0.134820|0.135260|1.44|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.092000|1.070000|1.092000|2.15|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.072020|0.070610|0.072020|0.74|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.008000|1.005500|1.008000|0.68|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.100000|274.030000|275.140000|0.80|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1167.970000|1160.060000|1168.230000|0.68|N|N/Y|Y/Y|Y|N|
|ZRO_USDT|1.960800|1.942800|1.960800|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.841500, depth_time=2026-10-17T08:30:15+00:00, book20_bid_proxy_usdt=114093, book20_ask_proxy_usdt=134396, funding_indicative=0.000062, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.20%, turnover=12012650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.189920, depth_time=2026-10-17T08:30:13+00:00, book20_bid_proxy_usdt=64342, book20_ask_proxy_usdt=54301, funding_indicative=-0.000016, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=27392968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.200030, depth_time=2026-10-17T08:30:36+00:00, book20_bid_proxy_usdt=203389, book20_ask_proxy_usdt=206346, funding_indicative=0.000012, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=38219652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.154340, depth_time=2026-10-17T08:30:41+00:00, book20_bid_proxy_usdt=68022, book20_ask_proxy_usdt=75391, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=7193007. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.195600, depth_time=2026-10-17T08:30:19+00:00, book20_bid_proxy_usdt=2096438, book20_ask_proxy_usdt=1103841, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=12174814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=1.180400, depth_time=2026-10-17T08:30:31+00:00, book20_bid_proxy_usdt=525422, book20_ask_proxy_usdt=563043, funding_indicative=0.000049, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=24591167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=3.028000, depth_time=2026-10-17T08:30:32+00:00, book20_bid_proxy_usdt=1049615, book20_ask_proxy_usdt=987887, funding_indicative=0.000027, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=8463737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=8.953000, depth_time=2026-10-17T08:30:21+00:00, book20_bid_proxy_usdt=345965, book20_ask_proxy_usdt=285895, funding_indicative=0.000249, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=93400603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.137400, depth_time=2026-10-17T08:30:09+00:00, book20_bid_proxy_usdt=63894, book20_ask_proxy_usdt=85588, funding_indicative=-0.000009, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=14990095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=1.098000, depth_time=2026-10-17T08:30:14+00:00, book20_bid_proxy_usdt=397761, book20_ask_proxy_usdt=381037, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=5050875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=0.071820, depth_time=2026-10-17T08:30:24+00:00, book20_bid_proxy_usdt=341827, book20_ask_proxy_usdt=166214, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=20217863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=1.012200, depth_time=2026-10-17T08:30:38+00:00, book20_bid_proxy_usdt=1355732, book20_ask_proxy_usdt=996333, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=91875468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=276.090000, depth_time=2026-10-17T08:30:26+00:00, book20_bid_proxy_usdt=149864, book20_ask_proxy_usdt=104054, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=64270614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=1174.140000, depth_time=2026-10-17T08:30:29+00:00, book20_bid_proxy_usdt=778476, book20_ask_proxy_usdt=242119, funding_indicative=0.000032, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=1328899644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T08:30:00+00:00, last15m_closed_end=2026-10-17T08:30+00:00, prior8high=1.972100, depth_time=2026-10-17T08:30:07+00:00, book20_bid_proxy_usdt=43381, book20_ask_proxy_usdt=28166, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.68%, turnover=12413357. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
