# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2025-02-21

### Added
- Initial release of AzureLab Dashboard
- Real-time VPS monitoring dashboard with automatic refresh every 5 seconds
- CPU usage monitoring with visual doughnut chart
- RAM usage tracking with used/total memory display
- Disk space monitoring showing free space in GB
- Server uptime display with formatted output
- Network bandwidth monitoring (Upload/Download) in kbit/s
- Latency monitoring with ping response time to 8.8.8.8
- Interactive doughnut charts using Chart.js
- Modern dark-themed UI with purple accent colors
- Responsive design for various screen sizes
- Comprehensive README documentation with installation and configuration instructions

### Technical Details
- PHP-based backend using system commands (uptime, free, ping)
- Chart.js integration for data visualization
- jQuery for DOM manipulation
- Automatic page reload mechanism for real-time updates
- Support for custom network interface configuration (default: ens18)

[Unreleased]: https://github.com/azuryonoff/AzureLab-Dashboard/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/azuryonoff/AzureLab-Dashboard/releases/tag/v1.0.0
