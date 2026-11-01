# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T04:15:31Z**
- feed_generated_utc: 2026-11-01T04:15:33+00:00
- source_sha256: `5acd438e5e1887b36ed7be16ef35eb83d2f0a35260ab7b50a0cda06fd0f29fd2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T04:15+00:00, close=77711, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.232660|-21.44|38.55|-21.63|30003227|1.29|
|BLESS_USDT|0.009646|-8.68|18.89|-8.87|6823796|4.15|
|ENA_USDT|0.187520|-3.34|0.39|-3.53|42394648|0.53|
|ZEC_USDT|1242.650000|-3.26|8.50|-3.45|962887211|0.08|
|XLM_USDT|0.168350|-1.97|-0.03|-2.16|20219793|0.59|
|BTW_USDT|1.102000|-1.77|-36.71|-1.96|5190609|1.81|
|TRX_USDT|0.307960|-1.39|-6.37|-1.58|10807689|0.33|
|FARTCOIN_USDT|0.120560|-1.17|-1.16|-1.36|6348355|0.83|
|TAO_USDT|235.040000|-1.05|-4.29|-1.24|22453928|0.42|
|ONDO_USDT|0.408800|-0.87|1.84|-1.06|21992558|2.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009646|0.009219|0.009646|0.95|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.102000|1.091400|1.102000|0.70|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187520|0.186020|0.187520|2.83|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120560|0.119750|0.120560|0.76|N|N/Y|Y/Y|Y|N|
|LSK_USDT|0.232660|0.226590|0.232660|0.93|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.408800|0.407900|0.408800|1.27|N|N/Y|N/N|Y|N|
|TAO_USDT|235.040000|235.280000|235.100000|1.64|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.307960|0.307340|0.307960|0.19|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168350|0.167510|0.168350|2.70|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1242.650000|1238.980000|1242.730000|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.009584, depth_time=2026-11-01T04:15:11+00:00, book20_bid_proxy_usdt=20274, book20_ask_proxy_usdt=9135, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.68%, turnover=6823796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=1.139700, depth_time=2026-11-01T04:15:20+00:00, book20_bid_proxy_usdt=11253, book20_ask_proxy_usdt=13040, funding_indicative=-0.000093, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=5190609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.189350, depth_time=2026-11-01T04:15:12+00:00, book20_bid_proxy_usdt=56178, book20_ask_proxy_usdt=265337, funding_indicative=0.000005, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=42394648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T04:15:00+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.121430, depth_time=2026-11-01T04:15:23+00:00, book20_bid_proxy_usdt=84147, book20_ask_proxy_usdt=84995, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=6348355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.236500, depth_time=2026-11-01T04:15:08+00:00, book20_bid_proxy_usdt=6603, book20_ask_proxy_usdt=9972, funding_indicative=-0.000687, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-21.44%, turnover=30003227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.412300, depth_time=2026-11-01T04:15:30+00:00, book20_bid_proxy_usdt=2664292, book20_ask_proxy_usdt=2652367, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=21992558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=237.740000, depth_time=2026-11-01T04:15:28+00:00, book20_bid_proxy_usdt=125298, book20_ask_proxy_usdt=192531, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=22453928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.309960, depth_time=2026-11-01T04:15:20+00:00, book20_bid_proxy_usdt=118340, book20_ask_proxy_usdt=85183, funding_indicative=-0.001215, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=10807689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=0.169340, depth_time=2026-11-01T04:15:17+00:00, book20_bid_proxy_usdt=171902, book20_ask_proxy_usdt=195304, funding_indicative=0.000006, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=20219793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T04:14:59+00:00, last15m_closed_end=2026-11-01T04:15+00:00, prior8high=1260.940000, depth_time=2026-11-01T04:15:14+00:00, book20_bid_proxy_usdt=634716, book20_ask_proxy_usdt=698910, funding_indicative=-0.000119, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=962887211. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
