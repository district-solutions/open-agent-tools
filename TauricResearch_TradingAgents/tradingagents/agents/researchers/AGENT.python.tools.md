# Agent Python Tools

- repo: TauricResearch/TradingAgents
- repo_uri: https://github.com/TauricResearch/TradingAgents

## File: TauricResearch_TradingAgents/tradingagents/agents/researchers/bear_researcher.py

Prompts

```
['create a bear analyst agent node that argues against investing in a stock using LLM-driven debate', 'build a bear research argument by combining market, sentiment, news, and fundamentals reports into a counter-bull case', "retrieve past research memories to inform the bear analyst's current argument with lessons from similar situations", 'update the investment debate state with the new bear argument, history, and round counter after each bear turn', 'refute bull analyst claims by analyzing their latest argument and presenting risk-focused counterpoints with supporting data', 'create a bull analyst node function that takes an LLM and memory to generate evidence-based investment arguments', 'build a bull analyst argument by combining market research, sentiment, news, and fundamentals reports with debate history', "refute a bear analyst's argument using market data, company fundamentals, and past lessons from similar situations", 'retrieve past recommendations from memory to inform current bull analysis and avoid repeating past mistakes']
```

Usage

```
{'create_bear_researcher': 'create a bear analyst agent node that argues against investing in a stock using LLM-driven debate', 'build_bear_debate_argument': 'build a bear research argument by combining market, sentiment, news, and fundamentals reports into a counter-bull case', 'retrieve_past_research_memories': "retrieve past research memories to inform the bear analyst's current argument with lessons from similar situations", 'update_debate_state': 'update the investment debate state with the new bear argument, history, and round counter after each bear turn', 'refute_bull_claims': 'refute bull analyst claims by analyzing their latest argument and presenting risk-focused counterpoints with supporting data'}
```

## File: TauricResearch_TradingAgents/tradingagents/agents/researchers/bull_researcher.py

Prompts

```
['create a bear analyst agent node that argues against investing in a stock using LLM-driven debate', 'build a bear research argument by combining market, sentiment, news, and fundamentals reports into a counter-bull case', "retrieve past research memories to inform the bear analyst's current argument with lessons from similar situations", 'update the investment debate state with the new bear argument, history, and round counter after each bear turn', 'refute bull analyst claims by analyzing their latest argument and presenting risk-focused counterpoints with supporting data', 'create a bull analyst node function that takes an LLM and memory to generate evidence-based investment arguments', 'build a bull analyst argument by combining market research, sentiment, news, and fundamentals reports with debate history', "refute a bear analyst's argument using market data, company fundamentals, and past lessons from similar situations", 'retrieve past recommendations from memory to inform current bull analysis and avoid repeating past mistakes']
```

Usage

```
{'create_bull_researcher': 'create a bull analyst node function that takes an LLM and memory to generate evidence-based investment arguments', 'build_bull_debate_argument': 'build a bull analyst argument by combining market research, sentiment, news, and fundamentals reports with debate history', 'refute_bear_argument': "refute a bear analyst's argument using market data, company fundamentals, and past lessons from similar situations", 'retrieve_past_recommendations': 'retrieve past recommendations from memory to inform current bull analysis and avoid repeating past mistakes', 'update_debate_state': 'update the investment debate state with the new bull argument, incremented round count, and extended conversation history'}
```

