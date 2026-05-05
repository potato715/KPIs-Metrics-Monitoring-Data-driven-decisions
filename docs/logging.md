# Basic Logging Plan

## What We Log
- Timestamp of each request
- Response time (ms)
- Error messages and error codes
- User actions (page visited, task completed or abandoned)

## How to Log (Simple Start)
- Use browser console logs during development
- Write errors to a log file on the server
- Use a free tool like **Logtail** or **Papertrail** for log management

## Log Example
```
[2026-05-06 10:32:01] GET /home - 145ms - 200 OK
[2026-05-06 10:32:05] POST /submit - 320ms - 500 ERROR
```
