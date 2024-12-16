<h1 align="center">
  <br>
    <img src="pict/logo.png" alt="logo" width="200">
</h1>

# Static Routing 
Welcome to the Static Routing Repository. This documentation will guide you through understanding and setting up Static Routing on your computer. You will receive all the necessary knowledge and tools from this comprehensive guide.

## Table of Contents
1. [Configuration](#configuration)
2. [Prerequisites](#prerequisites)
3. [Your Steps](#steps)

# Configuration
<h1 align="center">
  <br>
    <img src="pict/configuration.png" alt="configuration" width="1000">
</h1>

# Prerequisites
Before you proceed with the steps, make sure you have the following prerequisites:

1. **Ubuntu**: If you are using Windows, you can download Ubuntu from:
    [Ubuntu](https://ubuntu.com/desktop/wsl)

2. **Mininet**: Download Mininet from:
    [Mininet](https://mininet.org/)

3. Navigate to the Mininet directory:

    ```bash
    cd mininet
    ```

4. Install all Mininet companions by running the following command:

    ```bash
    ./util/install.sh -a 
    ```

5. Once the installation is complete, you can proceed to the next steps.

# Steps
Follow the steps below to get the system up and running on your computer:

1. Clone the repository:

    ```bash
    git clone https://github.com/TeamXNetRouter/JKL-StaticRouting.git
    ```

2. Navigate to the project directory:

    ```bash
    cd JKL-StaticRouting
    ```
    
3. Change the config storage place in the static_routing_2rtr.py file according to your ubuntu environment (line 39)

     ```bash
   ('/etc/frr', '/home/yourusername/net101/projects/frr-config/%(name)s'),
    ```

4. Run the project with the following command:

    ```bash
    sudo python3 static_routing_2rtr.py
    ```

6. To test the setup, you can use the following command in the terminal:

    ```bash
    h1 ping h2
    h1 traceroute -n h2
    ```

---
