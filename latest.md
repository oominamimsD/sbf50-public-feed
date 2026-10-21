# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T03:15:23Z**
- feed_generated_utc: 2026-10-21T03:15:26+00:00
- source_sha256: `01c55ea44b9b63b600bb242eba321c8e37cb5337aab4991bda898d656de907cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T03:15+00:00, close=82751.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T03:00+00:00, close=82770, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186080|-13.76|4.90|-13.96|10466997|1.07|
|XMR_USDT|577.380000|-6.90|9.37|-7.10|20206565|0.52|
|Q_USDT|0.116731|-4.90|183.83|-5.10|5043966|1.11|
|BR_USDT|0.620020|-4.71|43.18|-4.91|35330496|0.16|
|AGT_USDT|0.062285|-3.62|285.02|-3.82|6923386|2.24|
|TIA_USDT|0.610100|-2.02|5.68|-2.22|48511670|3.28|
|SEI_USDT|0.061080|-0.89|-2.06|-1.09|6212244|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062285|0.061412|0.062285|0.88|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186080|0.186500|0.186080|1.53|Y|Y/Y|N/N|N|N|
|BR_USDT|0.620020|0.614910|0.621640|0.76|N|Y/Y|N/N|N|N|
|Q_USDT|0.116731|0.116120|0.116731|0.68|N|Y/Y|N/N|N|N|
|SEI_USDT|0.061080|0.060850|0.061080|1.29|N|N/N|Y/Y|N|N|
|TIA_USDT|0.610100|0.605800|0.610100|0.27|N|Y/Y|Y/Y|N|N|
|XMR_USDT|577.380000|572.610000|577.400000|0.46|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T03:15:02+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=0.066868, depth_time=2026-10-21T03:15:18+00:00, book20_bid_proxy_usdt=7073, book20_ask_proxy_usdt=12288, funding_indicative=0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=6923386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T03:14:59+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=0.192280, depth_time=2026-10-21T03:15:08+00:00, book20_bid_proxy_usdt=37232, book20_ask_proxy_usdt=27568, funding_indicative=0.000046, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.76%, turnover=10466997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T03:15:02+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=0.664000, depth_time=2026-10-21T03:15:14+00:00, book20_bid_proxy_usdt=3751, book20_ask_proxy_usdt=2130, funding_indicative=-0.000018, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.71%, turnover=35330496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T03:15:02+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=0.123292, depth_time=2026-10-21T03:15:12+00:00, book20_bid_proxy_usdt=15416, book20_ask_proxy_usdt=21259, funding_indicative=-0.000140, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.90%, turnover=5043966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T03:14:59+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=0.061880, depth_time=2026-10-21T03:15:19+00:00, book20_bid_proxy_usdt=241004, book20_ask_proxy_usdt=467511, funding_indicative=-0.000081, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=6212244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T03:14:59+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=0.619700, depth_time=2026-10-21T03:15:20+00:00, book20_bid_proxy_usdt=273578, book20_ask_proxy_usdt=220453, funding_indicative=-0.000049, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=48511670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T03:14:59+00:00, last15m_closed_end=2026-10-21T03:15+00:00, prior8high=601.630000, depth_time=2026-10-21T03:15:10+00:00, book20_bid_proxy_usdt=10215, book20_ask_proxy_usdt=15178, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.90%, turnover=20206565. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
