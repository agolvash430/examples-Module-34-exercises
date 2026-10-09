# Lab 34 — Model State with Signals

## State List

selectedCustomerId, filterText, isLoading, errorMessage

## Read and Write

Use Signal<T> for mutable model state and expose read-only accessors so only the model can mutate.

## Computed

Use computed() for any value derived from other signals, such as filteredCustomers or selectedCustomer.

## Why Not a Field

Fields don’t notify the UI; signals provide reactivity, tracking, and automatic updates.

## Scope
Pre-lab only — do not finish the full lab in this exercise.
