# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T17:30:44Z**
- feed_generated_utc: 2026-10-12T17:30:47+00:00
- source_sha256: `14c094f8b93ddbddf64ecf071ba955afcbbfa2f2a2ff553681dd30d3ab15744e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T17:30+00:00, close=82413.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T17:00+00:00, close=82473.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CKB_USDT|0.001578|-4.63|19.09|-4.32|5694394|2.53|
|TIA_USDT|0.545800|-4.19|16.97|-3.88|41759196|1.83|
|CRV_USDT|0.348700|-3.72|-6.68|-3.41|5427828|2.87|
|INJ_USDT|7.594000|-3.40|1.33|-3.09|35418022|1.32|
|EIGEN_USDT|0.253300|-3.17|-2.42|-2.86|6718244|3.94|
|ZEC_USDT|1233.970000|-2.44|-4.70|-2.13|1457007895|0.08|
|ZRO_USDT|2.206600|-2.40|7.87|-2.09|27356523|1.36|
|APT_USDT|0.823100|-2.29|0.99|-1.98|24778786|1.22|
|ARB_USDT|0.184300|-2.21|-9.10|-1.90|37133307|0.54|
|AVAX_USDT|10.459000|-2.07|-3.60|-1.76|63856209|0.96|
|JUP_USDT|0.335900|-2.04|-0.59|-1.73|8527116|2.98|
|DOT_USDT|1.213500|-1.85|1.64|-1.54|23105809|0.82|
|BAT_USDT|0.147600|-1.80|41.21|-1.49|5294620|0.68|
|MAGIC_USDT|0.119800|-1.77|93.25|-1.46|12344456|1.67|
|SUI_USDT|1.068900|-1.69|-9.82|-1.38|95012153|0.94|
|PUMPFUN_USDT|0.005219|-1.69|-17.61|-1.38|25421645|1.92|
|OP_USDT|0.133070|-1.65|-0.50|-1.34|15856239|0.75|
|HBAR_USDT|0.089000|-1.65|-11.61|-1.34|14494469|1.12|
|NEAR_USDT|5.459000|-1.62|8.70|-1.31|270391723|1.83|
|VIRTUAL_USDT|0.708200|-1.51|-15.45|-1.20|5715775|2.82|
|TAO_USDT|281.970000|-1.50|-5.89|-1.19|105919771|1.06|
|ETHFI_USDT|0.690500|-1.32|-8.51|-1.01|5369752|1.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.823100|0.824600|0.822900|1.64|Y|Y/Y|Y/N|Y|N|
|ARB_USDT|0.184300|0.184160|0.184300|1.90|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.459000|10.435000|10.456000|0.47|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.147600|0.143660|0.147600|0.35|N|Y/Y|N/N|Y|N|
|CKB_USDT|0.001578|0.001574|0.001578|0.46|N|Y/Y|N/N|Y|N|
|CRV_USDT|0.348700|0.346300|0.348600|0.19|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.213500|1.215400|1.213500|0.75|N|Y/Y|N/N|Y|N|
|EIGEN_USDT|0.253300|0.254000|0.253300|0.15|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.594000|7.506000|7.593000|1.12|N|Y/Y|N/N|Y|N|
|JUP_USDT|0.335900|0.335900|0.335900|0.60|N|Y/Y|Y/Y|Y|N|
|MAGIC_USDT|0.119800|0.115400|0.119800|0.38|N|Y/Y|N/N|Y|N|
|SUI_USDT|1.068900|1.064000|1.068900|0.42|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.545800|0.548200|0.545800|1.18|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1233.970000|1234.740000|1233.320000|0.97|N|Y/Y|N/N|Y|N|
|ZRO_USDT|2.206600|2.190300|2.205700|0.35|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.848400, depth_time=2026-10-12T17:30:25+00:00, book20_bid_proxy_usdt=170575, book20_ask_proxy_usdt=135052, funding_indicative=-0.000134, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=24778786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.189800, depth_time=2026-10-12T17:30:28+00:00, book20_bid_proxy_usdt=44203, book20_ask_proxy_usdt=355630, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=37133307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=10.733000, depth_time=2026-10-12T17:30:30+00:00, book20_bid_proxy_usdt=544640, book20_ask_proxy_usdt=1819069, funding_indicative=-0.000015, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=63856209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-12T17:30:01+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.152640, depth_time=2026-10-12T17:30:35+00:00, book20_bid_proxy_usdt=17305, book20_ask_proxy_usdt=16654, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=5294620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CKB_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.001674, depth_time=2026-10-12T17:30:07+00:00, book20_bid_proxy_usdt=12333, book20_ask_proxy_usdt=30689, funding_indicative=-0.000684, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.63%, turnover=5694394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-12T17:30:01+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.363800, depth_time=2026-10-12T17:30:09+00:00, book20_bid_proxy_usdt=545002, book20_ask_proxy_usdt=549849, funding_indicative=0.000013, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=5427828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-12T17:30:01+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=1.251200, depth_time=2026-10-12T17:30:35+00:00, book20_bid_proxy_usdt=190859, book20_ask_proxy_usdt=311692, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=23105809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-12T17:30:01+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.264100, depth_time=2026-10-12T17:30:17+00:00, book20_bid_proxy_usdt=588528, book20_ask_proxy_usdt=685611, funding_indicative=0.000021, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=6718244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=7.887000, depth_time=2026-10-12T17:30:15+00:00, book20_bid_proxy_usdt=164705, book20_ask_proxy_usdt=208744, funding_indicative=0.000225, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.40%, turnover=35418022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-12T17:30:01+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.345600, depth_time=2026-10-12T17:30:30+00:00, book20_bid_proxy_usdt=534014, book20_ask_proxy_usdt=511652, funding_indicative=-0.000096, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=8527116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.123510, depth_time=2026-10-12T17:30:41+00:00, book20_bid_proxy_usdt=169986, book20_ask_proxy_usdt=183324, funding_indicative=-0.000185, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=12344456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=1.092900, depth_time=2026-10-12T17:30:43+00:00, book20_bid_proxy_usdt=778243, book20_ask_proxy_usdt=483081, funding_indicative=0.000034, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=95012153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=0.580000, depth_time=2026-10-12T17:30:11+00:00, book20_bid_proxy_usdt=156156, book20_ask_proxy_usdt=161740, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=41759196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=1273.660000, depth_time=2026-10-12T17:30:20+00:00, book20_bid_proxy_usdt=1069946, book20_ask_proxy_usdt=189283, funding_indicative=0.000051, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=1457007895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-12T17:30:00+00:00, last15m_closed_end=2026-10-12T17:30+00:00, prior8high=2.326400, depth_time=2026-10-12T17:30:23+00:00, book20_bid_proxy_usdt=54238, book20_ask_proxy_usdt=46298, funding_indicative=0.000043, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=27356523. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
