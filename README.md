# Facebook Page (Profile Plus) Creator

A lightweight Python script to automate the creation of Facebook Pages (Profile Plus) using GraphQL and Bloks API. This tool allows you to programmatically create pages by specifying a name, category ID, and a valid access token.
## 🚀 Features

* **Automated Creation**: Quickly generate pages without manual UI interaction.
* **Direct API Integration**: Uses Facebook's internal `GraphServices` and `Bloks` endpoints.
* **Android Emulation**: Includes dynamic latency markers and UUIDs to mimic legitimate Android app behavior.

## 🛠️ Prerequisites

Before running the script, ensure you have:

* **Python 3.x** installed.
* The `requests` library. Install it via:
```bash
pip install requests

```


* A valid **Facebook Access Token** (typically an `EAAU` token).

## 📂 Configuration

Modify the parameters in the script to suit your needs:

* **`name`**: The name of the page you want to create.
* **`category`**: A list of category IDs (e.g., `["2214"]` for Health/Beauty).
* **`token`**: Your Facebook Access Token.

## 🖥️ Usage

Run the script using the following command:

```bash
python main.py

```

### Example Output:

```text
Success Create Page!
Page Name  : BoyFifteen
Page ID    : 1000xxxxxxxxx
Profile ID : 1000xxxxxxxxx

```

## ⚠️ Disclaimer

> [!IMPORTANT]
> This tool is for educational purposes only. Automated page creation may violate Facebook's Terms of Service. Use responsibly to avoid account restrictions.

---

### Contact & Support

If you have any questions or need further customization, feel free to reach out on Telegram: **@WHI3PER**.

---
