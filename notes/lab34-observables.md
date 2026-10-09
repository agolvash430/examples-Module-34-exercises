# Lab 34 — Trace Observables and Subjects

## Cold Start

Cold observables do nothing until subscribed; each subscription restarts the producer.

## Cleanup

Unsubscribe in ngOnDestroy (or use takeUntil) so the producer stops and resources are released.

## BehaviorSubject

Holds a current value and immediately emits it to new subscribers; good for model state.

## Where It Fits

Use when the model must *own* state and push updates; components subscribe to stay in sync.

## Scope
Pre-lab only — do not finish the full lab in this exercise.
