# Subdomain Takeover Detection Template

## Overview
This repository provides a `nuclei` YAML template designed for identifying subdomains vulnerable to takeover. It scans for specific error responses that indicate abandoned or misconfigured services.

## Installation & Usage
1. Install `nuclei` if you haven't already:
   ```sh
   git clone https://github.com/projectdiscovery/nuclei.git
   cd nuclei
   go build
