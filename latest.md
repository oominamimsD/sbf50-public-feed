# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T01:15:34Z**
- feed_generated_utc: 2026-11-07T01:15:36+00:00
- source_sha256: `fff94f825400c26dd5bb2fd68de29928d8faed31fb5121155028edf3251640b2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T01:15+00:00, close=75869.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T01:00+00:00, close=75871, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.142200|-25.15|-46.46|-25.19|34588185|7.03|
|CYBER_USDT|0.318200|-10.11|16.47|-10.15|6701901|6.27|
|ANTHROPIC_USDT|1348.270000|-5.79|-19.57|-5.83|7280088|1.48|
|TRUMPOFFICIAL_USDT|1.199000|-3.46|-23.72|-3.50|11617589|8.34|
|DOT_USDT|0.908200|-3.08|-6.29|-3.12|6803626|1.10|
|PUMPFUN_USDT|0.003932|-2.79|-4.26|-2.83|12470339|2.54|
|APT_USDT|0.603200|-2.29|-3.90|-2.33|5056750|1.66|
|ARB_USDT|0.164530|-2.19|1.48|-2.23|26361529|0.61|
|ENA_USDT|0.163910|-2.14|-13.67|-2.18|31422632|0.61|
|OP_USDT|0.105130|-2.04|-2.84|-2.08|5796206|0.95|
|ONDO_USDT|0.371000|-1.46|-7.11|-1.50|11161226|2.70|
|FARTCOIN_USDT|0.118500|-1.27|-1.49|-1.31|12718643|0.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1348.270000|1322.000000|1348.270000|0.14|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.603200|0.603200|0.603200|1.31|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164530|0.164290|0.164530|0.37|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.318200|0.321300|0.318200|1.60|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.908200|0.907500|0.908200|1.56|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163910|0.163260|0.163910|0.56|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118500|0.117630|0.118500|1.02|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.371000|0.369900|0.371000|3.78|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.105130|0.104840|0.105130|0.26|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003932|0.003882|0.003932|0.28|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.199000|1.196000|1.199000|0.60|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.142200|0.130700|0.142100|1.04|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=1347.260000, depth_time=2026-11-07T01:15:11+00:00, book20_bid_proxy_usdt=15914, book20_ask_proxy_usdt=37987, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.79%, turnover=7280088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.608100, depth_time=2026-11-07T01:15:20+00:00, book20_bid_proxy_usdt=164126, book20_ask_proxy_usdt=166981, funding_indicative=0.000027, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=5056750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.165910, depth_time=2026-11-07T01:15:23+00:00, book20_bid_proxy_usdt=88521, book20_ask_proxy_usdt=108926, funding_indicative=0.000032, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=26361529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.342100, depth_time=2026-11-07T01:15:08+00:00, book20_bid_proxy_usdt=2066314, book20_ask_proxy_usdt=1263609, funding_indicative=-0.002296, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.11%, turnover=6701901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.917300, depth_time=2026-11-07T01:15:16+00:00, book20_bid_proxy_usdt=452150, book20_ask_proxy_usdt=354998, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=6803626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.164360, depth_time=2026-11-07T01:15:26+00:00, book20_bid_proxy_usdt=151349, book20_ask_proxy_usdt=213626, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.14%, turnover=31422632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.118900, depth_time=2026-11-07T01:15:32+00:00, book20_bid_proxy_usdt=78071, book20_ask_proxy_usdt=79450, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=12718643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.371700, depth_time=2026-11-07T01:15:29+00:00, book20_bid_proxy_usdt=1383354, book20_ask_proxy_usdt=1884430, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=11161226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.105740, depth_time=2026-11-07T01:15:28+00:00, book20_bid_proxy_usdt=169960, book20_ask_proxy_usdt=85563, funding_indicative=-0.000002, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=5796206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.003941, depth_time=2026-11-07T01:15:18+00:00, book20_bid_proxy_usdt=2184844, book20_ask_proxy_usdt=2301831, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=12470339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=1.215000, depth_time=2026-11-07T01:15:14+00:00, book20_bid_proxy_usdt=1372578, book20_ask_proxy_usdt=1651057, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=11617589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T01:15:02+00:00, last15m_closed_end=2026-11-07T01:15+00:00, prior8high=0.145700, depth_time=2026-11-07T01:15:05+00:00, book20_bid_proxy_usdt=149879, book20_ask_proxy_usdt=153670, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-25.15%, turnover=34588185. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
