# Release notes

<!-- do not remove -->

## 1.1.5

### Bugs Squashed

- `self.out` not initialised properly ([#118](https://github.com/AnswerDotAI/fastprogress/issues/118))


## 1.1.3

### New Features

- Add `show_styles` ([#116](https://github.com/AnswerDotAI/fastprogress/issues/116))


## 1.1.1

### New Features

- Add `hdrs` ([#115](https://github.com/AnswerDotAI/fastprogress/issues/115))


## 1.1.0

### Breaking Changes

- Convert to fasthtml and modernize ([#114](https://github.com/AnswerDotAI/fastprogress/issues/114))


## 1.0.5

### New Features

- Solveit compat ([#113](https://github.com/AnswerDotAI/fastprogress/issues/113))


## 1.0.3

### New Features

- support unknown `total` by passing `total='noinfer'` ([#102](https://github.com/fastai/fastprogress/pull/102)), thanks to [@seeM](https://github.com/seeM)
- support PyCharm console as TTY ([#101](https://github.com/fastai/fastprogress/issues/101))


## 1.0.2

### Bugs Squashed

- Check that stdout exposes `isatty` ([#81](https://github.com/fastai/fastprogress/pull/81)), thanks to [@scw](https://github.com/scw)


## 1.0.1

### Bugs Squashed

- Move the style overrides to a separate HTML widget ([#79](https://github.com/fastai/fastprogress/pull/79)), thanks to [@jpc](https://github.com/jpc)
  - This fixes performance problems on Safari

