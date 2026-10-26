# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T10:30:24Z**
- feed_generated_utc: 2026-10-26T10:30:27+00:00
- source_sha256: `4fe91ddf2b18f7232f2836cadb54eb0df9957b68a3e94944c04b69a65e43b8ba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T10:30+00:00, close=80378.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T10:00+00:00, close=80507.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.028930|-24.73|137.13|-24.46|12645111|3.46|
|CAP_USDT|0.081180|-24.46|22.07|-24.19|7296992|3.70|
|APR_USDT|0.034720|-15.95|27.45|-15.68|8997222|2.88|
|BTW_USDT|1.504400|-9.31|-34.74|-9.04|11079802|1.33|
|WLD_USDT|0.439300|-3.78|-7.76|-3.51|63425044|2.28|
|XMR_USDT|590.270000|-2.79|1.33|-2.52|5958014|0.17|
|DOT_USDT|1.018200|-2.02|-4.78|-1.75|9976238|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034720|0.033760|0.034720|0.91|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.504400|1.440500|1.504400|1.17|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.081180|0.074320|0.081180|0.38|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.018200|1.003200|1.018200|0.73|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.028930|0.028610|0.028930|0.31|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439300|0.435500|0.439300|1.07|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.270000|583.530000|590.270000|1.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=0.038620, depth_time=2026-10-26T10:30:13+00:00, book20_bid_proxy_usdt=83803, book20_ask_proxy_usdt=49556, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.95%, turnover=8997222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=1.549300, depth_time=2026-10-26T10:30:16+00:00, book20_bid_proxy_usdt=17427, book20_ask_proxy_usdt=13545, funding_indicative=-0.011169, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.31%, turnover=11079802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=0.087470, depth_time=2026-10-26T10:30:10+00:00, book20_bid_proxy_usdt=57686, book20_ask_proxy_usdt=56941, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.46%, turnover=7296992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=1.025400, depth_time=2026-10-26T10:30:23+00:00, book20_bid_proxy_usdt=440227, book20_ask_proxy_usdt=272330, funding_indicative=-0.000078, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=9976238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=0.029970, depth_time=2026-10-26T10:30:08+00:00, book20_bid_proxy_usdt=104506, book20_ask_proxy_usdt=70408, funding_indicative=-0.000508, next_funding_utc=2026-10-26T11:00:00+00:00, funding_cycle_h=1, 24h_change=-24.73%, turnover=12645111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=0.444800, depth_time=2026-10-26T10:30:18+00:00, book20_bid_proxy_usdt=2745698, book20_ask_proxy_usdt=2456965, funding_indicative=-0.000135, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=63425044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T10:30:00+00:00, last15m_closed_end=2026-10-26T10:30+00:00, prior8high=592.000000, depth_time=2026-10-26T10:30:17+00:00, book20_bid_proxy_usdt=21089, book20_ask_proxy_usdt=11345, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=5958014. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
