# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T12:30:33Z**
- feed_generated_utc: 2026-10-28T12:30:37+00:00
- source_sha256: `40cf6714767a06f823f7376e0aec0879b325201dc68bd0fde940824347d8a848`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T12:30+00:00, close=80935.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054400|-14.44|-55.68|-14.94|19220469|1.84|
|BEAT_USDT|0.079600|-12.61|6.54|-13.11|15875376|1.26|
|AKE_USDT|0.019617|-7.13|-36.90|-7.63|6550000|0.51|
|ENA_USDT|0.201930|-5.09|6.34|-5.59|76208321|0.99|
|INJ_USDT|7.886000|-3.73|-8.30|-4.23|24524392|1.27|
|WLD_USDT|0.430300|-1.30|-23.54|-1.80|62525948|2.32|
|ARB_USDT|0.166420|-1.23|-11.92|-1.73|15594958|0.60|
|UNI_USDT|7.087000|-1.00|-2.53|-1.50|13793809|1.41|
|DASH_USDT|53.670000|-0.92|7.46|-1.42|16073462|1.86|
|HBAR_USDT|0.075600|-0.68|-9.30|-1.18|9752554|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019617|0.019671|0.019621|1.51|Y|Y/Y|Y/Y|N|Y|
|ARB_USDT|0.166420|0.165980|0.166480|2.41|N|Y/N|Y/Y|N|N|
|BEAT_USDT|0.079600|0.074400|0.079600|0.50|N|Y/Y|Y/N|N|N|
|DASH_USDT|53.670000|53.440000|53.670000|1.68|N|Y/Y|N/N|N|N|
|ENA_USDT|0.201930|0.200230|0.201900|2.02|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.075600|0.075380|0.075600|2.84|N|Y/N|Y/Y|N|N|
|INJ_USDT|7.886000|7.851000|7.890000|3.08|N|Y/Y|N/N|N|N|
|Q_USDT|0.054400|0.054330|0.054330|2.43|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.087000|7.056000|7.087000|4.32|N|N/N|N/N|N|N|
|WLD_USDT|0.430300|0.428700|0.430500|2.82|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.020268, depth_time=2026-10-28T12:30:13+00:00, book20_bid_proxy_usdt=6821, book20_ask_proxy_usdt=2963, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.13%, turnover=6550000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.170030, depth_time=2026-10-28T12:30:23+00:00, book20_bid_proxy_usdt=93060, book20_ask_proxy_usdt=56408, funding_indicative=-0.000041, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=15594958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.087830, depth_time=2026-10-28T12:30:11+00:00, book20_bid_proxy_usdt=11049, book20_ask_proxy_usdt=12254, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.61%, turnover=15875376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=54.030000, depth_time=2026-10-28T12:30:23+00:00, book20_bid_proxy_usdt=872765, book20_ask_proxy_usdt=541024, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=16073462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.207950, depth_time=2026-10-28T12:30:17+00:00, book20_bid_proxy_usdt=140873, book20_ask_proxy_usdt=85314, funding_indicative=0.000000, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=76208321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.076640, depth_time=2026-10-28T12:30:32+00:00, book20_bid_proxy_usdt=1279642, book20_ask_proxy_usdt=1262113, funding_indicative=0.000055, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=9752554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=7.981000, depth_time=2026-10-28T12:30:18+00:00, book20_bid_proxy_usdt=197961, book20_ask_proxy_usdt=255986, funding_indicative=0.000207, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=24524392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.058330, depth_time=2026-10-28T12:30:08+00:00, book20_bid_proxy_usdt=18607, book20_ask_proxy_usdt=35322, funding_indicative=-0.000603, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.44%, turnover=19220469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=7.188000, depth_time=2026-10-28T12:30:26+00:00, book20_bid_proxy_usdt=2452761, book20_ask_proxy_usdt=2231405, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=13793809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T12:30:00+00:00, last15m_closed_end=2026-10-28T12:30+00:00, prior8high=0.439300, depth_time=2026-10-28T12:30:22+00:00, book20_bid_proxy_usdt=3522788, book20_ask_proxy_usdt=3466206, funding_indicative=-0.000115, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=62525948. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
