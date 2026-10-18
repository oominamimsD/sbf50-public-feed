# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T05:30:43Z**
- feed_generated_utc: 2026-10-18T05:30:46+00:00
- source_sha256: `e19aa695e04f94d53210bcf031fa3135ab2c399de8508232f80f30b8d3addadc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T05:30+00:00, close=81711, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T05:00+00:00, close=81766.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062740|-5.15|-32.84|-5.63|14092288|1.59|
|TIA_USDT|0.627000|-4.71|22.22|-5.19|64887969|1.59|
|EIGEN_USDT|0.245400|-4.25|4.15|-4.73|9066971|4.07|
|FILECOIN_USDT|1.044400|-3.95|-7.39|-4.43|20274495|1.92|
|QNT_USDT|193.130000|-3.63|-21.21|-4.11|71087535|0.52|
|PUMPFUN_USDT|0.004276|-3.08|-25.31|-3.56|23376344|2.34|
|OP_USDT|0.125890|-2.41|-9.13|-2.89|9527699|0.80|
|ZRO_USDT|1.841200|-2.33|-8.87|-2.81|7285849|0.54|
|DOT_USDT|1.093100|-2.17|-13.03|-2.65|16955128|3.66|
|WLD_USDT|0.486400|-1.85|-12.98|-2.33|61651997|2.06|
|APT_USDT|0.782900|-1.83|-5.30|-2.31|10257008|1.28|
|ARB_USDT|0.181100|-1.53|-2.98|-2.01|31117254|0.55|
|ENA_USDT|0.186930|-1.17|-15.81|-1.65|28531903|0.54|
|ICP_USDT|2.895000|-1.12|-8.06|-1.60|6493801|3.46|
|ZEC_USDT|1129.460000|-1.04|-8.30|-1.52|1156862384|0.09|
|AVAX_USDT|9.734000|-0.86|-7.51|-1.34|78789952|1.03|
|PEPE_USDT|0.000004|-0.79|-4.37|-1.27|58307539|0.26|
|SUI_USDT|0.974500|-0.74|-13.29|-1.22|74063848|1.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.782900|0.786100|0.782900|4.37|Y|Y/Y|Y/Y|N|Y|
|ARB_USDT|0.181100|0.181410|0.181150|0.91|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.093100|1.098300|1.093000|2.86|Y|Y/Y|Y/Y|N|Y|
|EIGEN_USDT|0.245400|0.247100|0.245500|2.54|Y|Y/Y|N/Y|N|N|
|ENA_USDT|0.186930|0.187820|0.186930|1.40|Y|Y/Y|Y/Y|N|Y|
|FILECOIN_USDT|1.044400|1.051200|1.044400|4.31|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|2.895000|2.913000|2.894000|3.29|Y|Y/Y|Y/Y|N|Y|
|OP_USDT|0.125890|0.126710|0.125890|3.91|Y|Y/Y|Y/Y|N|Y|
|PUMPFUN_USDT|0.004276|0.004282|0.004276|3.58|Y|Y/Y|Y/Y|N|Y|
|QNT_USDT|193.130000|193.320000|193.130000|1.05|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.062740|0.062790|0.062750|2.10|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.627000|0.626300|0.627100|1.03|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.486400|0.488400|0.486600|1.20|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1129.460000|1132.970000|1129.270000|1.34|Y|Y/N|Y/Y|N|N|
|ZRO_USDT|1.841200|1.851800|1.842100|4.44|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.800600, depth_time=2026-10-18T05:30:33+00:00, book20_bid_proxy_usdt=112912, book20_ask_proxy_usdt=151307, funding_indicative=-0.000114, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=10257008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.185600, depth_time=2026-10-18T05:30:33+00:00, book20_bid_proxy_usdt=130558, book20_ask_proxy_usdt=67942, funding_indicative=-0.000038, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=31117254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=1.120700, depth_time=2026-10-18T05:30:28+00:00, book20_bid_proxy_usdt=232771, book20_ask_proxy_usdt=285974, funding_indicative=-0.000048, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=16955128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.253900, depth_time=2026-10-18T05:30:12+00:00, book20_bid_proxy_usdt=539394, book20_ask_proxy_usdt=474006, funding_indicative=-0.000042, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=9066971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.192410, depth_time=2026-10-18T05:30:38+00:00, book20_bid_proxy_usdt=182205, book20_ask_proxy_usdt=194938, funding_indicative=-0.000026, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=28531903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=1.074100, depth_time=2026-10-18T05:30:13+00:00, book20_bid_proxy_usdt=380629, book20_ask_proxy_usdt=630912, funding_indicative=-0.000115, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=20274495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=2.955000, depth_time=2026-10-18T05:30:39+00:00, book20_bid_proxy_usdt=1000700, book20_ask_proxy_usdt=1175915, funding_indicative=0.000012, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=6493801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.129950, depth_time=2026-10-18T05:30:23+00:00, book20_bid_proxy_usdt=51197, book20_ask_proxy_usdt=74402, funding_indicative=-0.000187, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=9527699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.004401, depth_time=2026-10-18T05:30:20+00:00, book20_bid_proxy_usdt=1869318, book20_ask_proxy_usdt=1583289, funding_indicative=0.000023, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=23376344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=197.110000, depth_time=2026-10-18T05:30:18+00:00, book20_bid_proxy_usdt=66903, book20_ask_proxy_usdt=89861, funding_indicative=-0.000103, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=71087535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.064240, depth_time=2026-10-18T05:30:08+00:00, book20_bid_proxy_usdt=589827, book20_ask_proxy_usdt=347061, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=14092288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.638400, depth_time=2026-10-18T05:30:10+00:00, book20_bid_proxy_usdt=315393, book20_ask_proxy_usdt=216144, funding_indicative=-0.000006, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.71%, turnover=64887969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=0.498500, depth_time=2026-10-18T05:30:29+00:00, book20_bid_proxy_usdt=2059050, book20_ask_proxy_usdt=2075548, funding_indicative=-0.000161, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=61651997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=1156.430000, depth_time=2026-10-18T05:30:43+00:00, book20_bid_proxy_usdt=484222, book20_ask_proxy_usdt=368222, funding_indicative=0.000089, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=1156862384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T05:30:01+00:00, last15m_closed_end=2026-10-18T05:30+00:00, prior8high=1.918400, depth_time=2026-10-18T05:30:25+00:00, book20_bid_proxy_usdt=42010, book20_ask_proxy_usdt=49012, funding_indicative=0.000003, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=7285849. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
