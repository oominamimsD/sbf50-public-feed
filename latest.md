# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T23:30:27Z**
- feed_generated_utc: 2026-10-26T23:30:31+00:00
- source_sha256: `61d364099d45e4222e1312aaa95629abf95a82eaf1f1e224c98d1ba7f3588f20`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T23:30+00:00, close=80042.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T23:00+00:00, close=79977.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.623300|-4.90|-14.65|-4.46|5372187|0.62|
|QNT_USDT|201.770000|-4.04|3.10|-3.60|119008466|0.50|
|LIT_USDT|3.009300|-3.49|-0.74|-3.05|5094655|0.33|
|BR_USDT|0.483800|-3.14|-21.46|-2.70|10290761|2.06|
|NEAR_USDT|4.483000|-1.96|-8.58|-1.52|113996388|2.23|
|PEPE_USDT|0.000004|-1.80|4.24|-1.36|80154738|0.23|
|LINK_USDT|11.347000|-1.57|-4.99|-1.13|99848995|1.76|
|ARB_USDT|0.167360|-1.54|-14.45|-1.10|20357303|0.60|
|FILECOIN_USDT|0.907000|-1.48|-10.37|-1.04|6482173|1.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167360|0.165690|0.167360|1.02|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.483800|0.473800|0.483800|0.54|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|0.907000|0.894100|0.907000|1.26|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.347000|11.242000|11.346000|0.71|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.009300|2.972000|3.009300|0.54|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.483000|4.422000|4.483000|1.24|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.54|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.770000|200.530000|201.770000|0.84|N|Y/N|N/N|Y|N|
|ZRO_USDT|1.623300|1.609100|1.623300|0.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T23:30:01+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=0.168330, depth_time=2026-10-26T23:30:24+00:00, book20_bid_proxy_usdt=77619, book20_ask_proxy_usdt=117279, funding_indicative=-0.000016, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=20357303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T23:30:01+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=0.487600, depth_time=2026-10-26T23:30:15+00:00, book20_bid_proxy_usdt=43654, book20_ask_proxy_usdt=36979, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=10290761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T23:30:01+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=0.909400, depth_time=2026-10-26T23:30:25+00:00, book20_bid_proxy_usdt=949030, book20_ask_proxy_usdt=1307516, funding_indicative=0.000084, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=6482173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T23:30:01+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=11.397000, depth_time=2026-10-26T23:30:22+00:00, book20_bid_proxy_usdt=432303, book20_ask_proxy_usdt=539053, funding_indicative=0.000095, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=99848995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T23:30:01+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=3.013800, depth_time=2026-10-26T23:30:11+00:00, book20_bid_proxy_usdt=19166, book20_ask_proxy_usdt=21489, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.49%, turnover=5094655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T23:30:00+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=4.492000, depth_time=2026-10-26T23:30:17+00:00, book20_bid_proxy_usdt=3589173, book20_ask_proxy_usdt=4481286, funding_indicative=0.000051, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=113996388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T23:30:00+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=0.000004, depth_time=2026-10-26T23:30:19+00:00, book20_bid_proxy_usdt=76590, book20_ask_proxy_usdt=70967, funding_indicative=0.000081, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=80154738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T23:30:00+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=204.690000, depth_time=2026-10-26T23:30:10+00:00, book20_bid_proxy_usdt=53516, book20_ask_proxy_usdt=79399, funding_indicative=-0.000015, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=119008466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T23:30:01+00:00, last15m_closed_end=2026-10-26T23:30+00:00, prior8high=1.643300, depth_time=2026-10-26T23:30:06+00:00, book20_bid_proxy_usdt=24185, book20_ask_proxy_usdt=85288, funding_indicative=0.000005, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.90%, turnover=5372187. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
