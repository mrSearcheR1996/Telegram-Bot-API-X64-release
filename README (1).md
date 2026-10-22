# Telegram Bot API

Telegram Bot API is an HTTP server for building Telegram bots locally. This repository contains the server implementation and its TDLib dependencies. It is built with CMake and supports Windows x64 builds using Visual Studio 2022.

## Overview

This project provides a local Telegram Bot API server that can be used instead of the official hosted Bot API service. It is intended for:

- local bot development
- custom webhook handling
- local file access and testing
- full control over bot API server deployment

## Requirements

Before building on Windows, install:

- Visual Studio 2022 with Desktop C++ workload
- CMake 3.10 or newer
- Git with submodules support
- OpenSSL
- zlib
- Optional: vcpkg for installing dependencies

Recommended:
- vcpkg + x64-windows triplet

## Clone

```bat
git clone --recurse-submodules https://github.com/tdlib/telegram-bot-api.git
cd telegram-bot-api