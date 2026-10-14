# MotoParts Hub

Motorcycle parts and accessories website for **Event-Driven Programming (Final Project)** and **Business Analytics**, Cebu Eastern College.
Built with HTML, CSS and **PyScript** (Python in the browser).

## Pages
- `index.html` Home
- `products.html` Product catalog (search, category filter) and shopping cart (`products.py`)
- `services.html` Services
- `contact.html` Feedback / interest form (`contact.py`)

## Event-driven features
| Event | Where | What happens |
|---|---|---|
| `input` | search box | catalog filters live as you type |
| `change` | category dropdown | catalog filters by category |
| `click` | Add to cart, +, -, remove | cart and live total update |
| `click` | Place order | validates cart, confirms, clears cart |
| `input` | feedback message | live character counter |
| `submit` | feedback form | validates, saves, updates the list |

## Run locally
`python -m http.server` in this folder, then open http://localhost:8000
(Opening the files by double-click may block PyScript; GitHub Pages also works.)

## Group
Taborada, John Richard · Cabanada, Ysiah · Navidad, Tirsnavs · Pulgo, Michael · Arcenal, Kianzel
