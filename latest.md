# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T18:00:25Z**
- feed_generated_utc: 2026-10-17T18:00:26+00:00
- source_sha256: `713260f06abaad8cb6d6d22101191bd5643eccf100457411a7b191eca27e668b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T18:00+00:00, close=81340.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T18:00+00:00, close=81340.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.248200|-3.16|5.34|-3.19|9476176|4.03|
|DNA_USDT|0.264500|-2.79|UNKNOWN|-2.82|8110113|7.56|
|FILECOIN_USDT|1.066200|-1.94|-5.46|-1.97|26957455|0.94|
|ARB_USDT|0.181100|-1.53|-2.98|-1.56|29699593|0.55|
|QNT_USDT|197.610000|-1.39|-19.38|-1.42|65396873|0.51|
|DASH_USDT|48.370000|-1.30|-5.96|-1.33|6357518|2.07|
|ZEC_USDT|1126.910000|-1.26|-8.51|-1.29|1182912593|0.09|
|FARTCOIN_USDT|0.148490|-1.11|-9.40|-1.14|5438548|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181100|0.180230|0.181100|0.35|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.370000|47.830000|48.370000|1.60|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.264500|0.254400|0.264500|1.28|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.248200|0.247600|0.248200|0.23|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.148490|0.147400|0.148490|1.27|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.066200|1.059300|1.066200|0.58|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.610000|195.160000|197.610000|0.70|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1126.910000|1111.380000|1126.910000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T17:59:59+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=0.184590, depth_time=2026-10-17T18:00:14+00:00, book20_bid_proxy_usdt=85644, book20_ask_proxy_usdt=120702, funding_indicative=-0.000035, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=29699593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-17T18:00:00+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=48.630000, depth_time=2026-10-17T18:00:18+00:00, book20_bid_proxy_usdt=1082693, book20_ask_proxy_usdt=966247, funding_indicative=0.000033, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=6357518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T17:59:59+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=0.275100, depth_time=2026-10-17T18:00:10+00:00, book20_bid_proxy_usdt=87978, book20_ask_proxy_usdt=94237, funding_indicative=-0.001432, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=8110113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T17:59:59+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=0.257800, depth_time=2026-10-17T18:00:05+00:00, book20_bid_proxy_usdt=542246, book20_ask_proxy_usdt=315690, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=9476176. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T18:00:00+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=0.148910, depth_time=2026-10-17T18:00:24+00:00, book20_bid_proxy_usdt=62211, book20_ask_proxy_usdt=50946, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=5438548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T17:59:59+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=1.095600, depth_time=2026-10-17T18:00:12+00:00, book20_bid_proxy_usdt=485935, book20_ask_proxy_usdt=540865, funding_indicative=-0.000082, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=26957455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T17:59:59+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=201.050000, depth_time=2026-10-17T18:00:17+00:00, book20_bid_proxy_usdt=69691, book20_ask_proxy_usdt=67769, funding_indicative=-0.000088, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=65396873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T17:59:59+00:00, last15m_closed_end=2026-10-17T18:00+00:00, prior8high=1147.550000, depth_time=2026-10-17T18:00:22+00:00, book20_bid_proxy_usdt=241950, book20_ask_proxy_usdt=188370, funding_indicative=0.000059, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=1182912593. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
