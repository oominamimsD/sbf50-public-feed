# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T00:45:16Z**
- feed_generated_utc: 2026-10-28T00:45:19+00:00
- source_sha256: `797bc7f4ec58bc633187b33c4ad855e46ee8f2ed49535554f28315aa7366241d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T00:45+00:00, close=80720.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054005|-15.06|-56.00|-15.28|42687110|1.11|
|NIL_USDT|0.088980|-4.00|0.13|-4.22|5731824|7.88|
|IRYS_USDT|0.024410|-2.00|87.48|-2.22|5656792|4.10|
|SYN_USDT|0.178000|-1.87|-3.05|-2.09|5663665|5.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.024410|0.023220|0.024410|0.69|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.088980|0.089160|0.088980|6.77|Y|Y/Y|N/N|N|N|
|Q_USDT|0.054005|0.051075|0.054096|1.24|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.178000|0.177200|0.178100|0.98|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-28T00:45:02+00:00, last15m_closed_end=2026-10-28T00:45+00:00, prior8high=0.026530, depth_time=2026-10-28T00:45:12+00:00, book20_bid_proxy_usdt=100166, book20_ask_proxy_usdt=63540, funding_indicative=-0.001919, next_funding_utc=2026-10-28T01:00:00+00:00, funding_cycle_h=1, 24h_change=-2.00%, turnover=5656792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T00:45:02+00:00, last15m_closed_end=2026-10-28T00:45+00:00, prior8high=0.092300, depth_time=2026-10-28T00:45:10+00:00, book20_bid_proxy_usdt=30644, book20_ask_proxy_usdt=4188, funding_indicative=-0.000440, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=5731824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T00:45:02+00:00, last15m_closed_end=2026-10-28T00:45+00:00, prior8high=0.054785, depth_time=2026-10-28T00:45:08+00:00, book20_bid_proxy_usdt=26294, book20_ask_proxy_usdt=29212, funding_indicative=-0.000192, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.06%, turnover=42687110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-28T00:45:02+00:00, last15m_closed_end=2026-10-28T00:45+00:00, prior8high=0.180300, depth_time=2026-10-28T00:45:14+00:00, book20_bid_proxy_usdt=103658, book20_ask_proxy_usdt=120816, funding_indicative=0.000050, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=5663665. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
