# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T07:00:15Z**
- feed_generated_utc: 2026-11-04T07:00:17+00:00
- source_sha256: `a49489e35154b8adf20daff231a1419905a6e1af7411335a0dda2030ca5e2690`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T07:00+00:00, close=77970.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T07:00+00:00, close=77970.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.037560|-30.19|-20.95|-30.58|10766918|2.66|
|AKE_USDT|0.003199|-23.02|-84.85|-23.41|12215606|3.12|
|TRUMPOFFICIAL_USDT|1.517000|-5.54|-10.13|-5.93|8708871|6.59|
|Q_USDT|0.028050|-0.77|-55.88|-1.16|7334953|3.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.037560|0.036640|0.037580|0.62|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003199|0.002979|0.003192|0.62|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.028050|0.027450|0.028050|0.93|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.517000|1.501000|1.517000|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T07:00:01+00:00, last15m_closed_end=2026-11-04T07:00+00:00, prior8high=0.038670, depth_time=2026-11-04T07:00:07+00:00, book20_bid_proxy_usdt=34340, book20_ask_proxy_usdt=39408, funding_indicative=0.000168, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-30.19%, turnover=10766918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T07:00:01+00:00, last15m_closed_end=2026-11-04T07:00+00:00, prior8high=0.003370, depth_time=2026-11-04T07:00:10+00:00, book20_bid_proxy_usdt=75082, book20_ask_proxy_usdt=29894, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.02%, turnover=12215606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T07:00:01+00:00, last15m_closed_end=2026-11-04T07:00+00:00, prior8high=0.028280, depth_time=2026-11-04T07:00:14+00:00, book20_bid_proxy_usdt=52257, book20_ask_proxy_usdt=48203, funding_indicative=-0.000324, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.77%, turnover=7334953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T07:00:02+00:00, last15m_closed_end=2026-11-04T07:00+00:00, prior8high=1.536000, depth_time=2026-11-04T07:00:09+00:00, book20_bid_proxy_usdt=2284234, book20_ask_proxy_usdt=2963237, funding_indicative=-0.000081, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=8708871. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
