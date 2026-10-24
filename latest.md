# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T22:30:21Z**
- feed_generated_utc: 2026-10-24T22:30:25+00:00
- source_sha256: `4d67820f227e42bdb80d2b419d1467724df5c830964afee1fe055e89b45684ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T22:30+00:00, close=80472.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T22:00+00:00, close=80383.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.056120|-16.73|81.32|-17.62|12772193|3.56|
|BIRB_USDT|0.086040|-11.89|77.32|-12.78|11694759|1.16|
|IRYS_USDT|0.043610|-5.29|241.77|-6.18|36156472|2.29|
|BTW_USDT|1.688600|-3.02|-25.59|-3.91|11575971|2.96|
|STRK_USDT|0.046230|-1.06|-30.11|-1.95|8935414|2.16|
|DOT_USDT|1.036100|-0.28|-7.27|-1.17|12422380|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.086040|0.083640|0.086010|1.22|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.688600|1.713800|1.688100|2.42|Y|N/N|Y/Y|Y|N|
|DOT_USDT|1.036100|1.033000|1.036600|0.57|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.043610|0.042610|0.043610|0.62|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.056120|0.054530|0.056120|0.74|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046230|0.046250|0.046230|0.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T22:30:01+00:00, last15m_closed_end=2026-10-24T22:30+00:00, prior8high=0.094010, depth_time=2026-10-24T22:30:11+00:00, book20_bid_proxy_usdt=18511, book20_ask_proxy_usdt=15297, funding_indicative=-0.008680, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.89%, turnover=11694759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T22:30:01+00:00, last15m_closed_end=2026-10-24T22:30+00:00, prior8high=1.761200, depth_time=2026-10-24T22:30:15+00:00, book20_bid_proxy_usdt=15349, book20_ask_proxy_usdt=23813, funding_indicative=-0.005588, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=11575971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T22:30:02+00:00, last15m_closed_end=2026-10-24T22:30+00:00, prior8high=1.042700, depth_time=2026-10-24T22:30:20+00:00, book20_bid_proxy_usdt=367475, book20_ask_proxy_usdt=338661, funding_indicative=-0.000085, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.28%, turnover=12422380. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T22:30:01+00:00, last15m_closed_end=2026-10-24T22:30+00:00, prior8high=0.045590, depth_time=2026-10-24T22:30:13+00:00, book20_bid_proxy_usdt=58145, book20_ask_proxy_usdt=79408, funding_indicative=0.000012, next_funding_utc=2026-10-24T23:00:00+00:00, funding_cycle_h=1, 24h_change=-5.29%, turnover=36156472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T22:30:01+00:00, last15m_closed_end=2026-10-24T22:30+00:00, prior8high=0.064800, depth_time=2026-10-24T22:30:08+00:00, book20_bid_proxy_usdt=75595, book20_ask_proxy_usdt=55736, funding_indicative=-0.000988, next_funding_utc=2026-10-24T23:00:00+00:00, funding_cycle_h=1, 24h_change=-16.73%, turnover=12772193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T22:30:02+00:00, last15m_closed_end=2026-10-24T22:30+00:00, prior8high=0.047250, depth_time=2026-10-24T22:30:18+00:00, book20_bid_proxy_usdt=1108277, book20_ask_proxy_usdt=1157313, funding_indicative=0.000037, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=8935414. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
