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
        - interval
        - [never](./study/operators/never.html)
        - [of](./study/operators/of.html)
        - repeat
        - repeatWhen
        - range
        - [throw](./study/operators/throw.html)
        - timer

    - Transformation Operators
        - buffer
        - bufferCount
        - bufferTime
        - bufferToggle
        - bufferWhen
        - concatMap
        - concatMapTo
        - exhaustMap
        - expand
        - groupBy
        - map
        - mapTo
        - mergeMap
        - mergeMapTo
        - mergeScan
        - pairwise
        - partition
        - pluck
        - scan
        - [switchMap](./study/operators/switchMap.html)
        - switchMapTo
        - window
        - windowCount
        - windowTime
        - windowToggle
        - windowWhen

    - Filtering Operators
        - debounce
        - debounceTime
        - distinct
        - distinctKey
        - distinctUntilChanged
        - distinctUntilKeyChanged
        - elementAt
        - filter
        - first
        - ignoreElements
        - audit
        - auditTime
        - last
        - sample
        - sampleTime
        - single
        - skip
        - skipUntil
        - skipWhile
        - take
        - takeLast
        - takeUntil
        - takeWhile
        - throttle
        - throttleTime

    - Combination Operators
        - combineAll
        - combineLatest
        - concat
        - concatAll
        - exhaust
        - forkJoin
        - merge
        - mergeAll
        - race
        - startWith
        - [switch](./study/operators/switch.html)
        - withLatestFrom
        - zip
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
        - catch
        - retry
        - retryWhen

    - Utility Operators
        - do
        - delay
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
        - reduce