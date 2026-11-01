# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T08:30:31Z**
- feed_generated_utc: 2026-11-01T08:30:34+00:00
- source_sha256: `7f2286be823a677d1e64df72a2aa450be57a7612dd97c8b3e1f6f8ca7aa84809`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T08:30+00:00, close=77957.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.226010|-23.68|34.59|-24.19|30941299|1.77|
|AKE_USDT|0.009446|-15.19|-67.68|-15.70|10160223|4.24|
|BLESS_USDT|0.009494|-10.12|17.02|-10.63|6276599|2.11|
|XPL_USDT|0.073540|-9.55|1.84|-10.06|6638696|1.36|
|ENA_USDT|0.187530|-3.34|0.39|-3.85|43161755|0.53|
|ZEC_USDT|1246.460000|-2.96|8.84|-3.47|921267829|0.08|
|TIA_USDT|0.477500|-2.57|-9.16|-3.08|8353276|2.09|
|NEAR_USDT|4.374000|-2.27|-0.63|-2.78|52631943|2.29|
|SOL_USDT|95.320000|-0.59|-4.40|-1.10|214509283|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009446|0.009160|0.009491|2.49|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009494|0.009395|0.009494|0.33|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187530|0.186980|0.187540|0.57|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.226010|0.219110|0.225620|0.96|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.374000|4.356000|4.374000|0.83|N|Y/Y|Y/N|Y|N|
|SOL_USDT|95.320000|95.280000|95.320000|3.87|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.477500|0.478000|0.477300|1.24|N|N/N|Y/Y|Y|N|
|XPL_USDT|0.073540|0.072520|0.073490|2.95|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1246.460000|1239.270000|1246.450000|1.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=0.009928, depth_time=2026-11-01T08:30:12+00:00, book20_bid_proxy_usdt=9908, book20_ask_proxy_usdt=11759, funding_indicative=-0.002425, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.19%, turnover=10160223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=0.009785, depth_time=2026-11-01T08:30:15+00:00, book20_bid_proxy_usdt=13130, book20_ask_proxy_usdt=20451, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.12%, turnover=6276599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=0.190760, depth_time=2026-11-01T08:30:20+00:00, book20_bid_proxy_usdt=114215, book20_ask_proxy_usdt=154848, funding_indicative=0.000005, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=43161755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=0.239600, depth_time=2026-11-01T08:30:10+00:00, book20_bid_proxy_usdt=10932, book20_ask_proxy_usdt=8788, funding_indicative=-0.002243, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.68%, turnover=30941299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=4.410000, depth_time=2026-11-01T08:30:28+00:00, book20_bid_proxy_usdt=2210560, book20_ask_proxy_usdt=3952843, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=52631943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=95.920000, depth_time=2026-11-01T08:30:30+00:00, book20_bid_proxy_usdt=17679872, book20_ask_proxy_usdt=20499941, funding_indicative=0.000098, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.59%, turnover=214509283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=0.485100, depth_time=2026-11-01T08:30:23+00:00, book20_bid_proxy_usdt=279314, book20_ask_proxy_usdt=228433, funding_indicative=-0.000097, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=8353276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=0.074940, depth_time=2026-11-01T08:30:17+00:00, book20_bid_proxy_usdt=373583, book20_ask_proxy_usdt=363489, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.55%, turnover=6638696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T08:30:04+00:00, last15m_closed_end=2026-11-01T08:30+00:00, prior8high=1254.820000, depth_time=2026-11-01T08:30:23+00:00, book20_bid_proxy_usdt=759694, book20_ask_proxy_usdt=551681, funding_indicative=-0.000073, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=921267829. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
