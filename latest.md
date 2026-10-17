# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T08:45:41Z**
- feed_generated_utc: 2026-10-17T08:45:44+00:00
- source_sha256: `4f5e82679a85e94b48359b54144f50d6321377703b91a72c4b44de0bd4e3aee9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T08:45+00:00, close=81639.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.955000|-6.96|-4.01|-7.34|12463177|0.51|
|OP_USDT|0.135200|-3.42|9.72|-3.80|15113577|0.74|
|RIVER_USDT|1.090000|-3.19|-7.78|-3.57|5073939|9.18|
|APT_USDT|0.829100|-3.15|3.57|-3.53|12086733|1.21|
|ARB_USDT|0.188810|-3.14|4.43|-3.52|27491895|0.53|
|STRK_USDT|0.071770|-2.94|-4.70|-3.32|20289977|1.39|
|FET_USDT|0.194000|-2.80|-10.59|-3.18|12376579|5.16|
|INJ_USDT|8.775000|-2.26|26.64|-2.64|93690573|1.14|
|TAO_USDT|275.420000|-1.85|0.27|-2.23|64407091|1.09|
|FILECOIN_USDT|1.148000|-1.61|7.28|-1.99|24831713|0.87|
|ZEC_USDT|1169.610000|-1.54|-4.00|-1.92|1334879470|0.17|
|SUI_USDT|1.006000|-1.42|-4.87|-1.80|92608905|0.99|
|SEI_USDT|0.063410|-1.38|-3.16|-1.76|19211035|1.58|
|FARTCOIN_USDT|0.152630|-1.35|-6.57|-1.73|7238502|0.66|
|DOT_USDT|1.155800|-1.28|-2.71|-1.66|19645065|0.86|
|ENA_USDT|0.197380|-1.27|-8.44|-1.65|38398875|0.51|
|ICP_USDT|3.000000|-1.25|-0.62|-1.63|8527164|3.33|
|ONDO_USDT|0.452800|-0.94|-5.68|-1.32|28505904|2.21|
|XLM_USDT|0.179260|-0.78|-6.97|-1.16|14776156|0.56|
|LTC_USDT|59.420000|-0.73|-6.57|-1.11|8518236|3.37|
|AAVE_USDT|156.170000|-0.70|-8.04|-1.08|26787397|0.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.829100|0.823300|0.829000|0.98|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.188810|0.188080|0.188810|0.93|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.155800|1.154000|1.155800|0.92|N|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.152630|0.151850|0.152630|1.59|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194000|0.193900|0.194000|3.81|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.148000|1.145400|1.148000|1.66|N|N/N|N/N|Y|N|
|INJ_USDT|8.775000|8.733000|8.775000|0.68|N|N/N|N/N|Y|N|
|OP_USDT|0.135200|0.134820|0.135230|1.81|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.090000|1.070000|1.090000|2.26|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.063410|0.063040|0.063410|0.36|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.071770|0.070610|0.071770|0.87|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.006000|1.005500|1.006000|2.03|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.420000|274.030000|275.420000|0.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1169.610000|1160.060000|1169.610000|0.87|N|N/Y|Y/Y|Y|N|
|ZRO_USDT|1.955000|1.942800|1.955000|1.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.838500, depth_time=2026-10-17T08:45:15+00:00, book20_bid_proxy_usdt=90121, book20_ask_proxy_usdt=132380, funding_indicative=0.000065, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=12086733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.189530, depth_time=2026-10-17T08:45:17+00:00, book20_bid_proxy_usdt=45653, book20_ask_proxy_usdt=73994, funding_indicative=-0.000012, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=27491895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-17T08:45:00+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=1.174800, depth_time=2026-10-17T08:45:40+00:00, book20_bid_proxy_usdt=290184, book20_ask_proxy_usdt=236780, funding_indicative=0.000013, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=19645065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T08:45:00+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.154040, depth_time=2026-10-17T08:45:38+00:00, book20_bid_proxy_usdt=70391, book20_ask_proxy_usdt=54642, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=7238502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T08:45:00+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.195600, depth_time=2026-10-17T08:45:22+00:00, book20_bid_proxy_usdt=2306682, book20_ask_proxy_usdt=1101478, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=12376579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=1.176600, depth_time=2026-10-17T08:45:29+00:00, book20_bid_proxy_usdt=476383, book20_ask_proxy_usdt=895742, funding_indicative=0.000031, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=24831713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=8.946000, depth_time=2026-10-17T08:45:24+00:00, book20_bid_proxy_usdt=270397, book20_ask_proxy_usdt=304535, funding_indicative=0.000258, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=93690573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.137250, depth_time=2026-10-17T08:45:10+00:00, book20_bid_proxy_usdt=44895, book20_ask_proxy_usdt=82703, funding_indicative=-0.000003, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=15113577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T08:45:00+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=1.098000, depth_time=2026-10-17T08:45:09+00:00, book20_bid_proxy_usdt=412692, book20_ask_proxy_usdt=521478, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=5073939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T08:45:00+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.064010, depth_time=2026-10-17T08:45:35+00:00, book20_bid_proxy_usdt=275916, book20_ask_proxy_usdt=195340, funding_indicative=0.000074, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=19211035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=0.072350, depth_time=2026-10-17T08:45:19+00:00, book20_bid_proxy_usdt=271885, book20_ask_proxy_usdt=250336, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=20289977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=1.012200, depth_time=2026-10-17T08:45:33+00:00, book20_bid_proxy_usdt=1065092, book20_ask_proxy_usdt=1063101, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=92608905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=276.090000, depth_time=2026-10-17T08:45:26+00:00, book20_bid_proxy_usdt=118437, book20_ask_proxy_usdt=71192, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=64407091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=1174.140000, depth_time=2026-10-17T08:45:31+00:00, book20_bid_proxy_usdt=166799, book20_ask_proxy_usdt=580086, funding_indicative=0.000035, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=1334879470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T08:44:59+00:00, last15m_closed_end=2026-10-17T08:45+00:00, prior8high=1.969300, depth_time=2026-10-17T08:45:07+00:00, book20_bid_proxy_usdt=73781, book20_ask_proxy_usdt=58226, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.96%, turnover=12463177. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
