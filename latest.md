# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T14:15:29Z**
- feed_generated_utc: 2026-10-26T14:15:32+00:00
- source_sha256: `7469eddec7439c5d6bcf292c6364e6c6db526664fdf5776d93f98deec30b35ff`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T14:15+00:00, close=79924.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T14:00+00:00, close=79668.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027800|-27.67|127.86|-26.83|11705605|3.60|
|APR_USDT|0.032720|-20.79|20.11|-19.95|5928320|6.11|
|BTW_USDT|1.347200|-18.78|-41.56|-17.94|11309423|5.94|
|BRL_USDT|0.181500|-9.34|-7.77|-8.50|5149590|5.51|
|WLD_USDT|0.437800|-4.11|-8.08|-3.27|60751549|2.28|
|LIT_USDT|3.073200|-3.30|4.87|-2.46|5038073|0.33|
|XMR_USDT|591.820000|-2.54|1.60|-1.70|5511931|0.17|
|STRK_USDT|0.044630|-2.42|-27.50|-1.58|9426948|2.24|
|DOT_USDT|1.018000|-2.04|-4.80|-1.20|8927430|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032720|0.031070|0.032720|0.65|N|Y/Y|N/N|Y|N|
|BRL_USDT|0.181500|0.179700|0.181500|2.39|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.347200|1.386300|1.347500|3.76|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|1.018000|1.009100|1.018000|1.04|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.027800|0.027330|0.027800|0.99|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.073200|3.039700|3.073200|0.97|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044630|0.044200|0.044630|0.49|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437800|0.435800|0.437800|0.66|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.820000|590.550000|591.820000|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T14:15:00+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=0.037130, depth_time=2026-10-26T14:15:10+00:00, book20_bid_proxy_usdt=63783, book20_ask_proxy_usdt=42007, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.79%, turnover=5928320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BRL_USDT: quote_utc=2026-10-26T14:15:01+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=0.184300, depth_time=2026-10-26T14:15:10+00:00, book20_bid_proxy_usdt=404732, book20_ask_proxy_usdt=407991, funding_indicative=-0.000116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.34%, turnover=5149590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T14:15:00+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=1.468000, depth_time=2026-10-26T14:15:14+00:00, book20_bid_proxy_usdt=18841, book20_ask_proxy_usdt=14692, funding_indicative=-0.015795, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.78%, turnover=11309423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T14:15:00+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=1.025100, depth_time=2026-10-26T14:15:28+00:00, book20_bid_proxy_usdt=377345, book20_ask_proxy_usdt=302453, funding_indicative=-0.000042, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=8927430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T14:15:00+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=0.029430, depth_time=2026-10-26T14:15:08+00:00, book20_bid_proxy_usdt=70013, book20_ask_proxy_usdt=80902, funding_indicative=-0.000792, next_funding_utc=2026-10-26T15:00:00+00:00, funding_cycle_h=1, 24h_change=-27.67%, turnover=11705605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T14:15:01+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=3.115900, depth_time=2026-10-26T14:15:21+00:00, book20_bid_proxy_usdt=20044, book20_ask_proxy_usdt=20325, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=5038073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T14:15:01+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=0.044930, depth_time=2026-10-26T14:15:26+00:00, book20_bid_proxy_usdt=966585, book20_ask_proxy_usdt=671837, funding_indicative=0.000019, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=9426948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T14:15:00+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=0.444700, depth_time=2026-10-26T14:15:18+00:00, book20_bid_proxy_usdt=2417433, book20_ask_proxy_usdt=2302259, funding_indicative=-0.000155, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.11%, turnover=60751549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T14:15:01+00:00, last15m_closed_end=2026-10-26T14:15+00:00, prior8high=594.610000, depth_time=2026-10-26T14:15:22+00:00, book20_bid_proxy_usdt=39590, book20_ask_proxy_usdt=5233, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=5511931. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
