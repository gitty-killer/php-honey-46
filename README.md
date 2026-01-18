# php-honey-46

A small PHP tool that computes text statistics for honey.

## Objective
- Provide quick text metrics for honey documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate honey drafts for repeated terms before review.
- Summarize honey notes when preparing reports.

## Usage
php index.php data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
