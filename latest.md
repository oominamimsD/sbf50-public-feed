# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T00:45:37Z**
- feed_generated_utc: 2026-11-01T00:45:39+00:00
- source_sha256: `7999215937edf82e1979033227d9f789b15080fbd8abcb07a2a0888b2b00de74`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T00:45+00:00, close=77595.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.246500|-16.76|46.79|-16.80|29844995|0.41|
|BLESS_USDT|0.009559|-9.51|17.82|-9.55|7838800|6.28|
|BTW_USDT|1.054900|-5.97|-39.41|-6.01|5601938|2.84|
|ENA_USDT|0.188780|-2.69|1.06|-2.73|45488245|0.53|
|Q_USDT|0.031250|-2.58|-60.40|-2.62|10550274|3.20|
|ZEC_USDT|1254.780000|-2.31|9.56|-2.35|1045554563|0.08|
|FET_USDT|0.159600|-2.26|-7.37|-2.30|5847983|6.27|
|AKE_USDT|0.010888|-2.24|-62.75|-2.28|11491346|4.59|
|TRX_USDT|0.306570|-1.84|-6.79|-1.88|10944575|0.33|
|XLM_USDT|0.169310|-1.41|0.53|-1.45|21557509|0.59|
|WLD_USDT|0.398900|-1.36|-13.65|-1.40|34428966|2.51|
|FARTCOIN_USDT|0.120380|-1.31|-1.31|-1.35|6550254|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010888|0.010767|0.010888|0.73|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009559|0.009300|0.009557|0.66|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.054900|1.066200|1.054900|3.42|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.188780|0.187820|0.188710|1.03|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120380|0.119850|0.120380|1.79|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159600|0.159200|0.159600|0.04|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.246500|0.241380|0.246500|2.10|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031250|0.030800|0.031240|0.60|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.306570|0.300760|0.306570|2.46|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398900|0.397300|0.398900|1.34|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169310|0.169310|0.169310|0.78|N|N/N|N/N|Y|N|
|ZEC_USDT|1254.780000|1243.100000|1254.780000|1.02|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.011276, depth_time=2026-11-01T00:45:25+00:00, book20_bid_proxy_usdt=8952, book20_ask_proxy_usdt=11870, funding_indicative=-0.000252, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=11491346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.009626, depth_time=2026-11-01T00:45:10+00:00, book20_bid_proxy_usdt=20806, book20_ask_proxy_usdt=11747, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.51%, turnover=7838800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=1.111500, depth_time=2026-11-01T00:45:13+00:00, book20_bid_proxy_usdt=22397, book20_ask_proxy_usdt=23602, funding_indicative=-0.000309, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.97%, turnover=5601938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.189650, depth_time=2026-11-01T00:45:15+00:00, book20_bid_proxy_usdt=152549, book20_ask_proxy_usdt=122628, funding_indicative=0.000012, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=45488245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T00:45:01+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.120770, depth_time=2026-11-01T00:45:36+00:00, book20_bid_proxy_usdt=72399, book20_ask_proxy_usdt=82838, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6550254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T00:45:01+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.160300, depth_time=2026-11-01T00:45:23+00:00, book20_bid_proxy_usdt=1452407, book20_ask_proxy_usdt=1044142, funding_indicative=-0.000140, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=5847983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.253400, depth_time=2026-11-01T00:45:08+00:00, book20_bid_proxy_usdt=2644, book20_ask_proxy_usdt=12987, funding_indicative=-0.001569, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.76%, turnover=29844995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.032030, depth_time=2026-11-01T00:45:18+00:00, book20_bid_proxy_usdt=48683, book20_ask_proxy_usdt=69192, funding_indicative=-0.000912, next_funding_utc=2026-11-01T01:00:00+00:00, funding_cycle_h=1, 24h_change=-2.58%, turnover=10550274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.307230, depth_time=2026-11-01T00:45:28+00:00, book20_bid_proxy_usdt=50532, book20_ask_proxy_usdt=52143, funding_indicative=-0.001589, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=10944575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.400300, depth_time=2026-11-01T00:45:31+00:00, book20_bid_proxy_usdt=2872986, book20_ask_proxy_usdt=3079528, funding_indicative=0.000085, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=34428966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T00:45:01+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=0.170190, depth_time=2026-11-01T00:45:31+00:00, book20_bid_proxy_usdt=237241, book20_ask_proxy_usdt=200226, funding_indicative=-0.000051, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=21557509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T00:45:00+00:00, last15m_closed_end=2026-11-01T00:45+00:00, prior8high=1276.470000, depth_time=2026-11-01T00:45:21+00:00, book20_bid_proxy_usdt=497705, book20_ask_proxy_usdt=129207, funding_indicative=-0.000070, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=1045554563. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
