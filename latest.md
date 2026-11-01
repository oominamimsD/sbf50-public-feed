# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T03:30:30Z**
- feed_generated_utc: 2026-11-01T03:30:32+00:00
- source_sha256: `f655dfecff03515ffc52de9ae6210a72059adfa98c2d3fdb0e694c6b8a95d9f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T03:30+00:00, close=77734.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T03:00+00:00, close=77690, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.229660|-22.45|36.76|-22.68|29890211|0.43|
|AKE_USDT|0.008846|-20.57|-69.73|-20.80|11608890|5.65|
|BLESS_USDT|0.009350|-11.49|15.24|-11.72|7198933|4.28|
|ZEC_USDT|1243.010000|-3.23|8.53|-3.46|978642966|0.08|
|ENA_USDT|0.187780|-3.21|0.53|-3.44|44484559|0.53|
|XLM_USDT|0.168790|-1.71|0.22|-1.94|19995652|0.59|
|BTW_USDT|1.106500|-1.37|-36.45|-1.60|5291663|0.90|
|FARTCOIN_USDT|0.120560|-1.17|-1.16|-1.40|6345221|0.83|
|TRX_USDT|0.308830|-1.12|-6.11|-1.35|10941508|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.008846|0.008372|0.008838|2.36|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009350|0.009219|0.009350|1.05|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.106500|1.059400|1.106500|0.78|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187780|0.186020|0.187770|0.33|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120560|0.119750|0.120560|0.25|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.229660|0.226590|0.229640|0.31|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.308830|0.306950|0.308830|0.37|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168790|0.168390|0.168790|0.52|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1243.010000|1238.980000|1243.010000|0.56|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T03:30:00+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.011493, depth_time=2026-11-01T03:30:10+00:00, book20_bid_proxy_usdt=9876, book20_ask_proxy_usdt=7140, funding_indicative=-0.002955, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-20.57%, turnover=11608890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T03:30:01+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.009486, depth_time=2026-11-01T03:30:13+00:00, book20_bid_proxy_usdt=18627, book20_ask_proxy_usdt=12944, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.49%, turnover=7198933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T03:30:00+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=1.139700, depth_time=2026-11-01T03:30:23+00:00, book20_bid_proxy_usdt=14498, book20_ask_proxy_usdt=17519, funding_indicative=-0.000227, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=5291663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T03:30:00+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.190060, depth_time=2026-11-01T03:30:18+00:00, book20_bid_proxy_usdt=154474, book20_ask_proxy_usdt=161666, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=44484559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T03:30:01+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.120890, depth_time=2026-11-01T03:30:25+00:00, book20_bid_proxy_usdt=78755, book20_ask_proxy_usdt=85396, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=6345221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T03:30:00+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.243060, depth_time=2026-11-01T03:30:08+00:00, book20_bid_proxy_usdt=13082, book20_ask_proxy_usdt=4215, funding_indicative=-0.000837, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-22.45%, turnover=29890211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T03:30:01+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.309960, depth_time=2026-11-01T03:30:28+00:00, book20_bid_proxy_usdt=566232, book20_ask_proxy_usdt=76682, funding_indicative=-0.001301, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=10941508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T03:30:01+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=0.169340, depth_time=2026-11-01T03:30:20+00:00, book20_bid_proxy_usdt=140565, book20_ask_proxy_usdt=221083, funding_indicative=-0.000012, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=19995652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T03:30:00+00:00, last15m_closed_end=2026-11-01T03:30+00:00, prior8high=1263.460000, depth_time=2026-11-01T03:30:15+00:00, book20_bid_proxy_usdt=922783, book20_ask_proxy_usdt=911464, funding_indicative=-0.000101, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=978642966. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
