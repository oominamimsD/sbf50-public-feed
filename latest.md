# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T13:30:43Z**
- feed_generated_utc: 2026-10-28T13:30:47+00:00
- source_sha256: `45f55fa19bedab91b3bf06b2abe7786246a9cee397f92761e05a78ca1b2968f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T13:30+00:00, close=80608.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T13:00+00:00, close=80708.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053460|-15.92|-56.44|-16.01|18613426|1.87|
|BEAT_USDT|0.080040|-12.13|7.13|-12.22|15019040|2.50|
|AKE_USDT|0.019482|-7.77|-37.33|-7.86|6655409|1.03|
|ENA_USDT|0.198260|-6.81|4.41|-6.90|77728602|0.50|
|INJ_USDT|7.835000|-4.35|-8.89|-4.44|24477960|2.55|
|ARB_USDT|0.164480|-2.38|-12.95|-2.47|16396181|0.61|
|DASH_USDT|53.090000|-1.99|6.30|-2.08|16054530|1.88|
|UNI_USDT|7.022000|-1.91|-3.42|-2.00|14019823|1.42|
|WLD_USDT|0.428600|-1.69|-23.84|-1.78|64923147|2.33|
|ADA_USDT|0.202800|-1.36|-8.40|-1.45|35313587|4.93|
|PUMPFUN_USDT|0.004228|-1.33|-6.27|-1.42|16195534|2.37|
|HBAR_USDT|0.075280|-1.10|-9.69|-1.19|9582098|2.65|
|APT_USDT|0.680800|-1.00|-14.65|-1.09|6404372|1.47|
|OP_USDT|0.110200|-1.00|-16.06|-1.09|5879582|1.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.202800|0.202200|0.202800|1.49|N|Y/Y|N/N|N|N|
|AKE_USDT|0.019482|0.019409|0.019482|0.69|N|Y/Y|Y/Y|N|N|
|APT_USDT|0.680800|0.677500|0.680800|1.06|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.164480|0.164190|0.164480|0.91|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.080040|0.074400|0.080040|0.37|N|Y/Y|Y/N|N|N|
|DASH_USDT|53.090000|53.130000|53.110000|1.06|N|Y/Y|N/N|N|N|
|ENA_USDT|0.198260|0.198290|0.198290|1.45|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.075280|0.075140|0.075290|1.64|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.835000|7.808000|7.836000|0.64|N|Y/Y|N/N|N|N|
|OP_USDT|0.110200|0.110110|0.110200|0.78|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004228|0.004221|0.004228|1.05|N|Y/Y|N/N|N|N|
|Q_USDT|0.053460|0.053250|0.053460|1.37|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.022000|7.004000|7.022000|0.72|N|Y/Y|N/N|N|N|
|WLD_USDT|0.428600|0.425300|0.428300|0.64|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.207200, depth_time=2026-10-28T13:30:32+00:00, book20_bid_proxy_usdt=6461081, book20_ask_proxy_usdt=6815027, funding_indicative=-0.000052, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=35313587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.020235, depth_time=2026-10-28T13:30:14+00:00, book20_bid_proxy_usdt=6577, book20_ask_proxy_usdt=2630, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.77%, turnover=6655409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.699300, depth_time=2026-10-28T13:30:40+00:00, book20_bid_proxy_usdt=109452, book20_ask_proxy_usdt=161984, funding_indicative=-0.000059, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=6404372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.168910, depth_time=2026-10-28T13:30:21+00:00, book20_bid_proxy_usdt=58159, book20_ask_proxy_usdt=70926, funding_indicative=-0.000072, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=16396181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.084640, depth_time=2026-10-28T13:30:11+00:00, book20_bid_proxy_usdt=8916, book20_ask_proxy_usdt=9156, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.13%, turnover=15019040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=53.670000, depth_time=2026-10-28T13:30:23+00:00, book20_bid_proxy_usdt=776819, book20_ask_proxy_usdt=636009, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=16054530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.205170, depth_time=2026-10-28T13:30:17+00:00, book20_bid_proxy_usdt=105179, book20_ask_proxy_usdt=81959, funding_indicative=-0.000029, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.81%, turnover=77728602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.076410, depth_time=2026-10-28T13:30:36+00:00, book20_bid_proxy_usdt=513018, book20_ask_proxy_usdt=1059060, funding_indicative=0.000017, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=9582098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=7.964000, depth_time=2026-10-28T13:30:19+00:00, book20_bid_proxy_usdt=147673, book20_ask_proxy_usdt=212296, funding_indicative=0.000182, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.35%, turnover=24477960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.113020, depth_time=2026-10-28T13:30:43+00:00, book20_bid_proxy_usdt=72565, book20_ask_proxy_usdt=104592, funding_indicative=-0.000049, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=5879582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.004344, depth_time=2026-10-28T13:30:34+00:00, book20_bid_proxy_usdt=1644290, book20_ask_proxy_usdt=2083801, funding_indicative=0.000003, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.33%, turnover=16195534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.055830, depth_time=2026-10-28T13:30:09+00:00, book20_bid_proxy_usdt=19699, book20_ask_proxy_usdt=23293, funding_indicative=-0.000722, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.92%, turnover=18613426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=7.167000, depth_time=2026-10-28T13:30:27+00:00, book20_bid_proxy_usdt=1520187, book20_ask_proxy_usdt=1666100, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=14019823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T13:30:00+00:00, last15m_closed_end=2026-10-28T13:30+00:00, prior8high=0.438400, depth_time=2026-10-28T13:30:29+00:00, book20_bid_proxy_usdt=2657145, book20_ask_proxy_usdt=2613518, funding_indicative=-0.000094, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=64923147. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
