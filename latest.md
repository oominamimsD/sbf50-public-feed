# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T11:00:35Z**
- feed_generated_utc: 2026-10-31T11:00:37+00:00
- source_sha256: `e08ed039359cdea012dcd735a2b539e2e1845aa84fa65a4c84fcf5d75911c801`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T11:00+00:00, close=77376.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T11:00+00:00, close=77376.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010933|-43.13|-68.76|-42.87|10341246|1.83|
|Q_USDT|0.033050|-30.06|-72.07|-29.80|12996758|6.04|
|BLESS_USDT|0.010120|-25.06|24.00|-24.80|13255061|3.95|
|TRX_USDT|0.317820|-5.52|-3.49|-5.26|6940732|0.32|
|BTW_USDT|1.134300|-5.43|-33.37|-5.17|8842184|1.76|
|HYPE_USDT|87.828000|-5.30|12.01|-5.04|96580847|0.11|
|WLD_USDT|0.395300|-4.03|-25.75|-3.77|45157592|2.53|
|DASH_USDT|47.820000|-2.74|-11.19|-2.48|11468470|2.09|
|FET_USDT|0.161600|-2.11|-13.72|-1.85|5795504|6.19|
|ARB_USDT|0.160810|-1.68|-10.62|-1.42|18195787|0.62|
|LTC_USDT|54.870000|-1.34|-6.12|-1.08|6089042|3.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010933|0.010360|0.010934|1.70|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160810|0.160950|0.160810|3.19|Y|Y/Y|Y/Y|Y|Y|
|BLESS_USDT|0.010120|0.009971|0.010120|0.31|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.134300|1.118100|1.133800|0.60|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.820000|47.590000|47.820000|0.35|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161600|0.161100|0.161600|0.87|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.828000|86.630000|87.828000|0.67|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.870000|54.570000|54.870000|1.81|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.033050|0.031080|0.033070|0.66|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.317820|0.315970|0.317820|0.46|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395300|0.395100|0.395400|1.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.010956, depth_time=2026-10-31T11:00:08+00:00, book20_bid_proxy_usdt=7963, book20_ask_proxy_usdt=7417, funding_indicative=-0.000220, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-43.13%, turnover=10341246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.162180, depth_time=2026-10-31T11:00:29+00:00, book20_bid_proxy_usdt=58916, book20_ask_proxy_usdt=48663, funding_indicative=0.000052, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=18195787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.010383, depth_time=2026-10-31T11:00:14+00:00, book20_bid_proxy_usdt=7799, book20_ask_proxy_usdt=13015, funding_indicative=0.000125, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-25.06%, turnover=13255061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=1.167600, depth_time=2026-10-31T11:00:19+00:00, book20_bid_proxy_usdt=17976, book20_ask_proxy_usdt=10870, funding_indicative=-0.000231, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=8842184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=48.060000, depth_time=2026-10-31T11:00:26+00:00, book20_bid_proxy_usdt=848362, book20_ask_proxy_usdt=615212, funding_indicative=-0.000147, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=11468470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.162400, depth_time=2026-10-31T11:00:28+00:00, book20_bid_proxy_usdt=1097414, book20_ask_proxy_usdt=1011515, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=5795504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=88.220000, depth_time=2026-10-31T11:00:22+00:00, book20_bid_proxy_usdt=54776, book20_ask_proxy_usdt=195791, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.30%, turnover=96580847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=55.000000, depth_time=2026-10-31T11:00:29+00:00, book20_bid_proxy_usdt=1230633, book20_ask_proxy_usdt=1509430, funding_indicative=-0.000046, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=6089042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.033810, depth_time=2026-10-31T11:00:11+00:00, book20_bid_proxy_usdt=88264, book20_ask_proxy_usdt=59440, funding_indicative=-0.000564, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=1, 24h_change=-30.06%, turnover=12996758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.319880, depth_time=2026-10-31T11:00:16+00:00, book20_bid_proxy_usdt=72295, book20_ask_proxy_usdt=73660, funding_indicative=-0.001111, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.52%, turnover=6940732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T11:00:02+00:00, last15m_closed_end=2026-10-31T11:00+00:00, prior8high=0.399000, depth_time=2026-10-31T11:00:24+00:00, book20_bid_proxy_usdt=3797999, book20_ask_proxy_usdt=3578714, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=45157592. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
