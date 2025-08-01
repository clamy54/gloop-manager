# gloop-manager

**gloop-manager** is a key component of the **Gloop** freeware software suite, designed to centralize and simplify software deployment across Windows 10 and 11 workstations.

## Overview

`gloop-manager` is a graphical administration interface that runs on the administrator's machine. It allows IT admin to manage the entire **Gloop** solution and coordinate software deployments on workstations running the companion tool [`gloop-client`](https://github.com/your-org/gloop-client).

## Key Features

- Graphical user interface for managing software deployments
- Assign, update, or remove software packages from client machines
- Communicates directly with the **Gloop server**
- Designed for Windows 10 & 11 environments

## Requirements

- Windows 10 or Windows 11
- Access to a running **Gloop server**

## How It Works

1. `gloop-manager` connects to the central **Gloop server**.
2. It retrieves the list of registered client machines and available software packages.
3. Administrators can:
   - Assign software to specific workstations
   - Update or remove existing assignments
   - Monitor deployment status and configurations
4. The Gloop server then communicates with each client (`gloop-client`) to apply the changes.

## Installation

Simply run the provided installer on the administrator's workstation. Make sure it has network access to the Gloop server.

## License

This project is part of the **Gloop** freeware suite.

