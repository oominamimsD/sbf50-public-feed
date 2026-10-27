# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T03:30:38Z**
- feed_generated_utc: 2026-10-27T03:30:42+00:00
- source_sha256: `ae4d1043db89bfa309d5ffacb1eea0654dcb382c1ea498891a3d61d75b26ca49`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T03:30+00:00, close=79759.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T03:00+00:00, close=79789.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.619100|-5.15|-14.87|-4.36|5113558|1.24|
|PUMPFUN_USDT|0.004160|-3.88|-6.64|-3.09|21532811|2.40|
|ONDO_USDT|0.405900|-3.08|-6.17|-2.29|22583768|2.46|
|DOT_USDT|0.991500|-3.04|-13.54|-2.25|10927344|1.01|
|NEAR_USDT|4.436000|-2.99|-9.54|-2.20|104469428|2.25|
|AAVE_USDT|132.870000|-2.82|-9.74|-2.03|26208637|0.75|
|FILECOIN_USDT|0.897400|-2.53|-11.32|-1.74|6415506|1.11|
|AVAX_USDT|8.787000|-2.33|-8.10|-1.54|65009207|1.14|
|ICP_USDT|2.572000|-2.20|-9.84|-1.41|5173818|3.89|
|PENGU_USDT|0.007413|-2.12|-1.04|-1.33|5544621|1.35|
|TAO_USDT|248.370000|-2.02|-7.42|-1.23|46534828|0.81|
|LINK_USDT|11.300000|-1.97|-5.38|-1.18|108770805|1.77|
|TIA_USDT|0.525100|-1.97|-13.70|-1.18|18386596|1.91|
|WLD_USDT|0.436500|-1.91|-13.78|-1.12|71896445|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.870000|132.600000|132.870000|0.74|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.787000|8.782000|8.787000|2.77|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.991500|0.988800|0.991500|1.19|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.897400|0.893000|0.897400|0.78|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.572000|2.562000|2.572000|0.18|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.300000|11.264000|11.300000|1.07|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.436000|4.395000|4.436000|1.36|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.405900|0.404900|0.405900|1.38|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007413|0.007400|0.007414|1.57|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004160|0.004118|0.004160|1.98|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|248.370000|247.750000|248.370000|1.71|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.525100|0.525500|0.525100|0.90|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.436500|0.434500|0.436500|2.15|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.619100|1.607100|1.619100|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=135.600000, depth_time=2026-10-27T03:30:19+00:00, book20_bid_proxy_usdt=748771, book20_ask_proxy_usdt=406395, funding_indicative=0.000070, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=26208637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=8.937000, depth_time=2026-10-27T03:30:23+00:00, book20_bid_proxy_usdt=943094, book20_ask_proxy_usdt=1001165, funding_indicative=0.000010, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=65009207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=1.005700, depth_time=2026-10-27T03:30:14+00:00, book20_bid_proxy_usdt=242212, book20_ask_proxy_usdt=518478, funding_indicative=-0.000117, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=10927344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=0.911400, depth_time=2026-10-27T03:30:22+00:00, book20_bid_proxy_usdt=1362227, book20_ask_proxy_usdt=1478473, funding_indicative=0.000000, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=6415506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=2.622000, depth_time=2026-10-27T03:30:26+00:00, book20_bid_proxy_usdt=1289898, book20_ask_proxy_usdt=739602, funding_indicative=0.000090, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=5173818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=11.394000, depth_time=2026-10-27T03:30:32+00:00, book20_bid_proxy_usdt=583050, book20_ask_proxy_usdt=530242, funding_indicative=0.000012, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=108770805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T03:29:59+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=4.520000, depth_time=2026-10-27T03:30:16+00:00, book20_bid_proxy_usdt=3523447, book20_ask_proxy_usdt=4114373, funding_indicative=0.000056, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=104469428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=0.413000, depth_time=2026-10-27T03:30:12+00:00, book20_bid_proxy_usdt=1914921, book20_ask_proxy_usdt=3353517, funding_indicative=0.000020, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=22583768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=0.007532, depth_time=2026-10-27T03:30:28+00:00, book20_bid_proxy_usdt=168481, book20_ask_proxy_usdt=233257, funding_indicative=-0.000025, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=5544621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=0.004299, depth_time=2026-10-27T03:30:10+00:00, book20_bid_proxy_usdt=1585343, book20_ask_proxy_usdt=2607563, funding_indicative=0.000028, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=21532811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=251.150000, depth_time=2026-10-27T03:30:30+00:00, book20_bid_proxy_usdt=131283, book20_ask_proxy_usdt=80160, funding_indicative=0.000038, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=46534828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=0.542900, depth_time=2026-10-27T03:30:35+00:00, book20_bid_proxy_usdt=214594, book20_ask_proxy_usdt=291963, funding_indicative=0.000026, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=18386596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=0.444000, depth_time=2026-10-27T03:30:37+00:00, book20_bid_proxy_usdt=3121397, book20_ask_proxy_usdt=4224169, funding_indicative=-0.000182, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=71896445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T03:30:00+00:00, last15m_closed_end=2026-10-27T03:30+00:00, prior8high=1.634200, depth_time=2026-10-27T03:30:07+00:00, book20_bid_proxy_usdt=26950, book20_ask_proxy_usdt=27233, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=5113558. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
