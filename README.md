# POSHScheduler

POHScheduler is a PowerShell-based task scheduling framework that enables the automation and management of script execution on various schedules. Designed for both Windows PowerShell and PowerShell Core, it offers a robust solution for handling tasks across different environments with ease.

## Features

- Modular scheduling with hourly, daily, weekly, monthly, quarterly, and yearly options.
- Cross-version script execution compatible with PowerShell 5 and PowerShell 7.
- Asynchronous, non-blocking script execution for service-like operations.
- Built-in error handling and logging for reliability and troubleshooting.

## Getting Started

To get started with POSHScheduler, clone the repository to your local machine using:

\```shell
git clone https://github.com/your-username/POSHScheduler.git
\```

Set up the folder structure as per the guidelines in the repository and place your PowerShell scripts in the respective folders based on their intended schedule.

## Usage

Run the main scheduler script using PowerShell:

\```shell
pwsh ./POSHScheduler.ps1
\```

Or set it up as a Windows Service using a service wrapper like NSSM for continuous operation.

## Contributing

Contributions to POSHScheduler are welcome! Please read through our contributing guidelines to learn about our submission process, coding standards, and more.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you need help with POSHScheduler or have a question, please open an issue for support.

## Acknowledgments

- Thanks to all contributors who have helped to build and maintain this project.
