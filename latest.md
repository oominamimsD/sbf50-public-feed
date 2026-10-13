# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T08:15:36Z**
- feed_generated_utc: 2026-10-13T08:15:39+00:00
- source_sha256: `79282366f25432dba628da659d055461e1f3ab775bb6657bfd0b77ac1b4cad6c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T08:15+00:00, close=84130.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.228500|-21.07|7.27|-22.82|9385596|8.75|
|W_USDT|0.019448|-19.16|37.50|-20.91|30379815|6.67|
|NEAR_USDT|5.230000|-5.74|4.14|-7.49|270298201|1.91|
|RLC_USDT|0.933200|-5.60|70.29|-7.35|6696331|2.14|
|ZRO_USDT|2.147100|-5.03|4.96|-6.78|25419937|0.47|
|LIT_USDT|3.443300|-5.01|-9.43|-6.76|10224185|0.29|
|STRK_USDT|0.087260|-3.76|67.45|-5.51|61575033|2.30|
|PUMPFUN_USDT|0.005115|-3.65|-19.25|-5.40|31872442|5.87|
|JUP_USDT|0.335200|-2.24|-0.79|-3.99|8621323|2.98|
|PONS_USDT|0.290500|-1.42|-24.25|-3.17|6154926|3.44|
|QNT_USDT|225.620000|-1.20|-12.13|-2.95|76117922|0.44|
|GRASS_USDT|0.751100|0.54|6.50|-1.21|6475041|3.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.228500|0.226500|0.228500|0.99|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.751100|0.752000|0.751100|2.71|Y|Y/Y|N/N|N|N|
|JUP_USDT|0.335200|0.334000|0.335200|1.56|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.443300|3.407500|3.443300|1.93|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.230000|5.151000|5.230000|0.40|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.290500|0.287500|0.290600|0.49|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005115|0.005044|0.005115|0.65|N|Y/Y|Y/Y|N|N|
|QNT_USDT|225.620000|227.080000|225.620000|1.64|Y|Y/Y|Y/Y|N|Y|
|RLC_USDT|0.933200|0.917000|0.933200|1.20|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087260|0.083010|0.087260|2.53|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019448|0.019044|0.019448|0.76|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.147100|2.075100|2.147100|1.37|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.235200, depth_time=2026-10-13T08:15:08+00:00, book20_bid_proxy_usdt=44375, book20_ask_proxy_usdt=82678, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.07%, turnover=9385596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.794800, depth_time=2026-10-13T08:15:33+00:00, book20_bid_proxy_usdt=121922, book20_ask_proxy_usdt=104764, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=0.54%, turnover=6475041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T08:15:02+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.339200, depth_time=2026-10-13T08:15:27+00:00, book20_bid_proxy_usdt=703078, book20_ask_proxy_usdt=533914, funding_indicative=-0.000011, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=8621323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T08:15:02+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=3.465900, depth_time=2026-10-13T08:15:21+00:00, book20_bid_proxy_usdt=28653, book20_ask_proxy_usdt=27366, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.01%, turnover=10224185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=5.340000, depth_time=2026-10-13T08:15:13+00:00, book20_bid_proxy_usdt=3350517, book20_ask_proxy_usdt=2889320, funding_indicative=-0.000008, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.74%, turnover=270298201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.295200, depth_time=2026-10-13T08:15:30+00:00, book20_bid_proxy_usdt=226242, book20_ask_proxy_usdt=216211, funding_indicative=0.000059, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=6154926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.005142, depth_time=2026-10-13T08:15:24+00:00, book20_bid_proxy_usdt=1479272, book20_ask_proxy_usdt=1295152, funding_indicative=-0.000001, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=31872442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=231.170000, depth_time=2026-10-13T08:15:33+00:00, book20_bid_proxy_usdt=77582, book20_ask_proxy_usdt=63332, funding_indicative=0.000053, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=76117922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.963200, depth_time=2026-10-13T08:15:16+00:00, book20_bid_proxy_usdt=35707, book20_ask_proxy_usdt=46856, funding_indicative=-0.000917, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.60%, turnover=6696331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.088100, depth_time=2026-10-13T08:15:23+00:00, book20_bid_proxy_usdt=202592, book20_ask_proxy_usdt=159757, funding_indicative=0.000009, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.76%, turnover=61575033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=0.019841, depth_time=2026-10-13T08:15:11+00:00, book20_bid_proxy_usdt=39336, book20_ask_proxy_usdt=11584, funding_indicative=-0.000520, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.16%, turnover=30379815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T08:15:01+00:00, last15m_closed_end=2026-10-13T08:15+00:00, prior8high=2.157300, depth_time=2026-10-13T08:15:19+00:00, book20_bid_proxy_usdt=36899, book20_ask_proxy_usdt=34092, funding_indicative=-0.000032, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=25419937. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
