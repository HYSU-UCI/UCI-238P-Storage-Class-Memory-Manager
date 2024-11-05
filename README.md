# 238P OS Project3: Storage Class Memory Manager

## Overview

A robust memory management system featuring an API reminiscent of the C malloc() function. This system will utilize a file as its underlying storage to ensure persistent data availability across different processes.

## Usage

```
make
dd if=/dev/zero of=file bs=4096 count=10000
./cs238 ./file
```
