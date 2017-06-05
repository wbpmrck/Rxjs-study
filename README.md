# Rxjs-study
study cases of Rxjs library

# catalog(目录)

- 感性认识
    - [demo1](./study/exp01.html)
    - [demo2](./study/exp02.html)
    - [demo3](./study/exp03.html)
    - [demo4](./study/exp04.html)
- 基础概念
    - [exp05_observable](./study/exp05_observable.html)
    - [exp06_observable_subscribe_sync](./study/exp06_observable_subscribe_sync.html)
    - [exp07_observable_subscribe_isolated](./study/exp07_observable_subscribe_isolated.html)
    - [exp08_observable_execution](./study/exp08_observable_execution.html)
    - [exp09_observable_execution2](./study/exp09_observable_execution2.html)
    - [exp10_observer](./study/exp10_observer.html)
    - [exp11_subscription](./study/exp11_subscription.html)
    - [exp12_subject](./study/exp12_subject.html)
    - [exp13_multicast_observable](./study/exp13_multicast_observable.html)
    - [exp14_ref_count](./study/exp14_ref_count.html)
    - [exp15_behavior_subject](./study/exp15_behavior_subject.html)
    - [exp16_replay_subject](./study/exp16_replay_subject.html)
    - [exp17_async_subject](./study/exp17_async_subject.html)
    - [exp18_instance_operator](./study/exp18_instance_operator.html)
    - [exp19_static_operator](./study/exp19_static_operator.html)

- operators
    - Creation Operators
        - ajax
        - bindCallback
        - bindNodeCallback
        - create(参见之前的练习)
        - defer
        - [empty](./study/operators/empty.html)
        - [from](./study/operators/from.html)
        - [fromEvent](./study/operators/fromEvent.html)
        - [fromEventPattern](./study/operators/fromEventPattern.html)
        - [fromPromise](./study/operators/fromPromise.html)
        - generate
        - [interval](./study/operators/interval.html)
        - [never](./study/operators/never.html)
        - [of](./study/operators/of.html)
        - [repeat](./study/operators/repeat.html)
        - repeatWhen
        - range
        - [throw](./study/operators/throw.html)
        - [timer](./study/operators/timer.html)

    - Transformation Operators
        - [buffer](./study/operators/buffer.html)
        - [bufferCount](./study/operators/bufferCount.html)
        - [bufferTime](./study/operators/bufferTime.html)
        - bufferToggle
        - bufferWhen
        - [concatMap](./study/operators/concatMap.html)
        - concatMapTo
        - exhaustMap
        - expand
        - [groupBy](./study/operators/groupBy.html)
        - [map](./study/operators/map.html)
        - [mapTo](./study/operators/mapTo.html)
        - [mergeMap](./study/operators/mergeMap.html)
        - mergeMapTo
        - mergeScan
        - pairwise
        - partition
        - pluck
        - [scan](./study/operators/scan.html)
        - [switchMap](./study/operators/switchMap.html)
        - switchMapTo
        - [window](./study/operators/window.html)
        - windowCount
        - windowTime
        - [windowToggle](./study/operators/windowToggle.html)
        - windowWhen

    - Filtering Operators
        - [debounce](./study/operators/debounce.html)
        - [debounceTime](./study/operators/debounceTime.html)
        - [distinct](./study/operators/distinct.html)
        - distinctKey
        - [distinctUntilChanged](./study/operators/distinctUntilChanged.html)
        - distinctUntilKeyChanged
        - elementAt
        - [filter](./study/operators/filter.html)
        - [first](./study/operators/first.html)
        - ignoreElements
        - audit
        - auditTime
        - [last](./study/operators/last.html)
        - sample
        - sampleTime
        - single
        - [skip](./study/operators/skip.html)
        - skipUntil
        - skipWhile
        - [take](./study/operators/take.html)
        - [takeLast](./study/operators/takeLast.html)
        - [takeUntil](./study/operators/takeUntil.html)
        - takeWhile
        - [throttle](./study/operators/throttle.html)
        - [throttleTime](./study/operators/throttleTime.html)

    - Combination Operators
        - combineAll
        - [combineLatest](./study/operators/combineLatest.html)
        - [concat](./study/operators/concat.html)
        - [concatAll](./study/operators/concatAll.html)
        - exhaust
        - forkJoin
        - [merge](./study/operators/merge.html)
        - [mergeAll](./study/operators/mergeAll.html)
        - race
        - [startWith](./study/operators/startWith.html)
        - [switch](./study/operators/switch.html)
        - [withLatestFrom](./study/operators/withLatestFrom.html)
        - [zip](./study/operators/zip.html)
        - zipAll

    - Multicasting Operators
        - cache
        - multicast
        - publish
        - publishBehavior
        - publishLast
        - publishReplay
        - share

    - Error Handling Operators
        - [catch](./study/operators/catch.html)
        - [retry](./study/operators/retry.html)
        - [retryWhen](./study/operators/retryWhen.html)

    - Utility Operators
        - do
        - [delay](./study/operators/bufferTime.html)
        - delayWhen
        - dematerialize
        - finally
        - let
        - materialize
        - observeOn
        - subscribeOn
        - timeInterval
        - timestamp
        - timeout
        - timeoutWith
        - toArray
        - toPromise

    - Conditional and Boolean Operators

        - defaultIfEmpty
        - every
        - find
        - findIndex
        - isEmpty

    - Mathematical and Aggregate Operators

        - count
        - max
        - min
        - [reduce](./study/demos/reduce.html)
- 综合练习
    - [Drag DOM](./study/demos/dragDOM.html)
    - [DragDOM_extend](./study/demos/dragDOM_extend.html)
    - [follow_img](./study/demos/follow_img.html)

