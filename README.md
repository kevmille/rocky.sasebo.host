# Rocky Linux Server - rocky.sasebo.host

Welcome to the repository for `rocky.sasebo.host`, a Rocky Linux server designed to provide robust, secure, and scalable solutions.

## About Rocky Linux

[Rocky Linux](https://rockylinux.org/) is a community enterprise operating system designed to be 100% bug-for-bug compatible with America's top enterprise Linux distribution. It is under intensive development by the community.

## Server Specifications

- **Hostname**: rocky.sasebo.host
- **Location**: Seattle (Linode)
- **OS**: Rocky Linux 9

## Services Running

Here you can list the services/applications that are running on this server, for example:

- Web server (Apache/Nginx)
- Database server (MySQL/PostgreSQL)
- Custom applications

## Docker Containerization

This server utilizes Docker for containerization to manage individual Drupal and WordPress site environments. Each site runs within its own isolated container, ensuring scalability, portability, and a consistent development environment.

### Architecture

- **Drupal Containers**: Drupal sites are managed as individual containers, which include the necessary environment for running Drupal (e.g., PHP, Apache/Nginx, and any required extensions).
- **WordPress Containers**: Similarly, WordPress sites are contained with their required PHP and web server configurations, ensuring isolated and secure management.

### Managing Containers

The containers are managed using Docker Compose and custom scripts to simplify the processes of building, starting, stopping, and removing containers.

## Maintenance Schedule

Regular maintenance is performed on this server to ensure security and stability. The maintenance window is scheduled for:

- **Weekly**: Sunday 12:00 AM - 3:00 AM PST
- **Monthly**: First Saturday 1:00 AM - 4:00 AM PST

During maintenance windows, services may not be available.

## Security

Security is a top priority for `rocky.sasebo.host`. To ensure the integrity and confidentiality of the data, the following security measures are in place:

- **SELinux**: Security-Enhanced Linux (SELinux) is enabled on this server, providing an added layer of access control security. SELinux policies are strictly enforced, which helps to limit potential damage from vulnerabilities.

- **SSH**: Secure Shell (SSH) access is restricted and monitored. Regularly update your SSH keys and ensure passwords are strong and changed periodically.

- **Firewalls**: Firewalls are configured to allow only necessary ports and protocols. Regular audits are performed to ensure that firewall rules are up-to-date.

- **Docker Security**: Containers are run with the least privileges necessary, and images are kept up-to-date with the latest security patches. Network configurations are designed to restrict unnecessary internal and external communications.

- **Regular Updates**: System and application updates are regularly applied to ensure all components have the latest security fixes.

- **Monitoring**: Continuous monitoring is in place for detecting and alerting on suspicious activities.

Please adhere to the following guidelines:

- Do not share access with unauthorized users.
- Use key-based authentication for SSH where possible.
- Report any suspicious activity immediately.

In case you have any security concerns or notice unusual behavior, please contact the server admin at [admin@sasebo.host](mailto:admin@sasebo.host) immediately.

## Contribution

Contributions to this server's configuration and maintenance scripts are welcome. Please follow the steps below:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## Contact Information

For any additional information or help, please contact the server admin at [admin@sasebo.host](mailto:admin@sasebo.host).

---

**Note**: This README is for informative purposes and the details/specifications are subject to change based on server operations and maintenance.

# rocky.sasebo.host