# post_call_analysis documentation!

## Description

a startup project of the post call analysis

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://dl-projectx/post_call_analysis/data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://dl-projectx/post_call_analysis/data/` to `data/`.


