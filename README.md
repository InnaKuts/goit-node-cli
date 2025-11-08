# Contacts CLI

This is a simple CLI tool to manage your contacts using Node.js and Commander.

## Usage

Before working with the contacts, **run the seed command to populate the contact database** with sample data:

```bash
node index.js -a seed
```

### Available Commands

- **Seed contacts:**

  ```bash
  node index.js -a seed
  ```

- **List all contacts:**

  ```bash
  node index.js -a list
  ```

- **Get contact by id:**

  ```bash
  node index.js -a get -i <contactId>
  ```

- **Add new contact:**

  ```bash
  node index.js -a add --name <name> -e <email> -p <phone>
  ```

- **Remove a contact:**

  ```bash
  node index.js -a remove -i <contactId>
  ```

Replace `<contactId>`, `<name>`, `<email>`, and `<phone>` with the relevant information.

Exmaple:

```bash
node index.js -a seed
node index.js -a list
node index.js -a get -i 05olLMgyVQdWRwgKfg5J6
node index.js -a add -n Mango -e mango@gmail.com -p 322-22-22
node index.js -a remove -i qdggE76Jtbfd9eWJHrssH
```
