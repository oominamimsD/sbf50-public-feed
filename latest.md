# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T07:30:30Z**
- feed_generated_utc: 2026-11-08T07:30:31+00:00
- source_sha256: `0f92eb76adbc80c3cca49eb1fe4a9491b92cd688bd1ef21e651aaf9e5a6189ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T07:30+00:00, close=75820.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T07:00+00:00, close=75801.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005197|-13.13|-53.33|-13.25|37711763|1.92|
|ONE_USDT|0.001979|-2.82|68.55|-2.94|26226973|0.51|
|ENA_USDT|0.154220|-2.50|-20.50|-2.62|29256302|2.59|
|TIA_USDT|0.431000|-2.40|-12.05|-2.52|7767546|2.32|
|QNT_USDT|195.090000|-1.89|-2.96|-2.01|45586722|0.51|
|WLD_USDT|0.329800|-1.72|-18.44|-1.84|23655107|3.03|
|AAVE_USDT|130.390000|-1.39|-3.77|-1.51|10680595|0.77|
|ONDO_USDT|0.359100|-1.10|-12.92|-1.22|8595602|2.79|
|LINK_USDT|10.730000|-1.05|-7.26|-1.17|67110635|0.93|
|ADA_USDT|0.180000|-0.88|-7.02|-1.00|9688546|5.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.390000|129.910000|130.400000|0.47|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.180000|0.179600|0.180000|0.33|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005197|0.005067|0.005197|0.40|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.154220|0.153450|0.154220|0.84|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.730000|10.711000|10.729000|1.33|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359100|0.357600|0.359100|0.31|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001979|0.001900|0.001980|1.48|N|N/Y|N/N|Y|N|
|QNT_USDT|195.090000|194.160000|195.090000|0.51|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.431000|0.429800|0.431000|1.18|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.329800|0.328600|0.329800|2.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=131.110000, depth_time=2026-11-08T07:30:18+00:00, book20_bid_proxy_usdt=594364, book20_ask_proxy_usdt=370368, funding_indicative=0.000021, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=10680595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.180600, depth_time=2026-11-08T07:30:29+00:00, book20_bid_proxy_usdt=9611610, book20_ask_proxy_usdt=10719311, funding_indicative=0.000002, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=9688546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.005373, depth_time=2026-11-08T07:30:07+00:00, book20_bid_proxy_usdt=79669, book20_ask_proxy_usdt=53626, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.13%, turnover=37711763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.155160, depth_time=2026-11-08T07:30:08+00:00, book20_bid_proxy_usdt=286392, book20_ask_proxy_usdt=220581, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=29256302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=10.771000, depth_time=2026-11-08T07:30:19+00:00, book20_bid_proxy_usdt=377982, book20_ask_proxy_usdt=603388, funding_indicative=0.000070, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=67110635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.359600, depth_time=2026-11-08T07:30:24+00:00, book20_bid_proxy_usdt=1705374, book20_ask_proxy_usdt=1706994, funding_indicative=-0.000002, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=8595602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.002049, depth_time=2026-11-08T07:30:09+00:00, book20_bid_proxy_usdt=15557, book20_ask_proxy_usdt=12797, funding_indicative=-0.000548, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=26226973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=196.790000, depth_time=2026-11-08T07:30:16+00:00, book20_bid_proxy_usdt=74316, book20_ask_proxy_usdt=79002, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=45586722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.434500, depth_time=2026-11-08T07:30:13+00:00, book20_bid_proxy_usdt=289561, book20_ask_proxy_usdt=297239, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=7767546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T07:29:59+00:00, last15m_closed_end=2026-11-08T07:30+00:00, prior8high=0.332600, depth_time=2026-11-08T07:30:18+00:00, book20_bid_proxy_usdt=3629328, book20_ask_proxy_usdt=2937345, funding_indicative=-0.000134, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=23655107. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
