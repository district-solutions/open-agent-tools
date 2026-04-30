# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/optional-skills/productivity/memento-flashcards/scripts/memento_cards.py

Prompts

```
['create a flashcard with a question and answer using the memento_cards add subcommand', 'batch-add quiz flashcards from a JSON array of question-answer pairs using the add-quiz subcommand', 'list flashcards due for review using the due subcommand', 'rate a flashcard as easy, good, hard, or retire to update its spaced-repetition schedule', 'show flashcard statistics including total, learning, retired, due, and collection counts', 'fetch a YouTube transcript for a given video ID and return normalized text', 'run the youtube_quiz.py fetch command with a YouTube video ID argument', 'normalize raw transcript segments into a single whitespace-cleaned text string', 'handle missing youtube-transcript-api dependency and return an error JSON message', 'handle unavailable transcripts and return structured error JSON with error type and message']
```

Usage

```
{'create_flashcard': 'create a flashcard with a question and answer using the memento_cards add subcommand', 'batch_add_quiz_cards': 'batch-add quiz flashcards from a JSON array of question-answer pairs using the add-quiz subcommand', 'list_due_cards': 'list flashcards due for review using the due subcommand', 'rate_flashcard': 'rate a flashcard as easy, good, hard, or retire to update its spaced-repetition schedule', 'show_flashcard_stats': 'show flashcard statistics including total, learning, retired, due, and collection counts'}
```

## File: NousResearch_hermes-agent/optional-skills/productivity/memento-flashcards/scripts/youtube_quiz.py

Prompts

```
['create a flashcard with a question and answer using the memento_cards add subcommand', 'batch-add quiz flashcards from a JSON array of question-answer pairs using the add-quiz subcommand', 'list flashcards due for review using the due subcommand', 'rate a flashcard as easy, good, hard, or retire to update its spaced-repetition schedule', 'show flashcard statistics including total, learning, retired, due, and collection counts', 'fetch a YouTube transcript for a given video ID and return normalized text', 'run the youtube_quiz.py fetch command with a YouTube video ID argument', 'normalize raw transcript segments into a single whitespace-cleaned text string', 'handle missing youtube-transcript-api dependency and return an error JSON message', 'handle unavailable transcripts and return structured error JSON with error type and message']
```

Usage

```
{'fetch_youtube_transcript': 'fetch a YouTube transcript for a given video ID and return normalized text', 'run_youtube_quiz_fetch': 'run the youtube_quiz.py fetch command with a YouTube video ID argument', 'normalize_transcript_segments': 'normalize raw transcript segments into a single whitespace-cleaned text string', 'handle_missing_dependency': 'handle missing youtube-transcript-api dependency and return an error JSON message', 'handle_transcript_unavailable': 'handle unavailable transcripts and return structured error JSON with error type and message'}
```

