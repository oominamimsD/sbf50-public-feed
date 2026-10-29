# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T01:47:48Z**
- feed_generated_utc: 2026-10-29T01:47:53+00:00
- source_sha256: `99a338b82d2e7e71c2d40ae8bfa93fd380fb4e26d601cc615892d5e57c0d0ae5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T01:45+00:00, close=80516.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T01:00+00:00, close=81063.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T00:00+00:00, close=81308.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|284.780000|-2.78|-1.69|-2.69|5751757|4.21|
|HBAR_USDT|0.074230|-2.21|-13.62|-2.12|14102218|1.35|
|STRK_USDT|0.046010|-1.68|-25.75|-1.59|5289129|2.17|
|ONDO_USDT|0.412400|-1.62|-11.61|-1.53|19694304|2.42|
|NEAR_USDT|4.557000|-1.55|-15.37|-1.46|93347054|4.39|
|WLD_USDT|0.426300|-1.50|-25.67|-1.41|73606661|2.35|
|XMR_USDT|595.380000|-1.44|-0.14|-1.35|5444977|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|284.780000|286.730000|284.520000|6.37|Y|Y/Y|N/N|N|N|
|HBAR_USDT|0.074230|0.074620|0.074230|2.27|Y|Y/Y|Y/Y|N|Y|
|NEAR_USDT|4.557000|4.639000|4.570000|3.17|Y|Y/N|N/N|N|N|
|ONDO_USDT|0.412400|0.415800|0.413100|3.68|Y|Y/N|N/N|N|N|
|STRK_USDT|0.046010|0.046440|0.046120|1.14|N|Y/N|N/N|N|N|
|WLD_USDT|0.426300|0.430500|0.427200|3.71|Y|Y/N|Y/Y|N|N|
|XMR_USDT|595.380000|596.310000|595.640000|0.53|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=290.270000, depth_time=2026-10-29T01:47:13+00:00, book20_bid_proxy_usdt=94806, book20_ask_proxy_usdt=51129, funding_indicative=-0.000010, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=5751757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=0.075460, depth_time=2026-10-29T01:47:19+00:00, book20_bid_proxy_usdt=893187, book20_ask_proxy_usdt=936108, funding_indicative=0.000100, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=14102218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=4.748000, depth_time=2026-10-29T01:47:42+00:00, book20_bid_proxy_usdt=2029400, book20_ask_proxy_usdt=757679, funding_indicative=0.000100, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=93347054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=0.422000, depth_time=2026-10-29T01:47:35+00:00, book20_bid_proxy_usdt=1915533, book20_ask_proxy_usdt=1666631, funding_indicative=0.000050, next_funding_utc=2026-10-29T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=19694304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=0.047200, depth_time=2026-10-29T01:47:28+00:00, book20_bid_proxy_usdt=613400, book20_ask_proxy_usdt=790574, funding_indicative=0.000012, next_funding_utc=2026-10-29T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=5289129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=0.438800, depth_time=2026-10-29T01:47:44+00:00, book20_bid_proxy_usdt=3891532, book20_ask_proxy_usdt=2969119, funding_indicative=0.000093, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=73606661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-29T01:46:16+00:00, last15m_closed_end=2026-10-29T01:45+00:00, prior8high=600.190000, depth_time=2026-10-29T01:47:43+00:00, book20_bid_proxy_usdt=22256, book20_ask_proxy_usdt=17253, funding_indicative=0.000100, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=5444977. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
