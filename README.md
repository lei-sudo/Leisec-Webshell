# Leisec-Webshell
A stealthy PHP webshell with WAF bypass capabilities, file management, command execution, and a clean terminal-style interface.


# Overview
Leisec Shell is a PHP-based webshell designed for authorized penetration testing and server administration. It features a password-protected login system, session management, and multiple command execution methods to bypass common WAF restrictions.

---

## Key Features

- **WAF Bypass** - Uses multiple command execution fallbacks (`shell_exec`, `system`, `passthru`, `exec`)
- **Password Protection** - Secure login with session timeout (30 minutes default)
- **File Manager** - Browse, upload, download, edit, rename, and delete files/directories
- **Command Execution** - Run system commands with real-time output
- **File Editor** - Built-in editor for quick file modifications
- **Dynamic Security Key** - Host-based key generation for additional verification
- **Responsive UI** - Terminal-inspired dark theme with mobile support

## Tags

`webshell` `waf-bypass` `file-manager` `command-execution` `php-shell` `penetration-testing` `security-tool`
