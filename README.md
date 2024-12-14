<h1 align="center">
  <br>
    <img src="pict/logo.png" alt="logo" width="200">
</h1>

# Static Routing 
Welcome to Static Routing Repository. This documentation will guide you through understanding and setting up the Static Routing from your computer. You will receive all the required knowledge and tools from this extensive guide.

## Table of Contents
1. [Configuration](#configuration)
2. [Prerequisites](#prerequisites)
3. [Your Steps](#steps)

# Configuration
<h1 align="center">
  <br>
    <img src="pict/configuration.png" alt="configuration" width="200">
</h1>

# Prerequisites
Before you do all the step, you should have this prerequisites

1. Get your ubuntu. If you use Windows you can download from:
    [Ubuntu](https://ubuntu.com/desktop/wsl)

2. Get your mininet configuration from:
    [Mininet](https://mininet.org/)

3. Navigate to mininet directory:

    ```bash
    cd mininet
    ```

3. Install all of mininet companion:

    ```bash
    mininet/util/install.sh
    ```

4. You can move to steps

# Steps
follow all this steps below to get it running on your computer

1. Clone the repository:

    ```bash
    https://github.com/TeamXNetRouter/JKL-StaticRouting.git
    ```

2. Navigate to project directory:

    ```bash
    cd static-routing
    ```

3. Run the project:

    ```bash
    sudo pyhton3 static_routing_2rtr.py -c frr-config
    ```

4. You can test it from terminal:

    ```bash
    h1 ping h2
    ```