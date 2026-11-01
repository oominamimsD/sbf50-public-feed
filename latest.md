# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T08:00:36Z**
- feed_generated_utc: 2026-11-01T08:00:40+00:00
- source_sha256: `4629e9f36f734d76199e277878aa78c8c6961e38c35e0360d9045679c1dc544d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.229700|-22.44|36.79|-22.93|30515766|3.05|
|AKE_USDT|0.009390|-15.69|-67.87|-16.18|9919727|2.14|
|BLESS_USDT|0.009466|-11.21|16.67|-11.70|6176472|4.23|
|XPL_USDT|0.074510|-8.36|3.18|-8.85|6108653|1.34|
|ZEC_USDT|1245.660000|-3.02|8.77|-3.51|906964837|0.08|
|ENA_USDT|0.188230|-2.97|0.77|-3.46|42510388|0.53|
|NEAR_USDT|4.368000|-2.41|-0.77|-2.90|51366023|2.29|
|XLM_USDT|0.169160|-1.50|0.44|-1.99|19803903|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009390|0.009211|0.009380|0.68|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009466|0.009395|0.009468|1.33|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188230|0.186980|0.188220|0.79|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.229700|0.228710|0.230300|0.46|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.368000|4.359000|4.367000|1.12|N|Y/Y|Y/N|Y|N|
|XLM_USDT|0.169160|0.168690|0.169160|0.99|N|N/Y|N/Y|Y|N|
|XPL_USDT|0.074510|0.072520|0.074520|1.12|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1245.660000|1239.270000|1245.360000|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=0.010318, depth_time=2026-11-01T08:00:20+00:00, book20_bid_proxy_usdt=10777, book20_ask_proxy_usdt=10634, funding_indicative=-0.002286, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.69%, turnover=9919727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=0.009785, depth_time=2026-11-01T08:00:22+00:00, book20_bid_proxy_usdt=17550, book20_ask_proxy_usdt=16372, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.21%, turnover=6176472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=0.190760, depth_time=2026-11-01T08:00:29+00:00, book20_bid_proxy_usdt=172528, book20_ask_proxy_usdt=109170, funding_indicative=0.000000, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=42510388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=0.243440, depth_time=2026-11-01T08:00:16+00:00, book20_bid_proxy_usdt=9474, book20_ask_proxy_usdt=6758, funding_indicative=-0.002127, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.44%, turnover=30515766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=4.410000, depth_time=2026-11-01T08:00:33+00:00, book20_bid_proxy_usdt=4402371, book20_ask_proxy_usdt=3520700, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=51366023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=0.169690, depth_time=2026-11-01T08:00:36+00:00, book20_bid_proxy_usdt=157021, book20_ask_proxy_usdt=145178, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=19803903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=0.074940, depth_time=2026-11-01T08:00:25+00:00, book20_bid_proxy_usdt=364534, book20_ask_proxy_usdt=351429, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.36%, turnover=6108653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T08:00:08+00:00, last15m_closed_end=2026-11-01T08:00+00:00, prior8high=1254.820000, depth_time=2026-11-01T08:00:27+00:00, book20_bid_proxy_usdt=340902, book20_ask_proxy_usdt=303646, funding_indicative=-0.000088, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=906964837. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
