# Setup Library

A Flutter library for state management, networking, and preferences.

## Installation

Add this to your `pubspec.yaml`:

```yaml
dependencies:
  setup_library: ^0.0.1
```

Then run:

```bash
flutter pub get
```

## Usage

Import the library:

```dart
import 'package:setup_library/library.dart';
```

Example usage:

```dart
void main() {
  Bloc.observer = MyBlocObserver();
  runApp(MyApp());
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Changelog

### 0.0.1
- Initial release with BlocObserver, SharedPreferences, and UI resources.

---

## License

MIT License

```
MIT License

Copyright (c) 2025 Rewan Nashat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

- Proper attribution must be given.
```
