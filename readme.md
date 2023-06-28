# PoC: Streaming API Response PY+JS (Server and Client)

![](.readme/preview.gif)

## Details

||| |
| - | - | - |
| server | python | (Starlette/ FastAPI) https://pypi.org/project/sse-starlette |
| | CORS | https://codehammer.io/fastapi-access-to-fetch-blocked-by-cors-policy/#:~:text=When%20using%20FastAPI%2C%20this%20error%20can%20occur%20when,from%20starlette.middleware.cors%20and%20add%20it%20to%20your%20app. |
| client| JS | EventSource (inbuilt) |


## Bare Minimum Code
NA

## Playground

1. Install deps.
    ```python
    pip install -r requirements.txt
    ```

2. Run server
    ```python
    python server/p2.py
    ```

3. Running client side
    - open the file `client/index.html`
    - Or use VS Code live server


