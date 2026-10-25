# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T10:30:44Z**
- feed_generated_utc: 2026-10-25T10:30:48+00:00
- source_sha256: `a4077026d5689bc568766ee44eb71847453381051e29ecdd642098f7c164fde9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T10:30+00:00, close=80304.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T10:00+00:00, close=80293, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.050170|-25.56|62.10|-26.23|11754925|1.99|
|IRYS_USDT|0.035360|-23.21|177.11|-23.88|31801503|2.83|
|BTW_USDT|1.658700|-4.74|-26.91|-5.41|11376877|3.02|
|WLD_USDT|0.441500|-4.43|-10.91|-5.10|94145003|2.27|
|STRK_USDT|0.045180|-3.31|-31.70|-3.98|9323990|2.21|
|AGT_USDT|0.065490|-2.15|-9.11|-2.82|5079072|4.58|
|DOT_USDT|1.018800|-1.95|-8.82|-2.62|11881447|0.98|
|SUI_USDT|0.910400|-1.57|-7.27|-2.24|67357031|1.10|
|APT_USDT|0.692200|-1.38|-13.20|-2.05|5871395|1.45|
|PENGU_USDT|0.007360|-1.11|-1.24|-1.78|5764821|1.36|
|SEI_USDT|0.052300|-1.09|-15.65|-1.76|7793323|1.91|
|ARB_USDT|0.164430|-0.79|-10.59|-1.46|15747963|0.61|
|AKE_USDT|0.029020|-0.71|0.20|-1.38|5303908|0.34|
|LINK_USDT|11.313000|-0.60|-4.98|-1.27|47454596|0.88|
|ONDO_USDT|0.399600|-0.44|-9.09|-1.11|15013193|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.065490|0.064580|0.065570|2.83|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.029020|0.028536|0.029020|2.59|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.692200|0.687600|0.692200|0.10|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164430|0.163130|0.164460|1.28|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.658700|1.610600|1.658700|1.14|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.018800|1.011600|1.018700|0.81|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035360|0.034520|0.035350|1.04|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.313000|11.255000|11.314000|0.34|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.399600|0.396800|0.399600|2.40|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.050170|0.048370|0.050170|1.12|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007360|0.007294|0.007360|2.27|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052300|0.051870|0.052300|0.39|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045180|0.045060|0.045180|2.79|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.910400|0.903500|0.910400|0.80|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.441500|0.431900|0.441500|1.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.079030, depth_time=2026-10-25T10:30:18+00:00, book20_bid_proxy_usdt=8999, book20_ask_proxy_usdt=12486, funding_indicative=0.000185, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=5079072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.029203, depth_time=2026-10-25T10:30:37+00:00, book20_bid_proxy_usdt=15366, book20_ask_proxy_usdt=10476, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.71%, turnover=5303908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.700300, depth_time=2026-10-25T10:30:28+00:00, book20_bid_proxy_usdt=124684, book20_ask_proxy_usdt=159558, funding_indicative=-0.000091, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=5871395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.165910, depth_time=2026-10-25T10:30:36+00:00, book20_bid_proxy_usdt=144065, book20_ask_proxy_usdt=79219, funding_indicative=0.000050, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=15747963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=1.687200, depth_time=2026-10-25T10:30:13+00:00, book20_bid_proxy_usdt=20378, book20_ask_proxy_usdt=11777, funding_indicative=-0.018669, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.74%, turnover=11376877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=1.027700, depth_time=2026-10-25T10:30:23+00:00, book20_bid_proxy_usdt=298600, book20_ask_proxy_usdt=327637, funding_indicative=-0.000025, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=11881447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.038050, depth_time=2026-10-25T10:30:10+00:00, book20_bid_proxy_usdt=31100, book20_ask_proxy_usdt=47348, funding_indicative=-0.001182, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-23.21%, turnover=31801503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=11.387000, depth_time=2026-10-25T10:30:41+00:00, book20_bid_proxy_usdt=418229, book20_ask_proxy_usdt=572763, funding_indicative=0.000023, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=47454596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.403700, depth_time=2026-10-25T10:30:43+00:00, book20_bid_proxy_usdt=2750871, book20_ask_proxy_usdt=2331937, funding_indicative=0.000036, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.44%, turnover=15013193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.053130, depth_time=2026-10-25T10:30:08+00:00, book20_bid_proxy_usdt=64973, book20_ask_proxy_usdt=85037, funding_indicative=-0.001702, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-25.56%, turnover=11754925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.007443, depth_time=2026-10-25T10:30:30+00:00, book20_bid_proxy_usdt=185755, book20_ask_proxy_usdt=261314, funding_indicative=-0.000073, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=5764821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.052650, depth_time=2026-10-25T10:30:33+00:00, book20_bid_proxy_usdt=239516, book20_ask_proxy_usdt=376002, funding_indicative=-0.000125, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=7793323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T10:30:02+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.045940, depth_time=2026-10-25T10:30:18+00:00, book20_bid_proxy_usdt=659022, book20_ask_proxy_usdt=694956, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=9323990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.918200, depth_time=2026-10-25T10:30:26+00:00, book20_bid_proxy_usdt=1062490, book20_ask_proxy_usdt=1307978, funding_indicative=0.000040, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=67357031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T10:30:01+00:00, last15m_closed_end=2026-10-25T10:30+00:00, prior8high=0.463100, depth_time=2026-10-25T10:30:16+00:00, book20_bid_proxy_usdt=1488104, book20_ask_proxy_usdt=1981584, funding_indicative=-0.000011, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.43%, turnover=94145003. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
