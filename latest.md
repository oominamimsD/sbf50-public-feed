# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T20:30:21Z**
- feed_generated_utc: 2026-10-21T20:30:23+00:00
- source_sha256: `003002bb58e060232a32f92f61cd6e43fcf5f3aa591a69daa02f6741741c9d4e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T20:30+00:00, close=84492.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002490|-12.44|75.59|-12.44|9095132|4.02|
|BR_USDT|0.479490|-11.46|17.59|-11.46|14929683|2.71|
|INJ_USDT|8.566000|-2.19|12.13|-2.19|56732030|1.17|
|JCT_USDT|0.004161|-2.11|98.04|-2.11|14795584|9.61|
|AKE_USDT|0.026129|-2.10|0.95|-2.10|10261318|3.44|
|TIA_USDT|0.619700|-2.02|16.15|-2.02|39694208|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026129|0.025195|0.026129|0.74|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.479490|0.487860|0.479490|3.00|Y|Y/Y|Y/Y|N|Y|
|DOOD_USDT|0.002490|0.002224|0.002490|0.40|N|Y/Y|N/N|N|N|
|INJ_USDT|8.566000|8.474000|8.579000|0.94|N|Y/Y|Y/N|N|N|
|JCT_USDT|0.004161|0.004130|0.004161|0.32|N|Y/Y|N/N|N|N|
|TIA_USDT|0.619700|0.614400|0.619700|0.56|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T20:30:00+00:00, last15m_closed_end=2026-10-21T20:30+00:00, prior8high=0.026063, depth_time=2026-10-21T20:30:16+00:00, book20_bid_proxy_usdt=11581, book20_ask_proxy_usdt=10414, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=10261318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T20:29:59+00:00, last15m_closed_end=2026-10-21T20:30+00:00, prior8high=0.528660, depth_time=2026-10-21T20:30:11+00:00, book20_bid_proxy_usdt=5116, book20_ask_proxy_usdt=2754, funding_indicative=-0.000092, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.46%, turnover=14929683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T20:29:59+00:00, last15m_closed_end=2026-10-21T20:30+00:00, prior8high=0.002549, depth_time=2026-10-21T20:30:07+00:00, book20_bid_proxy_usdt=125289, book20_ask_proxy_usdt=137298, funding_indicative=0.000012, next_funding_utc=2026-10-21T21:00:00+00:00, funding_cycle_h=1, 24h_change=-12.44%, turnover=9095132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T20:29:59+00:00, last15m_closed_end=2026-10-21T20:30+00:00, prior8high=8.717000, depth_time=2026-10-21T20:30:13+00:00, book20_bid_proxy_usdt=219487, book20_ask_proxy_usdt=177667, funding_indicative=0.000101, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=56732030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T20:29:59+00:00, last15m_closed_end=2026-10-21T20:30+00:00, prior8high=0.004433, depth_time=2026-10-21T20:30:16+00:00, book20_bid_proxy_usdt=29814, book20_ask_proxy_usdt=29404, funding_indicative=0.000115, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=14795584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T20:29:59+00:00, last15m_closed_end=2026-10-21T20:30+00:00, prior8high=0.635600, depth_time=2026-10-21T20:30:20+00:00, book20_bid_proxy_usdt=122147, book20_ask_proxy_usdt=284636, funding_indicative=-0.000079, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=39694208. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
