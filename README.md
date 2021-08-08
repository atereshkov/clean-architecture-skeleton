[![Build Status](https://travis-ci.com/atereshkov/clean-architecture-skeleton.svg?branch=main)](https://travis-ci.com/atereshkov/clean-architecture-skeleton) [![codecov](https://codecov.io/gh/atereshkov/clean-architecture-skeleton/branch/main/graph/badge.svg)](https://codecov.io/gh/atereshkov/clean-architecture-skeleton)

# iOS Clean Architecture (MVVM) Skeleton
Swift (UIKit) sample app using Clean Architecture based on MVVM pattern. Examples of data persistence, networking, dependency injection, unit testing and more.

This is how I see implementation of scalable and maintainable architecture for iOS projects. Based on my personal point of view & experience.

## Overview

![Architecture Overview](https://github.com/atereshkov/blob_storage/blob/7404bde3c0a9a7de6e6e3185910e05baa8a73a51/clean-architecture-skeleton/clean-architecture-overview.png?raw=true)

## Features

* Designed with scalability in mind. Skeleton project can be used as a reference for building apps
* Redux-like centralized states used as the single source of truth
* Persistance layer written in abstract way (Realm is used under the hood)
* Simple and effective Dependency Injection implementation using Swinject
* Navigation separated from View
* Covered with Unit & UI tests

## Layers

### Presentation Layer
### Business Layer
### Data Access Layer

## Third-party libraries

Skeleton project uses following third party libraries:
* Swinject
* ...
* ...
* ...
* ...

## Usage

### Requirements

* Swift 5.1
* iOS 13.0

### Installation

1. Download repository
2. Run 'pod install'
3. Open **clean-architecture-skeleton.xcworkspace**

## Why I made it?

1. TBD
2. TBD
3. TBD
4. TBD
5. TBD

## Contributing

I'm really happy to accept contributions from the community to improve the code!

1. Fork it (https://github.com/atereshkov/clean-architecture-skeleton/fork)
2. Create your feature branch (git checkout -b feature/fooBar)
3. Commit your changes (git commit -am 'Add some fooBar')
4. Push to the branch (git push origin feature/fooBar)
5. Create a new [Pull Request](https://github.com/atereshkov/clean-architecture-skeleton/pulls)

## Maintainers

* Alexander Tereshkov | [Github](https://github.com/atereshkov) | [Contact me](https://tereshkov.pw/)

---

Insipred by [github | nalexn](https://github.com/nalexn/clean-architecture-swiftui).
