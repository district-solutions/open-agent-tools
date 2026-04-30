# Agent Python Tools

- repo: TauricResearch/TradingAgents
- repo_uri: https://github.com/TauricResearch/TradingAgents

## File: TauricResearch_TradingAgents/tradingagents/agents/analysts/fundamentals_analyst.py

Prompts

```
['create a fundamentals analyst agent node that analyzes company financials using an LLM', 'build instrument context for a given company of interest in the trading agent state', 'get comprehensive company fundamental analysis including profile and financial history', 'get balance sheet data for a company at a specified date', 'get income statement data for a company at a specified date', 'create a market analyst agent node that selects financial indicators and generates a detailed market report using an LLM', 'run the market analyst node with a state containing trade_date, company_of_interest, and messages to produce a market report', 'test the get_stock_data tool that retrieves stock data CSV for indicator generation', 'test the get_indicators tool that computes technical indicators like SMA, EMA, RSI, MACD, Bollinger Bands, and ATR', 'create a news analyst agent node that analyzes recent news and trends for trading decisions', 'get company-specific or targeted news using query, start_date, and end_date parameters', 'get broader macroeconomic news using current date, look_back_days, and limit parameters', 'create a langchain prompt chain that binds tools to an LLM for news analysis', 'create a social media analyst agent node that analyzes company news and sentiment using an LLM and the get_news tool', 'build a social media analyst agent node from a LangChain LLM that returns a sentiment report for a given company', 'run the social media analyst agent on a company to produce a sentiment report with news and public opinion analysis', 'test the social media analyst agent node with sample state containing trade date, company name, and messages', 'review the social media analyst agent to verify it uses get_news tool and appends a Markdown table to the report']
```

Usage

```
{'create_fundamentals_analyst': 'create a fundamentals analyst agent node that analyzes company financials using an LLM', 'build_instrument_context': 'build instrument context for a given company of interest in the trading agent state', 'get_fundamentals': 'get comprehensive company fundamental analysis including profile and financial history', 'get_balance_sheet': 'get balance sheet data for a company at a specified date', 'get_income_statement': 'get income statement data for a company at a specified date'}
```

## File: TauricResearch_TradingAgents/tradingagents/agents/analysts/market_analyst.py

Prompts

```
['create a fundamentals analyst agent node that analyzes company financials using an LLM', 'build instrument context for a given company of interest in the trading agent state', 'get comprehensive company fundamental analysis including profile and financial history', 'get balance sheet data for a company at a specified date', 'get income statement data for a company at a specified date', 'create a market analyst agent node that selects financial indicators and generates a detailed market report using an LLM', 'run the market analyst node with a state containing trade_date, company_of_interest, and messages to produce a market report', 'test the get_stock_data tool that retrieves stock data CSV for indicator generation', 'test the get_indicators tool that computes technical indicators like SMA, EMA, RSI, MACD, Bollinger Bands, and ATR', 'create a news analyst agent node that analyzes recent news and trends for trading decisions', 'get company-specific or targeted news using query, start_date, and end_date parameters', 'get broader macroeconomic news using current date, look_back_days, and limit parameters', 'create a langchain prompt chain that binds tools to an LLM for news analysis', 'create a social media analyst agent node that analyzes company news and sentiment using an LLM and the get_news tool', 'build a social media analyst agent node from a LangChain LLM that returns a sentiment report for a given company', 'run the social media analyst agent on a company to produce a sentiment report with news and public opinion analysis', 'test the social media analyst agent node with sample state containing trade date, company name, and messages', 'review the social media analyst agent to verify it uses get_news tool and appends a Markdown table to the report']
```

Usage

```
{'create_market_analyst': 'create a market analyst agent node that selects financial indicators and generates a detailed market report using an LLM', 'run_market_analyst_node': 'run the market analyst node with a state containing trade_date, company_of_interest, and messages to produce a market report', 'build_instrument_context': 'build an instrument context string from a company name to provide trading context to the market analyst', 'test_get_stock_data': 'test the get_stock_data tool that retrieves stock data CSV for indicator generation', 'test_get_indicators': 'test the get_indicators tool that computes technical indicators like SMA, EMA, RSI, MACD, Bollinger Bands, and ATR'}
```

## File: TauricResearch_TradingAgents/tradingagents/agents/analysts/news_analyst.py

Prompts

```
['create a fundamentals analyst agent node that analyzes company financials using an LLM', 'build instrument context for a given company of interest in the trading agent state', 'get comprehensive company fundamental analysis including profile and financial history', 'get balance sheet data for a company at a specified date', 'get income statement data for a company at a specified date', 'create a market analyst agent node that selects financial indicators and generates a detailed market report using an LLM', 'run the market analyst node with a state containing trade_date, company_of_interest, and messages to produce a market report', 'test the get_stock_data tool that retrieves stock data CSV for indicator generation', 'test the get_indicators tool that computes technical indicators like SMA, EMA, RSI, MACD, Bollinger Bands, and ATR', 'create a news analyst agent node that analyzes recent news and trends for trading decisions', 'get company-specific or targeted news using query, start_date, and end_date parameters', 'get broader macroeconomic news using current date, look_back_days, and limit parameters', 'create a langchain prompt chain that binds tools to an LLM for news analysis', 'create a social media analyst agent node that analyzes company news and sentiment using an LLM and the get_news tool', 'build a social media analyst agent node from a LangChain LLM that returns a sentiment report for a given company', 'run the social media analyst agent on a company to produce a sentiment report with news and public opinion analysis', 'test the social media analyst agent node with sample state containing trade date, company name, and messages', 'review the social media analyst agent to verify it uses get_news tool and appends a Markdown table to the report']
```

Usage

```
{'create_news_analyst': 'create a news analyst agent node that analyzes recent news and trends for trading decisions', 'build_instrument_context': 'build instrument context for a company of interest to provide trading-related background', 'get_news': 'get company-specific or targeted news using query, start_date, and end_date parameters', 'get_global_news': 'get broader macroeconomic news using current date, look_back_days, and limit parameters', 'create_news_analyst_chain': 'create a langchain prompt chain that binds tools to an LLM for news analysis'}
```

## File: TauricResearch_TradingAgents/tradingagents/agents/analysts/social_media_analyst.py

Prompts

```
['create a fundamentals analyst agent node that analyzes company financials using an LLM', 'build instrument context for a given company of interest in the trading agent state', 'get comprehensive company fundamental analysis including profile and financial history', 'get balance sheet data for a company at a specified date', 'get income statement data for a company at a specified date', 'create a market analyst agent node that selects financial indicators and generates a detailed market report using an LLM', 'run the market analyst node with a state containing trade_date, company_of_interest, and messages to produce a market report', 'test the get_stock_data tool that retrieves stock data CSV for indicator generation', 'test the get_indicators tool that computes technical indicators like SMA, EMA, RSI, MACD, Bollinger Bands, and ATR', 'create a news analyst agent node that analyzes recent news and trends for trading decisions', 'get company-specific or targeted news using query, start_date, and end_date parameters', 'get broader macroeconomic news using current date, look_back_days, and limit parameters', 'create a langchain prompt chain that binds tools to an LLM for news analysis', 'create a social media analyst agent node that analyzes company news and sentiment using an LLM and the get_news tool', 'build a social media analyst agent node from a LangChain LLM that returns a sentiment report for a given company', 'run the social media analyst agent on a company to produce a sentiment report with news and public opinion analysis', 'test the social media analyst agent node with sample state containing trade date, company name, and messages', 'review the social media analyst agent to verify it uses get_news tool and appends a Markdown table to the report']
```

Usage

```
{'create_social_media_analyst': 'create a social media analyst agent node that analyzes company news and sentiment using an LLM and the get_news tool', 'build_social_media_node': 'build a social media analyst agent node from a LangChain LLM that returns a sentiment report for a given company', 'run_social_media_analysis': 'run the social media analyst agent on a company to produce a sentiment report with news and public opinion analysis', 'test_social_media_analyst': 'test the social media analyst agent node with sample state containing trade date, company name, and messages', 'review_social_media_agent': 'review the social media analyst agent to verify it uses get_news tool and appends a Markdown table to the report'}
```

