# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T10:30:40Z**
- feed_generated_utc: 2026-11-10T10:30:41+00:00
- source_sha256: `d57d7b0915fab5d7ee75ce5fba4edfeabc1d2c1ccb1e008551b7d92239bfde67`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T10:30+00:00, close=74300.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T10:00+00:00, close=74485, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002462|-49.72|-55.25|-48.14|14443277|4.06|
|JCT_USDT|0.005523|-45.48|27.93|-43.90|24845339|3.63|
|ON_USDT|0.133700|-10.62|-21.12|-9.04|5716517|7.49|
|XMR_USDT|545.420000|-9.67|-9.89|-8.09|5714926|0.18|
|ARB_USDT|0.166250|-9.66|4.34|-8.08|37206172|0.60|
|AVAX_USDT|8.344000|-7.18|-1.84|-5.60|50649130|1.20|
|ZEC_USDT|1145.050000|-6.58|-8.69|-5.00|2310428011|0.09|
|AAVE_USDT|125.020000|-6.24|-4.24|-4.66|12047985|0.80|
|QNT_USDT|187.720000|-6.15|-7.27|-4.57|33350258|1.60|
|DOT_USDT|0.848100|-4.80|-9.20|-3.22|8030463|1.18|
|PUMPFUN_USDT|0.003530|-4.12|-13.98|-2.54|7412175|2.83|
|DASH_USDT|45.840000|-3.73|-2.88|-2.15|10213711|2.18|
|SUI_USDT|0.835700|-3.64|-5.54|-2.06|35008270|1.20|
|SOL_USDT|85.210000|-3.04|-8.87|-1.46|642828159|1.17|
|ENA_USDT|0.152540|-3.00|-12.85|-1.42|23015165|0.66|
|XRP_USDT|1.081800|-2.88|-13.34|-1.30|274040361|0.92|
|LINK_USDT|10.482000|-2.80|-6.69|-1.22|106606067|0.95|
|HYPE_USDT|74.189000|-2.78|-13.44|-1.20|46625086|0.14|
|WLD_USDT|0.317100|-2.70|-16.81|-1.12|27236533|6.31|
|HBAR_USDT|0.066630|-2.68|-5.44|-1.10|9635728|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.020000|124.350000|125.020000|0.76|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002462|0.002406|0.002462|1.05|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166250|0.165590|0.166250|0.85|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|8.344000|8.341000|8.344000|2.19|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.840000|45.390000|45.840000|1.80|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.848100|0.846200|0.848100|2.49|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.152540|0.151780|0.152540|1.38|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005523|0.005450|0.005522|2.11|N|Y/Y|Y/N|Y|N|
|ON_USDT|0.133700|0.122700|0.133700|0.79|N|Y/Y|N/Y|Y|N|
|PUMPFUN_USDT|0.003530|0.003516|0.003530|6.03|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.720000|186.660000|187.720000|2.36|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.210000|84.880000|85.210000|2.70|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.835700|0.836100|0.835800|2.37|Y|Y/N|Y/Y|Y|N|
|XMR_USDT|545.420000|542.500000|545.420000|3.73|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1145.050000|1134.630000|1145.000000|1.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=126.340000, depth_time=2026-11-10T10:30:22+00:00, book20_bid_proxy_usdt=429100, book20_ask_proxy_usdt=320907, funding_indicative=0.000049, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.24%, turnover=12047985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.002533, depth_time=2026-11-10T10:30:06+00:00, book20_bid_proxy_usdt=91168, book20_ask_proxy_usdt=79364, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.72%, turnover=14443277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.169380, depth_time=2026-11-10T10:30:13+00:00, book20_bid_proxy_usdt=90079, book20_ask_proxy_usdt=65016, funding_indicative=-0.000168, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.66%, turnover=37206172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=8.494000, depth_time=2026-11-10T10:30:18+00:00, book20_bid_proxy_usdt=688593, book20_ask_proxy_usdt=864982, funding_indicative=0.000012, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.18%, turnover=50649130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=46.340000, depth_time=2026-11-10T10:30:29+00:00, book20_bid_proxy_usdt=328961, book20_ask_proxy_usdt=565053, funding_indicative=-0.000020, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=10213711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.858200, depth_time=2026-11-10T10:30:26+00:00, book20_bid_proxy_usdt=648926, book20_ask_proxy_usdt=574762, funding_indicative=-0.000051, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.80%, turnover=8030463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.154000, depth_time=2026-11-10T10:30:38+00:00, book20_bid_proxy_usdt=147847, book20_ask_proxy_usdt=168540, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=23015165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.006657, depth_time=2026-11-10T10:30:09+00:00, book20_bid_proxy_usdt=45544, book20_ask_proxy_usdt=33288, funding_indicative=0.000282, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-45.48%, turnover=24845339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.194600, depth_time=2026-11-10T10:30:10+00:00, book20_bid_proxy_usdt=74604, book20_ask_proxy_usdt=50577, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.62%, turnover=5716517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.003569, depth_time=2026-11-10T10:30:27+00:00, book20_bid_proxy_usdt=2751762, book20_ask_proxy_usdt=3278680, funding_indicative=-0.000001, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=7412175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=190.680000, depth_time=2026-11-10T10:30:23+00:00, book20_bid_proxy_usdt=50752, book20_ask_proxy_usdt=68481, funding_indicative=-0.000133, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.15%, turnover=33350258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=85.950000, depth_time=2026-11-10T10:30:37+00:00, book20_bid_proxy_usdt=14634733, book20_ask_proxy_usdt=17043303, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=642828159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=0.848100, depth_time=2026-11-10T10:30:34+00:00, book20_bid_proxy_usdt=799969, book20_ask_proxy_usdt=2108234, funding_indicative=0.000058, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=35008270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=565.400000, depth_time=2026-11-10T10:30:13+00:00, book20_bid_proxy_usdt=8839, book20_ask_proxy_usdt=26207, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.67%, turnover=5714926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T10:30:01+00:00, last15m_closed_end=2026-11-10T10:30+00:00, prior8high=1148.610000, depth_time=2026-11-10T10:30:21+00:00, book20_bid_proxy_usdt=222175, book20_ask_proxy_usdt=239978, funding_indicative=0.000073, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.58%, turnover=2310428011. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
