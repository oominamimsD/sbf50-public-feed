# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T03:00:26Z**
- feed_generated_utc: 2026-11-01T03:00:28+00:00
- source_sha256: `6dec3aa64e244966accd28e6ba33684bb8a7efe1f7bfc9685a3e00dcde287065`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T03:00+00:00, close=77690, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T03:00+00:00, close=77690, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.008603|-22.75|-70.56|-22.91|11476738|6.98|
|LSK_USDT|0.229200|-22.60|36.49|-22.76|29726699|0.87|
|BLESS_USDT|0.009266|-13.09|14.21|-13.25|7122698|7.56|
|ENA_USDT|0.186170|-4.04|-0.33|-4.20|44136587|0.54|
|BTW_USDT|1.099300|-3.68|-36.86|-3.84|5188981|0.91|
|ZEC_USDT|1240.710000|-3.41|8.33|-3.57|969639790|0.08|
|TRX_USDT|0.309670|-1.77|-5.85|-1.93|10889269|1.29|
|FARTCOIN_USDT|0.119940|-1.02|-1.67|-1.18|6302256|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.008603|0.008615|0.008584|8.08|Y|Y/Y|Y/Y|Y|Y|
|BLESS_USDT|0.009266|0.009219|0.009266|0.22|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.099300|1.054400|1.099700|1.57|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.186170|0.186680|0.186170|1.59|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.119940|0.119770|0.119940|1.12|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.229200|0.230260|0.228860|0.91|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.309670|0.304130|0.309670|0.16|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1240.710000|1243.720000|1240.700000|0.94|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=0.011523, depth_time=2026-11-01T03:00:08+00:00, book20_bid_proxy_usdt=3702, book20_ask_proxy_usdt=68691, funding_indicative=-0.001753, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-22.75%, turnover=11476738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=0.009592, depth_time=2026-11-01T03:00:13+00:00, book20_bid_proxy_usdt=16941, book20_ask_proxy_usdt=10417, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.09%, turnover=7122698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=1.139700, depth_time=2026-11-01T03:00:18+00:00, book20_bid_proxy_usdt=13407, book20_ask_proxy_usdt=8917, funding_indicative=-0.000298, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=5188981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=0.190060, depth_time=2026-11-01T03:00:16+00:00, book20_bid_proxy_usdt=151539, book20_ask_proxy_usdt=181070, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=44136587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T03:00:03+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=0.120890, depth_time=2026-11-01T03:00:25+00:00, book20_bid_proxy_usdt=74713, book20_ask_proxy_usdt=89392, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.02%, turnover=6302256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=0.246820, depth_time=2026-11-01T03:00:10+00:00, book20_bid_proxy_usdt=9958, book20_ask_proxy_usdt=13072, funding_indicative=-0.001099, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-22.60%, turnover=29726699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=0.309960, depth_time=2026-11-01T03:00:22+00:00, book20_bid_proxy_usdt=380808, book20_ask_proxy_usdt=147292, funding_indicative=-0.001463, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=10889269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T03:00:02+00:00, last15m_closed_end=2026-11-01T03:00+00:00, prior8high=1263.460000, depth_time=2026-11-01T03:00:21+00:00, book20_bid_proxy_usdt=1126641, book20_ask_proxy_usdt=45402, funding_indicative=-0.000104, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=969639790. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
