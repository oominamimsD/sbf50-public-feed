# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T08:30:44Z**
- feed_generated_utc: 2026-10-25T08:30:47+00:00
- source_sha256: `c961d05ac07b2ed08f663ec7c800bcf6b898aefc41a370ae33216352ecee9e47`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T08:30+00:00, close=80360.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.049790|-26.12|60.87|-26.84|13957306|4.02|
|BIRB_USDT|0.077550|-20.59|59.83|-21.31|5140529|2.58|
|IRYS_USDT|0.037610|-18.32|194.74|-19.04|33841374|2.67|
|BTW_USDT|1.659200|-4.71|-26.88|-5.43|11718005|8.43|
|STRK_USDT|0.045530|-2.56|-31.17|-3.28|8936880|2.20|
|DOT_USDT|1.021400|-1.70|-8.59|-2.42|12009604|0.98|
|SUI_USDT|0.910300|-1.58|-7.28|-2.30|66765551|1.10|
|WLD_USDT|0.455400|-1.42|-8.11|-2.14|91421797|4.39|
|APT_USDT|0.694400|-1.06|-12.92|-1.78|6164500|4.32|
|SEI_USDT|0.052320|-1.05|-15.62|-1.77|9790514|1.91|
|AKE_USDT|0.028929|-1.02|-0.11|-1.74|6195306|0.69|
|PENGU_USDT|0.007373|-0.94|-1.07|-1.66|5659398|1.36|
|ARB_USDT|0.164490|-0.75|-10.56|-1.47|14996372|0.61|
|LINK_USDT|11.335000|-0.41|-4.79|-1.13|49574844|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028929|0.028767|0.028929|0.46|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.694400|0.697500|0.694400|2.09|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.164490|0.164850|0.164620|1.26|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.077550|0.077200|0.077550|0.60|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.659200|1.590000|1.659200|0.82|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.021400|1.017100|1.021200|4.30|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037610|0.036180|0.037610|0.45|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.335000|11.339000|11.335000|1.30|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.049790|0.049270|0.049710|0.85|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007373|0.007419|0.007378|5.96|Y|Y/Y|Y/Y|Y|Y|
|SEI_USDT|0.052320|0.052590|0.052350|3.69|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.045530|0.045810|0.045530|5.64|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.910300|0.911400|0.911300|2.21|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.455400|0.460500|0.455400|3.39|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.029702, depth_time=2026-10-25T08:30:34+00:00, book20_bid_proxy_usdt=14431, book20_ask_proxy_usdt=10307, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.02%, turnover=6195306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.704800, depth_time=2026-10-25T08:30:30+00:00, book20_bid_proxy_usdt=115075, book20_ask_proxy_usdt=186947, funding_indicative=-0.000052, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=6164500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.166810, depth_time=2026-10-25T08:30:40+00:00, book20_bid_proxy_usdt=68503, book20_ask_proxy_usdt=135030, funding_indicative=0.000028, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=14996372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.084430, depth_time=2026-10-25T08:30:11+00:00, book20_bid_proxy_usdt=22113, book20_ask_proxy_usdt=27848, funding_indicative=-0.009399, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.59%, turnover=5140529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=1.915400, depth_time=2026-10-25T08:30:16+00:00, book20_bid_proxy_usdt=7947, book20_ask_proxy_usdt=9615, funding_indicative=-0.009808, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.71%, turnover=11718005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=1.032000, depth_time=2026-10-25T08:30:21+00:00, book20_bid_proxy_usdt=142136, book20_ask_proxy_usdt=346712, funding_indicative=-0.000038, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=12009604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.042780, depth_time=2026-10-25T08:30:14+00:00, book20_bid_proxy_usdt=39519, book20_ask_proxy_usdt=34785, funding_indicative=-0.001492, next_funding_utc=2026-10-25T09:00:00+00:00, funding_cycle_h=1, 24h_change=-18.32%, turnover=33841374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=11.430000, depth_time=2026-10-25T08:30:43+00:00, book20_bid_proxy_usdt=608995, book20_ask_proxy_usdt=505640, funding_indicative=0.000037, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.41%, turnover=49574844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.057510, depth_time=2026-10-25T08:30:09+00:00, book20_bid_proxy_usdt=75383, book20_ask_proxy_usdt=68919, funding_indicative=-0.001045, next_funding_utc=2026-10-25T09:00:00+00:00, funding_cycle_h=1, 24h_change=-26.12%, turnover=13957306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T08:30:02+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.007489, depth_time=2026-10-25T08:30:37+00:00, book20_bid_proxy_usdt=131830, book20_ask_proxy_usdt=222936, funding_indicative=-0.000064, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=5659398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T08:30:02+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.053190, depth_time=2026-10-25T08:30:32+00:00, book20_bid_proxy_usdt=167148, book20_ask_proxy_usdt=423623, funding_indicative=-0.000091, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=9790514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.046630, depth_time=2026-10-25T08:30:19+00:00, book20_bid_proxy_usdt=668050, book20_ask_proxy_usdt=694225, funding_indicative=0.000026, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=8936880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.921900, depth_time=2026-10-25T08:30:24+00:00, book20_bid_proxy_usdt=329073, book20_ask_proxy_usdt=1307180, funding_indicative=0.000023, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=66765551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T08:30:01+00:00, last15m_closed_end=2026-10-25T08:30+00:00, prior8high=0.466600, depth_time=2026-10-25T08:30:27+00:00, book20_bid_proxy_usdt=1565175, book20_ask_proxy_usdt=2635609, funding_indicative=-0.000055, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=91421797. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
