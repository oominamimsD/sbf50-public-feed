# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T04:30:31Z**
- feed_generated_utc: 2026-10-31T04:30:33+00:00
- source_sha256: `641598eb0625c92829411d137c9aa1332c816344463757a385a7db586570185b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T04:30+00:00, close=77249.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011301|-40.27|-67.70|-39.85|6510114|3.54|
|BEAT_USDT|0.099850|-5.04|37.55|-4.62|8742929|2.00|
|EVAA_USDT|1.236900|-3.52|135.64|-3.10|6418119|4.85|
|HYPE_USDT|89.191000|-3.41|13.75|-2.99|111299551|0.11|
|PEPE_USDT|0.000005|-3.36|0.59|-2.94|138264166|0.20|
|BTW_USDT|1.161000|-3.20|-31.80|-2.78|9695590|3.45|
|LIT_USDT|2.744900|-2.80|-17.42|-2.38|5552681|0.36|
|TRX_USDT|0.326420|-2.70|-0.88|-2.28|7212246|0.92|
|DASH_USDT|48.240000|-1.63|-10.41|-1.21|16107881|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011301|0.011264|0.011302|0.51|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099850|0.096210|0.099850|0.38|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.161000|1.134400|1.161000|0.78|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.240000|48.220000|48.240000|5.68|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.236900|1.160400|1.236900|0.69|N|N/N|N/N|Y|N|
|HYPE_USDT|89.191000|89.108000|89.191000|0.32|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.744900|2.734100|2.744900|1.36|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.42|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.326420|0.324100|0.326420|0.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T04:29:59+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=0.012057, depth_time=2026-10-31T04:30:09+00:00, book20_bid_proxy_usdt=9932, book20_ask_proxy_usdt=7890, funding_indicative=-0.000107, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-40.27%, turnover=6510114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T04:30:00+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=0.101470, depth_time=2026-10-31T04:30:11+00:00, book20_bid_proxy_usdt=14179, book20_ask_proxy_usdt=10503, funding_indicative=0.000149, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=8742929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T04:29:59+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=1.291900, depth_time=2026-10-31T04:30:22+00:00, book20_bid_proxy_usdt=11584, book20_ask_proxy_usdt=8590, funding_indicative=-0.000321, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=9695590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T04:30:00+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=48.970000, depth_time=2026-10-31T04:30:29+00:00, book20_bid_proxy_usdt=856997, book20_ask_proxy_usdt=542996, funding_indicative=0.000079, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=16107881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T04:29:59+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=1.292600, depth_time=2026-10-31T04:30:14+00:00, book20_bid_proxy_usdt=2256, book20_ask_proxy_usdt=2596, funding_indicative=0.000187, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=6418119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T04:29:59+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=90.160000, depth_time=2026-10-31T04:30:15+00:00, book20_bid_proxy_usdt=140153, book20_ask_proxy_usdt=97874, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=111299551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T04:30:00+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=2.792700, depth_time=2026-10-31T04:30:25+00:00, book20_bid_proxy_usdt=34632, book20_ask_proxy_usdt=18850, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.80%, turnover=5552681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T04:29:59+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=0.000005, depth_time=2026-10-31T04:30:19+00:00, book20_bid_proxy_usdt=28774, book20_ask_proxy_usdt=18897, funding_indicative=-0.000211, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=138264166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T04:29:59+00:00, last15m_closed_end=2026-10-31T04:30+00:00, prior8high=0.327950, depth_time=2026-10-31T04:30:26+00:00, book20_bid_proxy_usdt=40405, book20_ask_proxy_usdt=46724, funding_indicative=-0.001457, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=7212246. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
