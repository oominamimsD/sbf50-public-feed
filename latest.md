# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T00:15:21Z**
- feed_generated_utc: 2026-10-31T00:15:23+00:00
- source_sha256: `f801e20c9abcf31bebb5f9817316401afdad2436eff1de6711fe87ce2b9b1d9e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T00:15+00:00, close=77307.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013869|-26.70|-60.37|-26.35|5803125|3.61|
|EVAA_USDT|1.157300|-9.73|120.48|-9.38|6671892|5.18|
|BTW_USDT|1.136800|-5.22|-33.22|-4.87|9719549|3.52|
|HYPE_USDT|89.558000|-3.01|14.22|-2.66|138968909|0.11|
|TRX_USDT|0.326380|-2.71|-0.89|-2.36|9664174|0.31|
|XMR_USDT|588.770000|-2.12|-3.00|-1.77|9943355|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013869|0.013043|0.013862|1.12|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.136800|1.135400|1.136800|0.94|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.157300|1.098500|1.157600|0.62|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.558000|89.002000|89.558000|0.77|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.326380|0.328370|0.326380|4.00|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|588.770000|588.230000|588.770000|0.18|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T00:15:01+00:00, last15m_closed_end=2026-10-31T00:15+00:00, prior8high=0.014277, depth_time=2026-10-31T00:15:08+00:00, book20_bid_proxy_usdt=4380, book20_ask_proxy_usdt=9009, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-26.70%, turnover=5803125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T00:15:01+00:00, last15m_closed_end=2026-10-31T00:15+00:00, prior8high=1.170200, depth_time=2026-10-31T00:15:13+00:00, book20_bid_proxy_usdt=26003, book20_ask_proxy_usdt=17521, funding_indicative=-0.000259, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.22%, turnover=9719549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T00:15:01+00:00, last15m_closed_end=2026-10-31T00:15+00:00, prior8high=1.154200, depth_time=2026-10-31T00:15:10+00:00, book20_bid_proxy_usdt=6403, book20_ask_proxy_usdt=8124, funding_indicative=0.000188, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.73%, turnover=6671892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T00:15:00+00:00, last15m_closed_end=2026-10-31T00:15+00:00, prior8high=90.278000, depth_time=2026-10-31T00:15:15+00:00, book20_bid_proxy_usdt=176526, book20_ask_proxy_usdt=82424, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=138968909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T00:15:00+00:00, last15m_closed_end=2026-10-31T00:15+00:00, prior8high=0.331360, depth_time=2026-10-31T00:15:17+00:00, book20_bid_proxy_usdt=92831, book20_ask_proxy_usdt=97270, funding_indicative=-0.000516, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=9664174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-31T00:15:01+00:00, last15m_closed_end=2026-10-31T00:15+00:00, prior8high=593.400000, depth_time=2026-10-31T00:15:20+00:00, book20_bid_proxy_usdt=13833, book20_ask_proxy_usdt=4416, funding_indicative=0.000495, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=9943355. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
