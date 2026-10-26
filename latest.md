# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T07:15:35Z**
- feed_generated_utc: 2026-10-26T07:15:39+00:00
- source_sha256: `054ec3d9ab2485856cbda459f73f120fb4bbe3f2098ae573ddcc3dbe8e0b69ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T07:15+00:00, close=80072.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T07:00+00:00, close=80093.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.031000|-19.35|154.09|-18.70|13228798|6.45|
|APR_USDT|0.033570|-18.73|23.23|-18.08|9274063|2.98|
|T_USDT|0.004810|-10.64|2.29|-9.99|5522225|2.08|
|WLD_USDT|0.438500|-3.96|-7.93|-3.31|68472970|2.28|
|XMR_USDT|585.410000|-3.59|0.49|-2.94|6190146|5.98|
|DOT_USDT|1.007900|-3.01|-5.75|-2.36|10545795|0.99|
|DASH_USDT|50.930000|-2.82|6.37|-2.17|11904391|1.96|
|BTW_USDT|1.614200|-2.69|-29.98|-2.04|10975602|3.10|
|STRK_USDT|0.044720|-2.22|-27.35|-1.57|9704574|2.24|
|PUMPFUN_USDT|0.004193|-2.14|-0.04|-1.49|16365582|2.38|
|INJ_USDT|7.550000|-1.99|-7.03|-1.34|25635408|1.32|
|TIA_USDT|0.527000|-1.88|-14.71|-1.23|17806084|1.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033570|0.034230|0.033570|3.75|Y|Y/Y|N/N|Y|N|
|BTW_USDT|1.614200|1.578900|1.614200|0.70|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.930000|50.820000|50.930000|2.78|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.007900|1.002800|1.007900|1.71|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.550000|7.528000|7.550000|2.01|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.031000|0.030290|0.031000|1.48|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004193|0.004163|0.004194|1.07|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044720|0.044490|0.044720|1.46|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.527000|0.519000|0.527100|0.81|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004810|0.004788|0.004812|0.41|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.438500|0.436400|0.438600|0.84|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|585.410000|584.290000|585.410000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T07:15:00+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.037240, depth_time=2026-10-26T07:15:10+00:00, book20_bid_proxy_usdt=90964, book20_ask_proxy_usdt=36550, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.73%, turnover=9274063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=1.667700, depth_time=2026-10-26T07:15:24+00:00, book20_bid_proxy_usdt=10386, book20_ask_proxy_usdt=27520, funding_indicative=-0.004035, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=10975602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=51.450000, depth_time=2026-10-26T07:15:22+00:00, book20_bid_proxy_usdt=880186, book20_ask_proxy_usdt=635310, funding_indicative=0.000043, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=11904391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=1.022500, depth_time=2026-10-26T07:15:19+00:00, book20_bid_proxy_usdt=298610, book20_ask_proxy_usdt=441212, funding_indicative=-0.000132, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=10545795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=7.718000, depth_time=2026-10-26T07:15:32+00:00, book20_bid_proxy_usdt=216581, book20_ask_proxy_usdt=373350, funding_indicative=0.000084, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=25635408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.035230, depth_time=2026-10-26T07:15:08+00:00, book20_bid_proxy_usdt=84755, book20_ask_proxy_usdt=93311, funding_indicative=-0.000553, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-19.35%, turnover=13228798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.004233, depth_time=2026-10-26T07:15:29+00:00, book20_bid_proxy_usdt=2162466, book20_ask_proxy_usdt=1770932, funding_indicative=-0.000019, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.14%, turnover=16365582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.045380, depth_time=2026-10-26T07:15:27+00:00, book20_bid_proxy_usdt=967909, book20_ask_proxy_usdt=689600, funding_indicative=0.000005, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=9704574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.536500, depth_time=2026-10-26T07:15:34+00:00, book20_bid_proxy_usdt=213644, book20_ask_proxy_usdt=357011, funding_indicative=-0.000039, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=17806084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.004895, depth_time=2026-10-26T07:15:13+00:00, book20_bid_proxy_usdt=89520, book20_ask_proxy_usdt=131116, funding_indicative=-0.000621, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-10.64%, turnover=5522225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=0.446600, depth_time=2026-10-26T07:15:15+00:00, book20_bid_proxy_usdt=2032722, book20_ask_proxy_usdt=2212218, funding_indicative=-0.000060, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=68472970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T07:15:01+00:00, last15m_closed_end=2026-10-26T07:15+00:00, prior8high=593.530000, depth_time=2026-10-26T07:15:15+00:00, book20_bid_proxy_usdt=21916, book20_ask_proxy_usdt=22698, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.59%, turnover=6190146. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
