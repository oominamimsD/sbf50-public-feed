# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T07:15:35Z**
- feed_generated_utc: 2026-10-13T07:15:38+00:00
- source_sha256: `2934a59e4a6e9227d504eb0d8806c4789663901afaa14cb811c769905502552b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T07:15+00:00, close=83721.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T07:00+00:00, close=83732.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.231700|-19.96|8.77|-21.21|9326483|4.32|
|W_USDT|0.019498|-18.96|37.86|-20.21|32568156|9.75|
|ZRO_USDT|2.090000|-7.56|2.17|-8.81|27717565|0.48|
|STRK_USDT|0.085140|-6.09|63.38|-7.34|62437342|1.18|
|NEAR_USDT|5.247000|-5.44|4.48|-6.69|272944868|1.91|
|LIT_USDT|3.443900|-5.00|-9.42|-6.25|10330161|0.29|
|PUMPFUN_USDT|0.005080|-4.31|-19.81|-5.56|31283230|1.97|
|RLC_USDT|0.947300|-4.17|72.86|-5.42|6668682|1.05|
|HBAR_USDT|0.087770|-3.01|-12.84|-4.26|22266157|1.14|
|USELESS_USDT|0.177650|-2.17|-21.65|-3.42|6419738|1.69|
|JUP_USDT|0.335900|-2.04|-0.59|-3.29|8549801|2.98|
|PONS_USDT|0.290400|-1.45|-24.27|-2.70|6230342|3.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.231700|0.227700|0.231700|1.02|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.087770|0.087550|0.087770|2.29|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.335900|0.335300|0.336000|1.18|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.443900|3.407500|3.443900|4.06|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.247000|5.280000|5.245000|2.14|Y|Y/Y|Y/Y|N|Y|
|PONS_USDT|0.290400|0.283300|0.290400|1.66|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005080|0.005057|0.005080|1.55|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.947300|0.950100|0.948100|2.02|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.085140|0.085720|0.085140|1.72|Y|Y/Y|Y/Y|N|Y|
|USELESS_USDT|0.177650|0.176460|0.177650|1.28|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019498|0.019044|0.019498|0.97|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.090000|2.087100|2.089700|0.56|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.247400, depth_time=2026-10-13T07:15:07+00:00, book20_bid_proxy_usdt=69399, book20_ask_proxy_usdt=68425, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.96%, turnover=9326483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.088580, depth_time=2026-10-13T07:15:27+00:00, book20_bid_proxy_usdt=470925, book20_ask_proxy_usdt=709615, funding_indicative=-0.000014, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=22266157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.339200, depth_time=2026-10-13T07:15:32+00:00, book20_bid_proxy_usdt=532289, book20_ask_proxy_usdt=471650, funding_indicative=-0.000010, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=8549801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=3.476600, depth_time=2026-10-13T07:15:19+00:00, book20_bid_proxy_usdt=23213, book20_ask_proxy_usdt=50445, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.00%, turnover=10330161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=5.363000, depth_time=2026-10-13T07:15:18+00:00, book20_bid_proxy_usdt=3747593, book20_ask_proxy_usdt=3668956, funding_indicative=-0.000077, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.44%, turnover=272944868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.291800, depth_time=2026-10-13T07:15:34+00:00, book20_bid_proxy_usdt=228816, book20_ask_proxy_usdt=210174, funding_indicative=0.000070, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=6230342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.005124, depth_time=2026-10-13T07:15:22+00:00, book20_bid_proxy_usdt=1351736, book20_ask_proxy_usdt=1853796, funding_indicative=0.000016, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=31283230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.964300, depth_time=2026-10-13T07:15:24+00:00, book20_bid_proxy_usdt=49886, book20_ask_proxy_usdt=65256, funding_indicative=-0.000653, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=6668682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.088540, depth_time=2026-10-13T07:15:16+00:00, book20_bid_proxy_usdt=157977, book20_ask_proxy_usdt=200839, funding_indicative=0.000013, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.09%, turnover=62437342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.179420, depth_time=2026-10-13T07:15:29+00:00, book20_bid_proxy_usdt=25622, book20_ask_proxy_usdt=33426, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=6419738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=0.019841, depth_time=2026-10-13T07:15:11+00:00, book20_bid_proxy_usdt=35171, book20_ask_proxy_usdt=16323, funding_indicative=-0.000502, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.96%, turnover=32568156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T07:15:01+00:00, last15m_closed_end=2026-10-13T07:15+00:00, prior8high=2.149200, depth_time=2026-10-13T07:15:13+00:00, book20_bid_proxy_usdt=35697, book20_ask_proxy_usdt=99313, funding_indicative=-0.000004, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.56%, turnover=27717565. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
