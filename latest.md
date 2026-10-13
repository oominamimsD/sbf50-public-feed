# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T09:30:42Z**
- feed_generated_utc: 2026-10-13T09:30:46+00:00
- source_sha256: `d0889d6cd0fb3d028a4952c94fd8d7cd3cbdf0289c8266d9e2d673ad7a6d9871`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 23; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T09:30+00:00, close=83405.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T09:00+00:00, close=83555.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.225600|-22.07|5.91|-22.94|9424963|4.43|
|W_USDT|0.019111|-20.56|35.12|-21.43|28353934|8.37|
|ZRO_USDT|2.076500|-8.16|1.51|-9.03|22545379|1.93|
|NEAR_USDT|5.118000|-7.76|1.91|-8.63|268846697|1.95|
|LIT_USDT|3.368900|-7.06|-11.39|-7.93|10157451|0.30|
|RLC_USDT|0.933900|-5.53|70.41|-6.40|6841191|3.21|
|ONDO_USDT|0.471300|-5.38|-3.58|-6.25|66155487|2.12|
|PUMPFUN_USDT|0.005032|-5.21|-20.56|-6.08|32154140|1.99|
|SEI_USDT|0.063490|-4.33|-11.70|-5.20|9204766|1.57|
|STRK_USDT|0.087110|-3.92|67.16|-4.79|61063202|3.44|
|HBAR_USDT|0.087050|-3.81|-13.55|-4.68|22842196|1.15|
|JUP_USDT|0.330100|-3.73|-2.30|-4.60|8705770|3.03|
|ICP_USDT|3.173000|-3.70|-8.45|-4.57|17380436|3.15|
|USELESS_USDT|0.175650|-3.27|-22.53|-4.14|6211555|2.85|
|ADA_USDT|0.235000|-3.05|-10.95|-3.92|65845590|4.25|
|SAND_USDT|0.060200|-3.04|-10.81|-3.91|7997909|1.66|
|AAVE_USDT|158.340000|-3.01|-13.39|-3.88|27120187|0.63|
|FET_USDT|0.215000|-2.93|-13.75|-3.80|21278084|4.65|
|QNT_USDT|221.800000|-2.88|-13.61|-3.75|76510282|0.45|
|PONS_USDT|0.286200|-2.88|-25.37|-3.75|6281243|3.50|
|HYPE_USDT|82.506000|-2.21|-10.94|-3.08|82883860|0.12|
|LTC_USDT|61.590000|-2.17|-11.96|-3.04|22598235|3.25|
|S_USDT|0.057100|-0.50|32.94|-1.37|6659177|5.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.235000|0.235300|0.235100|0.64|N|Y/Y|Y/Y|N|N|
|DOS_USDT|0.225600|0.221400|0.225600|0.24|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.087050|0.087230|0.087060|2.10|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|3.173000|3.165000|3.173000|0.94|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.330100|0.329900|0.330200|2.33|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.368900|3.349100|3.368900|1.12|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.118000|5.109000|5.118000|1.27|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.471300|0.472300|0.471200|1.50|Y|Y/Y|Y/Y|N|Y|
|PUMPFUN_USDT|0.005032|0.005012|0.005030|0.36|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.933900|0.917000|0.933900|1.60|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.063490|0.063530|0.063490|1.89|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.087110|0.083010|0.087110|0.99|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.175650|0.175510|0.175560|0.48|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019111|0.018976|0.019106|0.66|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.076500|2.074200|2.076500|1.04|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.239700, depth_time=2026-10-13T09:30:41+00:00, book20_bid_proxy_usdt=6531239, book20_ask_proxy_usdt=6163063, funding_indicative=0.000000, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=65845590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.234500, depth_time=2026-10-13T09:30:08+00:00, book20_bid_proxy_usdt=110911, book20_ask_proxy_usdt=82510, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.07%, turnover=9424963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.088760, depth_time=2026-10-13T09:30:31+00:00, book20_bid_proxy_usdt=445855, book20_ask_proxy_usdt=806305, funding_indicative=-0.000023, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=22842196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=3.230000, depth_time=2026-10-13T09:30:36+00:00, book20_bid_proxy_usdt=720917, book20_ask_proxy_usdt=759696, funding_indicative=-0.000023, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=17380436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T09:30:03+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.337700, depth_time=2026-10-13T09:30:34+00:00, book20_bid_proxy_usdt=529077, book20_ask_proxy_usdt=706853, funding_indicative=-0.000063, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=8705770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T09:30:03+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=3.456200, depth_time=2026-10-13T09:30:18+00:00, book20_bid_proxy_usdt=29223, book20_ask_proxy_usdt=25430, funding_indicative=0.000011, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.06%, turnover=10157451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=5.277000, depth_time=2026-10-13T09:30:16+00:00, book20_bid_proxy_usdt=3260914, book20_ask_proxy_usdt=3069732, funding_indicative=0.000070, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.76%, turnover=268846697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.482500, depth_time=2026-10-13T09:30:23+00:00, book20_bid_proxy_usdt=1853385, book20_ask_proxy_usdt=1984764, funding_indicative=-0.000005, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.38%, turnover=66155487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.005142, depth_time=2026-10-13T09:30:24+00:00, book20_bid_proxy_usdt=1268155, book20_ask_proxy_usdt=1321034, funding_indicative=-0.000003, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=32154140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.957000, depth_time=2026-10-13T09:30:20+00:00, book20_bid_proxy_usdt=54073, book20_ask_proxy_usdt=39937, funding_indicative=-0.000817, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.53%, turnover=6841191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T09:30:03+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.064840, depth_time=2026-10-13T09:30:27+00:00, book20_bid_proxy_usdt=198407, book20_ask_proxy_usdt=256111, funding_indicative=0.000064, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=9204766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.088210, depth_time=2026-10-13T09:30:30+00:00, book20_bid_proxy_usdt=202702, book20_ask_proxy_usdt=140277, funding_indicative=0.000016, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=61063202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T09:30:03+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.180980, depth_time=2026-10-13T09:30:39+00:00, book20_bid_proxy_usdt=59779, book20_ask_proxy_usdt=50055, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=6211555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=0.019627, depth_time=2026-10-13T09:30:11+00:00, book20_bid_proxy_usdt=17403, book20_ask_proxy_usdt=26474, funding_indicative=-0.000448, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.56%, turnover=28353934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T09:30:02+00:00, last15m_closed_end=2026-10-13T09:30+00:00, prior8high=2.157300, depth_time=2026-10-13T09:30:13+00:00, book20_bid_proxy_usdt=42331, book20_ask_proxy_usdt=64253, funding_indicative=-0.000023, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.16%, turnover=22545379. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
