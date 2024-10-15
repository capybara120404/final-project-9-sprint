# Parallel Number Generator

This project implements a concurrent number generator that distributes numbers across multiple workers, processes them, and validates the results.

## Features

- **Number Generator**: Continuously generates integers and passes them through channels.
- **Worker Pool**: Distributes numbers to multiple workers for processing.
- **Concurrent Execution**: Uses Go's concurrency model with goroutines and channels.
- **Data Validation**: Verifies that the sum and count of numbers processed by workers match the generated numbers.
