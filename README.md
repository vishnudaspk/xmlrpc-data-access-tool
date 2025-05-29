# XML-RPC Server Connector

This Python script demonstrates a **robust client for connecting to any XML-RPC based server** (commonly used by many enterprise software solutions). It showcases:

- **Establishing connections with configurable timeouts and detailed error handling**
- **Secure user authentication via XML-RPC API**
- **Retrieving and listing available databases on the server**
- **Querying metadata about available data models/tables**
- **Interactive CLI for user-friendly selection and exploration**
- **Modular, readable, and maintainable Python code**

---

## 🛠️ Technologies Used

- **Python 3.x**
- **`xmlrpc.client`** — native Python library implementing XML-RPC protocol
- Comprehensive error management for network and protocol errors

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/vishnudaspk/xmlrpc-data-access-tool.git
   cd xmlrpc-data-access-tool

Configure connection details (URL, username, password) in the script.

Run the script:

bash
Copy
Edit
python connector.py
Follow the CLI prompts to authenticate, list databases, and explore available data models or records.

## ⚙️ Features

- Network connection timeout and retries to handle unstable networks
- Graceful handling of XML-RPC faults and exceptions
- Flexible data fetching from arbitrary tables/models
- Pagination support and user-controlled data display limits
