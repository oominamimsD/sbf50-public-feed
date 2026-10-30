# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T15:15:39Z**
- feed_generated_utc: 2026-10-30T15:15:42+00:00
- source_sha256: `dbc2975feca6ac91bdf4120b0dc097c98f0c4a177844d1aac5e4703527f5cbdc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T15:15+00:00, close=77714.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T15:00+00:00, close=77214.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.216800|-25.71|-32.02|-20.80|9939584|3.29|
|TIA_USDT|0.459800|-16.27|-19.10|-11.36|19450906|2.18|
|CRV_USDT|0.289800|-13.75|-21.09|-8.84|9077240|3.45|
|INJ_USDT|7.178000|-11.73|-9.50|-6.82|32342233|1.39|
|LDO_USDT|0.336900|-10.96|-11.92|-6.05|6480687|2.97|
|ETHFI_USDT|0.609200|-10.34|-8.01|-5.43|5917096|1.64|
|TAO_USDT|234.660000|-9.32|-8.92|-4.41|85459518|1.28|
|PUMPFUN_USDT|0.004105|-9.28|-12.26|-4.37|27630236|2.44|
|SEI_USDT|0.048560|-9.13|-16.37|-4.22|7318357|2.06|
|ZEC_USDT|1251.830000|-7.77|1.42|-2.86|2111231299|0.08|
|SOL_USDT|95.260000|-7.19|-8.91|-2.28|886362513|1.05|
|AVAX_USDT|8.373000|-7.00|-8.65|-2.09|38210316|1.19|
|BNB_USDT|705.100000|-6.24|-3.58|-1.33|56435517|1.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|8.373000|8.183000|8.374000|2.48|N|Y/Y|Y/Y|Y|N|
|BNB_USDT|705.100000|694.700000|705.100000|2.58|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.216800|1.216100|1.216900|1.31|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.289800|0.280200|0.289600|2.41|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.609200|0.592200|0.609200|1.90|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.178000|7.034000|7.178000|0.76|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.336900|0.327900|0.336900|1.89|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004105|0.003974|0.004105|1.33|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048560|0.047390|0.048560|1.97|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|95.260000|93.890000|95.260000|2.83|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|234.660000|229.680000|234.690000|3.08|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.459800|0.447400|0.459800|2.20|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1251.830000|1215.450000|1251.830000|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=8.341000, depth_time=2026-10-30T15:15:36+00:00, book20_bid_proxy_usdt=1661631, book20_ask_proxy_usdt=2386045, funding_indicative=0.000093, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.00%, turnover=38210316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BNB_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=702.000000, depth_time=2026-10-30T15:15:39+00:00, book20_bid_proxy_usdt=174294, book20_ask_proxy_usdt=2683941, funding_indicative=0.000000, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.24%, turnover=56435517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=1.297300, depth_time=2026-10-30T15:15:08+00:00, book20_bid_proxy_usdt=18612, book20_ask_proxy_usdt=12674, funding_indicative=-0.000060, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.71%, turnover=9939584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=0.286800, depth_time=2026-10-30T15:15:12+00:00, book20_bid_proxy_usdt=511053, book20_ask_proxy_usdt=601101, funding_indicative=-0.000126, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-13.75%, turnover=9077240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=0.606000, depth_time=2026-10-30T15:15:21+00:00, book20_bid_proxy_usdt=126259, book20_ask_proxy_usdt=219258, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.34%, turnover=5917096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=7.246000, depth_time=2026-10-30T15:15:15+00:00, book20_bid_proxy_usdt=258161, book20_ask_proxy_usdt=321371, funding_indicative=0.000107, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.73%, turnover=32342233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=0.334100, depth_time=2026-10-30T15:15:18+00:00, book20_bid_proxy_usdt=362117, book20_ask_proxy_usdt=403192, funding_indicative=0.000082, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.96%, turnover=6480687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=0.004082, depth_time=2026-10-30T15:15:26+00:00, book20_bid_proxy_usdt=1124579, book20_ask_proxy_usdt=1531248, funding_indicative=-0.000007, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.28%, turnover=27630236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=0.048690, depth_time=2026-10-30T15:15:28+00:00, book20_bid_proxy_usdt=183170, book20_ask_proxy_usdt=171405, funding_indicative=0.000038, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.13%, turnover=7318357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=96.870000, depth_time=2026-10-30T15:15:33+00:00, book20_bid_proxy_usdt=13009888, book20_ask_proxy_usdt=18967649, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.19%, turnover=886362513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=233.810000, depth_time=2026-10-30T15:15:23+00:00, book20_bid_proxy_usdt=66077, book20_ask_proxy_usdt=92124, funding_indicative=0.000048, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.32%, turnover=85459518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=0.460300, depth_time=2026-10-30T15:15:11+00:00, book20_bid_proxy_usdt=212107, book20_ask_proxy_usdt=303362, funding_indicative=-0.000056, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.27%, turnover=19450906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-30T15:14:59+00:00, last15m_closed_end=2026-10-30T15:15+00:00, prior8high=1248.160000, depth_time=2026-10-30T15:15:31+00:00, book20_bid_proxy_usdt=365098, book20_ask_proxy_usdt=222608, funding_indicative=0.000075, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.77%, turnover=2111231299. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
