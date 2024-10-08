# Custom Pi-hole Blocklist

## Overview

This project provides a custom blocklist for Pi-hole, a popular network-wide ad blocker. The blocklist is designed to enhance your browsing experience by preventing unwanted ads, tracking scripts, and malicious domains.

## Features

- **Comprehensive Coverage:** The blocklist includes a wide range of domains known for serving ads and tracking users.
- **Regular Updates:** The blocklist is regularly updated to ensure effectiveness against the latest threats.
- **Customizable:** Users can easily add or remove domains based on their preferences.

## Installation

To add the custom blocklist to your Pi-hole setup, follow these steps:

1. **Access Pi-hole Admin Interface:**
   - Open your web browser and navigate to the Pi-hole admin panel (usually at `http://<your_pi-hole_ip>/admin`).

2. **Navigate to Blocklists:**
   - Go to **Group Management** > **Adlists**.

3. **Add the Custom Blocklist:**
   - In the "Address" field, enter the URL of your custom blocklist (e.g., `https://raw.githubusercontent.com/yourusername/custom-pihole-blocklist/master/blocklist.txt`).
   - Click on **Add**.

4. **Update Gravity:**
   - After adding the blocklist, run the following command in your terminal to update Pi-hole’s gravity:
     ```bash
     pihole -g
     ```

## Blocklist Format

The blocklist is provided in a simple text format, with each domain listed on a new line. It is compatible with Pi-hole and can be easily modified as needed.

## Contribution

Contributions are welcome! If you find additional domains that should be added to the blocklist or if you have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

Thanks to the Pi-hole community for their support and resources, and to all contributors who help keep the blocklist effective and up-to-date.

Feel free to reach out with any questions or suggestions!
