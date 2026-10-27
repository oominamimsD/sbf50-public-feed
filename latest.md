# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T11:00:44Z**
- feed_generated_utc: 2026-10-27T11:00:48+00:00
- source_sha256: `f7317689f41b18586a3c4eb994ba8e1896acfb5b56f08892d53b4b04313b9cb2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T11:00+00:00, close=79941, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T11:00+00:00, close=79941, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.072040|-51.68|0.02|-51.11|12337517|9.72|
|IRYS_USDT|0.025110|-8.95|104.47|-8.38|7627297|3.98|
|AAVE_USDT|130.850000|-4.30|-11.11|-3.73|27738808|0.76|
|ZRO_USDT|1.635100|-4.21|-14.03|-3.64|5134173|0.61|
|DOT_USDT|0.987300|-3.45|-13.90|-2.88|11221476|2.03|
|PUMPFUN_USDT|0.004188|-3.23|-6.01|-2.66|21663522|2.39|
|WLD_USDT|0.431200|-3.10|-14.83|-2.53|69409284|2.32|
|FILECOIN_USDT|0.894700|-2.82|-11.59|-2.25|6398929|1.12|
|QNT_USDT|204.780000|-2.61|4.63|-2.04|129184132|3.42|
|ONDO_USDT|0.408200|-2.53|-5.64|-1.96|23816928|2.45|
|AVAX_USDT|8.786000|-2.34|-8.11|-1.77|24011357|1.14|
|TIA_USDT|0.524200|-2.14|-13.85|-1.57|17646400|3.81|
|ARB_USDT|0.166590|-2.00|-14.84|-1.43|19236122|0.60|
|TAO_USDT|248.890000|-1.82|-7.23|-1.25|49027744|1.21|
|HBAR_USDT|0.075990|-1.77|-7.18|-1.20|11018619|1.32|
|NEAR_USDT|4.494000|-1.72|-8.36|-1.15|93120647|2.23|
|SOL_USDT|100.090000|-1.71|-3.84|-1.14|682314863|1.00|
|PEPE_USDT|0.000004|-1.63|4.42|-1.06|60724567|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.850000|129.420000|130.850000|0.87|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166590|0.164480|0.166590|2.16|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.786000|8.687000|8.786000|7.47|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.072040|0.067070|0.072040|0.91|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.987300|0.979300|0.987300|1.87|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.894700|0.884300|0.894700|6.86|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075990|0.075460|0.075990|3.19|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025110|0.024890|0.025110|0.40|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408200|0.402800|0.408200|1.61|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004188|0.004093|0.004188|1.50|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|204.780000|200.970000|204.780000|0.91|N|N/N|N/N|Y|N|
|TAO_USDT|248.890000|245.490000|248.890000|2.25|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.524200|0.519500|0.524200|1.81|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.431200|0.427500|0.431200|3.98|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.635100|1.605300|1.635100|3.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=131.330000, depth_time=2026-10-27T11:00:13+00:00, book20_bid_proxy_usdt=295650, book20_ask_proxy_usdt=806864, funding_indicative=0.000094, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=27738808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.167270, depth_time=2026-10-27T11:00:39+00:00, book20_bid_proxy_usdt=68960, book20_ask_proxy_usdt=112068, funding_indicative=0.000021, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=19236122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=8.800000, depth_time=2026-10-27T11:00:34+00:00, book20_bid_proxy_usdt=811547, book20_ask_proxy_usdt=973111, funding_indicative=0.000025, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=24011357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.129000, depth_time=2026-10-27T11:00:08+00:00, book20_bid_proxy_usdt=26696, book20_ask_proxy_usdt=16875, funding_indicative=-0.005763, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-51.68%, turnover=12337517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.996200, depth_time=2026-10-27T11:00:18+00:00, book20_bid_proxy_usdt=280288, book20_ask_proxy_usdt=523453, funding_indicative=-0.000082, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=11221476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.899200, depth_time=2026-10-27T11:00:26+00:00, book20_bid_proxy_usdt=851398, book20_ask_proxy_usdt=1333463, funding_indicative=0.000037, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=6398929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.076460, depth_time=2026-10-27T11:00:43+00:00, book20_bid_proxy_usdt=534722, book20_ask_proxy_usdt=1092743, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=11018619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.026140, depth_time=2026-10-27T11:00:11+00:00, book20_bid_proxy_usdt=121343, book20_ask_proxy_usdt=136956, funding_indicative=-0.000678, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=1, 24h_change=-8.95%, turnover=7627297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.408900, depth_time=2026-10-27T11:00:31+00:00, book20_bid_proxy_usdt=2241664, book20_ask_proxy_usdt=3515418, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=23816928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.004175, depth_time=2026-10-27T11:00:21+00:00, book20_bid_proxy_usdt=1762704, book20_ask_proxy_usdt=1878784, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=21663522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=207.860000, depth_time=2026-10-27T11:00:29+00:00, book20_bid_proxy_usdt=56910, book20_ask_proxy_usdt=45459, funding_indicative=-0.000208, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=129184132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=248.820000, depth_time=2026-10-27T11:00:41+00:00, book20_bid_proxy_usdt=103818, book20_ask_proxy_usdt=112550, funding_indicative=0.000023, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=49027744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.528800, depth_time=2026-10-27T11:00:35+00:00, book20_bid_proxy_usdt=216183, book20_ask_proxy_usdt=498376, funding_indicative=0.000019, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.14%, turnover=17646400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=0.436700, depth_time=2026-10-27T11:00:24+00:00, book20_bid_proxy_usdt=2497809, book20_ask_proxy_usdt=4491666, funding_indicative=-0.000107, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=69409284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T10:59:59+00:00, last15m_closed_end=2026-10-27T11:00+00:00, prior8high=1.642100, depth_time=2026-10-27T11:00:15+00:00, book20_bid_proxy_usdt=29040, book20_ask_proxy_usdt=19261, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=5134173. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
