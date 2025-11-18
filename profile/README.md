# bsub.io: zero‑setup batch execution for command-line tools

Cloud batch processing service for data transformations and document processing.

## What is bsub.io

bsub.io provides serverless batch processing for common file operations through a simple command-line interface. No setup, no infrastructure management—just submit files and retrieve results.

## Services

- **PDF extraction** — Extract text from PDFs with or without OCR
- **Audio transcription** — Convert audio files to text
- **Video conversion** — Convert videos to MP4 format
- **Document compilation** — Markdown and Typst to PDF conversion
- **Batch processing** — Submit multiple files for parallel processing

## Quick Start

```bash
curl -fsSL https://install.bsub.io/ | sh
bsubio register
bsubio submit pdf/extract document.pdf
```

## Resources

- **Website:** https://bsub.io
- **Documentation:** https://docs.bsub.io
- **CLI Repository:** https://github.com/bsubio/cli
- **Web App:** https://app.bsub.io

## Contributing

Contributions welcome. Open issues or pull requests on the [CLI repository](https://github.com/bsubio/cli).

## License

CLI is Open source. See repository for license details.
