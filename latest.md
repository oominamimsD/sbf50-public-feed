# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T02:45:21Z**
- feed_generated_utc: 2026-11-05T02:45:22+00:00
- source_sha256: `ae04ca0a8aa0da26178b47a2a5fed58fe03e14e967efc20e3604fc2ac4b75e72`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T02:45+00:00, close=80615, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T02:00+00:00, close=80640.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002442|-13.09|-87.84|-13.51|17214775|4.09|
|TRUMPOFFICIAL_USDT|1.265000|-11.16|-25.98|-11.58|27470988|7.91|
|CLANKER_USDT|16.600000|-10.80|24.25|-11.22|20321246|6.02|
|IDOL_USDT|0.021396|-8.82|147.15|-9.24|5925858|2.34|
|VVV_USDT|21.537000|-6.97|-9.57|-7.39|5073889|6.96|
|BTW_USDT|1.040100|-5.35|-40.15|-5.77|6041484|1.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002442|0.002197|0.002442|1.35|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.040100|1.003000|1.040100|1.60|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|16.600000|15.780000|16.600000|0.14|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021396|0.020956|0.021396|0.81|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.265000|1.228000|1.265000|1.55|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.537000|21.043000|21.537000|0.80|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T02:45:00+00:00, last15m_closed_end=2026-11-05T02:45+00:00, prior8high=0.002642, depth_time=2026-11-05T02:45:08+00:00, book20_bid_proxy_usdt=32022, book20_ask_proxy_usdt=39299, funding_indicative=-0.000623, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.09%, turnover=17214775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T02:45:00+00:00, last15m_closed_end=2026-11-05T02:45+00:00, prior8high=1.037600, depth_time=2026-11-05T02:45:20+00:00, book20_bid_proxy_usdt=22332, book20_ask_proxy_usdt=21752, funding_indicative=0.000022, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.35%, turnover=6041484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T02:45:00+00:00, last15m_closed_end=2026-11-05T02:45+00:00, prior8high=18.700000, depth_time=2026-11-05T02:45:11+00:00, book20_bid_proxy_usdt=135644, book20_ask_proxy_usdt=150521, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.80%, turnover=20321246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T02:45:00+00:00, last15m_closed_end=2026-11-05T02:45+00:00, prior8high=0.021763, depth_time=2026-11-05T02:45:13+00:00, book20_bid_proxy_usdt=5720, book20_ask_proxy_usdt=6430, funding_indicative=0.000085, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.82%, turnover=5925858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T02:45:00+00:00, last15m_closed_end=2026-11-05T02:45+00:00, prior8high=1.284000, depth_time=2026-11-05T02:45:09+00:00, book20_bid_proxy_usdt=1105544, book20_ask_proxy_usdt=1472351, funding_indicative=-0.000358, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.16%, turnover=27470988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T02:45:00+00:00, last15m_closed_end=2026-11-05T02:45+00:00, prior8high=21.524000, depth_time=2026-11-05T02:45:18+00:00, book20_bid_proxy_usdt=25874, book20_ask_proxy_usdt=16401, funding_indicative=-0.000314, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=5073889. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
