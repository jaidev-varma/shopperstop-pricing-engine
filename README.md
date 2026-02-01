# ShopperStop Promotional Pricing Engine (PPE)

A flexible, configuration-driven discount calculation engine built with **FastAPI** and **Python**. Designed to handle complex retail scenarios like tiered slab discounts, BOGO offers, and coupon stacking.

## 🌟 Key Features
* **Strategy Pattern Design:** Easily extensible for new discount types (e.g., Happy Hour, Category-based).
* **Configuration-Driven:** Marketing teams can create rules via API without deploying code.
* **Precision Math:** Uses `Decimal` for financial accuracy.
* **API-First:** Auto-generated Swagger documentation.

## 🛠️ Tech Stack
* **Language:** Python 3.11+
* **Framework:** FastAPIs   
* **Validation:** Pydantic v2
* **Testing:** Pytest

## 🚀 Quick Start

### Option 1: Docker (Recommended)
Run the application with a single command:
```bash
docker build -t discount-engine .
docker run -p 8000:8000 discount-engine
