# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T09:45:37Z**
- feed_generated_utc: 2026-10-31T09:45:40+00:00
- source_sha256: `db20781be42f0c0f6d2a0508785d96b959aa07212fc14bcd4fa6246ab7a74dfc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T09:45+00:00, close=77400.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T09:00+00:00, close=77320.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010459|-44.72|-70.11|-44.49|10142476|8.59|
|Q_USDT|0.031470|-33.71|-73.40|-33.48|15533427|3.17|
|IDOL_USDT|0.018673|-7.75|135.77|-7.52|15798026|5.36|
|HYPE_USDT|86.941000|-5.85|10.88|-5.62|104252871|0.12|
|TRX_USDT|0.316990|-5.51|-3.74|-5.28|7156632|0.32|
|BTW_USDT|1.136900|-5.21|-33.21|-4.98|9212415|2.63|
|BEAT_USDT|0.100380|-4.53|38.28|-4.30|8254511|1.00|
|EVAA_USDT|1.235600|-3.62|135.39|-3.39|5413602|4.05|
|WLD_USDT|0.397300|-3.54|-25.37|-3.31|49066951|2.52|
|FET_USDT|0.161900|-2.82|-13.56|-2.59|5979481|6.18|
|DASH_USDT|47.760000|-2.61|-11.30|-2.38|13342211|2.09|
|LTC_USDT|54.940000|-1.39|-6.00|-1.16|6527976|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010459|0.009146|0.010459|0.99|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100380|0.096500|0.100380|0.24|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.136900|1.124400|1.136900|0.53|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.760000|47.590000|47.760000|0.05|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.235600|1.198100|1.235600|0.85|N|N/N|N/N|Y|N|
|FET_USDT|0.161900|0.161500|0.161900|3.51|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.941000|86.343000|86.941000|0.75|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.018673|0.018443|0.018696|1.34|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.940000|54.520000|54.920000|5.85|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031470|0.031730|0.031480|1.83|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.316990|0.317860|0.316990|19.28|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.397300|0.394600|0.397300|1.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.013245, depth_time=2026-10-31T09:45:09+00:00, book20_bid_proxy_usdt=6236, book20_ask_proxy_usdt=12460, funding_indicative=-0.000904, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-44.72%, turnover=10142476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.100780, depth_time=2026-10-31T09:45:21+00:00, book20_bid_proxy_usdt=10554, book20_ask_proxy_usdt=16043, funding_indicative=0.000169, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=8254511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=1.181700, depth_time=2026-10-31T09:45:21+00:00, book20_bid_proxy_usdt=18509, book20_ask_proxy_usdt=10691, funding_indicative=-0.000150, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=9212415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=47.970000, depth_time=2026-10-31T09:45:34+00:00, book20_bid_proxy_usdt=887140, book20_ask_proxy_usdt=758905, funding_indicative=-0.000048, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=13342211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=1.272600, depth_time=2026-10-31T09:45:26+00:00, book20_bid_proxy_usdt=37757, book20_ask_proxy_usdt=12861, funding_indicative=0.000280, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=5413602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.163200, depth_time=2026-10-31T09:45:30+00:00, book20_bid_proxy_usdt=1130726, book20_ask_proxy_usdt=1058530, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=5979481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=88.615000, depth_time=2026-10-31T09:45:16+00:00, book20_bid_proxy_usdt=190766, book20_ask_proxy_usdt=80871, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=104252871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T09:45:00+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.023319, depth_time=2026-10-31T09:45:13+00:00, book20_bid_proxy_usdt=27930, book20_ask_proxy_usdt=4480, funding_indicative=0.000216, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.75%, turnover=15798026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=55.110000, depth_time=2026-10-31T09:45:33+00:00, book20_bid_proxy_usdt=1297601, book20_ask_proxy_usdt=1152673, funding_indicative=0.000002, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=6527976. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.033810, depth_time=2026-10-31T09:45:11+00:00, book20_bid_proxy_usdt=47943, book20_ask_proxy_usdt=65653, funding_indicative=-0.000634, next_funding_utc=2026-10-31T10:00:00+00:00, funding_cycle_h=1, 24h_change=-33.71%, turnover=15533427. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.323040, depth_time=2026-10-31T09:45:19+00:00, book20_bid_proxy_usdt=597426, book20_ask_proxy_usdt=144973, funding_indicative=-0.000594, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.51%, turnover=7156632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T09:45:01+00:00, last15m_closed_end=2026-10-31T09:45+00:00, prior8high=0.399700, depth_time=2026-10-31T09:45:29+00:00, book20_bid_proxy_usdt=2763631, book20_ask_proxy_usdt=2589304, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=49066951. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
