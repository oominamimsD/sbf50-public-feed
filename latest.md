# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T23:15:21Z**
- feed_generated_utc: 2026-10-30T23:15:23+00:00
- source_sha256: `4e85a92acc8e12affe740437407108dcb8b68c8e4eb5978ce2e0ca789eaf9d27`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T23:15+00:00, close=77039.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T23:00+00:00, close=76917, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013607|-28.08|-61.11|-27.39|5308759|5.15|
|EVAA_USDT|1.133600|-11.58|115.96|-10.89|6662951|4.42|
|BTW_USDT|1.153100|-3.86|-32.26|-3.17|10210608|0.87|
|HYPE_USDT|89.251000|-3.34|13.83|-2.65|145374692|0.11|
|LIT_USDT|2.740200|-2.97|-17.56|-2.28|8623542|0.36|
|XMR_USDT|588.930000|-2.09|-2.97|-1.40|10506696|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013607|0.013039|0.013603|0.76|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.153100|1.135400|1.153100|0.83|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.133600|1.082800|1.133600|1.16|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.251000|89.002000|89.251000|0.49|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.740200|2.686200|2.740200|0.36|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|588.930000|589.360000|588.930000|0.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T23:15:00+00:00, last15m_closed_end=2026-10-30T23:15+00:00, prior8high=0.013831, depth_time=2026-10-30T23:15:08+00:00, book20_bid_proxy_usdt=3332, book20_ask_proxy_usdt=8353, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-28.08%, turnover=5308759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T23:15:00+00:00, last15m_closed_end=2026-10-30T23:15+00:00, prior8high=1.210300, depth_time=2026-10-30T23:15:13+00:00, book20_bid_proxy_usdt=21272, book20_ask_proxy_usdt=10022, funding_indicative=-0.000212, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=10210608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T23:15:00+00:00, last15m_closed_end=2026-10-30T23:15+00:00, prior8high=1.132500, depth_time=2026-10-30T23:15:10+00:00, book20_bid_proxy_usdt=15264, book20_ask_proxy_usdt=3378, funding_indicative=0.000182, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.58%, turnover=6662951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T23:15:00+00:00, last15m_closed_end=2026-10-30T23:15+00:00, prior8high=90.590000, depth_time=2026-10-30T23:15:15+00:00, book20_bid_proxy_usdt=132195, book20_ask_proxy_usdt=77579, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=145374692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T23:15:01+00:00, last15m_closed_end=2026-10-30T23:15+00:00, prior8high=2.742300, depth_time=2026-10-30T23:15:18+00:00, book20_bid_proxy_usdt=27956, book20_ask_proxy_usdt=19751, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=8623542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-30T23:15:00+00:00, last15m_closed_end=2026-10-30T23:15+00:00, prior8high=598.060000, depth_time=2026-10-30T23:15:20+00:00, book20_bid_proxy_usdt=6382, book20_ask_proxy_usdt=11914, funding_indicative=0.000349, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=10506696. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
