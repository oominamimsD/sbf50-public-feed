# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T06:15:35Z**
- feed_generated_utc: 2026-10-31T06:15:37+00:00
- source_sha256: `c395e000f9b609653a9ee0835227af11de5f2eade6d80823e0bb6567e70a3e04`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T06:15+00:00, close=77254, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T06:00+00:00, close=77232.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011524|-39.09|-67.07|-38.68|6757684|5.21|
|Q_USDT|0.031510|-33.63|-73.37|-33.22|19559862|9.55|
|BEAT_USDT|0.096540|-8.18|32.99|-7.77|8496549|4.14|
|EVAA_USDT|1.185500|-7.53|125.85|-7.12|6099479|5.91|
|HYPE_USDT|88.206000|-4.48|12.50|-4.07|107525874|0.11|
|BTW_USDT|1.149000|-4.21|-32.50|-3.80|9497390|3.48|
|WLD_USDT|0.398300|-3.30|-25.18|-2.89|48483104|2.51|
|TRX_USDT|0.325630|-2.94|-1.12|-2.53|6684967|0.31|
|PEPE_USDT|0.000005|-2.66|1.32|-2.25|131381100|1.22|
|DASH_USDT|47.940000|-2.24|-10.97|-1.83|14833308|2.09|
|FET_USDT|0.163000|-2.16|-12.97|-1.75|6483377|6.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011524|0.010838|0.011526|0.74|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.096540|0.096950|0.096540|0.87|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.149000|1.108600|1.149000|1.60|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.940000|47.920000|47.940000|10.41|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.185500|1.141300|1.185500|1.04|N|N/N|N/N|Y|N|
|FET_USDT|0.163000|0.162200|0.163000|1.82|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.206000|88.342000|88.206000|4.26|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.42|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031510|0.027250|0.031510|0.41|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.325630|0.322650|0.325450|1.92|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398300|0.392600|0.398300|0.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.011974, depth_time=2026-10-31T06:15:08+00:00, book20_bid_proxy_usdt=9333, book20_ask_proxy_usdt=17004, funding_indicative=-0.000105, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-39.09%, turnover=6757684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.100320, depth_time=2026-10-31T06:15:14+00:00, book20_bid_proxy_usdt=15250, book20_ask_proxy_usdt=17277, funding_indicative=0.000118, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.18%, turnover=8496549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=1.189400, depth_time=2026-10-31T06:15:21+00:00, book20_bid_proxy_usdt=12730, book20_ask_proxy_usdt=7698, funding_indicative=-0.000387, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=9497390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=48.420000, depth_time=2026-10-31T06:15:31+00:00, book20_bid_proxy_usdt=758099, book20_ask_proxy_usdt=640834, funding_indicative=0.000049, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=14833308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=1.249300, depth_time=2026-10-31T06:15:16+00:00, book20_bid_proxy_usdt=4234, book20_ask_proxy_usdt=9264, funding_indicative=0.000205, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.53%, turnover=6099479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.164400, depth_time=2026-10-31T06:15:34+00:00, book20_bid_proxy_usdt=1124410, book20_ask_proxy_usdt=671861, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=6483377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=89.538000, depth_time=2026-10-31T06:15:18+00:00, book20_bid_proxy_usdt=121932, book20_ask_proxy_usdt=72892, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.48%, turnover=107525874. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.000005, depth_time=2026-10-31T06:15:29+00:00, book20_bid_proxy_usdt=25472, book20_ask_proxy_usdt=14576, funding_indicative=-0.000032, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=131381100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.032480, depth_time=2026-10-31T06:15:10+00:00, book20_bid_proxy_usdt=49438, book20_ask_proxy_usdt=36183, funding_indicative=-0.000756, next_funding_utc=2026-10-31T07:00:00+00:00, funding_cycle_h=1, 24h_change=-33.63%, turnover=19559862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.327290, depth_time=2026-10-31T06:15:26+00:00, book20_bid_proxy_usdt=39878, book20_ask_proxy_usdt=42825, funding_indicative=-0.000924, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=6684967. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T06:15:02+00:00, last15m_closed_end=2026-10-31T06:15+00:00, prior8high=0.400600, depth_time=2026-10-31T06:15:22+00:00, book20_bid_proxy_usdt=3266795, book20_ask_proxy_usdt=2772451, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=48483104. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
