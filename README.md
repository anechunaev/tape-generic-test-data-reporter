# Tape test reporter in Generic Test Data format

## Usage

```bash
tape-generic-test-data-reporter [OPTIONS]
```

### Options

#### -f &lt;file&gt;, --file &lt;file&gt;

If present, writes report to given path, otherwise prints to stdout.

### Example

```bash
tape module.spec.js | tape-generic-test-data-reporter -f /tmp/report.xml
```

## Restrictions

This module requires Node.js v9.0.0 or higher.