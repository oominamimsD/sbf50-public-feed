# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T10:45:25Z**
- feed_generated_utc: 2026-10-14T10:45:27+00:00
- source_sha256: `719b09a22f0c6a9083a8a3adc701af0b3c0cc2d8bae3845df468d629d640999e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T10:45+00:00, close=83355.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T10:00+00:00, close=83219.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078810|-9.34|51.00|-9.30|29417185|1.27|
|TIA_USDT|0.542200|-6.08|13.83|-6.04|37001881|1.84|
|W_USDT|0.016118|-4.07|11.06|-4.03|6860770|2.48|
|UNI_USDT|7.347000|-2.97|-15.21|-2.93|19103484|1.36|
|DOT_USDT|1.134700|-1.91|-5.55|-1.87|20457078|1.76|
|ICP_USDT|3.065000|-1.51|-9.90|-1.47|9863465|3.26|
|SILVER_USDT|58.700000|-1.16|-4.35|-1.12|259016029|1.70|
|XLM_USDT|0.188930|-1.07|-11.58|-1.03|9979399|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.134700|1.129300|1.134900|0.88|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.065000|3.053000|3.064000|1.13|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|58.700000|58.570000|58.700000|0.28|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.078810|0.077870|0.078810|0.45|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.542200|0.540100|0.542200|0.63|N|Y/Y|Y/N|Y|N|
|UNI_USDT|7.347000|7.328000|7.347000|0.20|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.016118|0.015659|0.016118|0.60|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.188930|0.188210|0.188930|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=1.152700, depth_time=2026-10-14T10:45:17+00:00, book20_bid_proxy_usdt=368124, book20_ask_proxy_usdt=389282, funding_indicative=0.000033, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=20457078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=3.121000, depth_time=2026-10-14T10:45:19+00:00, book20_bid_proxy_usdt=1175154, book20_ask_proxy_usdt=827983, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=9863465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=58.910000, depth_time=2026-10-14T10:45:22+00:00, book20_bid_proxy_usdt=53653248, book20_ask_proxy_usdt=32570927, funding_indicative=0.000097, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=259016029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=0.082290, depth_time=2026-10-14T10:45:07+00:00, book20_bid_proxy_usdt=209610, book20_ask_proxy_usdt=247422, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.34%, turnover=29417185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=0.557800, depth_time=2026-10-14T10:45:07+00:00, book20_bid_proxy_usdt=130968, book20_ask_proxy_usdt=189605, funding_indicative=-0.000024, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.08%, turnover=37001881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=7.413000, depth_time=2026-10-14T10:45:14+00:00, book20_bid_proxy_usdt=1374433, book20_ask_proxy_usdt=1456908, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=19103484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=0.016686, depth_time=2026-10-14T10:45:12+00:00, book20_bid_proxy_usdt=34690, book20_ask_proxy_usdt=13596, funding_indicative=-0.000296, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.07%, turnover=6860770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T10:45:02+00:00, last15m_closed_end=2026-10-14T10:45+00:00, prior8high=0.190890, depth_time=2026-10-14T10:45:24+00:00, book20_bid_proxy_usdt=222381, book20_ask_proxy_usdt=189071, funding_indicative=-0.000111, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=9979399. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
