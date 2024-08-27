## Promise
#### Promise.all
- Promise.all waits for all fulfillments「所有的primise都fulfill才返回」
- Promise.all is rejected if any of the elements are rejected「有一个promise出现fail就会返回，适合互相依赖的异步任务，需要每个任务都fulfill」

#### Promise.allSettled
- Promise.allSettled() is typically used when you have multiple asynchronous tasks that are not dependent on one another to complete successfully, or you'd always like to know the result of each promise.「与promise.all的区别在于，这个适用于不互相依赖的异步任务，需要知道每个异步任务结果时，适用此方法」