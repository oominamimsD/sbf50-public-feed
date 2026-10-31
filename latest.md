# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T11:30:32Z**
- feed_generated_utc: 2026-10-31T11:30:34+00:00
- source_sha256: `fece759ea19d9f0208462ac779eaf53908d2bc2d1ef5138e40cd1c6c43e81d31`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T11:30+00:00, close=77411.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T11:00+00:00, close=77376.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011537|-39.02|-67.03|-38.81|10770544|5.20|
|Q_USDT|0.031750|-33.12|-73.16|-32.91|13141261|3.15|
|HYPE_USDT|87.796000|-4.92|11.97|-4.71|97031371|0.11|
|TRX_USDT|0.319800|-4.67|-2.89|-4.46|7089608|1.56|
|BTW_USDT|1.144900|-4.55|-32.74|-4.34|8925607|0.87|
|WLD_USDT|0.395400|-4.00|-25.73|-3.79|45803027|2.53|
|FET_USDT|0.161500|-3.06|-13.77|-2.85|5867139|6.19|
|IDOL_USDT|0.019647|-2.93|148.06|-2.72|16102617|3.56|
|DASH_USDT|47.820000|-2.48|-11.19|-2.27|11628187|2.09|
|LTC_USDT|54.940000|-1.39|-6.00|-1.18|6094581|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011537|0.010360|0.011538|2.65|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.144900|1.118100|1.144900|1.44|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.820000|47.700000|47.820000|0.64|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161500|0.160800|0.161500|0.41|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.796000|86.889000|87.788000|0.26|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019647|0.017952|0.019691|1.68|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.940000|54.670000|54.940000|0.11|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031750|0.031080|0.031790|1.37|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.319800|0.315970|0.319800|0.84|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395400|0.394500|0.395300|0.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=0.011271, depth_time=2026-10-31T11:30:08+00:00, book20_bid_proxy_usdt=13130, book20_ask_proxy_usdt=7486, funding_indicative=-0.000001, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.02%, turnover=10770544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=1.141100, depth_time=2026-10-31T11:30:18+00:00, book20_bid_proxy_usdt=21219, book20_ask_proxy_usdt=13601, funding_indicative=-0.000243, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=8925607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T11:30:00+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=48.060000, depth_time=2026-10-31T11:30:27+00:00, book20_bid_proxy_usdt=814610, book20_ask_proxy_usdt=603000, funding_indicative=-0.000139, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=11628187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=0.162300, depth_time=2026-10-31T11:30:23+00:00, book20_bid_proxy_usdt=1360140, book20_ask_proxy_usdt=1080787, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=5867139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=88.220000, depth_time=2026-10-31T11:30:13+00:00, book20_bid_proxy_usdt=157111, book20_ask_proxy_usdt=97530, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.92%, turnover=97031371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=0.019981, depth_time=2026-10-31T11:30:25+00:00, book20_bid_proxy_usdt=6858, book20_ask_proxy_usdt=8534, funding_indicative=0.000250, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=16102617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=55.000000, depth_time=2026-10-31T11:30:28+00:00, book20_bid_proxy_usdt=1128983, book20_ask_proxy_usdt=1553398, funding_indicative=-0.000054, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=6094581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=0.033810, depth_time=2026-10-31T11:30:11+00:00, book20_bid_proxy_usdt=83984, book20_ask_proxy_usdt=52430, funding_indicative=-0.000578, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=1, 24h_change=-33.12%, turnover=13141261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=0.320100, depth_time=2026-10-31T11:30:15+00:00, book20_bid_proxy_usdt=27376, book20_ask_proxy_usdt=31886, funding_indicative=-0.001134, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.67%, turnover=7089608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T11:30:03+00:00, last15m_closed_end=2026-10-31T11:30+00:00, prior8high=0.398300, depth_time=2026-10-31T11:30:20+00:00, book20_bid_proxy_usdt=3619379, book20_ask_proxy_usdt=3463888, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=45803027. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
