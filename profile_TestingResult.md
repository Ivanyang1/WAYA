# Profile Setup Test Results

## Test Overview

This section documents the results from the automated tests conducted on the profile setup functionalities of our Telegram bot. The tests primarily assess the reliability of the asyncio event loops and ensure that the bot handles asynchronous operations accurately.

## Test Environment Details

- **Test Framework:** Python's `unittest`
- **Number of Tests Run:** 7
- **Total Test Duration:** 0.464 seconds

## Detailed Test Outcomes

All tests executed successfully, indicating robust and reliable profile setup operations. The test ensures that asynchronous event loop handling is efficient, with no errors or failures noted.

## Detailed Log Output

```plaintext
2024-07-28 17:21:43,417 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,466 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 17:21:43,483 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,531 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 17:21:43,548 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,598 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 17:21:43,615 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,665 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 17:21:43,681 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,732 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 17:21:43,748 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,798 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
2024-07-28 17:21:43,815 - asyncio - DEBUG - Using selector: KqueueSelector
2024-07-28 17:21:43,865 - asyncio - DEBUG - Close <_UnixSelectorEventLoop running=False closed=False debug=True>
