# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T14:30:37Z**
- feed_generated_utc: 2026-10-31T14:30:39+00:00
- source_sha256: `d76c697ab2108bc1ae10d693efd43b76deb08714e92c01a12813ac58da064842`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T14:30+00:00, close=77421.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T14:00+00:00, close=77477.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011191|-40.85|-68.02|-40.65|11806418|4.47|
|Q_USDT|0.032210|-32.16|-72.78|-31.96|11754498|3.10|
|BEAT_USDT|0.097600|-7.18|34.45|-6.98|6921907|2.05|
|HYPE_USDT|86.386000|-6.45|10.18|-6.25|97555737|0.12|
|TRX_USDT|0.316460|-5.67|-3.91|-5.47|6603076|0.32|
|BTW_USDT|1.145000|-4.54|-32.74|-4.34|8124858|4.36|
|WLD_USDT|0.395400|-4.00|-25.73|-3.80|40112686|2.53|
|FET_USDT|0.161300|-3.18|-13.88|-2.98|5869727|6.20|
|DASH_USDT|48.010000|-2.10|-10.84|-1.90|7874095|2.08|
|IDOL_USDT|0.019834|-2.01|150.42|-1.81|15853943|3.52|
|PEPE_USDT|0.000005|-1.94|2.07|-1.74|101379709|0.60|
|DOT_USDT|0.950800|-1.89|-15.61|-1.69|8416778|3.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011191|0.011295|0.011191|1.60|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097600|0.098560|0.097780|1.58|Y|Y/Y|N/N|Y|N|
|BTW_USDT|1.145000|1.081300|1.144800|1.07|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.010000|47.750000|48.030000|0.11|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.950800|0.951100|0.951400|0.74|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161300|0.160500|0.161300|0.68|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.386000|86.485000|86.372000|1.49|Y|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019834|0.018799|0.019834|0.90|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.29|N|Y/N|N/N|Y|N|
|Q_USDT|0.032210|0.031490|0.032210|0.31|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.316460|0.316970|0.316460|0.71|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395400|0.395300|0.395400|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T14:30:02+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.012080, depth_time=2026-10-31T14:30:09+00:00, book20_bid_proxy_usdt=7033, book20_ask_proxy_usdt=10646, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-40.85%, turnover=11806418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.101380, depth_time=2026-10-31T14:30:13+00:00, book20_bid_proxy_usdt=7645, book20_ask_proxy_usdt=12838, funding_indicative=0.000121, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.18%, turnover=6921907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=1.198400, depth_time=2026-10-31T14:30:20+00:00, book20_bid_proxy_usdt=15191, book20_ask_proxy_usdt=11671, funding_indicative=-0.000238, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.54%, turnover=8124858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=48.210000, depth_time=2026-10-31T14:30:27+00:00, book20_bid_proxy_usdt=620378, book20_ask_proxy_usdt=711480, funding_indicative=-0.000152, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=7874095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.958600, depth_time=2026-10-31T14:30:36+00:00, book20_bid_proxy_usdt=481930, book20_ask_proxy_usdt=291349, funding_indicative=0.000009, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=8416778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.161800, depth_time=2026-10-31T14:30:26+00:00, book20_bid_proxy_usdt=1505669, book20_ask_proxy_usdt=891490, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=5869727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T14:30:02+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=88.704000, depth_time=2026-10-31T14:30:16+00:00, book20_bid_proxy_usdt=189746, book20_ask_proxy_usdt=74448, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.45%, turnover=97555737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T14:30:02+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.020534, depth_time=2026-10-31T14:30:30+00:00, book20_bid_proxy_usdt=7604, book20_ask_proxy_usdt=4040, funding_indicative=0.000251, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=15853943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T14:30:02+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.000005, depth_time=2026-10-31T14:30:33+00:00, book20_bid_proxy_usdt=22381, book20_ask_proxy_usdt=43138, funding_indicative=-0.000807, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=101379709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T14:30:02+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.032810, depth_time=2026-10-31T14:30:11+00:00, book20_bid_proxy_usdt=70759, book20_ask_proxy_usdt=40705, funding_indicative=-0.000496, next_funding_utc=2026-10-31T15:00:00+00:00, funding_cycle_h=1, 24h_change=-32.16%, turnover=11754498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.322470, depth_time=2026-10-31T14:30:18+00:00, book20_bid_proxy_usdt=69191, book20_ask_proxy_usdt=80398, funding_indicative=-0.000693, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.67%, turnover=6603076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T14:30:03+00:00, last15m_closed_end=2026-10-31T14:30+00:00, prior8high=0.399000, depth_time=2026-10-31T14:30:23+00:00, book20_bid_proxy_usdt=3673467, book20_ask_proxy_usdt=3488236, funding_indicative=0.000099, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=40112686. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
