# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T22:15:24Z**
- feed_generated_utc: 2026-10-14T22:15:26+00:00
- source_sha256: `e2bcc97d2132ef4a5b21d1fac726d7cbc5e55967ffac90c4ef4f3feffa3ffb15`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T22:15+00:00, close=81680, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T22:00+00:00, close=81736.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.168590|-3.34|70.01|-3.44|27153223|0.59|
|FET_USDT|0.197300|-3.23|-12.89|-3.33|10722383|5.07|
|S_USDT|0.053060|-3.15|33.18|-3.25|5460937|1.89|
|LDO_USDT|0.399600|-1.52|-6.50|-1.62|5078215|2.50|
|AAVE_USDT|153.590000|-1.47|-10.57|-1.57|25780907|0.65|
|STRK_USDT|0.076270|-1.17|54.20|-1.27|24549506|1.31|
|ZEC_USDT|1131.020000|-1.10|-14.75|-1.20|1575463307|0.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.590000|153.370000|153.590000|1.54|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.168590|0.167700|0.168680|0.39|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.197300|0.194800|0.197300|0.46|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.399600|0.394500|0.399700|2.28|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.076270|0.075900|0.076270|0.80|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053060|0.052410|0.053070|0.46|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1131.020000|1128.550000|1131.000000|1.40|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=155.360000, depth_time=2026-10-14T22:15:17+00:00, book20_bid_proxy_usdt=191761, book20_ask_proxy_usdt=221909, funding_indicative=0.000082, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=25780907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=0.172860, depth_time=2026-10-14T22:15:08+00:00, book20_bid_proxy_usdt=42987, book20_ask_proxy_usdt=26360, funding_indicative=0.000013, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=27153223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=0.198200, depth_time=2026-10-14T22:15:11+00:00, book20_bid_proxy_usdt=954355, book20_ask_proxy_usdt=1249339, funding_indicative=-0.000017, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=10722383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=0.404100, depth_time=2026-10-14T22:15:16+00:00, book20_bid_proxy_usdt=565683, book20_ask_proxy_usdt=495024, funding_indicative=-0.000075, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=5078215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=0.078300, depth_time=2026-10-14T22:15:21+00:00, book20_bid_proxy_usdt=296073, book20_ask_proxy_usdt=222784, funding_indicative=0.000022, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=24549506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=0.053720, depth_time=2026-10-14T22:15:12+00:00, book20_bid_proxy_usdt=179607, book20_ask_proxy_usdt=174803, funding_indicative=-0.000070, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=5460937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-14T22:15:01+00:00, last15m_closed_end=2026-10-14T22:15+00:00, prior8high=1160.650000, depth_time=2026-10-14T22:15:23+00:00, book20_bid_proxy_usdt=109430, book20_ask_proxy_usdt=280826, funding_indicative=0.000086, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=1575463307. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
