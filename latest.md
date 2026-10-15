# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T14:45:38Z**
- feed_generated_utc: 2026-10-15T14:45:40+00:00
- source_sha256: `a08d60bcc86e1b469c0613160a7c5116cecf2d84b34b39434376258a35511835`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T14:45+00:00, close=81460.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T14:00+00:00, close=80171.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T12:00+00:00, close=80940.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.963500|-17.45|58.82|-17.28|33366019|1.02|
|PUMPFUN_USDT|0.004425|-6.21|-29.43|-6.04|25716737|2.26|
|LIT_USDT|3.038900|-5.19|-13.16|-5.02|6405608|0.33|
|FILECOIN_USDT|1.039300|-3.87|-0.07|-3.70|15500969|0.96|
|DOT_USDT|1.084200|-3.58|-1.79|-3.41|18606903|0.92|
|SEI_USDT|0.059810|-3.22|-12.31|-3.05|6485997|3.34|
|DOGE_USDT|0.079370|-3.18|-10.59|-3.01|112889956|1.26|
|ATOM_USDT|1.693000|-2.70|0.11|-2.53|6672862|5.91|
|SAND_USDT|0.054290|-2.53|-35.57|-2.36|5780312|1.84|
|XMR_USDT|537.320000|-1.75|-3.27|-1.58|5287342|1.86|
|COPPER_USDT|6.562000|-1.67|-1.83|-1.50|5272352|1.52|
|ZEC_USDT|1128.220000|-1.34|-14.96|-1.17|1801633572|0.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.693000|1.648000|1.693000|1.05|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.963500|1.900400|1.963500|0.63|N|Y/Y|Y/Y|Y|N|
|COPPER_USDT|6.562000|6.533000|6.562000|0.99|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.079370|0.077870|0.079370|3.82|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.084200|1.048800|1.084200|2.69|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.039300|1.001500|1.039300|0.70|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.038900|2.918900|3.038900|2.03|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004425|0.004236|0.004426|1.64|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.054290|0.052940|0.054290|0.36|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059810|0.057620|0.059810|1.17|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|537.320000|527.940000|537.320000|1.94|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1128.220000|1076.440000|1128.180000|1.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=1.688000, depth_time=2026-10-15T14:45:24+00:00, book20_bid_proxy_usdt=642154, book20_ask_proxy_usdt=1093231, funding_indicative=-0.000300, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=6672862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=2.057800, depth_time=2026-10-15T14:45:08+00:00, book20_bid_proxy_usdt=11759, book20_ask_proxy_usdt=7653, funding_indicative=0.000050, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.45%, turnover=33366019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-15T14:45:00+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=6.584000, depth_time=2026-10-15T14:45:32+00:00, book20_bid_proxy_usdt=1436983, book20_ask_proxy_usdt=1325188, funding_indicative=0.000000, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=5272352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=0.080520, depth_time=2026-10-15T14:45:24+00:00, book20_bid_proxy_usdt=1863488, book20_ask_proxy_usdt=2212001, funding_indicative=0.000063, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=112889956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=1.091200, depth_time=2026-10-15T14:45:20+00:00, book20_bid_proxy_usdt=395668, book20_ask_proxy_usdt=174633, funding_indicative=0.000049, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=18606903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=1.033800, depth_time=2026-10-15T14:45:15+00:00, book20_bid_proxy_usdt=578223, book20_ask_proxy_usdt=420486, funding_indicative=-0.000064, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=15500969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=3.026300, depth_time=2026-10-15T14:45:13+00:00, book20_bid_proxy_usdt=40928, book20_ask_proxy_usdt=35063, funding_indicative=0.000050, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=6405608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=0.004388, depth_time=2026-10-15T14:45:11+00:00, book20_bid_proxy_usdt=1501360, book20_ask_proxy_usdt=657853, funding_indicative=0.000005, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.21%, turnover=25716737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=0.054330, depth_time=2026-10-15T14:45:29+00:00, book20_bid_proxy_usdt=1188904, book20_ask_proxy_usdt=1068139, funding_indicative=-0.000112, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=5780312. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=0.059490, depth_time=2026-10-15T14:45:22+00:00, book20_bid_proxy_usdt=225735, book20_ask_proxy_usdt=263540, funding_indicative=0.000038, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=6485997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=540.100000, depth_time=2026-10-15T14:45:29+00:00, book20_bid_proxy_usdt=14753, book20_ask_proxy_usdt=22128, funding_indicative=0.000100, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=5287342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-15T14:44:59+00:00, last15m_closed_end=2026-10-15T14:45+00:00, prior8high=1114.000000, depth_time=2026-10-15T14:45:37+00:00, book20_bid_proxy_usdt=197723, book20_ask_proxy_usdt=270732, funding_indicative=0.000080, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=1801633572. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
