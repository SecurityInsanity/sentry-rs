## 2.2.0 (Febuary 25th, 2018)

- Use Hyper 0.11 instead of Hyper 0.10 (Async I/O!)
- Fix validation errors with device/event-id.
- Update some other dependencies.
- Have Examples actually log now.

## 2.1.2 (November 16th, 2017)

- Allow Extras to be a JSON Value.
- Use HashMap over BTreeMap.

## 2.1.1 (April 22nd, 2017)

- Bump Serde dependencies.

## 2.1.0 (April 8th, 2017)

- Removed Event Queue Draining before Event Posting.
- Added missing documentation for string parsing sentry credentials.

## 2.0.0 (March 29th, 2017)

- Allowed Specifying of Devices (Breaking Change). Still defaults to the same.
- Allowed parsing of the sentry credentials from a raw dsn string.
- Allowed you to compare equality of all models.

## 1.5.1 (March 12th, 2017)

- Fixed context line being one off.

## 1.5.0 (March 12th, 2017)

- Added "in app" field to stacktraces to quickly get you to your apps errors.
- Cleaned up some parts in json serialization.
- Added to the panic-handler-demo example.

## 1.4.1 (March 6th, 2017)

- Clean up internal structure to be more "modular".
- Add in more tests, and documentation.

## 1.4.0 (March 2nd, 2017)

- Make programs not wait the full 5 second HTTP Timeout on panic.

## 1.3.0 (March 2nd, 2017)

- Made Context Lines an optional feature that are enabled by default.
- Bumped amount of context lines from 2 on each side to 5.
- Cleaned up Serialization of Events. To no longer be a manual spaghetti.
- Bumped Backtrace-rs/Chrono dependencies to their latest version.

## 1.2.0 (Feburary 28th, 2017)

- Added the ability to have a callback function on your panic handler.

## 1.1.0 (Feburary 18th, 2017)

- Add 3 context lines always if we can parse the file.
- Added some Cargo.toml attributes.

## 1.0.0 (Feburary 15th, 2017)

- Initial Release of Sentry-RS.
