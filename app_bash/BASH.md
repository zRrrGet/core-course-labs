## Implementation
Ncat is used for sending HTTP responses. It's simple way of getting the job done though it's slow and not asynchronous.

## Coding standard
https://www.shellcheck.net/ linter is used to ensure bash code quality.

## Unit Testing
`test.sh` contains test code. Execute
```
./test.sh
```
to run tests.

Tests use following best practices:
- Have appropriate test names
- They're simple
- Same, stable output
- Single use case
- Fast