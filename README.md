
# Service Tweak

A simple Bash script to manage system services like MySQL, Apache2, and Node.js. Based on your input, the script allows you to start or stop these services.

## Features

- **Interactive Prompt**: Decide whether to start or stop services.
- **Supports Common Services**:
  - MySQL
  - Apache2
  - Node.js
- **Error Handling**: Provides feedback on the success or failure of each operation.

## Usage

### Clone the Repository
```bash
git clone https://github.com/TharinduWijayarathna/Service-Tweak.git
cd Service-Tweak
```

### Make the Script Executable
```bash
chmod +x service-tweak.sh
```

### Run the Script
```bash
./service-tweak.sh
```

### Example Workflow
1. The script will ask if you want to start or stop services.
2. Enter `start` to start the services or `stop` to stop them.
3. The script will perform the selected operation and provide status messages.

## Customization

- Modify the script to include additional services or specific commands as needed.
- For Node.js, include custom commands to start your applications.

## Requirements

- Bash shell
- Sudo privileges to manage system services

## Contributing

Feel free to fork the repository and submit pull requests for improvements or additional features.
