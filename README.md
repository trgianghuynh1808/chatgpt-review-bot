# chatgpt-review-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that A Probot app

## Demo
[![Watch the video](https://img.youtube.com/vi/EuKKCKgkBEM/hqdefault.jpg)](https://www.youtube.com/watch?v=EuKKCKgkBEM)

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t chatgpt-review-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> chatgpt-review-bot
```

## Contributing

If you have suggestions for how chatgpt-review-bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2024 Giang Huynh
