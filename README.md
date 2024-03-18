# redis-toolkit-dart
An intuitive, object-oriented Redis API for Dart & Flutter

`redis-toolkit-dart` is written following modern Dart conventions, such as:
- Strong typing & Null safety (you always know what is returned)
- Async API (write fast applications via `Future`)

## Features ✨
- High-level, pragmatic API specific to Redis data structures (e.g. `getListRange`, `setHashField`, `addSetItem`)
- (De)Serialization via generic API (e.g. `getValue<int>("counter")`, `getList<DateTime>("timestamps")`, etc.)
- Supports Redis Stream access as Dart Streams
- PubSub support via Dart Stream/Sink
- Key watching via `ValueProvider`
- Low-level API for direct access (`get`, `set`, `command`)
- Connection pooling
- Works on Android, iOS, macOS, Windows, Linux

### Supported Data Structures
- [String](https://redis.io/docs/data-types/strings/)
- [Hash](https://redis.io/docs/data-types/hashes/)
- [List](https://redis.io/docs/data-types/lists/)
- [Stream](https://redis.io/docs/data-types/streams/)

### Auto (De)Serialization
- [`String`](https://api.flutter.dev/flutter/dart-core/String-class.html)
- [`int`](https://api.flutter.dev/flutter/dart-core/int-class.html)
- [`double`](https://api.flutter.dev/flutter/dart-core/double-class.html)
- [`num`](https://api.flutter.dev/flutter/dart-core/num-class.html)
- [`bool`](https://api.flutter.dev/flutter/dart-core/bool-class.html)
- [`DateTime`](https://api.flutter.dev/flutter/dart-core/DateTime-class.html)
- JSON (as [`Map<String, dynamic>`](https://api.flutter.dev/flutter/dart-core/Map-class.html))

### Coming Soon 🚧
- Auto-reconnection
- Transactions
- Object Mapping
- Binary data storage for higher efficiency
- Custom (de)serialization support (e.g. `getValue<ComplexType>("key", deserializerFunc)`)
- Redis Sentinel/Cluster support
- Flutter Web support
- Support for more Redis data types
  - [Set](https://redis.io/docs/data-types/sets/)
  - [Sorted Set](https://redis.io/docs/data-types/sorted-sets/)
  - [Bitmap](https://redis.io/docs/data-types/bitmaps/)
  - [Bitfield](https://redis.io/docs/data-types/bitfields/)
  - [HyperLogLog](https://redis.io/docs/data-types/probabilistic/hyperloglogs/)
  - [Geospatial](https://redis.io/docs/data-types/geospatial/)

## Usage 
Example TBD

## Development 💻
Manual TBD

### Contributing 🥳
Would you like to contribute to the project? Check out the [open issues](https://github.com/mekomidev/redis-toolkit-dart/issues) and/or start a [pull request](https://github.com/mekomidev/redis-toolkit-dart/compare).

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) first

## Sponsorships 💖
Would you like us to prioritize a specific feature or bugfix, or just support further development?

Get in touch with us at `oss -at- mekomi.dev` 
