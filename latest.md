# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T10:45:45Z**
- feed_generated_utc: 2026-10-27T10:45:49+00:00
- source_sha256: `bff98a430be594ad9be78f3ac8e3f7ec2a0e1dc737f96a7ea6b89b961ffec2f0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T10:45+00:00, close=79889.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T10:00+00:00, close=79746.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025050|-9.17|103.99|-8.54|7604920|3.99|
|ZRO_USDT|1.626700|-4.70|-14.47|-4.07|5043424|0.61|
|AAVE_USDT|130.570000|-4.50|-11.30|-3.87|27407963|0.77|
|ENA_USDT|0.202480|-3.75|7.74|-3.12|86911554|0.99|
|PUMPFUN_USDT|0.004172|-3.60|-6.37|-2.97|21492472|2.40|
|DOT_USDT|0.988300|-3.35|-13.82|-2.72|11093192|1.01|
|WLD_USDT|0.431300|-3.07|-14.81|-2.44|68211738|2.32|
|FILECOIN_USDT|0.894100|-2.88|-11.65|-2.25|6286630|1.12|
|ONDO_USDT|0.407200|-2.76|-5.87|-2.13|23554830|2.45|
|QNT_USDT|204.720000|-2.64|4.60|-2.01|128400328|0.98|
|AVAX_USDT|8.769000|-2.53|-8.29|-1.90|23188280|1.14|
|NEAR_USDT|4.471000|-2.23|-8.82|-1.60|92105558|2.24|
|TAO_USDT|248.300000|-2.05|-7.45|-1.42|48130503|1.21|
|ARB_USDT|0.166580|-2.00|-14.84|-1.37|18979577|0.60|
|CHIP_USDT|0.050470|-1.96|23.45|-1.33|6731649|3.96|
|PEPE_USDT|0.000004|-1.78|4.25|-1.15|60185616|0.23|
|TIA_USDT|0.526400|-1.73|-13.49|-1.10|17428254|1.90|
|SOL_USDT|100.090000|-1.71|-3.84|-1.08|664815365|1.00|
|HBAR_USDT|0.076030|-1.71|-7.13|-1.08|10830269|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.570000|129.420000|130.450000|0.44|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166580|0.164480|0.166680|1.73|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.769000|8.687000|8.769000|1.45|N|Y/Y|Y/Y|Y|N|
|CHIP_USDT|0.050470|0.049770|0.050420|1.43|N|Y/N|N/N|Y|N|
|DOT_USDT|0.988300|0.979300|0.988000|3.02|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.202480|0.197200|0.202020|1.81|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.894100|0.884300|0.894000|8.88|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025050|0.025080|0.025050|1.42|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.471000|4.389000|4.470000|2.18|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407200|0.402800|0.407200|1.34|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004172|0.004093|0.004173|0.54|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|204.720000|200.970000|204.670000|1.24|N|N/N|N/N|Y|N|
|TAO_USDT|248.300000|245.490000|248.170000|2.85|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.431300|0.427500|0.431300|4.46|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.626700|1.605300|1.627100|2.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=131.330000, depth_time=2026-10-27T10:45:12+00:00, book20_bid_proxy_usdt=292103, book20_ask_proxy_usdt=879659, funding_indicative=0.000090, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.50%, turnover=27407963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.167270, depth_time=2026-10-27T10:45:41+00:00, book20_bid_proxy_usdt=61828, book20_ask_proxy_usdt=63871, funding_indicative=0.000015, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=18979577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=8.800000, depth_time=2026-10-27T10:45:33+00:00, book20_bid_proxy_usdt=923740, book20_ask_proxy_usdt=1457494, funding_indicative=0.000016, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=23188280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CHIP_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.051980, depth_time=2026-10-27T10:45:44+00:00, book20_bid_proxy_usdt=28366, book20_ask_proxy_usdt=46825, funding_indicative=0.000013, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=6731649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.996200, depth_time=2026-10-27T10:45:20+00:00, book20_bid_proxy_usdt=284550, book20_ask_proxy_usdt=656074, funding_indicative=-0.000095, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=11093192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.206280, depth_time=2026-10-27T10:45:15+00:00, book20_bid_proxy_usdt=160217, book20_ask_proxy_usdt=93434, funding_indicative=0.000018, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=86911554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.899200, depth_time=2026-10-27T10:45:25+00:00, book20_bid_proxy_usdt=1049807, book20_ask_proxy_usdt=1471756, funding_indicative=0.000035, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=6286630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.026140, depth_time=2026-10-27T10:45:08+00:00, book20_bid_proxy_usdt=125516, book20_ask_proxy_usdt=101168, funding_indicative=-0.000627, next_funding_utc=2026-10-27T11:00:00+00:00, funding_cycle_h=1, 24h_change=-9.17%, turnover=7604920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=4.469000, depth_time=2026-10-27T10:45:36+00:00, book20_bid_proxy_usdt=147020, book20_ask_proxy_usdt=3090832, funding_indicative=0.000093, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=92105558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.408900, depth_time=2026-10-27T10:45:28+00:00, book20_bid_proxy_usdt=1461074, book20_ask_proxy_usdt=2710141, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=23554830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.004175, depth_time=2026-10-27T10:45:18+00:00, book20_bid_proxy_usdt=1361113, book20_ask_proxy_usdt=2444895, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.60%, turnover=21492472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=208.760000, depth_time=2026-10-27T10:45:30+00:00, book20_bid_proxy_usdt=78383, book20_ask_proxy_usdt=72624, funding_indicative=-0.000202, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=128400328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=248.820000, depth_time=2026-10-27T10:45:38+00:00, book20_bid_proxy_usdt=92691, book20_ask_proxy_usdt=112750, funding_indicative=0.000022, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=48130503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=0.436700, depth_time=2026-10-27T10:45:22+00:00, book20_bid_proxy_usdt=2446718, book20_ask_proxy_usdt=3808232, funding_indicative=-0.000122, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=68211738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T10:45:02+00:00, last15m_closed_end=2026-10-27T10:45+00:00, prior8high=1.642100, depth_time=2026-10-27T10:45:10+00:00, book20_bid_proxy_usdt=19760, book20_ask_proxy_usdt=42098, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=5043424. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
