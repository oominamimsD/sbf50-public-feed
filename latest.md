# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T06:45:35Z**
- feed_generated_utc: 2026-10-18T06:45:38+00:00
- source_sha256: `94fbe885cb90623891e4b0029fe2b2732243581935745f78f3cd118d0be2c5d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T06:45+00:00, close=81723.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T06:00+00:00, close=81700.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.626100|-4.84|22.04|-5.34|62514473|1.60|
|STRK_USDT|0.063190|-4.47|-32.36|-4.97|14252756|1.58|
|FILECOIN_USDT|1.054100|-3.06|-6.53|-3.56|20276552|0.95|
|EIGEN_USDT|0.248500|-3.04|5.47|-3.54|8446907|4.03|
|QNT_USDT|194.490000|-2.95|-20.65|-3.45|70252791|0.51|
|PUMPFUN_USDT|0.004289|-2.78|-25.08|-3.28|23578065|2.33|
|ZRO_USDT|1.845100|-2.13|-8.68|-2.63|7332632|0.54|
|XPL_USDT|0.078530|-1.99|-9.48|-2.49|5266529|1.27|
|OP_USDT|0.126950|-1.58|-8.37|-2.08|9770121|0.79|
|DOT_USDT|1.104100|-1.19|-12.15|-1.69|17019806|0.91|
|APT_USDT|0.791700|-0.72|-4.24|-1.22|10498635|1.26|
|WLD_USDT|0.492900|-0.54|-11.82|-1.04|60339810|2.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.791700|0.780900|0.791700|1.34|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.104100|1.089000|1.104100|2.31|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.248500|0.244000|0.248600|1.73|N|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.054100|1.040400|1.054000|2.20|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.126950|0.124920|0.126950|0.43|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004289|0.004262|0.004288|1.26|N|Y/Y|Y/Y|N|N|
|QNT_USDT|194.490000|191.970000|194.490000|1.00|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063190|0.062400|0.063190|0.76|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.626100|0.622800|0.626200|2.02|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.492900|0.483600|0.492800|1.18|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.078530|0.077620|0.078540|1.01|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.845100|1.827700|1.845500|5.55|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.792600, depth_time=2026-10-18T06:45:31+00:00, book20_bid_proxy_usdt=164836, book20_ask_proxy_usdt=116835, funding_indicative=-0.000114, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.72%, turnover=10498635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=1.109100, depth_time=2026-10-18T06:45:29+00:00, book20_bid_proxy_usdt=341135, book20_ask_proxy_usdt=325764, funding_indicative=-0.000069, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=17019806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.250600, depth_time=2026-10-18T06:45:11+00:00, book20_bid_proxy_usdt=547905, book20_ask_proxy_usdt=312128, funding_indicative=-0.000037, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=8446907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=1.062400, depth_time=2026-10-18T06:45:12+00:00, book20_bid_proxy_usdt=522176, book20_ask_proxy_usdt=657576, funding_indicative=-0.000095, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=20276552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.128260, depth_time=2026-10-18T06:45:27+00:00, book20_bid_proxy_usdt=95454, book20_ask_proxy_usdt=93058, funding_indicative=-0.000166, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=9770121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.004354, depth_time=2026-10-18T06:45:19+00:00, book20_bid_proxy_usdt=1738721, book20_ask_proxy_usdt=1602333, funding_indicative=0.000043, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=23578065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=196.100000, depth_time=2026-10-18T06:45:16+00:00, book20_bid_proxy_usdt=83311, book20_ask_proxy_usdt=50921, funding_indicative=-0.000068, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=70252791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.063490, depth_time=2026-10-18T06:45:09+00:00, book20_bid_proxy_usdt=473425, book20_ask_proxy_usdt=333855, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.47%, turnover=14252756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.632400, depth_time=2026-10-18T06:45:06+00:00, book20_bid_proxy_usdt=329321, book20_ask_proxy_usdt=274650, funding_indicative=-0.000023, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=62514473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.493600, depth_time=2026-10-18T06:45:34+00:00, book20_bid_proxy_usdt=1871689, book20_ask_proxy_usdt=2028614, funding_indicative=-0.000125, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.54%, turnover=60339810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T06:45:03+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=0.078850, depth_time=2026-10-18T06:45:23+00:00, book20_bid_proxy_usdt=571910, book20_ask_proxy_usdt=557830, funding_indicative=0.000021, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=5266529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T06:45:02+00:00, last15m_closed_end=2026-10-18T06:45+00:00, prior8high=1.887400, depth_time=2026-10-18T06:45:21+00:00, book20_bid_proxy_usdt=44753, book20_ask_proxy_usdt=45043, funding_indicative=0.000041, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=7332632. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
