# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T21:45:21Z**
- feed_generated_utc: 2026-10-30T21:45:23+00:00
- source_sha256: `a78233de3f97cca3a559e5966f43654a48bd9469671f5b64053aa0925e816a66`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T21:45+00:00, close=76812, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T21:00+00:00, close=76891.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.087800|-15.15|107.23|-14.17|6746868|1.83|
|BLESS_USDT|0.009414|-4.43|15.35|-3.45|13340942|5.31|
|LIT_USDT|2.712800|-3.94|-18.38|-2.96|10488048|0.37|
|BTW_USDT|1.161400|-3.17|-31.77|-2.19|10517677|3.44|
|HYPE_USDT|89.507000|-3.07|14.16|-2.09|169443295|0.11|
|Q_USDT|0.046030|-3.05|-61.10|-2.07|22642263|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009414|0.008961|0.009414|0.35|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.161400|1.161300|1.161400|0.63|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.087800|1.082800|1.087700|0.69|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.507000|89.719000|89.507000|0.44|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.712800|2.703900|2.712800|1.09|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.046030|0.044150|0.046050|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T21:45:01+00:00, last15m_closed_end=2026-10-30T21:45+00:00, prior8high=0.009655, depth_time=2026-10-30T21:45:10+00:00, book20_bid_proxy_usdt=9904, book20_ask_proxy_usdt=14200, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=13340942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T21:45:01+00:00, last15m_closed_end=2026-10-30T21:45+00:00, prior8high=1.307500, depth_time=2026-10-30T21:45:15+00:00, book20_bid_proxy_usdt=17615, book20_ask_proxy_usdt=24266, funding_indicative=-0.000266, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=10517677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T21:45:00+00:00, last15m_closed_end=2026-10-30T21:45+00:00, prior8high=1.143000, depth_time=2026-10-30T21:45:07+00:00, book20_bid_proxy_usdt=9277, book20_ask_proxy_usdt=8009, funding_indicative=0.000088, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.15%, turnover=6746868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T21:45:00+00:00, last15m_closed_end=2026-10-30T21:45+00:00, prior8high=90.924000, depth_time=2026-10-30T21:45:17+00:00, book20_bid_proxy_usdt=37520, book20_ask_proxy_usdt=264724, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=169443295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T21:45:01+00:00, last15m_closed_end=2026-10-30T21:45+00:00, prior8high=2.780500, depth_time=2026-10-30T21:45:10+00:00, book20_bid_proxy_usdt=33213, book20_ask_proxy_usdt=24544, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=10488048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T21:45:00+00:00, last15m_closed_end=2026-10-30T21:45+00:00, prior8high=0.046340, depth_time=2026-10-30T21:45:20+00:00, book20_bid_proxy_usdt=27005, book20_ask_proxy_usdt=26454, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=22642263. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
