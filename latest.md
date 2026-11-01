# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T05:30:29Z**
- feed_generated_utc: 2026-11-01T05:30:31+00:00
- source_sha256: `9e04b79290474903607e1c9eccbeff884d993ffed1a4e1a0d9f078433be252e1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T05:30+00:00, close=77798.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T05:00+00:00, close=77770.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.246440|-16.78|46.76|-17.10|30689466|3.24|
|AKE_USDT|0.009527|-14.46|-67.40|-14.78|11663981|1.05|
|XPL_USDT|0.073290|-9.86|1.49|-10.18|5125786|1.37|
|BLESS_USDT|0.009559|-9.51|17.82|-9.83|6546851|8.38|
|ENA_USDT|0.187720|-3.24|0.49|-3.56|42925847|0.53|
|ZEC_USDT|1247.150000|-2.91|8.90|-3.23|954335294|0.08|
|NEAR_USDT|4.384000|-2.05|-0.40|-2.37|52304222|2.28|
|XLM_USDT|0.169050|-1.56|0.38|-1.88|20199083|2.37|
|BEAT_USDT|0.097530|-1.02|45.54|-1.34|6066409|1.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009527|0.008692|0.009496|0.59|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097530|0.096720|0.097530|1.23|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009559|0.009303|0.009559|1.02|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187720|0.185670|0.187720|0.18|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.246440|0.227750|0.246310|0.83|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.384000|4.379000|4.381000|0.29|N|Y/Y|N/N|Y|N|
|XLM_USDT|0.169050|0.167510|0.168990|0.57|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.073290|0.069100|0.073270|7.42|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1247.150000|1238.800000|1246.490000|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T05:30:03+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.009975, depth_time=2026-11-01T05:30:11+00:00, book20_bid_proxy_usdt=13818, book20_ask_proxy_usdt=8772, funding_indicative=-0.003300, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.46%, turnover=11663981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T05:30:04+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.099240, depth_time=2026-11-01T05:30:27+00:00, book20_bid_proxy_usdt=9299, book20_ask_proxy_usdt=15117, funding_indicative=0.000231, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.02%, turnover=6066409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T05:30:04+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.009822, depth_time=2026-11-01T05:30:15+00:00, book20_bid_proxy_usdt=13831, book20_ask_proxy_usdt=13062, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.51%, turnover=6546851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T05:30:03+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.189100, depth_time=2026-11-01T05:30:18+00:00, book20_bid_proxy_usdt=134398, book20_ask_proxy_usdt=189228, funding_indicative=0.000009, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=42925847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T05:30:03+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.246110, depth_time=2026-11-01T05:30:08+00:00, book20_bid_proxy_usdt=21671, book20_ask_proxy_usdt=8197, funding_indicative=-0.002221, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.78%, turnover=30689466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T05:30:03+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=4.443000, depth_time=2026-11-01T05:30:22+00:00, book20_bid_proxy_usdt=3979375, book20_ask_proxy_usdt=4123484, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=52304222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T05:30:04+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.169260, depth_time=2026-11-01T05:30:25+00:00, book20_bid_proxy_usdt=146228, book20_ask_proxy_usdt=150381, funding_indicative=0.000075, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=20199083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T05:30:04+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=0.086230, depth_time=2026-11-01T05:30:14+00:00, book20_bid_proxy_usdt=336144, book20_ask_proxy_usdt=272074, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=5125786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T05:30:03+00:00, last15m_closed_end=2026-11-01T05:30+00:00, prior8high=1251.980000, depth_time=2026-11-01T05:30:21+00:00, book20_bid_proxy_usdt=346984, book20_ask_proxy_usdt=589955, funding_indicative=-0.000132, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=954335294. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
