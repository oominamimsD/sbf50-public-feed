# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T03:45:24Z**
- feed_generated_utc: 2026-11-05T03:45:25+00:00
- source_sha256: `89e9c1c11879831fc397593057e06e30cd4f1df3d37c0162d956a6dc5245d43b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T03:45+00:00, close=80703.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T03:00+00:00, close=80544.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002463|-12.34|-87.74|-12.86|16973586|8.12|
|CLANKER_USDT|16.660000|-10.47|24.70|-10.99|20264468|5.99|
|IDOL_USDT|0.021132|-9.95|144.10|-10.47|5792314|0.95|
|TRUMPOFFICIAL_USDT|1.283000|-9.90|-24.92|-10.42|27075140|7.80|
|VVV_USDT|21.778000|-5.93|-8.56|-6.45|5058082|0.92|
|WLD_USDT|0.377500|-3.72|-12.77|-4.24|73137038|2.65|
|HYPE_USDT|83.935000|-2.29|5.10|-2.81|88798211|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002463|0.002197|0.002463|0.74|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.660000|16.230000|16.660000|0.48|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.935000|83.918000|83.953000|0.98|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021132|0.021092|0.021132|1.23|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.283000|1.228000|1.283000|0.99|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.778000|21.043000|21.778000|0.33|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377500|0.372900|0.377500|0.76|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=0.002642, depth_time=2026-11-05T03:45:07+00:00, book20_bid_proxy_usdt=40405, book20_ask_proxy_usdt=51310, funding_indicative=-0.000516, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.34%, turnover=16973586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=17.830000, depth_time=2026-11-05T03:45:09+00:00, book20_bid_proxy_usdt=143498, book20_ask_proxy_usdt=109135, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.47%, turnover=20264468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=84.644000, depth_time=2026-11-05T03:45:22+00:00, book20_bid_proxy_usdt=229115, book20_ask_proxy_usdt=216683, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=88798211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=0.021639, depth_time=2026-11-05T03:45:06+00:00, book20_bid_proxy_usdt=2449, book20_ask_proxy_usdt=17046, funding_indicative=0.000067, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.95%, turnover=5792314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=1.276000, depth_time=2026-11-05T03:45:15+00:00, book20_bid_proxy_usdt=1331378, book20_ask_proxy_usdt=1160316, funding_indicative=-0.000292, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.90%, turnover=27075140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=21.737000, depth_time=2026-11-05T03:45:15+00:00, book20_bid_proxy_usdt=22601, book20_ask_proxy_usdt=25143, funding_indicative=-0.000211, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.93%, turnover=5058082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T03:45:03+00:00, last15m_closed_end=2026-11-05T03:45+00:00, prior8high=0.380500, depth_time=2026-11-05T03:45:20+00:00, book20_bid_proxy_usdt=2843698, book20_ask_proxy_usdt=2017748, funding_indicative=-0.000344, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=73137038. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
