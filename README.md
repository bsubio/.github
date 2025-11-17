# bsub

Zero‑setup batch execution for command-line tools — run, schedule, and
observe groups of CLI commands with minimal friction.

Why bsub
-------

- **Zero setup:** get started without heavy configuration or services.
- **Batch & parallel:** run lists of commands in sequence or in parallel.
- **Portable:** works on macOS, Linux, WSL, and containers.
- **Observable:** realtime logs and concise summaries for each job.

Quick start
-----------

1. Download the binary for your platform from the releases page on
	https://bsub.io (or use your package manager if available).
2. Run a single command:

```
bsub run "echo hello from bsub"
```

3. Run multiple commands as a batch (example):

```
bsub run "echo step-1" "sleep 1" "echo step-3"
```

Core concepts
-------------

- `run` — execute one or more commands as a batch job.
- `parallel` — control concurrency for independent tasks.
- `dry-run` — preview what will run without executing.

Use cases
---------

- CI-friendly command batching for tests, linters, or build steps.
- Local automation of repetitive CLI workflows.
- Lightweight orchestration inside containers and ephemeral runners.

Contributing
------------

Contributions, bug reports, and feature requests are welcome. Please open
issues or pull requests on the upstream repository and follow the
contribution guidelines.

License
-------

This project is open source — see the repository for license details.

More
----
Visit https://bsub.io for docs, downloads, and examples.

