# v0.4.0

* upd: implement check `metric_filters` to collect only metrics in dashboard
* add: chunk large arbitrary metric collectors (ksm and ms)
* upd: collection metrics - remove accept/filter, add agent memory metrics
* add: collection metrics - agent memory and goroutine metrics
* upd: dependencies

# v0.3.1

* add: collection summary metrics (sent,accept,filter,bytes,duration)

# v0.3.0

* add: `--no-base64` switch to disable for test/debug (base64 stream tags)
* add: `--no-gzip` switch to disable for test/debug (gzip trap submissions)
* upd: switch to using gzip compression for trap submissions as default
* fix: stream tag quote escaping in printf

# v0.2.0

* add: abridged events
* add: pod filtering by label key/val

# v0.1.0

* initial preview release