# Enterprise Storage Manager (ESM)

## Overview
Enterprise Storage Manager is a C++ based storage orchestration engine built on RHEL. It provisions, expands, and manages logical volumes using LVM and enforces access control using ACL.

## Features
- Logical Volume creation
- Online volume expansion
- Persistent mounting
- ACL-based access control
- Logging and audit tracking
- Hybrid CLI + Web architecture (planned)

## Architecture
User → CLI / Web → C++ Engine → LVM / ACL → Linux Storage Stack

## Tech Stack
- C++
- LVM (Device Mapper)
- ACL
- RHEL
- Git

## Current Status
Core infrastructure setup completed.
C++ engine development in progress.
