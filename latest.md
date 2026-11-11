# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T12:45:33Z**
- feed_generated_utc: 2026-11-11T12:45:35+00:00
- source_sha256: `44e9c4e70ae9d9c6958b5d88786c521bea8a0812e49d7e3fe89fab91432dc0a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T12:45+00:00, close=73935.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.173270|-30.95|28.84|-31.98|67912138|4.05|
|ONE_USDT|0.001535|-14.42|37.49|-15.45|8217453|0.65|
|AKE_USDT|0.002566|-11.94|-38.25|-12.97|8773436|3.89|
|ZEC_USDT|983.740000|-10.02|-18.28|-11.05|2181769193|0.10|
|BTW_USDT|1.084400|-9.52|2.40|-10.55|6079070|2.77|
|UNI_USDT|6.439000|-5.72|-12.43|-6.75|41362632|1.55|
|PEPE_USDT|0.000005|-5.50|1.42|-6.53|82638704|0.20|
|DASH_USDT|44.020000|-2.48|-4.59|-3.51|17063586|2.27|
|QNT_USDT|177.420000|-1.81|-9.21|-2.84|44121729|0.56|
|ARB_USDT|0.159550|-1.13|-0.20|-2.16|27339263|0.63|
|XAUT_USDT|4029.020000|0.00|2.52|-1.03|102445261|0.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002566|0.002465|0.002566|0.76|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159550|0.158170|0.159550|0.51|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.084400|1.070000|1.084400|0.62|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.020000|43.670000|44.020000|0.07|N|N/Y|Y/Y|Y|N|
|INIT_USDT|0.173270|0.170630|0.173270|1.09|N|Y/Y|Y/N|Y|N|
|ONE_USDT|0.001535|0.001528|0.001535|0.59|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.58|N|Y/Y|Y/N|Y|N|
|QNT_USDT|177.420000|177.240000|177.420000|1.29|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.439000|6.413000|6.439000|0.91|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4029.020000|4030.930000|4029.020000|0.67|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|983.740000|977.330000|982.900000|1.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=0.002570, depth_time=2026-11-11T12:45:11+00:00, book20_bid_proxy_usdt=52284, book20_ask_proxy_usdt=35750, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.94%, turnover=8773436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=0.161860, depth_time=2026-11-11T12:45:28+00:00, book20_bid_proxy_usdt=44176, book20_ask_proxy_usdt=98488, funding_indicative=-0.000154, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=27339263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=1.095300, depth_time=2026-11-11T12:45:15+00:00, book20_bid_proxy_usdt=16995, book20_ask_proxy_usdt=12256, funding_indicative=-0.000383, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.52%, turnover=6079070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=44.430000, depth_time=2026-11-11T12:45:21+00:00, book20_bid_proxy_usdt=703154, book20_ask_proxy_usdt=675698, funding_indicative=0.000014, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=17063586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=0.190750, depth_time=2026-11-11T12:45:07+00:00, book20_bid_proxy_usdt=179927, book20_ask_proxy_usdt=15351, funding_indicative=-0.002572, next_funding_utc=2026-11-11T13:00:00+00:00, funding_cycle_h=1, 24h_change=-30.95%, turnover=67912138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=0.001569, depth_time=2026-11-11T12:45:08+00:00, book20_bid_proxy_usdt=17391, book20_ask_proxy_usdt=16552, funding_indicative=-0.000595, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.42%, turnover=8217453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=0.000005, depth_time=2026-11-11T12:45:20+00:00, book20_bid_proxy_usdt=28073, book20_ask_proxy_usdt=45792, funding_indicative=-0.000202, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.50%, turnover=82638704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=179.750000, depth_time=2026-11-11T12:45:25+00:00, book20_bid_proxy_usdt=60507, book20_ask_proxy_usdt=69813, funding_indicative=-0.000143, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=44121729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=6.519000, depth_time=2026-11-11T12:45:14+00:00, book20_bid_proxy_usdt=1948798, book20_ask_proxy_usdt=2861288, funding_indicative=-0.000014, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.72%, turnover=41362632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=4041.940000, depth_time=2026-11-11T12:45:28+00:00, book20_bid_proxy_usdt=72473, book20_ask_proxy_usdt=178842, funding_indicative=0.000079, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.00%, turnover=102445261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T12:45:02+00:00, last15m_closed_end=2026-11-11T12:45+00:00, prior8high=999.700000, depth_time=2026-11-11T12:45:14+00:00, book20_bid_proxy_usdt=675616, book20_ask_proxy_usdt=207573, funding_indicative=0.000036, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.02%, turnover=2181769193. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
