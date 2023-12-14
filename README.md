# Minecraft Docker Project

This project allows you to run a Minecraft server using Docker.

## Prerequisites

- Docker installed on your machine

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/mc-nations/config.git minecraft-nations
    ```

2. Initialize and update submodules:

    ```bash
    cd minecraft-nations
    git submodule init
    git submodule update
    ```

3. Create a `minecraft.env` file:

    ```bash
    touch minecraft.env
    ```

4. Customize the environment variables in the `minecraft.env` file as per your requirements. The two variables that can be configured are:

    - `min_memory`: The minimum memory allocation for the Minecraft server.
    - `max_memory`: The maximum memory allocation for the Minecraft server.

5. Start the Docker Compose with the `--build` flag:

    ```bash
    docker-compose up --build
    ```

    This command will build and start the Minecraft server container.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://github.com/mc-nations/.github/blob/main/LICENSE.txt).
    

    You can customize the environment variables in this file as per your requirements.
