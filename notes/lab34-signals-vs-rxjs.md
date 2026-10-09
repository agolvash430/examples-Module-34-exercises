# Lab 34 — Decide Signals versus RxJS

## Three Cases

Local UI state → Signals  
Async streams / external events → RxJS  
Shared model state → BehaviorSubject or Signal depending on push vs. derive

## Justify

Signals excel at synchronous, UI‑driven state with automatic reactivity; RxJS handles async, multi‑event, cancellation, and operators.

## Interop

Convert signals to observables with toObservable(), and observables to signals with toSignal() when UI needs reactive binding.

## Team Rule

Use signals for component‑local state; use RxJS for async workflows; use subjects only when the model must actively push state.

## Scope
Pre-lab only — do not finish the full lab in this exercise.
