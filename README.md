# A short guide to asynchronous programming<br>with asyncio
by Karol Horosin

Slides/notebook from a short asyncio workshop.

## Run presentation

Install requirements, open notebook and run using RISE plugin - [repo](https://github.com/damianavila/RISE).

Alternatively just generate html file:
```
jupyter nbconvert asyncio-workshop.ipynb --to slides --post serve
```

You can also just [browse the notebook](asyncio-workshop.ipynb).

## Acknowledgements
* Thanks to @klaussweiss for investigating default stack size for new threads
* Thanks to @nielsdenissen for inspiration for slides visualising how tasks are executed in a loop https://github.com/nielsdenissen/pydata-asyncio