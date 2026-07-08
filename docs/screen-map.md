# Screen Map

## Primary User Flows

```text
Landing Page
    │
    ├──> Registration Page
    │       │
    │       v
    │   Reading Log Page
    │
    ├──> Login Page
    │       │
    │       v
    │   Reading Log Page
    │
    └──> Book Search Results Page
            │
            ├──> (Logged Out)
            │       │
            │       v
            │  Registration Page
            │
            └──> (Logged In)
                    │
                    v
               Create Reading Log Entry Page
                    │
                    v
               Reading Log Page

Reading Log Page
    │
    ├──> Create Reading Log Entry Page
    │       │
    │       v
    │   Reading Log Page
    │
    ├──> Log Entry Details Page
    │       │
    │       v
    │   Edit Log Entry Page
    │       │
    │       v
    │   Log Entry Details Page
    │
    └──> Book Search Results Page
            │
            v
        Create Reading Log Entry Page
            │
            v
        Reading Log Page
```

## Error Flows

```text
Protected Route Access
    │
    v
Unauthorized Page

Invalid Route
    │
    v
404 Not Found Page
```

## Copy and paste to build:

```text
│
├──
└──
v
```