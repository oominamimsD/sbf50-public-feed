# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T05:00:22Z**
- feed_generated_utc: 2026-10-20T05:00:25+00:00
- source_sha256: `4b6e40114fda25669d35d5f51038946e1e5d5f6ed4b4b088131a16cfbc50a41e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T05:00+00:00, close=82060.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T05:00+00:00, close=82060.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.306520|-8.05|-10.40|-8.22|5383639|2.61|
|Q_USDT|0.116108|-6.07|277.08|-6.24|11440618|1.38|
|BTW_USDT|1.808400|-5.46|2.99|-5.63|29225439|1.11|
|SAND_USDT|0.056950|-4.38|-8.27|-4.55|8593108|1.76|
|NEAR_USDT|4.801000|-2.10|-13.47|-2.27|165238158|2.08|
|TAO_USDT|266.840000|-1.19|-6.79|-1.36|51291308|1.12|
|QNT_USDT|195.360000|-1.09|-14.45|-1.26|79083796|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.808400|1.834200|1.808400|2.42|Y|Y/Y|Y/Y|N|Y|
|CT_USDT|0.306520|0.307850|0.306520|0.72|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.801000|4.807000|4.800000|0.97|N|Y/Y|Y/Y|N|N|
|QNT_USDT|195.360000|194.080000|195.360000|1.36|N|Y/N|N/Y|N|N|
|Q_USDT|0.116108|0.116151|0.116108|1.71|Y|Y/Y|N/N|N|N|
|SAND_USDT|0.056950|0.057430|0.056950|0.78|N|Y/Y|Y/Y|N|N|
|TAO_USDT|266.840000|266.450000|266.840000|0.66|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=1.963100, depth_time=2026-10-20T05:00:12+00:00, book20_bid_proxy_usdt=10624, book20_ask_proxy_usdt=14966, funding_indicative=-0.003237, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.46%, turnover=29225439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=0.338440, depth_time=2026-10-20T05:00:07+00:00, book20_bid_proxy_usdt=6733, book20_ask_proxy_usdt=9766, funding_indicative=-0.002771, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.05%, turnover=5383639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=4.884000, depth_time=2026-10-20T05:00:16+00:00, book20_bid_proxy_usdt=4227501, book20_ask_proxy_usdt=3816086, funding_indicative=0.000026, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=165238158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=198.680000, depth_time=2026-10-20T05:00:22+00:00, book20_bid_proxy_usdt=72229, book20_ask_proxy_usdt=74278, funding_indicative=0.000006, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=79083796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=0.125191, depth_time=2026-10-20T05:00:10+00:00, book20_bid_proxy_usdt=24233, book20_ask_proxy_usdt=18189, funding_indicative=-0.000161, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.07%, turnover=11440618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=0.058600, depth_time=2026-10-20T05:00:14+00:00, book20_bid_proxy_usdt=663251, book20_ask_proxy_usdt=841790, funding_indicative=-0.001915, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.38%, turnover=8593108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T05:00:01+00:00, last15m_closed_end=2026-10-20T05:00+00:00, prior8high=269.360000, depth_time=2026-10-20T05:00:19+00:00, book20_bid_proxy_usdt=59464, book20_ask_proxy_usdt=188837, funding_indicative=0.000042, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=51291308. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
