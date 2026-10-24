# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T18:00:38Z**
- feed_generated_utc: 2026-10-24T18:00:42+00:00
- source_sha256: `4bff1b84b0214a309a129a5fad6d06bda8c4bdd48342268e6126d6d1d66b8487`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T18:00+00:00, close=80238.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T18:00+00:00, close=80238.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.092670|-16.11|90.99|-16.70|11844305|2.16|
|TIA_USDT|0.521800|-2.28|-20.69|-2.87|30669033|1.92|
|DOT_USDT|1.030000|-1.82|-7.82|-2.41|12822684|0.97|
|DASH_USDT|49.520000|-1.64|2.37|-2.23|16806478|2.02|
|WLD_USDT|0.458300|-1.16|-7.52|-1.75|104123085|2.18|
|ARB_USDT|0.165460|-1.02|-10.03|-1.61|23536549|0.60|
|INJ_USDT|7.514000|-0.88|-11.20|-1.47|14154606|1.33|
|ENA_USDT|0.185850|-0.50|-1.74|-1.09|65287675|1.08|
|UNI_USDT|6.667000|-0.49|-6.16|-1.08|13688300|1.50|
|AAVE_USDT|135.280000|-0.44|-11.00|-1.03|24036813|0.74|
|SEI_USDT|0.053070|-0.43|-14.41|-1.02|10666801|1.88|
|SUI_USDT|0.923800|-0.42|-5.90|-1.01|73243920|1.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|135.280000|134.040000|135.280000|0.92|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165460|0.163700|0.165460|0.54|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.092670|0.091630|0.092670|0.32|N|Y/Y|N/N|Y|N|
|DASH_USDT|49.520000|49.120000|49.520000|0.87|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.030000|1.022300|1.030000|0.35|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.185850|0.183920|0.185840|0.46|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.514000|7.423000|7.514000|1.48|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.053070|0.052460|0.053070|0.43|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.923800|0.917800|0.923800|0.45|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.521800|0.516000|0.521800|0.56|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.667000|6.546000|6.667000|1.76|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.458300|0.457900|0.458300|0.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=136.010000, depth_time=2026-10-24T18:00:31+00:00, book20_bid_proxy_usdt=379782, book20_ask_proxy_usdt=318283, funding_indicative=0.000054, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.44%, turnover=24036813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.166400, depth_time=2026-10-24T18:00:21+00:00, book20_bid_proxy_usdt=64925, book20_ask_proxy_usdt=96096, funding_indicative=0.000054, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=23536549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.099550, depth_time=2026-10-24T18:00:11+00:00, book20_bid_proxy_usdt=18466, book20_ask_proxy_usdt=15510, funding_indicative=-0.007777, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-16.11%, turnover=11844305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-24T18:00:03+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=50.050000, depth_time=2026-10-24T18:00:18+00:00, book20_bid_proxy_usdt=550246, book20_ask_proxy_usdt=761706, funding_indicative=-0.000077, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=16806478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=1.042100, depth_time=2026-10-24T18:00:16+00:00, book20_bid_proxy_usdt=272345, book20_ask_proxy_usdt=333165, funding_indicative=-0.000053, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=12822684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.188590, depth_time=2026-10-24T18:00:27+00:00, book20_bid_proxy_usdt=147301, book20_ask_proxy_usdt=179264, funding_indicative=-0.000018, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.50%, turnover=65287675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=7.582000, depth_time=2026-10-24T18:00:25+00:00, book20_bid_proxy_usdt=261917, book20_ask_proxy_usdt=243530, funding_indicative=0.000262, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=14154606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-24T18:00:03+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.053430, depth_time=2026-10-24T18:00:34+00:00, book20_bid_proxy_usdt=206902, book20_ask_proxy_usdt=369573, funding_indicative=-0.000043, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.43%, turnover=10666801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.932100, depth_time=2026-10-24T18:00:37+00:00, book20_bid_proxy_usdt=1171718, book20_ask_proxy_usdt=1430302, funding_indicative=-0.000038, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.42%, turnover=73243920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.526800, depth_time=2026-10-24T18:00:12+00:00, book20_bid_proxy_usdt=200780, book20_ask_proxy_usdt=226318, funding_indicative=0.000000, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=30669033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=6.680000, depth_time=2026-10-24T18:00:30+00:00, book20_bid_proxy_usdt=2477816, book20_ask_proxy_usdt=2878613, funding_indicative=-0.000046, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.49%, turnover=13688300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-24T18:00:02+00:00, last15m_closed_end=2026-10-24T18:00+00:00, prior8high=0.466700, depth_time=2026-10-24T18:00:20+00:00, book20_bid_proxy_usdt=2619019, book20_ask_proxy_usdt=2008902, funding_indicative=-0.000162, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=104123085. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
