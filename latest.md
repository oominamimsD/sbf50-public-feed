# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T03:00:27Z**
- feed_generated_utc: 2026-10-31T03:00:29+00:00
- source_sha256: `74e3d5733b641009f117f2339c982254600b645b79828320ce62b5f22f3cb9da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T03:00+00:00, close=77402.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T03:00+00:00, close=77402.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.028460|-40.05|-75.95|-39.82|19668463|7.06|
|AKE_USDT|0.011810|-37.58|-66.25|-37.35|6679677|1.70|
|BLESS_USDT|0.009547|-29.30|16.98|-29.07|12442599|2.10|
|BEAT_USDT|0.098450|-6.88|35.62|-6.65|8652992|1.01|
|PEPE_USDT|0.000005|-3.86|1.70|-3.63|142510692|2.83|
|TRX_USDT|0.325680|-3.18|-1.11|-2.95|7615957|0.31|
|HYPE_USDT|89.678000|-2.88|14.37|-2.65|115110927|0.11|
|LIT_USDT|2.772000|-1.84|-16.60|-1.61|5919508|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011810|0.011547|0.011865|1.17|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098450|0.096210|0.098450|1.00|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009547|0.009190|0.009547|1.61|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|89.678000|89.156000|89.681000|0.46|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.772000|2.751900|2.771100|1.81|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.53|N|Y/Y|N/N|Y|N|
|Q_USDT|0.028460|0.030910|0.028480|5.38|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.325680|0.321930|0.325680|2.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=0.013801, depth_time=2026-10-31T03:00:11+00:00, book20_bid_proxy_usdt=5121, book20_ask_proxy_usdt=25907, funding_indicative=-0.000091, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-37.58%, turnover=6679677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=0.105150, depth_time=2026-10-31T03:00:15+00:00, book20_bid_proxy_usdt=10266, book20_ask_proxy_usdt=10097, funding_indicative=0.000117, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.88%, turnover=8652992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=0.009805, depth_time=2026-10-31T03:00:14+00:00, book20_bid_proxy_usdt=17425, book20_ask_proxy_usdt=10863, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-29.30%, turnover=12442599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=90.160000, depth_time=2026-10-31T03:00:24+00:00, book20_bid_proxy_usdt=70652, book20_ask_proxy_usdt=136886, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=115110927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T03:00:04+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=2.792700, depth_time=2026-10-31T03:00:26+00:00, book20_bid_proxy_usdt=23417, book20_ask_proxy_usdt=19672, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=5919508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=0.000005, depth_time=2026-10-31T03:00:19+00:00, book20_bid_proxy_usdt=27654, book20_ask_proxy_usdt=38011, funding_indicative=-0.000211, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=142510692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=0.044420, depth_time=2026-10-31T03:00:09+00:00, book20_bid_proxy_usdt=38742, book20_ask_proxy_usdt=84487, funding_indicative=-0.013644, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-40.05%, turnover=19668463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T03:00:03+00:00, last15m_closed_end=2026-10-31T03:00+00:00, prior8high=0.327100, depth_time=2026-10-31T03:00:21+00:00, book20_bid_proxy_usdt=62232, book20_ask_proxy_usdt=32838, funding_indicative=-0.001659, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=7615957. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
