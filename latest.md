# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T04:45:42Z**
- feed_generated_utc: 2026-10-13T04:45:45+00:00
- source_sha256: `525989b7c833435bdf96741a1fec4b3d9ae02e47ad0f5cbdfdbcdcbeb31b112f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T04:45+00:00, close=83428, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.019120|-20.53|35.19|-21.43|37561654|9.41|
|DOS_USDT|0.247800|-14.40|16.33|-15.30|9210196|8.07|
|ZRO_USDT|2.115100|-6.45|3.39|-7.35|31561621|0.95|
|LIT_USDT|3.456800|-4.64|-9.08|-5.54|11455030|0.29|
|PUMPFUN_USDT|0.005070|-4.50|-19.96|-5.40|33257283|1.97|
|DOT_USDT|1.182300|-4.37|-0.97|-5.27|24809792|0.85|
|PONS_USDT|0.282400|-4.17|-26.36|-5.07|6468159|3.54|
|RLC_USDT|0.947800|-4.12|72.95|-5.02|7584325|4.22|
|ZEC_USDT|1213.050000|-4.09|-6.31|-4.99|1746286660|0.08|
|ENA_USDT|0.212640|-4.07|-13.40|-4.97|73730757|0.47|
|NEAR_USDT|5.333000|-3.89|6.19|-4.79|288480018|1.88|
|SEI_USDT|0.063790|-3.88|-11.29|-4.78|11044039|1.57|
|ICP_USDT|3.181000|-3.45|-8.22|-4.35|16315802|3.14|
|HBAR_USDT|0.087700|-3.09|-12.90|-3.99|21998844|1.14|
|STRK_USDT|0.088320|-2.59|69.48|-3.49|67316749|1.13|
|FET_USDT|0.216100|-2.43|-13.31|-3.33|22168379|4.63|
|USELESS_USDT|0.177290|-2.37|-21.81|-3.27|6975261|0.56|
|JUP_USDT|0.335500|-2.15|-0.71|-3.05|9057216|2.98|
|HYPE_USDT|82.636000|-2.05|-10.80|-2.95|86648802|0.12|
|QNT_USDT|227.110000|-0.55|-11.55|-1.45|80420268|0.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.247800|0.227600|0.247700|0.89|N|Y/Y|Y/N|N|N|
|DOT_USDT|1.182300|1.146700|1.182500|1.94|N|Y/Y|Y/Y|N|N|
|ENA_USDT|0.212640|0.206190|0.212640|1.07|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.087700|0.086760|0.087700|0.53|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.181000|3.076000|3.181000|2.02|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.456800|3.303200|3.456800|0.18|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.333000|5.193000|5.333000|0.74|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.282400|0.275000|0.282400|0.38|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005070|0.004936|0.005070|0.88|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.947800|0.939400|0.947800|0.58|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.063790|0.062310|0.063790|0.67|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.088320|0.082550|0.088320|1.08|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019120|0.018313|0.019123|0.64|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1213.050000|1190.170000|1213.500000|0.76|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.115100|2.051800|2.114200|0.54|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.244500, depth_time=2026-10-13T04:45:10+00:00, book20_bid_proxy_usdt=56612, book20_ask_proxy_usdt=40097, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.40%, turnover=9210196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=1.185100, depth_time=2026-10-13T04:45:19+00:00, book20_bid_proxy_usdt=334328, book20_ask_proxy_usdt=205091, funding_indicative=0.000092, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=24809792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.212630, depth_time=2026-10-13T04:45:28+00:00, book20_bid_proxy_usdt=116318, book20_ask_proxy_usdt=71896, funding_indicative=-0.000037, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.07%, turnover=73730757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.087920, depth_time=2026-10-13T04:45:39+00:00, book20_bid_proxy_usdt=462803, book20_ask_proxy_usdt=665078, funding_indicative=0.000004, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=21998844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=3.175000, depth_time=2026-10-13T04:45:35+00:00, book20_bid_proxy_usdt=699550, book20_ask_proxy_usdt=850337, funding_indicative=-0.000040, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=16315802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=3.460700, depth_time=2026-10-13T04:45:13+00:00, book20_bid_proxy_usdt=26833, book20_ask_proxy_usdt=23348, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=11455030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=5.351000, depth_time=2026-10-13T04:45:31+00:00, book20_bid_proxy_usdt=3338731, book20_ask_proxy_usdt=2092756, funding_indicative=-0.000057, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=288480018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.284500, depth_time=2026-10-13T04:45:20+00:00, book20_bid_proxy_usdt=219949, book20_ask_proxy_usdt=217827, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=6468159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.005084, depth_time=2026-10-13T04:45:16+00:00, book20_bid_proxy_usdt=1867185, book20_ask_proxy_usdt=1435790, funding_indicative=0.000005, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=33257283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.984900, depth_time=2026-10-13T04:45:23+00:00, book20_bid_proxy_usdt=53334, book20_ask_proxy_usdt=62266, funding_indicative=-0.000503, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=7584325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.063720, depth_time=2026-10-13T04:45:33+00:00, book20_bid_proxy_usdt=201650, book20_ask_proxy_usdt=184571, funding_indicative=-0.000088, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=11044039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.090150, depth_time=2026-10-13T04:45:41+00:00, book20_bid_proxy_usdt=171982, book20_ask_proxy_usdt=162968, funding_indicative=0.000020, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=67316749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=0.019910, depth_time=2026-10-13T04:45:08+00:00, book20_bid_proxy_usdt=27380, book20_ask_proxy_usdt=14391, funding_indicative=-0.000447, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.53%, turnover=37561654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=1218.100000, depth_time=2026-10-13T04:45:26+00:00, book20_bid_proxy_usdt=274395, book20_ask_proxy_usdt=307358, funding_indicative=0.000011, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=1746286660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T04:45:01+00:00, last15m_closed_end=2026-10-13T04:45+00:00, prior8high=2.133900, depth_time=2026-10-13T04:45:12+00:00, book20_bid_proxy_usdt=75430, book20_ask_proxy_usdt=48356, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.45%, turnover=31561621. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
