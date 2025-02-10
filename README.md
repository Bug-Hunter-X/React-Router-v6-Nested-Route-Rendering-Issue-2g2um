# React Router v6 Nested Route Bug

This repository demonstrates a common, yet subtle, bug in React Router v6 related to nested routes and their rendering behavior.  The issue occurs when a seemingly correctly defined route fails to render its component. The problem is often difficult to diagnose due to its non-obvious nature.

## Problem Description
The `Contact` component fails to render when you navigate to `/contact`.  This happens despite the route definition seeming perfectly valid.  The bug is due to an incorrect route configuration.  The solution involves properly structuring the routes and nesting them appropriately within the parent Route.