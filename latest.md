# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T12:15:34Z**
- feed_generated_utc: 2026-10-28T12:15:38+00:00
- source_sha256: `73686a9acf900e9ea71db25d7a284c31271432e5271061b9c8cea1cf898889c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T12:15+00:00, close=80884.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055070|-13.39|-55.13|-13.83|19006731|1.82|
|BEAT_USDT|0.080280|-11.86|7.45|-12.30|15805962|3.75|
|AKE_USDT|0.019725|-6.62|-36.55|-7.06|6484203|0.51|
|ENA_USDT|0.200320|-5.85|5.49|-6.29|74471474|0.50|
|INJ_USDT|7.853000|-4.13|-8.68|-4.57|24264791|1.27|
|WLD_USDT|0.428800|-1.65|-23.80|-2.09|60851522|2.33|
|BULLA_USDT|0.057850|-1.53|-17.83|-1.97|9531099|5.20|
|UNI_USDT|7.055000|-1.45|-2.97|-1.89|13222066|1.42|
|ARB_USDT|0.166110|-1.41|-12.08|-1.85|15324110|0.60|
|DASH_USDT|53.450000|-1.32|7.02|-1.76|15957381|3.74|
|HBAR_USDT|0.075380|-0.97|-9.57|-1.41|9517085|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019725|0.019671|0.019729|0.82|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.166110|0.167570|0.166110|4.56|Y|Y/N|Y/Y|N|N|
|BEAT_USDT|0.080280|0.074400|0.080320|0.54|N|Y/Y|Y/N|N|N|
|BULLA_USDT|0.057850|0.056250|0.058010|0.45|N|Y/Y|Y/Y|N|N|
|DASH_USDT|53.450000|53.440000|53.480000|1.82|N|Y/Y|N/N|N|N|
|ENA_USDT|0.200320|0.202410|0.200270|5.22|Y|Y/Y|Y/N|N|N|
|HBAR_USDT|0.075380|0.076110|0.075390|6.69|Y|Y/N|Y/Y|N|N|
|INJ_USDT|7.853000|7.902000|7.853000|4.50|Y|Y/Y|N/N|N|N|
|Q_USDT|0.055070|0.054330|0.055140|0.67|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.055000|7.137000|7.058000|4.70|Y|N/N|N/N|N|N|
|WLD_USDT|0.428800|0.433500|0.428900|5.18|Y|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.020648, depth_time=2026-10-28T12:15:14+00:00, book20_bid_proxy_usdt=16308, book20_ask_proxy_usdt=6252, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.62%, turnover=6484203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.170250, depth_time=2026-10-28T12:15:29+00:00, book20_bid_proxy_usdt=54248, book20_ask_proxy_usdt=94160, funding_indicative=-0.000038, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=15324110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.087880, depth_time=2026-10-28T12:15:11+00:00, book20_bid_proxy_usdt=6817, book20_ask_proxy_usdt=8844, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.86%, turnover=15805962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.065130, depth_time=2026-10-28T12:15:24+00:00, book20_bid_proxy_usdt=5880, book20_ask_proxy_usdt=7677, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=9531099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=54.100000, depth_time=2026-10-28T12:15:29+00:00, book20_bid_proxy_usdt=746237, book20_ask_proxy_usdt=729323, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=15957381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.207950, depth_time=2026-10-28T12:15:16+00:00, book20_bid_proxy_usdt=102703, book20_ask_proxy_usdt=229586, funding_indicative=0.000004, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=74471474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.076640, depth_time=2026-10-28T12:15:33+00:00, book20_bid_proxy_usdt=513995, book20_ask_proxy_usdt=576112, funding_indicative=0.000060, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=9517085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=7.998000, depth_time=2026-10-28T12:15:18+00:00, book20_bid_proxy_usdt=167202, book20_ask_proxy_usdt=250839, funding_indicative=0.000212, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=24264791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.059370, depth_time=2026-10-28T12:15:09+00:00, book20_bid_proxy_usdt=19091, book20_ask_proxy_usdt=23535, funding_indicative=-0.000500, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.39%, turnover=19006731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=7.209000, depth_time=2026-10-28T12:15:25+00:00, book20_bid_proxy_usdt=1227738, book20_ask_proxy_usdt=2235002, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=13222066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T12:15:02+00:00, last15m_closed_end=2026-10-28T12:15+00:00, prior8high=0.439500, depth_time=2026-10-28T12:15:22+00:00, book20_bid_proxy_usdt=3372912, book20_ask_proxy_usdt=3892693, funding_indicative=-0.000125, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=60851522. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
