# sampl
Write an API out of sample responses.

This allows you to write APIs out of sample responses and instructions. You give it something like:
```
sampl create contributions
> Response: { "contributions_public": 420, "contributions_private": 69 }
> Input URL: https://example.com/%s
> Fields:
> contributions_public: public_contributions
> contributions_private: private_contributions
Created API in /contributions
```