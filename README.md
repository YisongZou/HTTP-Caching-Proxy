# HTTP-Caching-Proxy

1. Established a proxy server on Linux VM to handle GET, POST and CONNECT HTTP request from browser.
2. Implemented multithreading for concurrent requests and achieved synchronization by RAII strategy.
3. Integrated an LRU cache for efficiency and accomplished response expire-checking and re-validation.
4. Achieved robustness to external failures by providing exception guarantee for request and response.
