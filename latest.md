# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T11:30:38Z**
- feed_generated_utc: 2026-11-09T11:30:40+00:00
- source_sha256: `360c5b1e8743e269539ec950df3107d579657cada653e265d7eeb2a14820060b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T11:30+00:00, close=74447.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T11:00+00:00, close=74125.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001524|-22.18|30.83|-20.10|6637198|1.31|
|JCT_USDT|0.008845|-10.05|77.64|-7.97|71192248|5.64|
|ASTER_USDT|0.632400|-6.97|-9.57|-4.89|5580377|1.58|
|XRP_USDT|1.086500|-5.99|-13.07|-3.91|275866900|0.92|
|ETH_USDT|2118.190000|-5.48|-6.51|-3.40|1561070350|0.05|
|TRUMPOFFICIAL_USDT|1.128000|-5.13|-34.26|-3.05|6466252|8.86|
|HYPE_USDT|73.532000|-5.03|-16.14|-2.95|48807921|0.14|
|NEAR_USDT|3.519000|-4.91|-18.74|-2.83|45832076|2.84|
|ZEC_USDT|1214.500000|-4.42|-1.89|-2.34|2309491934|0.08|
|SOL_USDT|86.490000|-3.55|-8.72|-1.47|718206608|1.16|
|XLM_USDT|0.146110|-3.37|-13.21|-1.29|28024773|0.68|
|DOT_USDT|0.861700|-3.27|-9.00|-1.19|10381359|1.16|
|LIT_USDT|3.092000|-3.17|-4.27|-1.09|13424088|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.632400|0.623900|0.632400|1.61|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.861700|0.854600|0.861400|0.54|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2118.190000|2098.500000|2118.000000|2.65|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.532000|72.747000|73.532000|4.31|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008845|0.008581|0.008803|0.65|N|N/Y|N/N|Y|N|
|LIT_USDT|3.092000|3.083700|3.094000|2.43|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.519000|3.480000|3.518000|1.74|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001524|0.001531|0.001524|1.24|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.490000|85.770000|86.510000|2.43|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.128000|1.124000|1.128000|1.65|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.146110|0.145030|0.146130|1.46|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.086500|1.076200|1.086200|1.44|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1214.500000|1192.400000|1213.930000|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=0.635000, depth_time=2026-11-09T11:30:12+00:00, book20_bid_proxy_usdt=819866, book20_ask_proxy_usdt=638781, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=5580377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=0.872200, depth_time=2026-11-09T11:30:31+00:00, book20_bid_proxy_usdt=380498, book20_ask_proxy_usdt=1222591, funding_indicative=0.000073, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=10381359. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=2119.350000, depth_time=2026-11-09T11:30:17+00:00, book20_bid_proxy_usdt=4248192, book20_ask_proxy_usdt=2524363, funding_indicative=-0.000033, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.48%, turnover=1561070350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=73.882000, depth_time=2026-11-09T11:30:22+00:00, book20_bid_proxy_usdt=153440, book20_ask_proxy_usdt=42425, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=48807921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=0.009792, depth_time=2026-11-09T11:30:10+00:00, book20_bid_proxy_usdt=46800, book20_ask_proxy_usdt=61359, funding_indicative=0.001331, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.05%, turnover=71192248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=3.127200, depth_time=2026-11-09T11:30:37+00:00, book20_bid_proxy_usdt=21132, book20_ask_proxy_usdt=21220, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=13424088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=3.567000, depth_time=2026-11-09T11:30:24+00:00, book20_bid_proxy_usdt=1668748, book20_ask_proxy_usdt=2026529, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=45832076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=0.001610, depth_time=2026-11-09T11:30:06+00:00, book20_bid_proxy_usdt=31090, book20_ask_proxy_usdt=4173, funding_indicative=-0.000023, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.18%, turnover=6637198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=86.940000, depth_time=2026-11-09T11:30:29+00:00, book20_bid_proxy_usdt=19627157, book20_ask_proxy_usdt=14871056, funding_indicative=0.000023, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=718206608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=1.148000, depth_time=2026-11-09T11:30:19+00:00, book20_bid_proxy_usdt=2629319, book20_ask_proxy_usdt=2532912, funding_indicative=0.000023, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=6466252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=0.146650, depth_time=2026-11-09T11:30:32+00:00, book20_bid_proxy_usdt=80548, book20_ask_proxy_usdt=171566, funding_indicative=-0.000027, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=28024773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=1.096500, depth_time=2026-11-09T11:30:15+00:00, book20_bid_proxy_usdt=3478490, book20_ask_proxy_usdt=3453762, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.99%, turnover=275866900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T11:30:02+00:00, last15m_closed_end=2026-11-09T11:30+00:00, prior8high=1225.900000, depth_time=2026-11-09T11:30:27+00:00, book20_bid_proxy_usdt=322468, book20_ask_proxy_usdt=185895, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.42%, turnover=2309491934. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
