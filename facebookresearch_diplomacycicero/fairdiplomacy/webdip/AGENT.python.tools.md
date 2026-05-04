# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/fairdiplomacy/webdip/message_approval_cache_api.py

Prompts

```
['get a message review from the Redis cache for a given game filepath', 'set or update a message review entry in the Redis cache with approval data', 'delete a message review from the Redis cache and optionally archive it', 'get a summary of all archived message reviews across webdip games with rejection rates', 'get archived message review statistics grouped by parallel recipient game stems', 'convert a webdip turn number and subphase string into a dipcc phase string like S1901M', 'convert a dipcc phase string like F1902R back into its corresponding webdip turn number', 'extract the human-readable phase type like Diplomacy Retreats or Builds from a dipcc phase string', 'review the turn_to_phase function to understand how it handles Pre-game Unknown and Finished subphase edge cases', 'test the round-trip conversion between webdip turn subphase pairs and dipcc phase strings for correctness']
```

Usage

```
{'get_message_review': 'get a message review from the Redis cache for a given game filepath', 'set_message_review': 'set or update a message review entry in the Redis cache with approval data', 'delete_message_review': 'delete a message review from the Redis cache and optionally archive it', 'get_webdip_games_archived_message_review_summary': 'get a summary of all archived message reviews across webdip games with rejection rates', 'get_parallel_recipient_archived_message_review_stats': 'get archived message review statistics grouped by parallel recipient game stems'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy/webdip/utils.py

Prompts

```
['get a message review from the Redis cache for a given game filepath', 'set or update a message review entry in the Redis cache with approval data', 'delete a message review from the Redis cache and optionally archive it', 'get a summary of all archived message reviews across webdip games with rejection rates', 'get archived message review statistics grouped by parallel recipient game stems', 'convert a webdip turn number and subphase string into a dipcc phase string like S1901M', 'convert a dipcc phase string like F1902R back into its corresponding webdip turn number', 'extract the human-readable phase type like Diplomacy Retreats or Builds from a dipcc phase string', 'review the turn_to_phase function to understand how it handles Pre-game Unknown and Finished subphase edge cases', 'test the round-trip conversion between webdip turn subphase pairs and dipcc phase strings for correctness']
```

Usage

```
{'convert_turn_to_phase': 'convert a webdip turn number and subphase string into a dipcc phase string like S1901M', 'convert_phase_to_turn': 'convert a dipcc phase string like F1902R back into its corresponding webdip turn number', 'extract_phase_type': 'extract the human-readable phase type like Diplomacy Retreats or Builds from a dipcc phase string', 'review_turn_to_phase': 'review the turn_to_phase function to understand how it handles Pre-game Unknown and Finished subphase edge cases', 'test_phase_conversions': 'test the round-trip conversion between webdip turn subphase pairs and dipcc phase strings for correctness'}
```

