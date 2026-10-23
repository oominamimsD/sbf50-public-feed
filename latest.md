# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T10:30:32Z**
- feed_generated_utc: 2026-10-23T10:30:34+00:00
- source_sha256: `2c3adf7efe7dc148bbdec5dac75135de0802d8df79650c1b025b9472dd840152`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T10:30+00:00, close=81692.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T10:00+00:00, close=81630.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004058|-11.93|104.43|-11.97|7791371|7.39|
|LIT_USDT|3.380300|-6.47|9.34|-6.51|9255073|0.30|
|STRK_USDT|0.051430|-5.38|-46.62|-5.42|11948048|1.95|
|QNT_USDT|181.500000|-4.82|-12.70|-4.86|51392907|1.10|
|TIA_USDT|0.549300|-3.36|-8.82|-3.40|25357721|1.82|
|SILVER_USDT|53.980000|-2.31|-5.53|-2.35|332750567|1.85|
|PUMPFUN_USDT|0.004579|-2.13|1.17|-2.17|35864697|2.19|
|ZEC_USDT|1214.370000|-1.61|2.93|-1.65|1900868163|0.08|
|ARB_USDT|0.180850|-1.51|-4.78|-1.55|25307343|0.55|
|OP_USDT|0.118280|-1.30|-14.82|-1.34|6245025|0.85|
|HBAR_USDT|0.079310|-0.99|-5.07|-1.03|20108646|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180850|0.179350|0.180910|0.28|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.079310|0.078930|0.079310|1.47|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004058|0.004054|0.004058|1.60|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.380300|3.369300|3.380300|0.46|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.118280|0.117700|0.118280|1.20|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004579|0.004556|0.004579|2.20|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.500000|182.940000|181.500000|5.22|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|53.980000|53.870000|53.980000|0.33|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051430|0.051520|0.051460|1.43|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.549300|0.548100|0.549700|1.24|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1214.370000|1214.440000|1214.590000|1.11|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.182370, depth_time=2026-10-23T10:30:25+00:00, book20_bid_proxy_usdt=71573, book20_ask_proxy_usdt=97860, funding_indicative=-0.000018, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=25307343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.080330, depth_time=2026-10-23T10:30:29+00:00, book20_bid_proxy_usdt=1040382, book20_ask_proxy_usdt=1061095, funding_indicative=0.000044, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=20108646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T10:30:01+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.004279, depth_time=2026-10-23T10:30:06+00:00, book20_bid_proxy_usdt=53951, book20_ask_proxy_usdt=64048, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.93%, turnover=7791371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=3.438600, depth_time=2026-10-23T10:30:09+00:00, book20_bid_proxy_usdt=18957, book20_ask_proxy_usdt=24977, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.47%, turnover=9255073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.120000, depth_time=2026-10-23T10:30:29+00:00, book20_bid_proxy_usdt=172662, book20_ask_proxy_usdt=79956, funding_indicative=0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=6245025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.004660, depth_time=2026-10-23T10:30:21+00:00, book20_bid_proxy_usdt=1985502, book20_ask_proxy_usdt=1762668, funding_indicative=0.000007, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=35864697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T10:30:01+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=189.100000, depth_time=2026-10-23T10:30:14+00:00, book20_bid_proxy_usdt=118339, book20_ask_proxy_usdt=82405, funding_indicative=-0.000147, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.82%, turnover=51392907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T10:30:01+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=54.210000, depth_time=2026-10-23T10:30:18+00:00, book20_bid_proxy_usdt=42633439, book20_ask_proxy_usdt=32199844, funding_indicative=0.000056, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=332750567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.053160, depth_time=2026-10-23T10:30:12+00:00, book20_bid_proxy_usdt=562373, book20_ask_proxy_usdt=659900, funding_indicative=0.000037, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.38%, turnover=11948048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T10:30:02+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=0.556800, depth_time=2026-10-23T10:30:17+00:00, book20_bid_proxy_usdt=421589, book20_ask_proxy_usdt=361420, funding_indicative=0.000006, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=25357721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T10:30:01+00:00, last15m_closed_end=2026-10-23T10:30+00:00, prior8high=1237.640000, depth_time=2026-10-23T10:30:24+00:00, book20_bid_proxy_usdt=680767, book20_ask_proxy_usdt=244912, funding_indicative=0.000023, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=1900868163. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
