# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T10:45:23Z**
- feed_generated_utc: 2026-10-26T10:45:26+00:00
- source_sha256: `8a4c107cf0ced721246da8c3c00f988fee7469dfc49d4d0b677dc4415e19e900`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T10:45+00:00, close=80409.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T10:00+00:00, close=80507.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.079860|-25.69|20.09|-25.46|7381098|6.27|
|IRYS_USDT|0.028930|-24.73|137.13|-24.50|12683347|6.91|
|APR_USDT|0.034580|-16.29|26.94|-16.06|9024253|2.89|
|BTW_USDT|1.495400|-9.85|-35.13|-9.62|11199007|2.01|
|WLD_USDT|0.440800|-3.46|-7.45|-3.23|64114032|2.27|
|XMR_USDT|589.520000|-2.92|1.20|-2.69|5959963|0.34|
|LIT_USDT|3.099300|-2.48|5.76|-2.25|5599190|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034580|0.033760|0.034590|0.69|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.495400|1.488600|1.495400|1.61|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.079860|0.074320|0.079860|1.27|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.028930|0.028610|0.028920|0.39|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.099300|3.066900|3.099300|0.48|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.440800|0.437300|0.440800|1.15|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.520000|587.500000|589.520000|0.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=0.038620, depth_time=2026-10-26T10:45:13+00:00, book20_bid_proxy_usdt=57209, book20_ask_proxy_usdt=50767, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.29%, turnover=9024253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=1.538500, depth_time=2026-10-26T10:45:15+00:00, book20_bid_proxy_usdt=8529, book20_ask_proxy_usdt=14532, funding_indicative=-0.011905, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.85%, turnover=11199007. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=0.087050, depth_time=2026-10-26T10:45:08+00:00, book20_bid_proxy_usdt=56360, book20_ask_proxy_usdt=65163, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-25.69%, turnover=7381098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=0.029970, depth_time=2026-10-26T10:45:08+00:00, book20_bid_proxy_usdt=94100, book20_ask_proxy_usdt=78128, funding_indicative=-0.000620, next_funding_utc=2026-10-26T11:00:00+00:00, funding_cycle_h=1, 24h_change=-24.73%, turnover=12683347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=3.121700, depth_time=2026-10-26T10:45:20+00:00, book20_bid_proxy_usdt=21051, book20_ask_proxy_usdt=15728, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=5599190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=0.444800, depth_time=2026-10-26T10:45:17+00:00, book20_bid_proxy_usdt=2635375, book20_ask_proxy_usdt=2781251, funding_indicative=-0.000134, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=64114032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T10:45:01+00:00, last15m_closed_end=2026-10-26T10:45+00:00, prior8high=592.000000, depth_time=2026-10-26T10:45:20+00:00, book20_bid_proxy_usdt=11222, book20_ask_proxy_usdt=11167, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=5959963. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
