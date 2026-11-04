# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T21:00:26Z**
- feed_generated_utc: 2026-11-04T21:00:28+00:00
- source_sha256: `5c454e9d93dbd37ab549a86a41c2c420726deb247222b9baa891774eeb1d0b89`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T21:00+00:00, close=80098.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T21:00+00:00, close=80098.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002655|-16.74|-86.78|-16.55|16648689|3.77|
|TRUMPOFFICIAL_USDT|1.282000|-10.09|-24.98|-9.90|25216618|7.80|
|BTW_USDT|1.035000|-6.47|-40.44|-6.28|6346186|0.97|
|PUMPFUN_USDT|0.004215|-4.78|0.19|-4.59|19052391|2.37|
|ZRO_USDT|1.801900|-4.64|5.25|-4.45|11136105|1.11|
|IDOL_USDT|0.021256|-4.01|145.53|-3.82|6303729|4.24|
|WLD_USDT|0.376200|-3.66|-13.07|-3.47|76505694|2.66|
|HYPE_USDT|83.632000|-3.08|4.72|-2.89|90102463|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002655|0.002455|0.002655|0.58|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.035000|1.036000|1.035000|0.84|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.632000|83.096000|83.632000|2.54|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021256|0.021140|0.021256|0.74|N|Y/N|N/N|N|N|
|PUMPFUN_USDT|0.004215|0.004138|0.004215|0.09|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.282000|1.275000|1.282000|0.23|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.376200|0.370800|0.376200|0.88|N|Y/Y|Y/N|N|N|
|ZRO_USDT|1.801900|1.757900|1.801900|0.29|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=0.002656, depth_time=2026-11-04T21:00:08+00:00, book20_bid_proxy_usdt=98264, book20_ask_proxy_usdt=36579, funding_indicative=-0.000614, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.74%, turnover=16648689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=1.079200, depth_time=2026-11-04T21:00:11+00:00, book20_bid_proxy_usdt=18380, book20_ask_proxy_usdt=22249, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.47%, turnover=6346186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=84.880000, depth_time=2026-11-04T21:00:24+00:00, book20_bid_proxy_usdt=76440, book20_ask_proxy_usdt=189050, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=90102463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=0.023600, depth_time=2026-11-04T21:00:20+00:00, book20_bid_proxy_usdt=3427, book20_ask_proxy_usdt=7074, funding_indicative=0.000220, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=6303729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=0.004240, depth_time=2026-11-04T21:00:15+00:00, book20_bid_proxy_usdt=1255733, book20_ask_proxy_usdt=2157681, funding_indicative=0.000049, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=19052391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=1.310000, depth_time=2026-11-04T21:00:09+00:00, book20_bid_proxy_usdt=1281040, book20_ask_proxy_usdt=905915, funding_indicative=-0.000262, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.09%, turnover=25216618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T21:00:00+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=0.380100, depth_time=2026-11-04T21:00:21+00:00, book20_bid_proxy_usdt=914094, book20_ask_proxy_usdt=2370215, funding_indicative=-0.000497, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=76505694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T21:00:01+00:00, last15m_closed_end=2026-11-04T21:00+00:00, prior8high=1.805800, depth_time=2026-11-04T21:00:18+00:00, book20_bid_proxy_usdt=42114, book20_ask_proxy_usdt=20744, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=11136105. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
