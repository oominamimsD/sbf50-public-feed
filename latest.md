# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T20:00:41Z**
- feed_generated_utc: 2026-11-10T20:00:43+00:00
- source_sha256: `b704e06997239e0f7e163049121ff8a2380aaf44a37e9050e5c6369abd7051cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.811600|-10.58|54.12|-10.93|8059057|1.10|
|DASH_USDT|42.980000|-7.66|-6.84|-8.01|13123171|2.33|
|ZEC_USDT|1033.140000|-5.50|-14.17|-5.85|2364943096|0.10|
|ENA_USDT|0.148740|-5.12|-13.61|-5.47|29321889|0.67|
|UNI_USDT|6.711000|-5.01|-8.73|-5.36|28839571|1.49|
|ONDO_USDT|0.362900|-4.52|-6.75|-4.87|14524235|2.75|
|PUMPFUN_USDT|0.003439|-3.48|-19.40|-3.83|9575333|2.91|
|VVV_USDT|19.158000|-3.32|-14.32|-3.67|5015410|0.52|
|DOT_USDT|0.836300|-3.03|-11.27|-3.38|8507783|1.20|
|TIA_USDT|0.422000|-2.85|-3.16|-3.20|9074944|2.37|
|FARTCOIN_USDT|0.115250|-2.35|-3.44|-2.70|5021191|0.87|
|BNB_USDT|675.440000|-2.05|-3.72|-2.40|7108167|0.15|
|ADA_USDT|0.173700|-2.03|-9.00|-2.38|22463130|5.75|
|AKE_USDT|0.002859|-1.88|-31.20|-2.23|16033248|3.50|
|JCT_USDT|0.005177|-1.85|23.91|-2.20|21790263|3.87|
|ANTHROPIC_USDT|1296.110000|-1.62|-22.57|-1.97|8038740|1.08|
|ARB_USDT|0.159210|-1.34|-0.41|-1.69|35364687|0.63|
|AAVE_USDT|123.540000|-1.16|-3.82|-1.51|10958850|0.81|
|XLM_USDT|0.144190|-1.12|-12.50|-1.47|23837213|0.69|
|QNT_USDT|181.050000|-1.11|-7.35|-1.46|45296526|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.173700|0.171300|0.173700|0.97|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002859|0.002782|0.002859|0.35|N|Y/Y|Y/Y|Y|N|
|BNB_USDT|675.440000|671.340000|675.440000|0.26|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.980000|42.790000|42.980000|0.46|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.836300|0.832800|0.836300|0.34|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.148740|0.146700|0.148740|0.40|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.115250|0.113710|0.115250|0.50|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005177|0.005014|0.005177|0.72|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.362900|0.358400|0.362900|0.17|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.811600|1.808000|1.811600|0.79|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003439|0.003366|0.003439|0.14|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.422000|0.418100|0.422000|0.53|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.711000|6.608000|6.711000|0.61|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.158000|18.330000|19.159000|0.62|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1033.140000|1020.790000|1033.130000|0.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.173600, depth_time=2026-11-10T20:00:36+00:00, book20_bid_proxy_usdt=10813665, book20_ask_proxy_usdt=9506922, funding_indicative=-0.000046, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=22463130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T19:59:59+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.002942, depth_time=2026-11-10T20:00:38+00:00, book20_bid_proxy_usdt=27852, book20_ask_proxy_usdt=40796, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=16033248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BNB_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=676.550000, depth_time=2026-11-10T20:00:32+00:00, book20_bid_proxy_usdt=166552, book20_ask_proxy_usdt=228143, funding_indicative=0.000000, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=7108167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=43.750000, depth_time=2026-11-10T20:00:09+00:00, book20_bid_proxy_usdt=960554, book20_ask_proxy_usdt=534696, funding_indicative=-0.000159, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.66%, turnover=13123171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.845000, depth_time=2026-11-10T20:00:21+00:00, book20_bid_proxy_usdt=1006689, book20_ask_proxy_usdt=654624, funding_indicative=-0.000061, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=8507783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.150710, depth_time=2026-11-10T20:00:14+00:00, book20_bid_proxy_usdt=168557, book20_ask_proxy_usdt=215052, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.12%, turnover=29321889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.116180, depth_time=2026-11-10T20:00:29+00:00, book20_bid_proxy_usdt=41006, book20_ask_proxy_usdt=26022, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=5021191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T19:59:59+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.005277, depth_time=2026-11-10T20:00:40+00:00, book20_bid_proxy_usdt=47804, book20_ask_proxy_usdt=34356, funding_indicative=0.000091, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=21790263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.364800, depth_time=2026-11-10T20:00:19+00:00, book20_bid_proxy_usdt=2344507, book20_ask_proxy_usdt=3324390, funding_indicative=-0.000019, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=14524235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T19:59:59+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=1.873800, depth_time=2026-11-10T20:00:07+00:00, book20_bid_proxy_usdt=23629, book20_ask_proxy_usdt=29643, funding_indicative=0.000165, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.58%, turnover=8059057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.003476, depth_time=2026-11-10T20:00:22+00:00, book20_bid_proxy_usdt=3180003, book20_ask_proxy_usdt=2708598, funding_indicative=0.000011, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=9575333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=0.426100, depth_time=2026-11-10T20:00:28+00:00, book20_bid_proxy_usdt=525358, book20_ask_proxy_usdt=438994, funding_indicative=0.000034, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=9074944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=6.745000, depth_time=2026-11-10T20:00:11+00:00, book20_bid_proxy_usdt=2722416, book20_ask_proxy_usdt=2686078, funding_indicative=-0.000014, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.01%, turnover=28839571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-10T20:00:00+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=19.408000, depth_time=2026-11-10T20:00:24+00:00, book20_bid_proxy_usdt=43129, book20_ask_proxy_usdt=24524, funding_indicative=0.000021, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.32%, turnover=5015410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T19:59:59+00:00, last15m_closed_end=2026-11-10T20:00+00:00, prior8high=1045.180000, depth_time=2026-11-10T20:00:12+00:00, book20_bid_proxy_usdt=149100, book20_ask_proxy_usdt=102248, funding_indicative=-0.000004, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.50%, turnover=2364943096. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
