# Agent Python Tools

- repo: virattt/ai-hedge-fund
- repo_uri: https://github.com/virattt/ai-hedge-fund

## File: virattt_ai-hedge-fund/v2/data/client.py

Prompts

```
['create an FDClient instance to fetch financial data from the Financial Datasets API', 'fetch OHLC price bars for a ticker between a start date and end date with configurable interval', 'fetch financial metrics for a ticker up to a given end date with period and limit options', 'fetch company news articles for a ticker within a date range with a configurable limit', 'fetch insider trades for a ticker within a filing date range with a configurable limit', 'get market cap for a ticker from company facts or financial metrics as a fallback', 'fetch quarterly and annual earnings data for a ticker', 'fetch company metadata including name, sector, and market cap for a ticker', 'build a data provider class implementing DataClient protocol with get_prices to fetch stock price data', 'build a data provider class implementing DataClient protocol with get_financial_metrics to retrieve company financial data', 'build a data provider class implementing DataClient protocol with get_news to fetch company news articles', 'build a data provider class implementing DataClient protocol with get_insider_trades to retrieve insider trading records', 'build a data provider class implementing DataClient protocol with get_company_facts to fetch company factual data', 'test the FDClient.get_prices method to retrieve price bars for a ticker over a date range', 'test the FDClient.get_financial_metrics method to retrieve TTM financial metrics for a ticker', 'test the FDClient.get_earnings method to retrieve earnings data including quarterly results for a ticker', 'test the FDClient.get_news method to retrieve recent news articles for a ticker', 'test the FDClient.get_insider_trades method to retrieve insider trading records for a ticker', 'test the FDClient.get_company_facts method to retrieve company sector and exchange information']
```

Usage

```
{'create_fdclient': 'create an FDClient instance to fetch financial data from the Financial Datasets API', 'fetch_prices': 'fetch OHLC price bars for a ticker between a start date and end date with configurable interval', 'fetch_financial_metrics': 'fetch financial metrics for a ticker up to a given end date with period and limit options', 'fetch_company_news': 'fetch company news articles for a ticker within a date range with a configurable limit', 'fetch_insider_trades': 'fetch insider trades for a ticker within a filing date range with a configurable limit', 'get_market_cap': 'get market cap for a ticker from company facts or financial metrics as a fallback', 'fetch_earnings': 'fetch quarterly and annual earnings data for a ticker', 'fetch_company_facts': 'fetch company metadata including name, sector, and market cap for a ticker'}
```

## File: virattt_ai-hedge-fund/v2/data/protocol.py

Prompts

```
['create an FDClient instance to fetch financial data from the Financial Datasets API', 'fetch OHLC price bars for a ticker between a start date and end date with configurable interval', 'fetch financial metrics for a ticker up to a given end date with period and limit options', 'fetch company news articles for a ticker within a date range with a configurable limit', 'fetch insider trades for a ticker within a filing date range with a configurable limit', 'get market cap for a ticker from company facts or financial metrics as a fallback', 'fetch quarterly and annual earnings data for a ticker', 'fetch company metadata including name, sector, and market cap for a ticker', 'build a data provider class implementing DataClient protocol with get_prices to fetch stock price data', 'build a data provider class implementing DataClient protocol with get_financial_metrics to retrieve company financial data', 'build a data provider class implementing DataClient protocol with get_news to fetch company news articles', 'build a data provider class implementing DataClient protocol with get_insider_trades to retrieve insider trading records', 'build a data provider class implementing DataClient protocol with get_company_facts to fetch company factual data', 'test the FDClient.get_prices method to retrieve price bars for a ticker over a date range', 'test the FDClient.get_financial_metrics method to retrieve TTM financial metrics for a ticker', 'test the FDClient.get_earnings method to retrieve earnings data including quarterly results for a ticker', 'test the FDClient.get_news method to retrieve recent news articles for a ticker', 'test the FDClient.get_insider_trades method to retrieve insider trading records for a ticker', 'test the FDClient.get_company_facts method to retrieve company sector and exchange information']
```

Usage

```
{'build_dataclient_get_prices': 'build a data provider class implementing DataClient protocol with get_prices to fetch stock price data', 'build_dataclient_get_financial_metrics': 'build a data provider class implementing DataClient protocol with get_financial_metrics to retrieve company financial data', 'build_dataclient_get_news': 'build a data provider class implementing DataClient protocol with get_news to fetch company news articles', 'build_dataclient_get_insider_trades': 'build a data provider class implementing DataClient protocol with get_insider_trades to retrieve insider trading records', 'build_dataclient_get_company_facts': 'build a data provider class implementing DataClient protocol with get_company_facts to fetch company factual data'}
```

## File: virattt_ai-hedge-fund/v2/data/test_client.py

Prompts

```
['create an FDClient instance to fetch financial data from the Financial Datasets API', 'fetch OHLC price bars for a ticker between a start date and end date with configurable interval', 'fetch financial metrics for a ticker up to a given end date with period and limit options', 'fetch company news articles for a ticker within a date range with a configurable limit', 'fetch insider trades for a ticker within a filing date range with a configurable limit', 'get market cap for a ticker from company facts or financial metrics as a fallback', 'fetch quarterly and annual earnings data for a ticker', 'fetch company metadata including name, sector, and market cap for a ticker', 'build a data provider class implementing DataClient protocol with get_prices to fetch stock price data', 'build a data provider class implementing DataClient protocol with get_financial_metrics to retrieve company financial data', 'build a data provider class implementing DataClient protocol with get_news to fetch company news articles', 'build a data provider class implementing DataClient protocol with get_insider_trades to retrieve insider trading records', 'build a data provider class implementing DataClient protocol with get_company_facts to fetch company factual data', 'test the FDClient.get_prices method to retrieve price bars for a ticker over a date range', 'test the FDClient.get_financial_metrics method to retrieve TTM financial metrics for a ticker', 'test the FDClient.get_earnings method to retrieve earnings data including quarterly results for a ticker', 'test the FDClient.get_news method to retrieve recent news articles for a ticker', 'test the FDClient.get_insider_trades method to retrieve insider trading records for a ticker', 'test the FDClient.get_company_facts method to retrieve company sector and exchange information']
```

Usage

```
{'test_FDClient_get_prices': 'test the FDClient.get_prices method to retrieve price bars for a ticker over a date range', 'test_FDClient_get_financial_metrics': 'test the FDClient.get_financial_metrics method to retrieve TTM financial metrics for a ticker', 'test_FDClient_get_earnings': 'test the FDClient.get_earnings method to retrieve earnings data including quarterly results for a ticker', 'test_FDClient_get_news': 'test the FDClient.get_news method to retrieve recent news articles for a ticker', 'test_FDClient_get_insider_trades': 'test the FDClient.get_insider_trades method to retrieve insider trading records for a ticker', 'test_FDClient_get_company_facts': 'test the FDClient.get_company_facts method to retrieve company sector and exchange information'}
```

