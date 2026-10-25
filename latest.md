# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T15:30:26Z**
- feed_generated_utc: 2026-10-25T15:30:29+00:00
- source_sha256: `5363d8aa74fd06afef24c4b53fb1505b0f569459c36e23de0b4d4fa748e67d75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T15:30+00:00, close=80540, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T15:00+00:00, close=80618, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047200|-29.97|52.50|-30.94|5034496|4.24|
|IRYS_USDT|0.037030|-19.58|190.20|-20.55|24344985|2.70|
|BTW_USDT|1.677900|-3.64|-26.06|-4.61|11888722|1.19|
|STRK_USDT|0.045310|-3.03|-31.50|-4.00|10650487|2.21|
|SUI_USDT|0.914400|-1.14|-6.86|-2.11|63398519|1.09|
|APT_USDT|0.698800|-0.44|-12.37|-1.41|5245364|1.43|
|LINK_USDT|11.376000|-0.05|-4.45|-1.02|45044652|0.88|
|SEI_USDT|0.052860|-0.03|-14.75|-1.00|5176786|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.698800|0.689900|0.698800|0.70|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.677900|1.650000|1.677900|0.47|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037030|0.034410|0.037140|0.65|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.376000|11.313000|11.376000|1.99|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047200|0.045800|0.047220|0.64|N|Y/Y|N/N|Y|N|
|SEI_USDT|0.052860|0.052220|0.052800|0.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045310|0.044430|0.045310|0.25|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.914400|0.907500|0.914400|1.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=0.701700, depth_time=2026-10-25T15:30:20+00:00, book20_bid_proxy_usdt=111225, book20_ask_proxy_usdt=136428, funding_indicative=-0.000092, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.44%, turnover=5245364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=1.701100, depth_time=2026-10-25T15:30:09+00:00, book20_bid_proxy_usdt=13930, book20_ask_proxy_usdt=7393, funding_indicative=-0.009622, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=11888722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=0.040280, depth_time=2026-10-25T15:30:11+00:00, book20_bid_proxy_usdt=51574, book20_ask_proxy_usdt=29303, funding_indicative=-0.000165, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-19.58%, turnover=24344985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=11.436000, depth_time=2026-10-25T15:30:22+00:00, book20_bid_proxy_usdt=565021, book20_ask_proxy_usdt=459529, funding_indicative=-0.000027, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.05%, turnover=45044652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=0.048570, depth_time=2026-10-25T15:30:08+00:00, book20_bid_proxy_usdt=86854, book20_ask_proxy_usdt=84047, funding_indicative=-0.001072, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-29.97%, turnover=5034496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=0.053130, depth_time=2026-10-25T15:30:25+00:00, book20_bid_proxy_usdt=221732, book20_ask_proxy_usdt=232104, funding_indicative=-0.000005, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.03%, turnover=5176786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=0.045690, depth_time=2026-10-25T15:30:16+00:00, book20_bid_proxy_usdt=555684, book20_ask_proxy_usdt=689199, funding_indicative=0.000007, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=10650487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T15:30:01+00:00, last15m_closed_end=2026-10-25T15:30+00:00, prior8high=0.919500, depth_time=2026-10-25T15:30:17+00:00, book20_bid_proxy_usdt=1218602, book20_ask_proxy_usdt=1313240, funding_indicative=-0.000021, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=63398519. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
