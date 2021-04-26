## 0xSSRF - WEB

![task](task.png)

Clearly the name refers to Server Side Request Forgery

Clicking on ```Get flag``` won't give you the flag but tell you that your IP address
isn't 127.0.0.1. Well it isn't.

So make a request to the flag endpoint using the provided proxy service itself

![website_1](website_1.png)

Nope! Tried some common SSRF payloads and this one worked.

![website_2](website_2.png)
