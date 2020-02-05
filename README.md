# Today-I-Learned
Document what I have learned today to track the knowledge graph.

## 2020-02-04
### SameSite cookies

- None
    - allow cross-site requests and same-site requests
- Strict
    - The browser will only send cookies for same-site requests (requests originating from the site that set the cookie). If the request originated from a different URL than the URL of the current location, none of the cookies tagged with the **Strict** attribute will be included.
- Lax
    - Default since Chrome 80
    - Withhold cross-site subrequests: load images or frames, allow user navigation.
    
References: https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies#SameSite_cookies

