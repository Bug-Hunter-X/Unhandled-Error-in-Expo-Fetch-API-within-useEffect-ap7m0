# Unhandled Error in Expo Fetch API within useEffect

This repository demonstrates a common error when using the `fetch` API within a `useEffect` hook in Expo. The issue is that if the fetch fails or the server returns an error, it might not properly handle the error, leading to a crash or unexpected behavior.  This example shows a common approach to error handling, but there might still be edge cases not fully covered.  The solution demonstrates how to enhance the error handling to improve its robustness.  It also showcases the use of a custom error handling mechanism for additional clarity and extensibility.