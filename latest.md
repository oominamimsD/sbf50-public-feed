# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T09:45:33Z**
- feed_generated_utc: 2026-11-08T09:45:35+00:00
- source_sha256: `eacf490b42e223e1eb3d1178e14267439fd8adf45269b749c51886d21144a5af`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T09:45+00:00, close=75925.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T09:00+00:00, close=75900.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005433|-9.19|-51.22|-9.45|36365929|1.84|
|TIA_USDT|0.426200|-3.48|-13.03|-3.74|7563548|7.04|
|ENA_USDT|0.154020|-2.62|-20.61|-2.88|29596107|0.65|
|WLD_USDT|0.327500|-2.41|-19.01|-2.67|24592533|3.05|
|QNT_USDT|195.270000|-1.80|-2.87|-2.06|43284891|0.51|
|AAVE_USDT|130.340000|-1.42|-3.81|-1.68|10632311|0.77|
|ADA_USDT|0.179600|-1.10|-7.23|-1.36|10182085|5.57|
|DOGE_USDT|0.070850|-1.01|-6.33|-1.27|42207992|1.41|
|ONDO_USDT|0.359700|-0.93|-12.77|-1.19|8548258|2.78|
|SUI_USDT|0.849900|-0.84|-5.77|-1.10|23158410|1.18|
|LINK_USDT|10.762000|-0.75|-6.99|-1.01|66109347|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.340000|129.470000|130.340000|1.53|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179600|0.178900|0.179600|1.38|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005433|0.005196|0.005433|2.20|N|N/N|N/N|Y|N|
|DOGE_USDT|0.070850|0.070450|0.070850|1.28|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154020|0.152950|0.154020|0.70|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.762000|10.704000|10.762000|2.40|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359700|0.358000|0.359700|2.14|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.270000|193.880000|195.270000|1.05|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.849900|0.846700|0.849900|1.29|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.426200|0.424900|0.426200|0.64|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327500|0.325700|0.327500|2.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=130.820000, depth_time=2026-11-08T09:45:18+00:00, book20_bid_proxy_usdt=448087, book20_ask_proxy_usdt=787651, funding_indicative=0.000021, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=10632311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.180600, depth_time=2026-11-08T09:45:22+00:00, book20_bid_proxy_usdt=10374789, book20_ask_proxy_usdt=9379693, funding_indicative=-0.000030, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=10182085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.006025, depth_time=2026-11-08T09:45:07+00:00, book20_bid_proxy_usdt=38855, book20_ask_proxy_usdt=37445, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=36365929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.071310, depth_time=2026-11-08T09:45:21+00:00, book20_bid_proxy_usdt=5291064, book20_ask_proxy_usdt=4259906, funding_indicative=0.000040, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=42207992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.154850, depth_time=2026-11-08T09:45:11+00:00, book20_bid_proxy_usdt=344809, book20_ask_proxy_usdt=305525, funding_indicative=0.000044, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=29596107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=10.753000, depth_time=2026-11-08T09:45:32+00:00, book20_bid_proxy_usdt=354318, book20_ask_proxy_usdt=499808, funding_indicative=0.000060, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=66109347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.360600, depth_time=2026-11-08T09:45:25+00:00, book20_bid_proxy_usdt=1310414, book20_ask_proxy_usdt=1773163, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=8548258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=196.140000, depth_time=2026-11-08T09:45:17+00:00, book20_bid_proxy_usdt=85245, book20_ask_proxy_usdt=98969, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=43284891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.855500, depth_time=2026-11-08T09:45:30+00:00, book20_bid_proxy_usdt=1850506, book20_ask_proxy_usdt=1484704, funding_indicative=-0.000016, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=23158410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.431700, depth_time=2026-11-08T09:45:08+00:00, book20_bid_proxy_usdt=392005, book20_ask_proxy_usdt=281851, funding_indicative=0.000049, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=7563548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T09:45:01+00:00, last15m_closed_end=2026-11-08T09:45+00:00, prior8high=0.330400, depth_time=2026-11-08T09:45:15+00:00, book20_bid_proxy_usdt=3959456, book20_ask_proxy_usdt=4057764, funding_indicative=-0.000098, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=24592533. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
