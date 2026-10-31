# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T02:30:30Z**
- feed_generated_utc: 2026-10-31T02:30:32+00:00
- source_sha256: `a34497d15a02d5d7e60a02720575334623b9779d1cdc89e741668d1abbef5892`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T02:30+00:00, close=77355, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T02:00+00:00, close=77358.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011778|-37.75|-66.34|-37.47|6520286|4.25|
|Q_USDT|0.033970|-28.45|-71.29|-28.17|19638314|2.94|
|BEAT_USDT|0.097070|-7.68|33.72|-7.40|8727057|2.06|
|EVAA_USDT|1.190400|-7.15|126.78|-6.87|6539651|6.72|
|BLESS_USDT|0.009522|-3.33|16.67|-3.05|12459287|7.34|
|TRX_USDT|0.325350|-3.02|-1.21|-2.74|8282398|0.31|
|HYPE_USDT|89.809000|-2.74|14.54|-2.46|119612726|0.11|
|XMR_USDT|592.620000|-1.48|-2.36|-1.20|8917157|0.17|
|LIT_USDT|2.782900|-1.46|-16.27|-1.18|6222781|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011778|0.011886|0.011778|1.44|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097070|0.096340|0.097130|1.43|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009522|0.009190|0.009519|1.89|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.190400|1.106900|1.190400|2.34|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.809000|89.156000|89.844000|0.54|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.782900|2.749900|2.782900|2.84|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.033970|0.033060|0.033970|4.15|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.325350|0.321930|0.325350|4.89|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.620000|588.520000|592.660000|2.80|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=0.014222, depth_time=2026-10-31T02:30:08+00:00, book20_bid_proxy_usdt=5764, book20_ask_proxy_usdt=8415, funding_indicative=-0.000078, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-37.75%, turnover=6520286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=0.106270, depth_time=2026-10-31T02:30:13+00:00, book20_bid_proxy_usdt=10235, book20_ask_proxy_usdt=7917, funding_indicative=0.000118, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.68%, turnover=8727057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=0.009853, depth_time=2026-10-31T02:30:19+00:00, book20_bid_proxy_usdt=12923, book20_ask_proxy_usdt=13224, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=12459287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=1.176200, depth_time=2026-10-31T02:30:17+00:00, book20_bid_proxy_usdt=3688, book20_ask_proxy_usdt=4198, funding_indicative=0.000121, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.15%, turnover=6539651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=90.251000, depth_time=2026-10-31T02:30:23+00:00, book20_bid_proxy_usdt=49736, book20_ask_proxy_usdt=131060, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=119612726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T02:30:02+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=2.792300, depth_time=2026-10-31T02:30:28+00:00, book20_bid_proxy_usdt=27476, book20_ask_proxy_usdt=22628, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=6222781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=0.048730, depth_time=2026-10-31T02:30:11+00:00, book20_bid_proxy_usdt=14050, book20_ask_proxy_usdt=25672, funding_indicative=-0.002185, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-28.45%, turnover=19638314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T02:30:01+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=0.327580, depth_time=2026-10-31T02:30:22+00:00, book20_bid_proxy_usdt=70428, book20_ask_proxy_usdt=33477, funding_indicative=-0.001549, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=8282398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-31T02:30:02+00:00, last15m_closed_end=2026-10-31T02:30+00:00, prior8high=601.200000, depth_time=2026-10-31T02:30:27+00:00, book20_bid_proxy_usdt=23776, book20_ask_proxy_usdt=24467, funding_indicative=0.000512, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=8917157. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
