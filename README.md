<p align="center">
    <em>Quicker FastApi developing tools</em>
</p>
<p align="center">
<img src="https://img.shields.io/github/last-commit/yuval9313/fastapi-restful.svg">
<a href="https://fastapi-restful.netlify.app">
    <img src="https://img.shields.io/netlify/28b2a077-65b1-4d6c-9dba-13aaf6059877" alt="Netlify status">
</a>
<br />
<a href="https://pypi.org/project/FastApi-RESTful" target="_blank">
    <img src="https://badge.fury.io/py/fastapi-restful.svg" alt="Package version">
</a>
<a href="https://github.com/yuval9313/fastapi-restful" target="_blank">
    <img src="https://img.shields.io/pypi/pyversions/FastApi-RESTful.svg" alt="Python versions">
    <img src="https://img.shields.io/github/license/yuval9313/fastapi-utils.svg" alt="License">
</a>
</p>

---

**Documentation**: <a href="https://fastapi-restful.netlify.app" target="_blank">https://fastapi-restful.netlify.app</a>

**Source Code**: <a href="https://github.com/yuval9313/fastapi-restful" target="_blank">https://github.com/yuval9313/fastapi-restful</a>

Base on: <a href="https://github.com/dmontagu/fastapi-utils" target="_blank">https://github.com/dmontagu/fastapi-utils</a>

---

<a href="https://fastapi.tiangolo.com">FastAPI</a> is a modern, fast web framework for building APIs with Python 3.6+.

But if you're here, you probably already knew that!

---

## Features

This package includes a number of utilities to help reduce boilerplate and reuse common functionality across projects:

* **Resource Class**: Create CRUD with ease the OOP way with `Resource` base class that lets you implement methods quick.
* **Class Based Views**: Stop repeating the same dependencies over and over in the signature of related endpoints.
* **Response-Model Inferring Router**: Let FastAPI infer the `response_model` to use based on your return type annotation. 
* **Repeated Tasks**: Easily trigger periodic tasks on server startup
* **Timing Middleware**: Log basic timing information for every request
* **SQLAlchemy Sessions**: The `FastAPISessionMaker` class provides an easily-customized SQLAlchemy Session dependency 
* **OpenAPI Spec Simplification**: Simplify your OpenAPI Operation IDs for cleaner output from OpenAPI Generator

---

It also adds a variety of more basic utilities that are useful across a wide variety of projects:

* **APIModel**: A reusable `pydantic.BaseModel`-derived base class with useful defaults
* **APISettings**: A subclass of `pydantic.BaseSettings` that makes it easy to configure FastAPI through environment variables 
* **String-Valued Enums**: The `StrEnum` and `CamelStrEnum` classes make string-valued enums easier to maintain
* **CamelCase Conversions**: Convenience functions for converting strings from `snake_case` to `camelCase` or `PascalCase` and back
* **GUID Type**: The provided GUID type makes it easy to use UUIDs as the primary keys for your database tables

See the [docs](https://fastapi-restful.netlify.app/) for more details and examples. 

## Requirements

This package is intended for use with any recent version of FastAPI (depending on `pydantic>=1.0`), and Python 3.6+.

## Installation

```bash
pip install fastapi-restful
```

## License

This project is licensed under the terms of the MIT license.
