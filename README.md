# LUH-Observer
Experimenting with Go by monitoring my university's exam schedule and module catalog. When updates occur, a message is sent using _Telegram_.

## Basic Build Instructions

1. Clone this repo.
2. Navigate to the root directory.
3. Create a `.env` file with **CHAT_ID** and **API_KEY** as keys and your corresponding values, e. g.:
    ```sh
    CHAT_ID: 123456789
    API_KEY: 0123456789:XYZXiK0SHm1ge_BmwEwwOZQigv8LSAy92v6
    ```
4. `$ go install luh_observer.einheitsviktor`
5. `$ go build luh_observer.go`
6. `$ ./luh_observer`

Suggestion: Schedule a job to run periodically via [cron](https://wiki.archlinux.org/title/cron).
