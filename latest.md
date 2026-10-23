# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T14:15:41Z**
- feed_generated_utc: 2026-10-23T14:15:44+00:00
- source_sha256: `d6397ae6d97d6bdeae2b874dc98dffdc1960cc807c38c4ac3fc0c6a49ba6afb5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T14:15+00:00, close=81639.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T14:00+00:00, close=81969.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.413890|-17.55|75.04|-17.54|5390060|1.21|
|LIT_USDT|3.313000|-8.33|7.16|-8.32|8391444|2.42|
|TIA_USDT|0.544200|-4.25|-9.67|-4.24|24172643|1.84|
|QNT_USDT|182.800000|-4.14|-12.07|-4.13|56756682|1.09|
|STRK_USDT|0.052380|-3.64|-45.64|-3.63|11787637|1.91|
|SILVER_USDT|53.850000|-2.55|-5.75|-2.54|311981628|1.86|
|PUMPFUN_USDT|0.004582|-2.07|1.23|-2.06|36925917|2.18|
|ARB_USDT|0.179900|-2.03|-5.28|-2.02|24383504|0.56|
|OP_USDT|0.117600|-1.87|-15.31|-1.86|6138909|1.70|
|APT_USDT|0.759300|-1.67|-8.15|-1.66|7348300|1.32|
|XAU_USDT|4016.750000|-1.05|-3.35|-1.04|578253716|0.03|
|XAUT_USDT|4011.710000|-1.04|-3.21|-1.03|218587740|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.759300|0.756500|0.759300|3.14|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.179900|0.178680|0.179900|1.50|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.313000|3.317600|3.313000|3.04|Y|Y/Y|Y/Y|Y|Y|
|MAGMA_USDT|0.413890|0.415880|0.413890|1.40|Y|Y/Y|N/N|Y|N|
|OP_USDT|0.117600|0.117120|0.117630|3.35|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004582|0.004564|0.004582|1.16|N|N/Y|Y/Y|Y|N|
|QNT_USDT|182.800000|180.210000|182.700000|0.98|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.850000|53.830000|53.850000|4.90|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052380|0.052180|0.052380|0.68|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.544200|0.543400|0.544100|1.74|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4011.710000|4019.800000|4011.740000|7.02|Y|Y/Y|Y/Y|Y|Y|
|XAU_USDT|4016.750000|4025.100000|4016.780000|4.14|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.770000, depth_time=2026-10-23T14:15:35+00:00, book20_bid_proxy_usdt=114517, book20_ask_proxy_usdt=84603, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=7348300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.182320, depth_time=2026-10-23T14:15:30+00:00, book20_bid_proxy_usdt=125941, book20_ask_proxy_usdt=56992, funding_indicative=-0.000023, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=24383504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=3.406000, depth_time=2026-10-23T14:15:12+00:00, book20_bid_proxy_usdt=21549, book20_ask_proxy_usdt=29500, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.33%, turnover=8391444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T14:15:00+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.462420, depth_time=2026-10-23T14:15:09+00:00, book20_bid_proxy_usdt=3423, book20_ask_proxy_usdt=4996, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.55%, turnover=5390060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.118690, depth_time=2026-10-23T14:15:32+00:00, book20_bid_proxy_usdt=94634, book20_ask_proxy_usdt=72720, funding_indicative=-0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=6138909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.004656, depth_time=2026-10-23T14:15:27+00:00, book20_bid_proxy_usdt=2068386, book20_ask_proxy_usdt=1169466, funding_indicative=0.000012, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=36925917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=183.520000, depth_time=2026-10-23T14:15:18+00:00, book20_bid_proxy_usdt=100679, book20_ask_proxy_usdt=36955, funding_indicative=-0.000180, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=56756682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=54.240000, depth_time=2026-10-23T14:15:24+00:00, book20_bid_proxy_usdt=29640353, book20_ask_proxy_usdt=33382092, funding_indicative=0.000075, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=311981628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.053770, depth_time=2026-10-23T14:15:22+00:00, book20_bid_proxy_usdt=616326, book20_ask_proxy_usdt=544845, funding_indicative=-0.000027, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=11787637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=0.552300, depth_time=2026-10-23T14:15:15+00:00, book20_bid_proxy_usdt=330148, book20_ask_proxy_usdt=332766, funding_indicative=-0.000009, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=24172643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T14:15:01+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=4035.760000, depth_time=2026-10-23T14:15:40+00:00, book20_bid_proxy_usdt=150184, book20_ask_proxy_usdt=738262, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=218587740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T14:15:00+00:00, last15m_closed_end=2026-10-23T14:15+00:00, prior8high=4042.750000, depth_time=2026-10-23T14:15:38+00:00, book20_bid_proxy_usdt=330353, book20_ask_proxy_usdt=3280389, funding_indicative=0.000167, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=578253716. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
