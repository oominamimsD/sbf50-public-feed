# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T19:30:18Z**
- feed_generated_utc: 2026-10-30T19:30:20+00:00
- source_sha256: `20e3c295adad760f0d46f22802221cc4d10ab3b3a3005876dbaa5e3c40bcc292`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T19:30+00:00, close=76558.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T19:00+00:00, close=76616.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.118200|-12.78|113.03|-11.45|6738980|0.89|
|BLESS_USDT|0.008985|-8.79|10.09|-7.46|15048057|5.58|
|Q_USDT|0.044710|-5.83|-62.21|-4.50|24339921|4.47|
|PUMPFUN_USDT|0.003982|-3.04|-12.73|-1.71|25439060|2.51|
|LIT_USDT|2.754500|-2.46|-17.13|-1.13|12413924|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.008985|0.008624|0.008985|0.44|N|Y/Y|Y/N|Y|N|
|EVAA_USDT|1.118200|1.072200|1.118200|0.91|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.754500|2.683300|2.754500|0.32|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003982|0.003918|0.003982|0.56|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.044710|0.044090|0.044710|0.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T19:30:01+00:00, last15m_closed_end=2026-10-30T19:30+00:00, prior8high=0.009789, depth_time=2026-10-30T19:30:10+00:00, book20_bid_proxy_usdt=9383, book20_ask_proxy_usdt=13355, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.79%, turnover=15048057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T19:30:01+00:00, last15m_closed_end=2026-10-30T19:30+00:00, prior8high=1.289400, depth_time=2026-10-30T19:30:08+00:00, book20_bid_proxy_usdt=3677, book20_ask_proxy_usdt=13657, funding_indicative=0.000123, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-12.78%, turnover=6738980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T19:30:02+00:00, last15m_closed_end=2026-10-30T19:30+00:00, prior8high=2.800000, depth_time=2026-10-30T19:30:17+00:00, book20_bid_proxy_usdt=35678, book20_ask_proxy_usdt=18299, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=12413924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T19:30:02+00:00, last15m_closed_end=2026-10-30T19:30+00:00, prior8high=0.004064, depth_time=2026-10-30T19:30:15+00:00, book20_bid_proxy_usdt=656962, book20_ask_proxy_usdt=1014862, funding_indicative=-0.000024, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=25439060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T19:30:01+00:00, last15m_closed_end=2026-10-30T19:30+00:00, prior8high=0.048140, depth_time=2026-10-30T19:30:13+00:00, book20_bid_proxy_usdt=20598, book20_ask_proxy_usdt=19150, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.83%, turnover=24339921. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
