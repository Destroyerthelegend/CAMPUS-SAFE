# CAMPUS-SAFE Automated Tests

## Test Execution

Tests were executed locally using Python 3.12.10 and pytest 9.1.1.

Command:

```bash
python -m pytest -v
```

## Results

- Tests collected: 9
- Tests passed: 9
- Tests failed: 0
- Execution time: 0.09 seconds

## Coverage

The test suite checks:

1. Packet priority values.
2. Packet hop tracking.
3. Packet TTL expiration.
4. TTL decrement during forwarding.
5. Bidirectional network links.
6. Shortest-path route selection.
7. Handling of unreachable destinations.
8. Alternative-route selection after a node failure.
9. Avoidance of a failed link.

These tests cover selected behaviours of the simulation. They do not constitute exhaustive testing of every network condition.