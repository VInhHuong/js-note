# js-note
1. Event Loop
 - https://dev.to/moyedx3/9-message-queue-and-event-loop-5092
 - https://viblo.asia/p/hieu-ve-co-che-xu-ly-su-kien-event-loop-trong-javascript-07LKXjX2lV4
 - https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif
 - Event loop is a running process that watches call stack(FILO) & queues(FIFO) . If the call stack is empty, it takes first event in Task queue and pushes it to the call stack.
 - Most importantly, Mictrotask queue(Job Queue) has priority to Task queue. Additonaly, Mictrotask queue continues to push its callback into call stack untill the Mictrotask queue is empty.
 - ![image](https://user-images.githubusercontent.com/38858796/167368527-64d6c76c-03a8-461f-8026-badae50ec3f8.png)
2. Worker Thread
 - https://dev.to/deepal/deep-dive-into-worker-threads-in-node-js-4bc8
 - https://dev.to/bnevilleoneill/node-js-multithreading-what-are-worker-threads-and-why-do-they-matter-1obo
 - https://dev.to/feezyhendrix/worker-threads-in-node-js-2ikh
3. Blocking and Non-Blocking
 - https://nodejs.org/en/docs/guides/blocking-vs-non-blocking/
 - https://dev.to/arnaldobadin/nodejs-non-blocking-processing-k5i
4. Asynchronous Programming (Callback, Promise, async await )
 - https://dev.to/ngnijland/run-asynchronous-tasks-in-batches-in-nodejs-599a
 - https://nodejs.dev/learn/javascript-asynchronous-programming-and-callbacks
 - https://nodejs.dev/learn/understanding-javascript-promises
 - https://nodejs.dev/learn/modern-asynchronous-javascript-with-async-and-await
