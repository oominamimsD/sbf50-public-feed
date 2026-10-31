# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T22:30:30Z**
- feed_generated_utc: 2026-10-31T22:30:32+00:00
- source_sha256: `a823207a77ed283f6f8db9ae2e9c9dca433cd4ee59984218a3fa24d2602929e4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T22:30+00:00, close=77627.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T22:00+00:00, close=77631.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.246000|-16.93|46.49|-17.01|28122518|4.07|
|BLESS_USDT|0.009489|-10.17|16.96|-10.25|7961567|2.11|
|TRX_USDT|0.301050|-3.61|-8.47|-3.69|10237845|0.33|
|IDOL_USDT|0.017073|-2.55|116.11|-2.63|6706502|3.52|
|BTW_USDT|1.095900|-2.31|-37.06|-2.39|5639120|0.91|
|FET_USDT|0.160100|-1.95|-7.08|-2.03|5691738|6.24|
|WLD_USDT|0.399100|-1.31|-13.61|-1.39|34490263|2.51|
|APT_USDT|0.633300|-1.17|-9.77|-1.25|5037302|1.58|
|Q_USDT|0.031730|-1.09|-59.80|-1.17|10546145|3.15|
|FARTCOIN_USDT|0.120770|-1.00|-0.99|-1.08|6122518|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.633300|0.629300|0.633300|0.41|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009489|0.009313|0.009489|0.90|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.095900|1.094100|1.095900|1.07|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120770|0.120130|0.120770|1.12|N|N/Y|Y/Y|Y|N|
|FET_USDT|0.160100|0.159500|0.160200|0.42|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.017073|0.016323|0.017073|0.47|N|Y/Y|N/N|Y|N|
|LSK_USDT|0.246000|0.237060|0.246000|0.54|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031730|0.031610|0.031730|0.50|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.301050|0.301700|0.301050|1.16|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399100|0.394900|0.399200|0.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.638000, depth_time=2026-10-31T22:30:23+00:00, book20_bid_proxy_usdt=118178, book20_ask_proxy_usdt=172892, funding_indicative=0.000066, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=5037302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.010161, depth_time=2026-10-31T22:30:10+00:00, book20_bid_proxy_usdt=10522, book20_ask_proxy_usdt=9837, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.17%, turnover=7961567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=1.131000, depth_time=2026-10-31T22:30:18+00:00, book20_bid_proxy_usdt=20445, book20_ask_proxy_usdt=22674, funding_indicative=-0.000211, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=5639120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.121480, depth_time=2026-10-31T22:30:29+00:00, book20_bid_proxy_usdt=82954, book20_ask_proxy_usdt=83743, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=6122518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.161300, depth_time=2026-10-31T22:30:20+00:00, book20_bid_proxy_usdt=1504178, book20_ask_proxy_usdt=1052335, funding_indicative=-0.000214, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=5691738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.017648, depth_time=2026-10-31T22:30:12+00:00, book20_bid_proxy_usdt=5710, book20_ask_proxy_usdt=5767, funding_indicative=0.000096, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=6706502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.249390, depth_time=2026-10-31T22:30:08+00:00, book20_bid_proxy_usdt=12716, book20_ask_proxy_usdt=5400, funding_indicative=-0.000899, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.93%, turnover=28122518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.032920, depth_time=2026-10-31T22:30:27+00:00, book20_bid_proxy_usdt=70789, book20_ask_proxy_usdt=47630, funding_indicative=-0.001102, next_funding_utc=2026-10-31T23:00:00+00:00, funding_cycle_h=1, 24h_change=-1.09%, turnover=10546145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.306800, depth_time=2026-10-31T22:30:13+00:00, book20_bid_proxy_usdt=167651, book20_ask_proxy_usdt=85380, funding_indicative=-0.000867, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=10237845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T22:30:01+00:00, last15m_closed_end=2026-10-31T22:30+00:00, prior8high=0.400500, depth_time=2026-10-31T22:30:22+00:00, book20_bid_proxy_usdt=2453188, book20_ask_proxy_usdt=2640483, funding_indicative=0.000072, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=34490263. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
