# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T05:30:41Z**
- feed_generated_utc: 2026-10-13T05:30:45+00:00
- source_sha256: `7142f3052880e0a76ebce7844d046ff48a0d6df673abb9342d76f6c541555ee4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T05:30+00:00, close=83700.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T05:00+00:00, close=83419.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.019485|-19.01|37.77|-20.24|35298150|8.73|
|DOS_USDT|0.236500|-18.30|11.03|-19.53|9274405|8.45|
|ZRO_USDT|2.142600|-5.23|4.74|-6.46|30474440|0.47|
|LIT_USDT|3.466800|-4.36|-8.81|-5.59|11234134|0.29|
|PUMPFUN_USDT|0.005087|-4.18|-19.70|-5.41|32751856|1.97|
|ENA_USDT|0.213620|-3.63|-13.01|-4.86|69947855|0.94|
|ICP_USDT|3.188000|-3.24|-8.02|-4.47|16501131|3.14|
|RLC_USDT|0.958700|-3.02|74.94|-4.25|7216764|3.13|
|STRK_USDT|0.088210|-2.71|69.27|-3.94|65122297|1.14|
|HBAR_USDT|0.088080|-2.67|-12.53|-3.90|22119700|1.14|
|SEI_USDT|0.064660|-2.57|-10.08|-3.80|9541183|3.09|
|HYPE_USDT|82.737000|-1.93|-10.69|-3.16|86072953|0.12|
|USELESS_USDT|0.178100|-1.92|-21.45|-3.15|6891154|1.12|
|JUP_USDT|0.337000|-1.72|-0.26|-2.95|9018429|2.97|
|PONS_USDT|0.290300|-1.49|-24.30|-2.72|6346180|6.89|
|BR_USDT|0.439700|0.00|13.39|-1.23|6186841|2.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.236500|0.231400|0.236500|0.75|N|Y/Y|Y/N|N|N|
|ENA_USDT|0.213620|0.208270|0.213620|0.91|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.088080|0.086850|0.088080|1.16|N|Y/Y|Y/Y|N|N|
|HYPE_USDT|82.737000|82.095000|82.737000|0.93|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.188000|3.107000|3.188000|1.48|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.337000|0.332400|0.337000|1.57|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.466800|3.396200|3.466800|0.29|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.290300|0.278200|0.290300|1.72|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005087|0.004996|0.005087|0.64|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.958700|0.939400|0.958500|1.37|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.064660|0.062710|0.064660|0.78|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.088210|0.082550|0.088210|0.38|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.178100|0.171150|0.178100|1.22|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019485|0.018531|0.019485|0.70|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.142600|2.098900|2.142600|1.79|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.251000, depth_time=2026-10-13T05:30:10+00:00, book20_bid_proxy_usdt=61952, book20_ask_proxy_usdt=82403, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.30%, turnover=9274405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.214000, depth_time=2026-10-13T05:30:20+00:00, book20_bid_proxy_usdt=82483, book20_ask_proxy_usdt=113404, funding_indicative=-0.000031, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=69947855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.088290, depth_time=2026-10-13T05:30:29+00:00, book20_bid_proxy_usdt=499856, book20_ask_proxy_usdt=616287, funding_indicative=0.000006, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=22119700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=83.024000, depth_time=2026-10-13T05:30:34+00:00, book20_bid_proxy_usdt=62144, book20_ask_proxy_usdt=195708, funding_indicative=0.000007, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=86072953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=3.199000, depth_time=2026-10-13T05:30:21+00:00, book20_bid_proxy_usdt=812652, book20_ask_proxy_usdt=738774, funding_indicative=-0.000058, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=16501131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T05:30:01+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.337300, depth_time=2026-10-13T05:30:38+00:00, book20_bid_proxy_usdt=722792, book20_ask_proxy_usdt=450590, funding_indicative=-0.000052, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=9018429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T05:30:01+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=3.472500, depth_time=2026-10-13T05:30:14+00:00, book20_bid_proxy_usdt=25952, book20_ask_proxy_usdt=31869, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=11234134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T05:30:01+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.287200, depth_time=2026-10-13T05:30:40+00:00, book20_bid_proxy_usdt=209283, book20_ask_proxy_usdt=236472, funding_indicative=0.000071, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=6346180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.005098, depth_time=2026-10-13T05:30:17+00:00, book20_bid_proxy_usdt=1367251, book20_ask_proxy_usdt=1488738, funding_indicative=0.000011, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.18%, turnover=32751856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T05:30:01+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.964800, depth_time=2026-10-13T05:30:24+00:00, book20_bid_proxy_usdt=90737, book20_ask_proxy_usdt=50034, funding_indicative=-0.000485, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=7216764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T05:30:01+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.064350, depth_time=2026-10-13T05:30:31+00:00, book20_bid_proxy_usdt=187735, book20_ask_proxy_usdt=193657, funding_indicative=-0.000069, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=9541183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.089670, depth_time=2026-10-13T05:30:27+00:00, book20_bid_proxy_usdt=146160, book20_ask_proxy_usdt=145316, funding_indicative=0.000028, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=65122297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T05:30:01+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.178460, depth_time=2026-10-13T05:30:36+00:00, book20_bid_proxy_usdt=50476, book20_ask_proxy_usdt=18297, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=6891154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=0.019485, depth_time=2026-10-13T05:30:05+00:00, book20_bid_proxy_usdt=23722, book20_ask_proxy_usdt=16420, funding_indicative=-0.000452, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.01%, turnover=35298150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T05:30:00+00:00, last15m_closed_end=2026-10-13T05:30+00:00, prior8high=2.138500, depth_time=2026-10-13T05:30:12+00:00, book20_bid_proxy_usdt=44790, book20_ask_proxy_usdt=26245, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.23%, turnover=30474440. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
