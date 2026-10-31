# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T03:45:27Z**
- feed_generated_utc: 2026-10-31T03:45:29+00:00
- source_sha256: `200d71ddc284222ee5f08cb0d9b9661e26332f850d506da9044545c9cc1a7c47`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T03:45+00:00, close=77182.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T03:00+00:00, close=77402.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011774|-37.77|-66.35|-37.26|6872857|3.40|
|Q_USDT|0.032880|-30.74|-72.21|-30.23|20481716|9.08|
|BEAT_USDT|0.098720|-6.11|35.99|-5.60|8900165|3.04|
|EVAA_USDT|1.238700|-3.38|135.98|-2.87|6608404|4.84|
|HYPE_USDT|89.495000|-3.08|14.14|-2.57|115885760|0.11|
|PEPE_USDT|0.000005|-2.79|1.18|-2.28|143980271|0.61|
|LIT_USDT|2.751400|-2.57|-17.22|-2.06|5963139|0.36|
|TRX_USDT|0.326910|-2.56|-0.73|-2.05|7747765|0.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011774|0.011264|0.011774|0.54|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098720|0.096210|0.098960|0.66|N|Y/Y|N/N|Y|N|
|EVAA_USDT|1.238700|1.118300|1.238700|0.23|N|N/Y|N/N|Y|N|
|HYPE_USDT|89.495000|89.165000|89.504000|0.57|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.751400|2.756200|2.751400|0.27|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.05|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032880|0.026260|0.032850|1.02|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.326910|0.322160|0.326910|0.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=0.012934, depth_time=2026-10-31T03:45:08+00:00, book20_bid_proxy_usdt=6101, book20_ask_proxy_usdt=8860, funding_indicative=-0.000065, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-37.77%, turnover=6872857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=0.101470, depth_time=2026-10-31T03:45:13+00:00, book20_bid_proxy_usdt=12230, book20_ask_proxy_usdt=7420, funding_indicative=0.000126, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.11%, turnover=8900165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=1.292600, depth_time=2026-10-31T03:45:16+00:00, book20_bid_proxy_usdt=13262, book20_ask_proxy_usdt=8753, funding_indicative=0.000169, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=6608404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=90.160000, depth_time=2026-10-31T03:45:18+00:00, book20_bid_proxy_usdt=197601, book20_ask_proxy_usdt=90130, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=115885760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=2.792700, depth_time=2026-10-31T03:45:20+00:00, book20_bid_proxy_usdt=19509, book20_ask_proxy_usdt=36383, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=5963139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=0.000005, depth_time=2026-10-31T03:45:20+00:00, book20_bid_proxy_usdt=23040, book20_ask_proxy_usdt=23000, funding_indicative=-0.000199, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=143980271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=0.037820, depth_time=2026-10-31T03:45:11+00:00, book20_bid_proxy_usdt=17774, book20_ask_proxy_usdt=48986, funding_indicative=-0.020000, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-30.74%, turnover=20481716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T03:45:01+00:00, last15m_closed_end=2026-10-31T03:45+00:00, prior8high=0.327100, depth_time=2026-10-31T03:45:25+00:00, book20_bid_proxy_usdt=670982, book20_ask_proxy_usdt=37941, funding_indicative=-0.001657, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=7747765. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
