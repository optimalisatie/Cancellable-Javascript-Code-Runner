# WebWorker vs Exec.js Round Trip / Ping Test

The test `webworker-vs-execjs-ping.js` shows the round trip time of WebWorker and Exec.js.

As of `v1.0.4` (+/- 10 hours old) WebWorkers are 3x faster (0,1ms vs 0,3ms) but WebWorkers require 100ms to startup compared to 10-20ms for Exec.js, making exec.js much faster for smaller workloads.

Further optimization may enable exec.js to achieve the same round trip performance as WebWorkers.

![WebWorker vs Exec.js](https://raw.githubusercontent.com/optimalisatie/exec.js/master/tests/webworker-vs-execjs-ping.png)
