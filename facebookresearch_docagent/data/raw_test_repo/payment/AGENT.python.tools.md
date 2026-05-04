# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/data/raw_test_repo/payment/payment_processor.py

Prompts

```
['create a Cash handler instance to process cash payments with a starting balance', 'process a cash payment by calling proc on a Cash handler with a Decimal amount', 'refund a completed transaction by calling rev on a Cash handler with the Tx object', 'add funds to a Cash handler balance by calling the add method with a Decimal amount', 'retrieve and reset the Cash handler balance by calling the ret method']
```

Usage

```
{'create_cash_handler': 'create a Cash handler instance to process cash payments with a starting balance', 'proc_cash_payment': 'process a cash payment by calling proc on a Cash handler with a Decimal amount', 'refund_transaction': 'refund a completed transaction by calling rev on a Cash handler with the Tx object', 'add_funds': 'add funds to a Cash handler balance by calling the add method with a Decimal amount', 'retrieve_balance': 'retrieve and reset the Cash handler balance by calling the ret method'}
```

