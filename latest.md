# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T08:30:44Z**
- feed_generated_utc: 2026-11-05T08:30:45+00:00
- source_sha256: `1e5e76413dce19199a6fabf2e16e1335fcc83c77f2d8c53fb85d446c656d43e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T08:30+00:00, close=80566.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T08:00+00:00, close=80362.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T08:00+00:00, close=80362.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.018318|-21.94|111.59|-22.28|5069078|4.37|
|TRUMPOFFICIAL_USDT|1.259000|-11.58|-26.33|-11.92|26595854|7.94|
|CLANKER_USDT|17.140000|-7.89|28.29|-8.23|19674868|5.85|
|BTW_USDT|1.030400|-6.24|-40.71|-6.58|5378750|0.97|
|FARTCOIN_USDT|0.125180|-3.78|-4.43|-4.12|17014844|0.80|
|PEPE_USDT|0.000005|-3.44|2.97|-3.78|128108826|4.21|
|ZRO_USDT|1.807900|-3.04|5.60|-3.38|7775241|0.55|
|WLD_USDT|0.380700|-2.90|-12.03|-3.24|63210450|2.63|
|HYPE_USDT|83.534000|-2.76|4.60|-3.10|80050111|0.12|
|PENGU_USDT|0.007243|-2.67|-6.61|-3.01|6892072|2.76|
|NEAR_USDT|4.036000|-2.60|-12.81|-2.94|75302238|2.48|
|SEI_USDT|0.048900|-2.60|-7.47|-2.94|6062014|2.04|
|ENA_USDT|0.180990|-2.57|-7.74|-2.91|93194921|0.55|
|ARB_USDT|0.163990|-2.54|-2.21|-2.88|21768309|0.61|
|OP_USDT|0.111590|-2.28|0.45|-2.62|8696396|0.90|
|FET_USDT|0.159700|-2.20|-12.10|-2.54|7137234|6.27|
|AVAX_USDT|8.784000|-1.82|-1.15|-2.16|23026289|1.14|
|DOT_USDT|0.951900|-1.76|-5.15|-2.10|11908688|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.163990|0.162760|0.164050|3.02|N|N/N|N/N|N|N|
|BTW_USDT|1.030400|1.023900|1.030400|1.45|N|N/N|Y/Y|N|N|
|CLANKER_USDT|17.140000|16.610000|17.140000|0.42|N|Y/Y|N/N|N|N|
|ENA_USDT|0.180990|0.178620|0.181100|0.83|N|Y/Y|N/N|N|N|
|FARTCOIN_USDT|0.125180|0.123350|0.125180|1.57|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.534000|83.126000|83.534000|1.15|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.018318|0.018518|0.018319|1.30|Y|Y/Y|Y/N|N|N|
|NEAR_USDT|4.036000|4.005000|4.039000|1.35|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.111590|0.110280|0.111590|2.26|N|N/Y|N/Y|N|N|
|PENGU_USDT|0.007243|0.007163|0.007248|1.00|N|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.61|N|Y/Y|N/N|N|N|
|SEI_USDT|0.048900|0.048330|0.048920|0.66|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.259000|1.246000|1.259000|0.72|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.380700|0.373100|0.380900|3.14|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.807900|1.794700|1.807900|0.75|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.164630, depth_time=2026-11-05T08:30:39+00:00, book20_bid_proxy_usdt=802946, book20_ask_proxy_usdt=108179, funding_indicative=-0.000088, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=21768309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=1.060000, depth_time=2026-11-05T08:30:14+00:00, book20_bid_proxy_usdt=13313, book20_ask_proxy_usdt=15714, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.24%, turnover=5378750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=17.930000, depth_time=2026-11-05T08:30:10+00:00, book20_bid_proxy_usdt=170453, book20_ask_proxy_usdt=159732, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.89%, turnover=19674868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.182040, depth_time=2026-11-05T08:30:38+00:00, book20_bid_proxy_usdt=155687, book20_ask_proxy_usdt=156372, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=93194921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.125310, depth_time=2026-11-05T08:30:15+00:00, book20_bid_proxy_usdt=272778, book20_ask_proxy_usdt=73942, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.78%, turnover=17014844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=83.600000, depth_time=2026-11-05T08:30:27+00:00, book20_bid_proxy_usdt=55476, book20_ask_proxy_usdt=138494, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=80050111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.019721, depth_time=2026-11-05T08:30:07+00:00, book20_bid_proxy_usdt=6425, book20_ask_proxy_usdt=6818, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.94%, turnover=5069078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=4.058000, depth_time=2026-11-05T08:30:32+00:00, book20_bid_proxy_usdt=4201156, book20_ask_proxy_usdt=4231668, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=75302238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.111500, depth_time=2026-11-05T08:30:43+00:00, book20_bid_proxy_usdt=87584, book20_ask_proxy_usdt=63673, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=8696396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T08:30:03+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.007255, depth_time=2026-11-05T08:30:30+00:00, book20_bid_proxy_usdt=211589, book20_ask_proxy_usdt=249679, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=6892072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.000005, depth_time=2026-11-05T08:30:19+00:00, book20_bid_proxy_usdt=86554, book20_ask_proxy_usdt=43339, funding_indicative=0.000058, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=128108826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T08:30:03+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.048840, depth_time=2026-11-05T08:30:33+00:00, book20_bid_proxy_usdt=226938, book20_ask_proxy_usdt=266836, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=6062014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=1.292000, depth_time=2026-11-05T08:30:10+00:00, book20_bid_proxy_usdt=1348737, book20_ask_proxy_usdt=1481410, funding_indicative=-0.000373, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.58%, turnover=26595854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=0.378700, depth_time=2026-11-05T08:30:23+00:00, book20_bid_proxy_usdt=2295576, book20_ask_proxy_usdt=1595150, funding_indicative=-0.000328, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=63210450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T08:30:02+00:00, last15m_closed_end=2026-11-05T08:30+00:00, prior8high=1.832500, depth_time=2026-11-05T08:30:19+00:00, book20_bid_proxy_usdt=65155, book20_ask_proxy_usdt=21301, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=7775241. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
