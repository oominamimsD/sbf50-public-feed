# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T22:30:26Z**
- feed_generated_utc: 2026-11-05T22:30:28+00:00
- source_sha256: `d91fa242c1c47916a29c2042263c92c28252a9d2c552317cdd3d49e8903b372d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T22:30+00:00, close=75974.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T22:00+00:00, close=75826.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002239|-13.21|-89.36|-13.17|19556899|4.46|
|FLUID_USDT|2.390000|-5.60|15.79|-5.56|8035615|8.37|
|BCH_USDT|271.110000|-2.86|-5.95|-2.82|8893936|3.32|
|ATOM_USDT|1.384000|-2.53|-15.14|-2.49|5323736|7.23|
|XRP_USDT|1.222200|-1.79|-6.66|-1.75|436640050|0.82|
|QNT_USDT|188.690000|-1.63|-5.05|-1.59|43220978|1.59|
|HYPE_USDT|77.604000|-1.39|-17.38|-1.35|89395727|0.13|
|ONDO_USDT|0.367600|-1.31|-14.47|-1.27|30021115|2.72|
|ZRO_USDT|1.601200|-1.29|-9.24|-1.25|7070448|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002239|0.002015|0.002239|0.27|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.384000|1.387000|1.384000|1.56|Y|Y/Y|Y/N|Y|N|
|BCH_USDT|271.110000|270.070000|271.110000|0.45|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.390000|2.347000|2.390000|0.80|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.604000|76.900000|77.604000|0.46|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.367600|0.367400|0.367600|0.89|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.690000|187.390000|188.660000|1.20|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.222200|1.217300|1.222200|0.44|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.601200|1.594300|1.601200|1.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=0.002263, depth_time=2026-11-05T22:30:06+00:00, book20_bid_proxy_usdt=33984, book20_ask_proxy_usdt=58100, funding_indicative=-0.000726, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.21%, turnover=19556899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=1.447000, depth_time=2026-11-05T22:30:13+00:00, book20_bid_proxy_usdt=2047624, book20_ask_proxy_usdt=1890705, funding_indicative=-0.000060, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=5323736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=278.650000, depth_time=2026-11-05T22:30:09+00:00, book20_bid_proxy_usdt=47598, book20_ask_proxy_usdt=67595, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=8893936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=2.407000, depth_time=2026-11-05T22:30:07+00:00, book20_bid_proxy_usdt=187121, book20_ask_proxy_usdt=122105, funding_indicative=0.000155, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.60%, turnover=8035615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=78.964000, depth_time=2026-11-05T22:30:20+00:00, book20_bid_proxy_usdt=229296, book20_ask_proxy_usdt=68125, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=89395727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=0.375900, depth_time=2026-11-05T22:30:23+00:00, book20_bid_proxy_usdt=1727644, book20_ask_proxy_usdt=1371761, funding_indicative=-0.000035, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=30021115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=191.110000, depth_time=2026-11-05T22:30:17+00:00, book20_bid_proxy_usdt=54841, book20_ask_proxy_usdt=86104, funding_indicative=-0.000008, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=43220978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=1.243800, depth_time=2026-11-05T22:30:15+00:00, book20_bid_proxy_usdt=3093603, book20_ask_proxy_usdt=2753938, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=436640050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T22:30:01+00:00, last15m_closed_end=2026-11-05T22:30+00:00, prior8high=1.647700, depth_time=2026-11-05T22:30:25+00:00, book20_bid_proxy_usdt=50712, book20_ask_proxy_usdt=169197, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=7070448. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
