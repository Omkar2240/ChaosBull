# 🐂 ChaosBull

> Break your website on purpose. Before your users do.

ChaosBull is a Chrome extension that lets developers simulate real-world failures directly inside the browser with a single click.

Test how your application behaves under bad networks, offline conditions, failed API requests, and other production incidents without touching your backend infrastructure.

Perfect for frontend developers, QA engineers, and teams practicing chaos engineering.

## ✨ Features

* 🌐 Simulate Offline Mode
* 🐌 Slow 2G, 3G and custom network throttling
* ❌ Force API failures
* ⏳ Inject artificial latency into requests
* 🔄 Retry and timeout testing
* 📦 Test loading states and skeleton screens
* ⚡ Toggle failures instantly with one click
* 🧪 Safe browser-side chaos experiments

## Why ChaosBull?

Most developers test their applications on:

* Fast WiFi
* Perfect API responses
* Zero latency
* Stable internet

Real users don't.

ChaosBull helps you answer questions like:

* What happens if the user loses internet?
* Does the UI handle failed requests gracefully?
* Are loading states actually usable?
* Does the app recover after reconnecting?
* Will the checkout flow survive API timeouts?

If the answer is "I don't know", ChaosBull is for you.

## Installation

### Option 1 — Install from ZIP

1. Download the extension ZIP:

https://github.com/Omkar2240/ChaosBull/releases/downloads/v1.0.0/chaosbull.zip

2. Extract the ZIP file.

3. Open Chrome and navigate to:

```text
chrome://extensions
```

4. Enable **Developer Mode**.

5. Click **Load unpacked**.

6. Select the extracted ChaosBull folder.

7. Pin the extension to your toolbar.

Done 🎉

## Usage

1. Open your web application.
2. Click the ChaosBull extension icon.
3. Select the failure you want to simulate.
4. Refresh your application if necessary.
5. Observe how your application behaves.

## Example Scenarios

### Offline Testing

Turn your website completely offline and verify:

* Offline pages
* Error handling
* Reconnect logic
* Cache behavior

### Slow Network Testing

Simulate:

* Slow 2G
* Slow 3G
* High latency users

Useful for testing:

* Skeleton loaders
* Suspense boundaries
* Streaming responses
* Progressive loading

### API Failure Testing

Force requests to fail and verify:

* Retry mechanisms
* Error states
* Toast notifications
* Recovery flows

## Built For

* Frontend Developers
* QA Engineers
* Indie Hackers
* SaaS Teams
* Developer Advocates
* Performance Engineers

## Chaos Engineering in the Browser

Chaos Engineering is the practice of intentionally introducing failures into a system under controlled conditions to verify resilience and recovery behavior.

ChaosBull brings that philosophy directly to frontend development.

## Roadmap

* [ ] Packet loss simulation
* [ ] Custom latency profiles
* [ ] Scheduled failures
* [ ] Team presets
* [ ] Session recording
* [ ] Shareable testing scenarios

## Contributing

Issues and feature requests are welcome.

If ChaosBull helped you find a bug before your users did, consider starring the repository ⭐

## Author

Built by Omkar Ramgirwar.

## License

MIT License
