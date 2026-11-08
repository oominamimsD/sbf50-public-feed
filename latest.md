# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T02:00:36Z**
- feed_generated_utc: 2026-11-08T02:00:38+00:00
- source_sha256: `306b0c255167a33f4dbca120703f16e6d35724b177e7e46035c0a9cfd9fd3670`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T02:00+00:00, close=75713.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T02:00+00:00, close=75713.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.142820|-7.78|-38.48|-7.77|9550872|1.40|
|ONE_USDT|0.001959|-2.94|66.85|-2.93|26458657|0.51|
|ENA_USDT|0.155770|-2.79|-19.71|-2.78|27502059|0.64|
|PUMPFUN_USDT|0.003638|-2.77|-13.00|-2.76|17127852|2.75|
|QNT_USDT|194.030000|-2.55|-3.49|-2.54|42581535|1.03|
|ZEC_USDT|1248.750000|-1.79|-2.78|-1.78|1779807172|0.08|
|PEPE_USDT|0.000005|-1.66|-2.74|-1.65|38049421|0.21|
|WLD_USDT|0.330900|-1.63|-18.17|-1.62|25287921|3.02|
|ADA_USDT|0.179900|-1.47|-7.07|-1.46|11257374|5.56|
|LINK_USDT|10.768000|-1.25|-6.93|-1.24|73028265|1.86|
|SUI_USDT|0.850800|-1.16|-5.67|-1.15|23258137|1.18|
|TAO_USDT|221.230000|-1.16|-6.86|-1.15|21856735|1.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.179900|0.179800|0.179900|0.26|N|Y/Y|Y/Y|Y|N|
|AIN_USDT|0.142820|0.142090|0.142820|1.54|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.155770|0.155920|0.155770|1.97|Y|Y/Y|Y/Y|Y|Y|
|LINK_USDT|10.768000|10.765000|10.768000|0.53|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001959|0.002010|0.001959|0.80|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.53|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003638|0.003637|0.003638|0.28|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.030000|194.080000|194.030000|0.73|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.850800|0.850000|0.850800|0.19|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|221.230000|221.110000|221.230000|0.61|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.330900|0.330100|0.330900|0.17|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1248.750000|1246.710000|1248.750000|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.181800, depth_time=2026-11-08T02:00:27+00:00, book20_bid_proxy_usdt=10006167, book20_ask_proxy_usdt=9595060, funding_indicative=-0.000107, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=11257374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AIN_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.146520, depth_time=2026-11-08T02:00:07+00:00, book20_bid_proxy_usdt=6530, book20_ask_proxy_usdt=16330, funding_indicative=0.000244, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.78%, turnover=9550872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.159120, depth_time=2026-11-08T02:00:11+00:00, book20_bid_proxy_usdt=197406, book20_ask_proxy_usdt=295023, funding_indicative=-0.000095, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=27502059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=10.838000, depth_time=2026-11-08T02:00:30+00:00, book20_bid_proxy_usdt=662524, book20_ask_proxy_usdt=298943, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=73028265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.002162, depth_time=2026-11-08T02:00:10+00:00, book20_bid_proxy_usdt=10838, book20_ask_proxy_usdt=17009, funding_indicative=-0.000073, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=26458657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.000005, depth_time=2026-11-08T02:00:22+00:00, book20_bid_proxy_usdt=47835, book20_ask_proxy_usdt=35109, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=38049421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.003722, depth_time=2026-11-08T02:00:12+00:00, book20_bid_proxy_usdt=2476864, book20_ask_proxy_usdt=2481956, funding_indicative=-0.000090, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=17127852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=196.770000, depth_time=2026-11-08T02:00:17+00:00, book20_bid_proxy_usdt=66633, book20_ask_proxy_usdt=118961, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=42581535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.857400, depth_time=2026-11-08T02:00:31+00:00, book20_bid_proxy_usdt=1735917, book20_ask_proxy_usdt=1157132, funding_indicative=-0.000007, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=23258137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=223.440000, depth_time=2026-11-08T02:00:35+00:00, book20_bid_proxy_usdt=126432, book20_ask_proxy_usdt=185844, funding_indicative=0.000050, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=21856735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=0.335400, depth_time=2026-11-08T02:00:25+00:00, book20_bid_proxy_usdt=3684544, book20_ask_proxy_usdt=4034104, funding_indicative=-0.000113, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=25287921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T02:00:00+00:00, last15m_closed_end=2026-11-08T02:00+00:00, prior8high=1263.230000, depth_time=2026-11-08T02:00:19+00:00, book20_bid_proxy_usdt=108928, book20_ask_proxy_usdt=858614, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=1779807172. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
