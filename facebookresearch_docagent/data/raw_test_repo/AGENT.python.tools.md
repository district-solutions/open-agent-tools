# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/data/raw_test_repo/vending_machine.py

Prompts

```
['create a Sys instance to manage a vending machine with an optional payment handler', 'call ls on a Sys instance to list all items with their slot positions', 'call pick with a slot position on Sys to select an available item', 'call buy with a slot position on Sys to purchase an item and get change', 'call cancel on Sys to revoke the current transaction and retrieve a refund']
```

Usage

```
{'create_vending_machine_system': 'create a Sys instance to manage a vending machine with an optional payment handler', 'list_vending_items': 'call ls on a Sys instance to list all items with their slot positions', 'pick_vending_item': 'call pick with a slot position on Sys to select an available item', 'buy_vending_item': 'call buy with a slot position on Sys to purchase an item and get change', 'cancel_vending_transaction': 'call cancel on Sys to revoke the current transaction and retrieve a refund'}
```

