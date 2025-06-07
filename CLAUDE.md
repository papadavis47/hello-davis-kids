# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple Go application called "hello-davis-kids" that prints a greeting message. The project uses Go 1.24.0 and follows standard Go project structure.

## Common Commands

- **Run the application**: `go run main.go`
- **Build the application**: `go build .`
- **Format code**: `go fmt ./...`
- **Vet code for common errors**: `go vet ./...`
- **Run tests**: `go test ./...`
- **Tidy module dependencies**: `go mod tidy`

## Architecture

The application consists of a single `main.go` file with a simple main function that outputs "Hello, Davis Kids!" using the standard fmt package. The module is defined in `go.mod` as "hello-davis-kids".