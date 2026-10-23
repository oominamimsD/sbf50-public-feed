# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T11:00:44Z**
- feed_generated_utc: 2026-10-23T11:00:46+00:00
- source_sha256: `5e24449501664e4a7a3a18b40d30ac9436cc95725b0f34f466d679af20fcb553`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T11:00+00:00, close=81656.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T11:00+00:00, close=81656.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004127|-17.62|107.90|-17.62|7667604|9.70|
|LIT_USDT|3.374800|-7.29|9.16|-7.29|8911770|0.30|
|STRK_USDT|0.051370|-6.49|-46.68|-6.49|11698414|1.95|
|QNT_USDT|182.750000|-5.26|-12.10|-5.26|51398567|0.55|
|TIA_USDT|0.548200|-4.77|-9.01|-4.77|24928063|1.82|
|BR_USDT|0.488900|-4.38|25.60|-4.38|9468568|4.09|
|PUMPFUN_USDT|0.004545|-3.31|0.41|-3.31|36196789|2.20|
|SILVER_USDT|54.020000|-2.49|-5.46|-2.49|327588817|1.85|
|XMR_USDT|606.460000|-2.27|11.48|-2.27|16130191|3.79|
|ARB_USDT|0.179890|-2.21|-5.29|-2.21|24568464|0.56|
|ZEC_USDT|1207.390000|-2.17|2.34|-2.17|1943707090|0.08|
|OP_USDT|0.117700|-1.81|-15.24|-1.81|5842479|0.85|
|HBAR_USDT|0.078990|-1.64|-5.45|-1.64|20033248|1.27|
|NEAR_USDT|4.880000|-1.29|-4.66|-1.29|122654919|2.05|
|SEI_USDT|0.057530|-1.21|-6.39|-1.21|7662843|1.74|
|INJ_USDT|7.968000|-1.04|-0.51|-1.04|24640371|1.25|
|HYPE_USDT|77.484000|-1.03|-5.11|-1.03|69973326|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.179890|0.179350|0.179890|1.09|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.488900|0.488600|0.488900|0.77|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.078990|0.078930|0.078990|1.45|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004127|0.004042|0.004127|0.55|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.374800|3.369300|3.374800|1.17|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.880000|4.889000|4.880000|1.17|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.117700|0.117700|0.117700|0.97|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004545|0.004556|0.004545|10.71|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|182.750000|181.170000|182.750000|0.80|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057530|0.057620|0.057530|0.74|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.020000|53.870000|54.020000|0.54|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051370|0.051330|0.051370|0.41|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.548200|0.548100|0.548200|0.71|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|606.460000|607.540000|606.460000|1.31|Y|Y/Y|N/Y|Y|N|
|ZEC_USDT|1207.390000|1207.840000|1207.390000|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.182330, depth_time=2026-10-23T11:00:30+00:00, book20_bid_proxy_usdt=152648, book20_ask_proxy_usdt=143855, funding_indicative=-0.000018, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=24568464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.505000, depth_time=2026-10-23T11:00:20+00:00, book20_bid_proxy_usdt=23490, book20_ask_proxy_usdt=29431, funding_indicative=-0.000134, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=9468568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.080230, depth_time=2026-10-23T11:00:38+00:00, book20_bid_proxy_usdt=723476, book20_ask_proxy_usdt=715349, funding_indicative=0.000038, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=20033248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.004238, depth_time=2026-10-23T11:00:07+00:00, book20_bid_proxy_usdt=55532, book20_ask_proxy_usdt=47662, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.62%, turnover=7667604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=3.438600, depth_time=2026-10-23T11:00:10+00:00, book20_bid_proxy_usdt=22116, book20_ask_proxy_usdt=25068, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.29%, turnover=8911770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T10:59:59+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=4.992000, depth_time=2026-10-23T11:00:41+00:00, book20_bid_proxy_usdt=3626692, book20_ask_proxy_usdt=2656063, funding_indicative=-0.000006, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=122654919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.119730, depth_time=2026-10-23T11:00:35+00:00, book20_bid_proxy_usdt=73461, book20_ask_proxy_usdt=102995, funding_indicative=0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=5842479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.004660, depth_time=2026-10-23T11:00:22+00:00, book20_bid_proxy_usdt=2159722, book20_ask_proxy_usdt=1715499, funding_indicative=0.000009, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=36196789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=188.130000, depth_time=2026-10-23T11:00:14+00:00, book20_bid_proxy_usdt=109229, book20_ask_proxy_usdt=94545, funding_indicative=-0.000152, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.26%, turnover=51398567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.058880, depth_time=2026-10-23T11:00:43+00:00, book20_bid_proxy_usdt=435385, book20_ask_proxy_usdt=259713, funding_indicative=0.000073, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=7662843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=54.210000, depth_time=2026-10-23T11:00:25+00:00, book20_bid_proxy_usdt=41432696, book20_ask_proxy_usdt=32764611, funding_indicative=0.000026, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=327588817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.052870, depth_time=2026-10-23T11:00:12+00:00, book20_bid_proxy_usdt=608196, book20_ask_proxy_usdt=742188, funding_indicative=0.000047, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.49%, turnover=11698414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=0.555200, depth_time=2026-10-23T11:00:17+00:00, book20_bid_proxy_usdt=326491, book20_ask_proxy_usdt=345021, funding_indicative=0.000013, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.77%, turnover=24928063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T11:00:00+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=616.000000, depth_time=2026-10-23T11:00:27+00:00, book20_bid_proxy_usdt=14796, book20_ask_proxy_usdt=20452, funding_indicative=0.000100, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=16130191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T10:59:59+00:00, last15m_closed_end=2026-10-23T11:00+00:00, prior8high=1237.640000, depth_time=2026-10-23T11:00:33+00:00, book20_bid_proxy_usdt=995105, book20_ask_proxy_usdt=440784, funding_indicative=0.000026, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=1943707090. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
