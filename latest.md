# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T12:45:38Z**
- feed_generated_utc: 2026-10-28T12:45:42+00:00
- source_sha256: `9f16171d2b488eedbdcc3ea122605cd4f587d272361b6446331707e3a1e6918a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T12:45+00:00, close=80791.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054220|-14.72|-55.83|-15.04|19297346|3.69|
|BEAT_USDT|0.079780|-12.41|6.78|-12.73|15999810|5.02|
|AKE_USDT|0.019638|-7.03|-36.83|-7.35|6570948|4.08|
|ENA_USDT|0.200070|-5.96|5.36|-6.28|78844724|1.00|
|INJ_USDT|7.847000|-4.21|-8.75|-4.53|24931823|1.27|
|ARB_USDT|0.165420|-1.82|-12.45|-2.14|16329607|0.60|
|UNI_USDT|7.030000|-1.80|-3.31|-2.12|14172594|1.42|
|WLD_USDT|0.428800|-1.65|-23.80|-1.97|64632254|4.66|
|DASH_USDT|53.460000|-1.31|7.04|-1.63|16141099|1.87|
|ASTER_USDT|0.704900|-1.13|-1.27|-1.45|5020345|1.42|
|ADA_USDT|0.203700|-0.92|-7.99|-1.24|34356533|4.91|
|HBAR_USDT|0.075450|-0.88|-9.48|-1.20|10142945|1.32|
|QNT_USDT|196.300000|-0.80|0.58|-1.12|70317244|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.203700|0.204200|0.203700|10.46|Y|N/N|N/N|N|N|
|AKE_USDT|0.019638|0.019582|0.019655|0.60|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.165420|0.165790|0.165430|6.62|Y|Y/N|Y/Y|N|N|
|ASTER_USDT|0.704900|0.706200|0.704900|3.19|Y|Y/N|N/N|N|N|
|BEAT_USDT|0.079780|0.074400|0.079780|0.93|N|Y/Y|Y/N|N|N|
|DASH_USDT|53.460000|53.420000|53.460000|0.81|N|Y/Y|N/N|N|N|
|ENA_USDT|0.200070|0.199880|0.200120|2.53|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.075450|0.075250|0.075450|4.51|N|Y/N|Y/Y|N|N|
|INJ_USDT|7.847000|7.851000|7.845000|4.03|Y|Y/Y|N/N|N|N|
|QNT_USDT|196.300000|195.380000|196.360000|1.47|N|N/N|N/N|N|N|
|Q_USDT|0.054220|0.053250|0.054220|0.87|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.030000|7.047000|7.033000|2.63|Y|N/N|N/N|N|N|
|WLD_USDT|0.428800|0.427900|0.428900|3.55|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.207800, depth_time=2026-10-28T12:45:32+00:00, book20_bid_proxy_usdt=6225780, book20_ask_proxy_usdt=7593987, funding_indicative=-0.000072, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=34356533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.020260, depth_time=2026-10-28T12:45:12+00:00, book20_bid_proxy_usdt=5579, book20_ask_proxy_usdt=7512, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.03%, turnover=6570948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.169870, depth_time=2026-10-28T12:45:20+00:00, book20_bid_proxy_usdt=143403, book20_ask_proxy_usdt=68132, funding_indicative=-0.000054, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=16329607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.712700, depth_time=2026-10-28T12:45:30+00:00, book20_bid_proxy_usdt=1254087, book20_ask_proxy_usdt=636277, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=5020345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.087830, depth_time=2026-10-28T12:45:10+00:00, book20_bid_proxy_usdt=6440, book20_ask_proxy_usdt=8237, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.41%, turnover=15999810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=54.030000, depth_time=2026-10-28T12:45:25+00:00, book20_bid_proxy_usdt=868119, book20_ask_proxy_usdt=764808, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=16141099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.207950, depth_time=2026-10-28T12:45:15+00:00, book20_bid_proxy_usdt=206038, book20_ask_proxy_usdt=178990, funding_indicative=-0.000008, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=78844724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.076630, depth_time=2026-10-28T12:45:34+00:00, book20_bid_proxy_usdt=967379, book20_ask_proxy_usdt=1114748, funding_indicative=0.000046, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=10142945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=7.972000, depth_time=2026-10-28T12:45:17+00:00, book20_bid_proxy_usdt=354126, book20_ask_proxy_usdt=257794, funding_indicative=0.000201, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=24931823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=201.870000, depth_time=2026-10-28T12:45:37+00:00, book20_bid_proxy_usdt=85198, book20_ask_proxy_usdt=59241, funding_indicative=-0.000346, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.80%, turnover=70317244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.058330, depth_time=2026-10-28T12:45:06+00:00, book20_bid_proxy_usdt=18551, book20_ask_proxy_usdt=27101, funding_indicative=-0.000638, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.72%, turnover=19297346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=7.188000, depth_time=2026-10-28T12:45:22+00:00, book20_bid_proxy_usdt=2367302, book20_ask_proxy_usdt=2379698, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=14172594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T12:45:02+00:00, last15m_closed_end=2026-10-28T12:45+00:00, prior8high=0.439300, depth_time=2026-10-28T12:45:25+00:00, book20_bid_proxy_usdt=3721182, book20_ask_proxy_usdt=3827702, funding_indicative=-0.000103, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=64632254. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
