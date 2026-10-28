# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T17:00:26Z**
- feed_generated_utc: 2026-10-28T17:00:30+00:00
- source_sha256: `dbe2048243ac83d5fbd086c80e816008b889f1c253b51474e491b1e9533ae13f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T17:00+00:00, close=80591.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T17:00+00:00, close=80591.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.060040|-2.48|-25.83|-2.52|5306759|5.00|
|STRK_USDT|0.045830|-2.07|-26.04|-2.11|5110883|2.18|
|WLD_USDT|0.424500|-1.91|-25.99|-1.95|62876179|2.35|
|TIA_USDT|0.530600|-1.68|-16.11|-1.72|14151244|1.89|
|OP_USDT|0.109890|-1.07|-16.68|-1.11|6267156|0.91|
|ONDO_USDT|0.414800|-1.04|-11.10|-1.08|16754234|2.41|
|HBAR_USDT|0.075150|-1.00|-12.55|-1.04|10102484|1.33|
|APT_USDT|0.681800|-1.00|-18.40|-1.04|6117694|1.47|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.681800|0.680700|0.682200|2.00|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.060040|0.059390|0.060060|1.01|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075150|0.074980|0.075170|4.41|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.414800|0.413500|0.414900|1.61|N|Y/Y|N/N|Y|N|
|OP_USDT|0.109890|0.109740|0.109960|1.19|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045830|0.045790|0.045800|1.39|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.530600|0.531600|0.530300|2.45|Y|Y/N|N/Y|Y|N|
|WLD_USDT|0.424500|0.426200|0.425000|5.63|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.690600, depth_time=2026-10-28T17:00:25+00:00, book20_bid_proxy_usdt=166106, book20_ask_proxy_usdt=165835, funding_indicative=-0.000094, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=6117694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.068880, depth_time=2026-10-28T17:00:07+00:00, book20_bid_proxy_usdt=17716, book20_ask_proxy_usdt=7731, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=5306759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.075940, depth_time=2026-10-28T17:00:22+00:00, book20_bid_proxy_usdt=1320753, book20_ask_proxy_usdt=694806, funding_indicative=-0.000019, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=10102484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.419600, depth_time=2026-10-28T17:00:21+00:00, book20_bid_proxy_usdt=1823860, book20_ask_proxy_usdt=1677233, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=16754234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.111260, depth_time=2026-10-28T17:00:18+00:00, book20_bid_proxy_usdt=116428, book20_ask_proxy_usdt=84632, funding_indicative=-0.000030, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=6267156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.047080, depth_time=2026-10-28T17:00:10+00:00, book20_bid_proxy_usdt=944080, book20_ask_proxy_usdt=889279, funding_indicative=0.000006, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=5110883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.546100, depth_time=2026-10-28T17:00:16+00:00, book20_bid_proxy_usdt=277988, book20_ask_proxy_usdt=357815, funding_indicative=0.000014, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=14151244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T17:00:02+00:00, last15m_closed_end=2026-10-28T17:00+00:00, prior8high=0.435200, depth_time=2026-10-28T17:00:13+00:00, book20_bid_proxy_usdt=4139833, book20_ask_proxy_usdt=3999228, funding_indicative=0.000011, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=62876179. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
