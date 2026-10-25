# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T08:00:43Z**
- feed_generated_utc: 2026-10-25T08:00:46+00:00
- source_sha256: `97eb29e70e2ecc94311b523f0c7f7042ee85d3fb23a221cdff3cecad1e87a8b6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.037100|-34.82|190.75|-35.41|33515319|2.70|
|ORDER_USDT|0.050530|-25.76|63.26|-26.35|13900159|3.95|
|BIRB_USDT|0.078360|-19.76|61.50|-20.35|5102986|2.55|
|BTW_USDT|1.675900|-3.75|-26.15|-4.34|11433263|1.19|
|DOT_USDT|1.029500|-1.86|-7.86|-2.45|11724338|0.97|
|STRK_USDT|0.046480|-1.75|-29.73|-2.34|8597717|2.15|
|PENGU_USDT|0.007451|-1.31|-0.02|-1.90|5403797|1.34|
|SUI_USDT|0.918400|-1.00|-6.45|-1.59|65403648|1.09|
|SEI_USDT|0.052850|-0.84|-14.77|-1.43|9593620|1.89|
|APT_USDT|0.702300|-0.60|-11.93|-1.19|5806758|1.42|
|LINK_USDT|11.397000|-0.54|-4.27|-1.13|48850843|0.88|
|ARB_USDT|0.166370|-0.48|-9.54|-1.07|14826586|0.60|
|TIA_USDT|0.531500|-0.46|-19.22|-1.05|20428715|3.76|
|AKE_USDT|0.028963|-0.43|0.00|-1.02|6155799|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028963|0.028767|0.028963|0.49|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.702300|0.697500|0.702300|0.34|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166370|0.164850|0.166370|0.81|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.078360|0.077430|0.078410|1.02|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.675900|1.590000|1.676800|1.20|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.029500|1.017100|1.029500|1.01|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037100|0.036630|0.037100|0.52|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.397000|11.339000|11.397000|0.29|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.050530|0.051130|0.050530|2.74|Y|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007451|0.007419|0.007451|0.27|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052850|0.052650|0.052850|0.50|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046480|0.045690|0.046480|1.28|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.918400|0.911400|0.918400|1.35|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.531500|0.525200|0.531500|1.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.030208, depth_time=2026-10-25T08:00:41+00:00, book20_bid_proxy_usdt=11105, book20_ask_proxy_usdt=12306, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.43%, turnover=6155799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.708900, depth_time=2026-10-25T08:00:27+00:00, book20_bid_proxy_usdt=112760, book20_ask_proxy_usdt=137398, funding_indicative=-0.000025, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=5806758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.166840, depth_time=2026-10-25T08:00:35+00:00, book20_bid_proxy_usdt=105162, book20_ask_proxy_usdt=71666, funding_indicative=0.000025, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=14826586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.085440, depth_time=2026-10-25T08:00:13+00:00, book20_bid_proxy_usdt=18693, book20_ask_proxy_usdt=26077, funding_indicative=-0.010450, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.76%, turnover=5102986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=1.915400, depth_time=2026-10-25T08:00:16+00:00, book20_bid_proxy_usdt=6835, book20_ask_proxy_usdt=7512, funding_indicative=-0.007715, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=11433263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=1.038100, depth_time=2026-10-25T08:00:18+00:00, book20_bid_proxy_usdt=312591, book20_ask_proxy_usdt=305597, funding_indicative=-0.000027, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=11724338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.044650, depth_time=2026-10-25T08:00:08+00:00, book20_bid_proxy_usdt=52977, book20_ask_proxy_usdt=50043, funding_indicative=-0.002179, next_funding_utc=2026-10-25T09:00:00+00:00, funding_cycle_h=1, 24h_change=-34.82%, turnover=33515319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=11.452000, depth_time=2026-10-25T08:00:32+00:00, book20_bid_proxy_usdt=497898, book20_ask_proxy_usdt=474689, funding_indicative=0.000054, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.54%, turnover=48850843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.057510, depth_time=2026-10-25T08:00:11+00:00, book20_bid_proxy_usdt=66413, book20_ask_proxy_usdt=53962, funding_indicative=-0.001050, next_funding_utc=2026-10-25T09:00:00+00:00, funding_cycle_h=1, 24h_change=-25.76%, turnover=13900159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.007508, depth_time=2026-10-25T08:00:23+00:00, book20_bid_proxy_usdt=193509, book20_ask_proxy_usdt=313350, funding_indicative=-0.000042, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=5403797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.053330, depth_time=2026-10-25T08:00:28+00:00, book20_bid_proxy_usdt=229815, book20_ask_proxy_usdt=410942, funding_indicative=-0.000068, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=9593620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.046590, depth_time=2026-10-25T08:00:19+00:00, book20_bid_proxy_usdt=828473, book20_ask_proxy_usdt=626165, funding_indicative=0.000039, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=8597717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.922400, depth_time=2026-10-25T08:00:25+00:00, book20_bid_proxy_usdt=1117692, book20_ask_proxy_usdt=948477, funding_indicative=0.000039, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=65403648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T08:00:01+00:00, last15m_closed_end=2026-10-25T08:00+00:00, prior8high=0.532300, depth_time=2026-10-25T08:00:39+00:00, book20_bid_proxy_usdt=227005, book20_ask_proxy_usdt=273861, funding_indicative=0.000008, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.46%, turnover=20428715. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
