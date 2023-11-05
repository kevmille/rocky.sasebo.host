# Rocky Linux Server - rocky.sasebo.host

Welcome to the repository for `rocky.sasebo.host`, a Rocky Linux server designed to provide robust, secure, and scalable solutions.

## About Rocky Linux

[Rocky Linux](https://rockylinux.org/) is a community enterprise operating system designed to be 100% bug-for-bug compatible with America's top enterprise Linux distribution, [Red Hat Enterprise Linux®].(https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux). It is under intensive development by the community.

## Server Specifications

- **Hostname**: [rocky.sasebo.host](https://rocky.sasebo.host).
- **Location**: Seattle ([Linode](https://linode.com)).
- **OS**: [Rocky Linux 9](https://rockylinux.org/).
- **Rainblur Landing Page**: [https://www.tailwindawesome.com/resources/rainblur-landing-page](https://www.tailwindawesome.com/resources/rainblur-landing-page).

## Services Running

Here you can list the services/applications that are running on this server, for example:

- Web servers ([Apache](https://httpd.apache.org/)/[Nginx](https://nginx.org/en/)).
- Database servers ([MySQL](https://dev.mysql.com/downloads/)/[PostgreSQL](https://www.postgresql.org/)).
- Containers ([Docker](https://www.docker.com/)/[Kubernetes](https://kubernetes.io/)).
- Custom applications ([Astro](https://astro.build/)/[SvelteKit](https://kit.svelte.dev/)).

## Docker Containerization

This server utilizes Docker for containerization to manage individual [Drupal](https://www.drupal.org/) and [WordPress](https://wordpress.org) site environments. Each site runs within its own isolated container, ensuring scalability, portability, and a consistent development environment.

### Architecture

- **Drupal Containers**: Drupal sites are managed as individual containers, which include the necessary environment for running Drupal (e.g., PHP, Apache/Nginx, and any required extensions).
- **WordPress Containers**: Similarly, WordPress sites are contained with their required PHP and web server configurations, ensuring isolated and secure management.

### Managing Containers

The containers are managed using [Docker Compose](https://docs.docker.com/compose/) and custom scripts to simplify the processes of building, starting, stopping, and removing containers.

## Maintenance Schedule

Regular maintenance is performed on this server to ensure security and stability. The maintenance window is scheduled for:

- **Weekly**: Sunday 12:00 AM - 3:00 AM PST.
- **Monthly**: First Saturday 1:00 AM - 4:00 AM PST.

During maintenance windows, services may not be available. Maintenance times are subject to change.

## Security

Security is a top priority for `rocky.sasebo.host`. To ensure the integrity and confidentiality of the data, the following security measures are in place:

- **SELinux**: Security-Enhanced Linux ([SELinux](https://docs.docker.com/compose/)) is enabled on this server, providing an added layer of access control security. SELinux policies are strictly enforced, which helps to limit potential damage from vulnerabilities.

- **SSH**: Secure Shell ([SSH](https://www.linode.com/docs/guides/security/ssh/)) access is restricted and monitored. Regularly update your SSH keys and ensure passwords are strong and changed periodically.

- **Firewalls**: Firewalls are configured to allow only necessary ports and protocols. Regular audits are performed to ensure that firewall rules are up-to-date.

- **Docker Security**: Containers are run with the least privileges necessary, and images are kept up-to-date with the latest security patches. Network configurations are designed to restrict unnecessary internal and external communications.

- **Regular Updates**: System and application updates are regularly applied to ensure all components have the latest security fixes.

- **Monitoring**: Continuous monitoring is in place for detecting and alerting on suspicious activities. We plan to use [Ansible](https://www.ansible.com/).

Please adhere to the following guidelines:

- Do not share access with unauthorized users.
- Use key-based authentication for SSH where possible.
- Report any suspicious activity immediately.

In case you have any security concerns or notice unusual behavior, please contact the server admin at [security@sasebo.host](mailto:security@sasebo.host) immediately.

## Contact Information

For any additional information or help, please contact the server admin at [admin@sasebo.host](mailto:admin@sasebo.host).

---

**Note**: This README is for informative purposes and the details/specifications are subject to change based on server operations and maintenance.

# rocky.sasebo.host