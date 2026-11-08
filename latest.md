# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T10:45:31Z**
- feed_generated_utc: 2026-11-08T10:45:33+00:00
- source_sha256: `769252a2d26ec4d6db411694c88ed49c83e82221d9b0e52720b5978301d76c6f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T10:45+00:00, close=75866.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T10:00+00:00, close=75899.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.424600|-3.84|-13.36|-4.01|7554447|2.35|
|ENA_USDT|0.152740|-3.43|-21.27|-3.60|29396251|0.66|
|ONE_USDT|0.001981|-2.71|68.75|-2.88|26919107|0.51|
|WLD_USDT|0.328100|-2.23|-18.86|-2.40|24275318|3.05|
|AAVE_USDT|130.140000|-1.58|-3.96|-1.75|10407258|0.77|
|SUI_USDT|0.847800|-1.08|-6.00|-1.25|21992023|1.18|
|ADA_USDT|0.179700|-1.04|-7.17|-1.21|10088105|5.56|
|DOGE_USDT|0.070870|-0.99|-6.30|-1.16|40259786|1.41|
|ONDO_USDT|0.359500|-0.99|-12.82|-1.16|8282906|2.78|
|XLM_USDT|0.149750|-0.97|-12.80|-1.14|17247313|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.140000|129.470000|130.120000|0.91|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179700|0.178900|0.179700|1.47|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.070870|0.070450|0.070870|0.32|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.152740|0.152630|0.152740|2.35|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359500|0.358000|0.359500|6.48|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001981|0.002036|0.001984|2.08|Y|N/N|N/N|Y|N|
|SUI_USDT|0.847800|0.846600|0.847800|1.19|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.424600|0.424700|0.424600|1.95|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.328100|0.325700|0.328100|0.91|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.149750|0.149640|0.149750|4.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=130.820000, depth_time=2026-11-08T10:45:16+00:00, book20_bid_proxy_usdt=379404, book20_ask_proxy_usdt=402402, funding_indicative=0.000034, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=10407258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.180300, depth_time=2026-11-08T10:45:22+00:00, book20_bid_proxy_usdt=10350798, book20_ask_proxy_usdt=8493477, funding_indicative=-0.000070, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=10088105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.071180, depth_time=2026-11-08T10:45:22+00:00, book20_bid_proxy_usdt=3807900, book20_ask_proxy_usdt=5854760, funding_indicative=0.000073, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=40259786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.154630, depth_time=2026-11-08T10:45:09+00:00, book20_bid_proxy_usdt=200838, book20_ask_proxy_usdt=241084, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=29396251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.360700, depth_time=2026-11-08T10:45:26+00:00, book20_bid_proxy_usdt=1182070, book20_ask_proxy_usdt=1486851, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=8282906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.002247, depth_time=2026-11-08T10:45:12+00:00, book20_bid_proxy_usdt=11841, book20_ask_proxy_usdt=13440, funding_indicative=-0.002475, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=26919107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.853300, depth_time=2026-11-08T10:45:20+00:00, book20_bid_proxy_usdt=997282, book20_ask_proxy_usdt=1184544, funding_indicative=-0.000005, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=21992023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.428800, depth_time=2026-11-08T10:45:07+00:00, book20_bid_proxy_usdt=291903, book20_ask_proxy_usdt=336555, funding_indicative=0.000045, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=7554447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.329400, depth_time=2026-11-08T10:45:14+00:00, book20_bid_proxy_usdt=4153092, book20_ask_proxy_usdt=4980152, funding_indicative=-0.000046, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=24275318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-08T10:45:01+00:00, last15m_closed_end=2026-11-08T10:45+00:00, prior8high=0.150510, depth_time=2026-11-08T10:45:30+00:00, book20_bid_proxy_usdt=160970, book20_ask_proxy_usdt=215238, funding_indicative=-0.000072, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=17247313. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
