# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T10:15:43Z**
- feed_generated_utc: 2026-10-25T10:15:47+00:00
- source_sha256: `3557d987cc6294c3afd72e760538e4224826b83ecddd4282ab54206d6dc33d6e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T10:15+00:00, close=80358.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T10:00+00:00, close=80293, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.051080|-24.21|65.04|-24.95|11731050|5.87|
|IRYS_USDT|0.034930|-24.14|173.74|-24.88|31640841|2.87|
|BTW_USDT|1.611900|-7.43|-28.97|-8.17|11277111|0.62|
|WLD_USDT|0.445600|-3.54|-10.08|-4.28|92569136|2.24|
|STRK_USDT|0.045350|-2.95|-31.44|-3.69|9096933|2.21|
|DOT_USDT|1.023300|-1.52|-8.42|-2.26|11807095|0.98|
|SUI_USDT|0.911900|-1.41|-7.11|-2.15|66720741|1.10|
|AGT_USDT|0.066090|-1.25|-8.28|-1.99|5013306|1.51|
|APT_USDT|0.693900|-1.13|-12.99|-1.87|5865535|2.88|
|SEI_USDT|0.052430|-0.85|-15.44|-1.59|7770223|1.91|
|PENGU_USDT|0.007380|-0.84|-0.97|-1.58|5659584|1.35|
|AKE_USDT|0.029012|-0.74|0.17|-1.48|5238038|5.86|
|ARB_USDT|0.164530|-0.73|-10.54|-1.47|15604281|0.61|
|LINK_USDT|11.318000|-0.56|-4.93|-1.30|47265310|0.88|
|ONDO_USDT|0.400200|-0.29|-8.96|-1.03|14726058|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066090|0.064580|0.066090|1.20|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.029012|0.028536|0.029012|4.66|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.693900|0.687600|0.693900|0.34|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164530|0.163130|0.164530|2.08|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.611900|1.636300|1.611900|1.38|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|1.023300|1.011600|1.023300|1.39|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034930|0.034520|0.034930|0.78|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.318000|11.255000|11.318000|0.64|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.400200|0.396800|0.400200|0.45|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.051080|0.048370|0.051070|1.33|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007380|0.007294|0.007380|0.93|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052430|0.051870|0.052430|0.43|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045350|0.045060|0.045350|1.13|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.911900|0.903500|0.911900|1.03|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.445600|0.431900|0.445600|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-25T10:15:00+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.079780, depth_time=2026-10-25T10:15:24+00:00, book20_bid_proxy_usdt=9200, book20_ask_proxy_usdt=9809, funding_indicative=0.000221, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=5013306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.029155, depth_time=2026-10-25T10:15:35+00:00, book20_bid_proxy_usdt=10325, book20_ask_proxy_usdt=12272, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.74%, turnover=5238038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.703200, depth_time=2026-10-25T10:15:27+00:00, book20_bid_proxy_usdt=204172, book20_ask_proxy_usdt=169171, funding_indicative=-0.000081, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=5865535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.166520, depth_time=2026-10-25T10:15:35+00:00, book20_bid_proxy_usdt=113495, book20_ask_proxy_usdt=93961, funding_indicative=0.000052, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=15604281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=1.692100, depth_time=2026-10-25T10:15:12+00:00, book20_bid_proxy_usdt=7568, book20_ask_proxy_usdt=21608, funding_indicative=-0.017572, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.43%, turnover=11277111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=1.030300, depth_time=2026-10-25T10:15:19+00:00, book20_bid_proxy_usdt=371190, book20_ask_proxy_usdt=323535, funding_indicative=-0.000013, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=11807095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T10:15:00+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.038050, depth_time=2026-10-25T10:15:10+00:00, book20_bid_proxy_usdt=65997, book20_ask_proxy_usdt=64267, funding_indicative=-0.001283, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-24.14%, turnover=31640841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=11.404000, depth_time=2026-10-25T10:15:39+00:00, book20_bid_proxy_usdt=595676, book20_ask_proxy_usdt=525976, funding_indicative=0.000032, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.56%, turnover=47265310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.404600, depth_time=2026-10-25T10:15:42+00:00, book20_bid_proxy_usdt=3599826, book20_ask_proxy_usdt=2234617, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.29%, turnover=14726058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T10:15:00+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.053130, depth_time=2026-10-25T10:15:07+00:00, book20_bid_proxy_usdt=91488, book20_ask_proxy_usdt=55199, funding_indicative=-0.001678, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-24.21%, turnover=11731050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.007459, depth_time=2026-10-25T10:15:32+00:00, book20_bid_proxy_usdt=209650, book20_ask_proxy_usdt=243722, funding_indicative=-0.000061, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=5659584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.052870, depth_time=2026-10-25T10:15:29+00:00, book20_bid_proxy_usdt=293173, book20_ask_proxy_usdt=329408, funding_indicative=-0.000111, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=7770223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T10:15:01+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.046510, depth_time=2026-10-25T10:15:17+00:00, book20_bid_proxy_usdt=794656, book20_ask_proxy_usdt=695699, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=9096933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T10:15:00+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.920000, depth_time=2026-10-25T10:15:22+00:00, book20_bid_proxy_usdt=1747966, book20_ask_proxy_usdt=1045994, funding_indicative=0.000067, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=66720741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T10:15:00+00:00, last15m_closed_end=2026-10-25T10:15+00:00, prior8high=0.465800, depth_time=2026-10-25T10:15:15+00:00, book20_bid_proxy_usdt=2174836, book20_ask_proxy_usdt=1745705, funding_indicative=-0.000001, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=92569136. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
