![Hook Watcher Banner](https://raw.githubusercontent.com/Tsy1417/Hook-Watcher/main/banner.png)

# Hook Watcher

Hook Watcher is a webhook scrapper that continuously monitors webhooks and provides real-time updates via an endpoint. With Hook Watcher, you can easily integrate with any application that supports webhooks, and get notified whenever a new event or disovery occurs.

## Features

- Real-time monitoring of new webhooks
- Configurable filters for webhook detection
- Integration with multiple applications and services
- Web-based interface for managing and monitoring new webhooks

## Getting Started

To use Hook Watcher, you will need to install the dependencies and configure your environment variables. Here are the steps to get started:

1. Clone the repository:

    ```git clone https://github.com/Tsy1417/Hook-Watcher.git```

2. Install the dependencies:

    ```pip install -r requirements.txt```

3. Start the server:

    ```python app.py```

## Usage

To use Hook Watcher, you will need to create a webhook URL in an application or service that you want to integrate with (like Discord).

Here's an example of how to create a webhook URL in Discord:

1. Make a account then a discord server
2. Right click on a channel (edit channel)
3. Press on Intergrations
4. Webhooks
5. Create new
6. Copy webhook url
7. Paste it into the config.json file as the endpoint url

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
