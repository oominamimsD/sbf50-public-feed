# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T08:45:24Z**
- feed_generated_utc: 2026-10-14T08:45:26+00:00
- source_sha256: `c22dab8a2fd5215fd18fae6df773c1c4dd536f52ae1bcf73e82f3c5e0d0f9d22`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T08:45+00:00, close=83435.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.081370|-6.39|55.91|-6.43|30693326|1.23|
|TIA_USDT|0.552500|-4.29|15.99|-4.33|40253412|1.81|
|MAGIC_USDT|0.114110|-3.82|67.51|-3.86|5322942|0.88|
|UNI_USDT|7.367000|-2.70|-14.97|-2.74|19883995|1.36|
|W_USDT|0.016390|-2.45|12.94|-2.49|6815445|3.06|
|SILVER_USDT|58.640000|-1.26|-4.44|-1.30|253798613|1.71|
|CRV_USDT|0.332200|-1.13|-7.67|-1.17|5109213|3.01|
|DOT_USDT|1.145600|-0.97|-4.64|-1.01|19946543|0.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CRV_USDT|0.332200|0.332000|0.332200|92.65|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.145600|1.149100|1.146400|3.95|Y|Y/Y|Y/Y|N|Y|
|MAGIC_USDT|0.114110|0.110660|0.114110|0.94|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.640000|58.560000|58.640000|2.36|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.081370|0.080760|0.081370|0.97|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.552500|0.553800|0.552500|2.68|Y|Y/Y|Y/N|N|N|
|UNI_USDT|7.367000|7.344000|7.367000|3.20|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016390|0.016011|0.016390|1.39|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CRV_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=0.337600, depth_time=2026-10-14T08:45:18+00:00, book20_bid_proxy_usdt=384193, book20_ask_proxy_usdt=445719, funding_indicative=-0.000032, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=5109213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=1.164200, depth_time=2026-10-14T08:45:23+00:00, book20_bid_proxy_usdt=250999, book20_ask_proxy_usdt=188984, funding_indicative=-0.000034, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=19946543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=0.114510, depth_time=2026-10-14T08:45:12+00:00, book20_bid_proxy_usdt=177117, book20_ask_proxy_usdt=184507, funding_indicative=-0.000035, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=5322942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=59.010000, depth_time=2026-10-14T08:45:18+00:00, book20_bid_proxy_usdt=59453970, book20_ask_proxy_usdt=52732023, funding_indicative=0.000067, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=253798613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=0.083840, depth_time=2026-10-14T08:45:08+00:00, book20_bid_proxy_usdt=322508, book20_ask_proxy_usdt=256247, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.39%, turnover=30693326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=0.564000, depth_time=2026-10-14T08:45:10+00:00, book20_bid_proxy_usdt=133364, book20_ask_proxy_usdt=166472, funding_indicative=0.000007, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=40253412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=7.502000, depth_time=2026-10-14T08:45:14+00:00, book20_bid_proxy_usdt=1701210, book20_ask_proxy_usdt=1213962, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=19883995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T08:45:01+00:00, last15m_closed_end=2026-10-14T08:45+00:00, prior8high=0.016686, depth_time=2026-10-14T08:45:16+00:00, book20_bid_proxy_usdt=67355, book20_ask_proxy_usdt=23071, funding_indicative=-0.000281, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=6815445. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
