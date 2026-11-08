# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T09:15:32Z**
- feed_generated_utc: 2026-11-08T09:15:33+00:00
- source_sha256: `2cc5b81aaf79d9aa42f931f859cd849a45a62a0fade6130ad8cfbb757087931c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T09:15+00:00, close=75858.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T09:00+00:00, close=75900.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.426300|-3.46|-13.01|-3.63|7473382|2.35|
|ENA_USDT|0.153620|-2.88|-20.81|-3.05|29210709|0.65|
|WLD_USDT|0.326400|-2.74|-19.28|-2.91|23810044|3.06|
|QNT_USDT|194.820000|-2.02|-3.09|-2.19|42750361|1.03|
|AAVE_USDT|130.000000|-1.68|-4.06|-1.85|10418215|0.77|
|ONDO_USDT|0.358500|-1.26|-13.06|-1.43|8345017|2.79|
|LINK_USDT|10.723000|-1.11|-7.32|-1.28|65075290|0.93|
|ADA_USDT|0.179600|-1.10|-7.23|-1.27|9664625|5.57|
|SUI_USDT|0.848700|-0.98|-5.90|-1.15|22804167|1.18|
|DOGE_USDT|0.070950|-0.88|-6.20|-1.05|39939435|1.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.000000|130.120000|130.030000|1.66|Y|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179600|0.179700|0.179600|2.06|Y|Y/Y|Y/Y|Y|Y|
|DOGE_USDT|0.070950|0.071010|0.070930|6.84|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.153620|0.153800|0.153630|0.98|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.723000|10.708000|10.724000|1.40|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358500|0.357900|0.358500|4.27|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.820000|194.330000|194.860000|1.36|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.848700|0.850100|0.848900|3.19|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.426300|0.426800|0.426300|1.62|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.326400|0.327600|0.326600|3.37|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=130.820000, depth_time=2026-11-08T09:15:13+00:00, book20_bid_proxy_usdt=868945, book20_ask_proxy_usdt=395153, funding_indicative=0.000015, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=10418215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.180600, depth_time=2026-11-08T09:15:26+00:00, book20_bid_proxy_usdt=11646942, book20_ask_proxy_usdt=8752050, funding_indicative=-0.000022, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=9664625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.071310, depth_time=2026-11-08T09:15:30+00:00, book20_bid_proxy_usdt=5043153, book20_ask_proxy_usdt=4286353, funding_indicative=0.000030, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=39939435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.154850, depth_time=2026-11-08T09:15:09+00:00, book20_bid_proxy_usdt=243433, book20_ask_proxy_usdt=152896, funding_indicative=0.000026, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=29210709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=10.753000, depth_time=2026-11-08T09:15:21+00:00, book20_bid_proxy_usdt=667989, book20_ask_proxy_usdt=336821, funding_indicative=0.000063, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=65075290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.360600, depth_time=2026-11-08T09:15:21+00:00, book20_bid_proxy_usdt=2111212, book20_ask_proxy_usdt=1487422, funding_indicative=0.000041, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=8345017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=196.140000, depth_time=2026-11-08T09:15:14+00:00, book20_bid_proxy_usdt=142535, book20_ask_proxy_usdt=108814, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=42750361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.855500, depth_time=2026-11-08T09:15:28+00:00, book20_bid_proxy_usdt=1553099, book20_ask_proxy_usdt=1349894, funding_indicative=-0.000028, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=22804167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.431700, depth_time=2026-11-08T09:15:03+00:00, book20_bid_proxy_usdt=344271, book20_ask_proxy_usdt=321325, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=7473382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T09:15:02+00:00, last15m_closed_end=2026-11-08T09:15+00:00, prior8high=0.331200, depth_time=2026-11-08T09:15:13+00:00, book20_bid_proxy_usdt=3757442, book20_ask_proxy_usdt=4862841, funding_indicative=-0.000152, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=23810044. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
