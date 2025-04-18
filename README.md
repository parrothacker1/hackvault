<div align="center">
  <h1>HackVault</h1>
  <p><strong>A highly optimized CTF platform backend written in Go</strong></p>
</div>

> [!WARNING]
> This project is currently under active development and does not have a stable release. Use it at your own discretion.

---

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)

---

## Introduction

HackVault aims to be a highly efficient backend for CTF (Capture The Flag) platforms, with performance and scalability in mind. The project is being developed using Go (Golang) for its concurrency model and lightweight footprint.

---

## Requirements

- **Docker**  
  Please refer to the official [Docker installation documentation](https://docs.docker.com/get-docker/) for setup instructions.

> **Why Docker?**  
> Some of the services in this project are tightly coupled. The recommended way to run everything is via Docker Compose, which ensures proper coordination between services.  
>  
> If you prefer running services individually on your local environment, be aware that some components might break or not function as expected without the full stack.
