# Spam & Likes Automation API

Welcome to the **Spam & Likes API** – a powerful and flexible RESTful API designed for developers who need to automate likes, gather user information, or simulate interactions at scale.

## Features

- **Auto-Likes Engine:** Instantly send mass likes to any target using simple endpoints.
- **Spam Messaging:** Send high-volume custom messages for testing or automation purposes.
- **User Info Fetcher:** Retrieve clean and structured user data (ID, username, etc.).
- **Secure Access:** JWT-based authentication and rate-limiting to ensure control and stability.

---

## Endpoints

### 1. `POST /like`
Send automated likes to a specified target.

**Parameters:**
```json
{
  "uid": "target_user_id"
}
