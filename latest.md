# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T21:30:21Z**
- feed_generated_utc: 2026-10-30T21:30:23+00:00
- source_sha256: `d540633845460407dadc7d8b9f560298d56d6d25863b631319864403cbf96b5e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T21:30+00:00, close=76828.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T21:00+00:00, close=76891.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.098100|-14.35|109.20|-13.39|6723884|5.46|
|LIT_USDT|2.713300|-3.92|-18.37|-2.96|10419271|0.37|
|Q_USDT|0.045700|-3.74|-61.38|-2.78|22583431|2.19|
|BLESS_USDT|0.009495|-3.61|16.34|-2.65|13286486|1.05|
|BTW_USDT|1.165600|-2.82|-31.53|-1.86|10436271|0.86|
|HYPE_USDT|90.106000|-2.42|14.92|-1.46|169067388|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009495|0.008805|0.009498|0.31|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.165600|1.177900|1.165600|0.95|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.098100|1.082800|1.099300|1.01|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|90.106000|89.821000|90.084000|0.72|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.713300|2.703900|2.713300|0.37|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045700|0.044150|0.045700|0.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T21:30:02+00:00, last15m_closed_end=2026-10-30T21:30+00:00, prior8high=0.009655, depth_time=2026-10-30T21:30:16+00:00, book20_bid_proxy_usdt=11369, book20_ask_proxy_usdt=15350, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.61%, turnover=13286486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T21:30:02+00:00, last15m_closed_end=2026-10-30T21:30+00:00, prior8high=1.307800, depth_time=2026-10-30T21:30:18+00:00, book20_bid_proxy_usdt=16257, book20_ask_proxy_usdt=14765, funding_indicative=-0.000244, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=10436271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T21:30:02+00:00, last15m_closed_end=2026-10-30T21:30+00:00, prior8high=1.143000, depth_time=2026-10-30T21:30:07+00:00, book20_bid_proxy_usdt=9639, book20_ask_proxy_usdt=5543, funding_indicative=0.000062, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.35%, turnover=6723884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T21:30:02+00:00, last15m_closed_end=2026-10-30T21:30+00:00, prior8high=90.924000, depth_time=2026-10-30T21:30:20+00:00, book20_bid_proxy_usdt=39483, book20_ask_proxy_usdt=312534, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=169067388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T21:30:02+00:00, last15m_closed_end=2026-10-30T21:30+00:00, prior8high=2.780500, depth_time=2026-10-30T21:30:09+00:00, book20_bid_proxy_usdt=36054, book20_ask_proxy_usdt=23081, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=10419271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T21:30:02+00:00, last15m_closed_end=2026-10-30T21:30+00:00, prior8high=0.046340, depth_time=2026-10-30T21:30:13+00:00, book20_bid_proxy_usdt=40373, book20_ask_proxy_usdt=30916, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=22583431. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
