# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T04:45:30Z**
- feed_generated_utc: 2026-11-01T04:45:31+00:00
- source_sha256: `760223e709ddb85dafa098463ec6d8e24349c5f163523bf54e85d3f5ba5647da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T04:45+00:00, close=77806.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.237280|-19.88|41.30|-20.19|30371231|1.69|
|AKE_USDT|0.009378|-15.80|-67.91|-16.11|11743313|3.21|
|BLESS_USDT|0.009602|-9.10|18.35|-9.41|6912030|3.12|
|ENA_USDT|0.187490|-3.36|0.37|-3.67|43205865|1.60|
|ZEC_USDT|1246.300000|-2.97|8.82|-3.28|974755699|0.08|
|XLM_USDT|0.168240|-2.03|-0.10|-2.34|20578347|0.59|
|BEAT_USDT|0.097320|-1.23|45.23|-1.54|6272436|3.08|
|TRX_USDT|0.309000|-1.06|-6.05|-1.37|10892969|0.32|
|BTW_USDT|1.111100|-0.96|-36.19|-1.27|5246118|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009378|0.008372|0.009378|2.66|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097320|0.097440|0.097320|1.21|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009602|0.009219|0.009607|0.77|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.111100|1.091400|1.111100|0.53|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187490|0.185670|0.187510|1.95|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.237280|0.226590|0.237230|1.25|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.309000|0.307330|0.309000|0.03|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168240|0.167510|0.168210|1.37|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1246.300000|1238.800000|1246.380000|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.009741, depth_time=2026-11-01T04:45:11+00:00, book20_bid_proxy_usdt=14507, book20_ask_proxy_usdt=8488, funding_indicative=-0.003532, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.80%, turnover=11743313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.099240, depth_time=2026-11-01T04:45:23+00:00, book20_bid_proxy_usdt=10149, book20_ask_proxy_usdt=18676, funding_indicative=0.000233, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=6272436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.009822, depth_time=2026-11-01T04:45:13+00:00, book20_bid_proxy_usdt=21852, book20_ask_proxy_usdt=21603, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.10%, turnover=6912030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=1.139700, depth_time=2026-11-01T04:45:28+00:00, book20_bid_proxy_usdt=13884, book20_ask_proxy_usdt=8677, funding_indicative=-0.000058, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=5246118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.189100, depth_time=2026-11-01T04:45:16+00:00, book20_bid_proxy_usdt=55714, book20_ask_proxy_usdt=198799, funding_indicative=-0.000008, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=43205865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.240290, depth_time=2026-11-01T04:45:08+00:00, book20_bid_proxy_usdt=7289, book20_ask_proxy_usdt=11202, funding_indicative=-0.001169, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.88%, turnover=30371231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.309960, depth_time=2026-11-01T04:45:21+00:00, book20_bid_proxy_usdt=158746, book20_ask_proxy_usdt=170967, funding_indicative=-0.001058, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=10892969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=0.169260, depth_time=2026-11-01T04:45:21+00:00, book20_bid_proxy_usdt=142842, book20_ask_proxy_usdt=180231, funding_indicative=0.000037, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=20578347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T04:45:01+00:00, last15m_closed_end=2026-11-01T04:45+00:00, prior8high=1250.300000, depth_time=2026-11-01T04:45:19+00:00, book20_bid_proxy_usdt=380466, book20_ask_proxy_usdt=1437594, funding_indicative=-0.000125, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=974755699. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
