# Event Management Testing Results

## Summary of Bot Functionality Tests

This section presents the results from automated tests conducted to ensure the correct functioning of asynchronous operations within our Telegram bot. The tests specifically target the event loop management by the `asyncio` library to ensure stability and efficiency.

### Test Environment Details

- **Test Framework:** Python's `unittest`
- **Number of Tests Run:** 7
- **Total Duration:** 0.202 seconds

### Test Outcomes

All tests executed successfully with no failures, indicating that the bot's asynchronous operations are stable and efficient.

### Detailed Log Output

```plaintext
2024-07-28 13:22:04,852 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:04,885 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 13:22:04,901 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:04,918 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 13:22:04,921 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:04,938 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 13:22:04,951 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:04,968 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 13:22:04,971 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:04,988 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 13:22:05,001 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:05,018 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 13:22:05,021 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 13:22:05,052 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
