# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T00:30:19Z**
- feed_generated_utc: 2026-11-10T00:30:21+00:00
- source_sha256: `4fd1006dd7e2efc406a407fd58fe12c1fb830ce929ebdf075b7dd2099cb7ee08`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T00:30+00:00, close=75102.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002396|-51.07|-56.45|-50.55|11757767|4.20|
|ZEC_USDT|1166.900000|-4.79|-6.95|-4.27|2434688533|0.17|
|PEPE_USDT|0.000005|-4.09|9.27|-3.57|84767627|0.39|
|DOT_USDT|0.855200|-4.00|-8.44|-3.48|10778018|1.17|
|QNT_USDT|193.970000|-3.03|-4.18|-2.51|40906896|0.52|
|HBAR_USDT|0.066550|-2.80|-5.56|-2.28|8936255|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002396|0.002408|0.002391|18.27|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.855200|0.853200|0.855200|0.82|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066550|0.066470|0.066550|8.52|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.63|N|N/Y|N/N|Y|N|
|QNT_USDT|193.970000|193.880000|193.990000|2.28|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1166.900000|1152.430000|1166.900000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T00:30:01+00:00, last15m_closed_end=2026-11-10T00:30+00:00, prior8high=0.005150, depth_time=2026-11-10T00:30:07+00:00, book20_bid_proxy_usdt=68530, book20_ask_proxy_usdt=15796, funding_indicative=-0.000976, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-51.07%, turnover=11757767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T00:30:02+00:00, last15m_closed_end=2026-11-10T00:30+00:00, prior8high=0.864400, depth_time=2026-11-10T00:30:14+00:00, book20_bid_proxy_usdt=642748, book20_ask_proxy_usdt=724512, funding_indicative=0.000060, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=10778018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T00:30:02+00:00, last15m_closed_end=2026-11-10T00:30+00:00, prior8high=0.067330, depth_time=2026-11-10T00:30:16+00:00, book20_bid_proxy_usdt=550908, book20_ask_proxy_usdt=898988, funding_indicative=0.000089, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=8936255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T00:30:01+00:00, last15m_closed_end=2026-11-10T00:30+00:00, prior8high=0.000005, depth_time=2026-11-10T00:30:09+00:00, book20_bid_proxy_usdt=74743, book20_ask_proxy_usdt=22759, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=84767627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T00:30:02+00:00, last15m_closed_end=2026-11-10T00:30+00:00, prior8high=197.070000, depth_time=2026-11-10T00:30:15+00:00, book20_bid_proxy_usdt=46593, book20_ask_proxy_usdt=93359, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=40906896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T00:30:01+00:00, last15m_closed_end=2026-11-10T00:30+00:00, prior8high=1184.660000, depth_time=2026-11-10T00:30:09+00:00, book20_bid_proxy_usdt=205914, book20_ask_proxy_usdt=141504, funding_indicative=0.000091, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.79%, turnover=2434688533. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
