# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T10:00:44Z**
- feed_generated_utc: 2026-10-27T10:00:49+00:00
- source_sha256: `68c63f9da509d49710e7dc451a00a2e3b7f6610050e5d8c64703a50cf749f824`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T10:00+00:00, close=79746.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T10:00+00:00, close=79746.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.099070|-33.56|37.55|-32.75|11736773|9.09|
|IRYS_USDT|0.025370|-9.00|106.59|-8.19|7434537|3.95|
|AAVE_USDT|130.280000|-5.51|-11.50|-4.70|25647587|1.53|
|PUMPFUN_USDT|0.004120|-4.80|-7.54|-3.99|21245790|2.43|
|ENA_USDT|0.200320|-4.77|6.59|-3.96|82574811|0.50|
|NEAR_USDT|4.436000|-4.70|-9.54|-3.89|89565793|2.25|
|QNT_USDT|204.370000|-4.16|4.43|-3.35|125161056|1.96|
|ONDO_USDT|0.405600|-4.00|-6.24|-3.19|23104422|2.46|
|FILECOIN_USDT|0.891600|-3.76|-11.89|-2.95|6026189|1.12|
|WLD_USDT|0.431400|-3.74|-14.79|-2.93|65529180|2.32|
|DOT_USDT|0.985200|-3.65|-14.09|-2.84|10678553|1.01|
|ARB_USDT|0.165820|-3.53|-15.23|-2.72|18627536|0.60|
|TIA_USDT|0.522500|-3.52|-14.13|-2.71|17063161|1.91|
|AVAX_USDT|8.739000|-2.91|-8.60|-2.10|22642961|1.14|
|HBAR_USDT|0.075730|-2.51|-7.49|-1.70|10163067|1.32|
|TAO_USDT|247.470000|-2.38|-7.76|-1.57|45525379|1.21|
|LINK_USDT|11.296000|-2.32|-5.41|-1.51|122698833|0.89|
|INJ_USDT|7.750000|-2.31|-9.36|-1.50|21817290|1.29|
|ADA_USDT|0.202400|-2.08|-6.72|-1.27|19890098|4.94|
|CHIP_USDT|0.050410|-2.07|23.31|-1.26|6700197|1.98|
|SOL_USDT|99.860000|-1.94|-4.06|-1.13|645496103|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.280000|130.020000|130.280000|2.98|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165820|0.164480|0.165820|2.37|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.739000|8.727000|8.739000|1.96|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.099070|0.100490|0.098830|1.43|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.985200|0.982200|0.985100|1.38|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.200320|0.199380|0.200350|4.02|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.891600|0.888600|0.891600|14.72|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075730|0.075690|0.075730|2.34|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025370|0.025430|0.025370|2.55|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.436000|4.425000|4.436000|0.91|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.405600|0.404600|0.405600|4.14|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004120|0.004097|0.004119|1.40|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|204.370000|204.390000|204.370000|1.29|N|N/N|N/N|Y|N|
|TIA_USDT|0.522500|0.521500|0.522500|1.49|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.431400|0.430500|0.431400|5.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=132.300000, depth_time=2026-10-27T10:00:13+00:00, book20_bid_proxy_usdt=838737, book20_ask_proxy_usdt=429535, funding_indicative=0.000093, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.51%, turnover=25647587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.168680, depth_time=2026-10-27T10:00:36+00:00, book20_bid_proxy_usdt=46402, book20_ask_proxy_usdt=87870, funding_indicative=-0.000002, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.53%, turnover=18627536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=8.828000, depth_time=2026-10-27T10:00:41+00:00, book20_bid_proxy_usdt=861866, book20_ask_proxy_usdt=1601730, funding_indicative=-0.000017, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=22642961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.133100, depth_time=2026-10-27T10:00:09+00:00, book20_bid_proxy_usdt=5947, book20_ask_proxy_usdt=44974, funding_indicative=-0.001090, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-33.56%, turnover=11736773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=1.001200, depth_time=2026-10-27T10:00:34+00:00, book20_bid_proxy_usdt=362590, book20_ask_proxy_usdt=385956, funding_indicative=-0.000088, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=10678553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.208980, depth_time=2026-10-27T10:00:19+00:00, book20_bid_proxy_usdt=115426, book20_ask_proxy_usdt=204678, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.77%, turnover=82574811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.903000, depth_time=2026-10-27T10:00:26+00:00, book20_bid_proxy_usdt=1297542, book20_ask_proxy_usdt=1330835, funding_indicative=0.000032, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=6026189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.076930, depth_time=2026-10-27T10:00:43+00:00, book20_bid_proxy_usdt=1105994, book20_ask_proxy_usdt=1410313, funding_indicative=0.000094, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=10163067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.026610, depth_time=2026-10-27T10:00:11+00:00, book20_bid_proxy_usdt=109095, book20_ask_proxy_usdt=98444, funding_indicative=-0.000311, next_funding_utc=2026-10-27T11:00:00+00:00, funding_cycle_h=1, 24h_change=-9.00%, turnover=7434537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=4.488000, depth_time=2026-10-27T10:00:22+00:00, book20_bid_proxy_usdt=3740984, book20_ask_proxy_usdt=4714189, funding_indicative=0.000078, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.70%, turnover=89565793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.411600, depth_time=2026-10-27T10:00:26+00:00, book20_bid_proxy_usdt=2226578, book20_ask_proxy_usdt=3253030, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=23104422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.004216, depth_time=2026-10-27T10:00:17+00:00, book20_bid_proxy_usdt=2219863, book20_ask_proxy_usdt=3000818, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=21245790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=211.600000, depth_time=2026-10-27T10:00:25+00:00, book20_bid_proxy_usdt=52212, book20_ask_proxy_usdt=64547, funding_indicative=-0.000235, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=125161056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.533400, depth_time=2026-10-27T10:00:38+00:00, book20_bid_proxy_usdt=351561, book20_ask_proxy_usdt=533286, funding_indicative=0.000001, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=17063161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T10:00:02+00:00, last15m_closed_end=2026-10-27T10:00+00:00, prior8high=0.439800, depth_time=2026-10-27T10:00:32+00:00, book20_bid_proxy_usdt=3233798, book20_ask_proxy_usdt=4901298, funding_indicative=-0.000161, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=65529180. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
