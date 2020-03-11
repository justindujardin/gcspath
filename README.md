# GCSPath

[![Build status](https://travis-ci.org/justindujardin/gcspath.svg?branch=master)](https://travis-ci.org/justindujardin/gcspath)
[![Pypi version](https://badgen.net/pypi/v/gcspath)](https://pypi.org/project/gcspath/)

> IMPORTANT: this library is not ready for use

GCSPath provides a convenient Pythonic File-System/Path like interface to Google Cloud Storage using [google-cloud-storage](https://pypi.org/project/google-cloud-storage/) package as a driver.

It is based on the [S3Path](https://github.com/liormizr/s3path) project, which provides a similar interface for S3 buckets.

---

GCS is among the popular cloud storage solutions. It's object storage built to store and retrieve various amounts of data from anywhere.

Rather than directly use `google-cloud-storage` to connect / put / get / list / delete files from GCS, gcspath extends pathlib classes to provide a familiar API for developers that normally work with local file paths.

# Install:

From PyPI:

```bash
$ pip install gcspath
```

# Requirements:

- Python >= 3.6
- google-cloud-storage