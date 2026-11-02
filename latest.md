# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T22:45:43Z**
- feed_generated_utc: 2026-11-02T22:45:45+00:00
- source_sha256: `7df08940365692fcbe8f9a740e54ef899cbdb7eaa2def7f57a60c79e08459574`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T22:45+00:00, close=76809, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T22:00+00:00, close=76830.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.115600|-12.88|-53.53|-12.02|6588674|8.64|
|ZEC_USDT|1149.250000|-8.36|-7.89|-7.50|1902130242|0.17|
|XPL_USDT|0.066800|-3.99|-10.08|-3.13|10759161|1.50|
|QNT_USDT|194.510000|-3.92|-7.49|-3.06|50465785|0.51|
|NEAR_USDT|3.874000|-3.39|-15.28|-2.53|84271026|2.58|
|PUMPFUN_USDT|0.003965|-3.38|-8.38|-2.52|9443594|2.52|
|AAVE_USDT|126.750000|-2.91|-7.29|-2.05|23676316|0.79|
|ZRO_USDT|1.717500|-2.86|0.60|-2.00|6258004|0.58|
|XLM_USDT|0.163190|-2.63|-3.77|-1.77|33856100|0.61|
|ENA_USDT|0.170630|-2.51|-18.89|-1.65|76145065|0.59|
|ARB_USDT|0.155570|-2.35|-8.48|-1.49|13659463|2.57|
|TIA_USDT|0.446200|-2.34|-16.70|-1.48|12476009|2.24|
|TRUMPOFFICIAL_USDT|1.602000|-2.07|-5.15|-1.21|12612841|6.24|
|DASH_USDT|46.270000|-1.97|-11.39|-1.11|10357045|2.16|
|HYPE_USDT|84.028000|-1.96|7.11|-1.10|106957718|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.750000|126.730000|126.750000|1.08|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155570|0.155130|0.155620|0.67|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.270000|45.690000|46.270000|0.76|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170630|0.169020|0.170630|0.83|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|84.028000|83.150000|84.028000|0.34|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.874000|3.856000|3.874000|0.27|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003965|0.003913|0.003965|0.10|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.510000|192.940000|194.510000|0.88|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.446200|0.441500|0.446200|0.45|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.602000|1.576000|1.602000|0.59|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.115600|0.112100|0.115400|0.73|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163190|0.163240|0.163190|0.74|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066800|0.066130|0.066790|0.98|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1149.250000|1135.710000|1149.240000|0.76|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.717500|1.692200|1.717500|3.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=128.160000, depth_time=2026-11-02T22:45:22+00:00, book20_bid_proxy_usdt=421291, book20_ask_proxy_usdt=469029, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=23676316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.157480, depth_time=2026-11-02T22:45:31+00:00, book20_bid_proxy_usdt=101446, book20_ask_proxy_usdt=75081, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=13659463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=46.500000, depth_time=2026-11-02T22:45:39+00:00, book20_bid_proxy_usdt=767669, book20_ask_proxy_usdt=536363, funding_indicative=0.000061, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=10357045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.172390, depth_time=2026-11-02T22:45:30+00:00, book20_bid_proxy_usdt=191766, book20_ask_proxy_usdt=384201, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=76145065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=84.799000, depth_time=2026-11-02T22:45:41+00:00, book20_bid_proxy_usdt=39474, book20_ask_proxy_usdt=74620, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=106957718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=3.921000, depth_time=2026-11-02T22:45:17+00:00, book20_bid_proxy_usdt=3711677, book20_ask_proxy_usdt=3612495, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=84271026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.003996, depth_time=2026-11-02T22:45:19+00:00, book20_bid_proxy_usdt=2480265, book20_ask_proxy_usdt=2664643, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=9443594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=197.490000, depth_time=2026-11-02T22:45:15+00:00, book20_bid_proxy_usdt=111039, book20_ask_proxy_usdt=58358, funding_indicative=0.000094, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=50465785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.452100, depth_time=2026-11-02T22:45:33+00:00, book20_bid_proxy_usdt=311696, book20_ask_proxy_usdt=288878, funding_indicative=0.000045, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=12476009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=1.612000, depth_time=2026-11-02T22:45:37+00:00, book20_bid_proxy_usdt=2080974, book20_ask_proxy_usdt=2180269, funding_indicative=0.000002, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=12612841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.121600, depth_time=2026-11-02T22:45:08+00:00, book20_bid_proxy_usdt=162199, book20_ask_proxy_usdt=136056, funding_indicative=-0.000058, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.88%, turnover=6588674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.165190, depth_time=2026-11-02T22:45:27+00:00, book20_bid_proxy_usdt=186282, book20_ask_proxy_usdt=269628, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=33856100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=0.067370, depth_time=2026-11-02T22:45:13+00:00, book20_bid_proxy_usdt=377261, book20_ask_proxy_usdt=513367, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=10759161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=1162.310000, depth_time=2026-11-02T22:45:10+00:00, book20_bid_proxy_usdt=267110, book20_ask_proxy_usdt=552567, funding_indicative=0.000042, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.36%, turnover=1902130242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T22:45:02+00:00, last15m_closed_end=2026-11-02T22:45+00:00, prior8high=1.727400, depth_time=2026-11-02T22:45:23+00:00, book20_bid_proxy_usdt=77550, book20_ask_proxy_usdt=76684, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=6258004. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
