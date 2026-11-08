# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T06:45:30Z**
- feed_generated_utc: 2026-11-08T06:45:31+00:00
- source_sha256: `59212f24ecf24e21ae77ef7280f5e4f12638cd71bdd0eb49e8a88562a5b45c14`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T06:45+00:00, close=75748, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T06:00+00:00, close=75800, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005091|-14.90|-54.29|-14.92|40632767|5.89|
|ENA_USDT|0.153570|-2.91|-20.84|-2.93|28899544|0.65|
|TIA_USDT|0.431600|-2.26|-11.93|-2.28|7638009|2.32|
|WLD_USDT|0.328800|-2.02|-18.69|-2.04|23723666|3.04|
|QNT_USDT|195.380000|-1.74|-2.82|-1.76|46241765|0.51|
|AAVE_USDT|129.930000|-1.73|-4.11|-1.75|10844059|0.77|
|ONE_USDT|0.002007|-1.46|70.92|-1.48|26323351|1.00|
|ONDO_USDT|0.357900|-1.43|-13.21|-1.45|8662533|2.79|
|LINK_USDT|10.721000|-1.13|-7.34|-1.15|67996182|0.93|
|ADA_USDT|0.179700|-1.04|-7.17|-1.06|11618104|5.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.930000|130.350000|129.930000|0.98|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.179700|0.179600|0.179700|2.81|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005091|0.005077|0.005084|0.67|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.153570|0.153230|0.153570|3.05|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.721000|10.733000|10.720000|3.15|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.357900|0.357400|0.357900|0.53|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.002007|0.001804|0.002007|1.06|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.380000|193.770000|195.380000|0.53|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.431600|0.431800|0.431600|2.22|Y|Y/Y|Y/N|Y|N|
|WLD_USDT|0.328800|0.329700|0.328800|2.23|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=131.310000, depth_time=2026-11-08T06:45:15+00:00, book20_bid_proxy_usdt=365537, book20_ask_proxy_usdt=340027, funding_indicative=0.000014, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=10844059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.180600, depth_time=2026-11-08T06:45:29+00:00, book20_bid_proxy_usdt=11200948, book20_ask_proxy_usdt=9519111, funding_indicative=-0.000017, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=11618104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.005418, depth_time=2026-11-08T06:45:07+00:00, book20_bid_proxy_usdt=59332, book20_ask_proxy_usdt=54182, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.90%, turnover=40632767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.155160, depth_time=2026-11-08T06:45:10+00:00, book20_bid_proxy_usdt=260296, book20_ask_proxy_usdt=278555, funding_indicative=0.000047, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=28899544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=10.771000, depth_time=2026-11-08T06:45:23+00:00, book20_bid_proxy_usdt=391084, book20_ask_proxy_usdt=490846, funding_indicative=0.000069, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=67996182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.359700, depth_time=2026-11-08T06:45:23+00:00, book20_bid_proxy_usdt=1707660, book20_ask_proxy_usdt=1358327, funding_indicative=-0.000024, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=8662533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.002018, depth_time=2026-11-08T06:45:21+00:00, book20_bid_proxy_usdt=12624, book20_ask_proxy_usdt=20015, funding_indicative=-0.000237, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=26323351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=196.790000, depth_time=2026-11-08T06:45:16+00:00, book20_bid_proxy_usdt=76228, book20_ask_proxy_usdt=57852, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=46241765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.435400, depth_time=2026-11-08T06:45:10+00:00, book20_bid_proxy_usdt=300176, book20_ask_proxy_usdt=360784, funding_indicative=0.000032, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=7638009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T06:45:03+00:00, last15m_closed_end=2026-11-08T06:45+00:00, prior8high=0.332600, depth_time=2026-11-08T06:45:12+00:00, book20_bid_proxy_usdt=3867338, book20_ask_proxy_usdt=3812187, funding_indicative=-0.000169, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=23723666. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
